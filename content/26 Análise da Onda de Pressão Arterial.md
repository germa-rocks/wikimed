---
publish: true
---



# Análise da Onda de Pressão Arterial (APWA) para Monitorização do Débito Cardíaco

## Princípios Fisiológicos e Premissa Básica
- **A premissa central da APWA é que a pressão arterial possui uma relação proporcional e previsível com o Volume Sistólico (VS), permitindo a monitorização do Débito Cardíaco (DC) batimento a batimento.**
	- A pressão arterial é o produto da interação entre o fluxo ejetado pelo coração (VS) e o estado do sistema arterial (carga arterial).
	- Se a "carga arterial" (resistência, complacência, reflexões de onda) muda, a relação pressão-volume muda também, e a pressão deixa de refletir fielmente o VS isolado.
	- Fisiologia profunda: A relação entre pressão e VS é não-linear e dependente da pressão.
		- À medida que o volume sistólico aumenta, a distensibilidade da parede aórtica diminui progressivamente, fazendo com que a pressão arterial suba muito mais rápido. Essa não-linearidade exige algoritmos complexos de correção.
		- Existe o fenômeno de amplificação fisiológica da pressão de pulso da aorta central até a artéria radial, gerando diferenças morfológicas e de amplitude nas ondas. Algoritmos modernos aplicam funções de transferência e o modelo de *Windkessel* para compensar essa amplificação.
			- 📎 Refs: 1, 2, 3, 4, 20, 21, 22.

## Calibração: Por que e Quando Fazer
- **Para que a APWA estime o VS corretamente, ela precisa estabelecer o "estado atual" do sistema arterial do paciente. A isso dá-se o nome de Calibração (Fator de Escala X).**
	- Fórmula básica conceitual: `VS Estimado = Pressão de Pulso Arterial × Fator X` (sendo `DC = VS × Frequência Cardíaca`).
	- **Métodos Autocalibrados (Calibração Interna):** O sistema utiliza dados biométricos do paciente ou a análise morfológica da onda para inferir a impedância aórtica.
		- Dispositivos: Vigileo/FloTrac, MostCare, LiDCOrapid, Nexfin/ClearSight, PulsioFlex, CNAP.
		- Limitação Clínica: Como baseiam a calibração em dados populacionais (frequentemente de indivíduos estáveis/saudáveis), o valor absoluto do DC tem baixa confiabilidade em pacientes críticos severamente descompensados.
			- 📎 Refs: 4, 7, 8.
	- **Métodos com Calibração Externa:** O Fator X é ajustado introduzindo uma medida real de DC obtida por um método independente e preciso.
		- Opções de calibração: Termodiluição transpulmonar (EV1000, PiCCO2), diluição de lítio (LiDCO plus) ou Doppler Esofágico (CardioQ).
		- Vantagem clínica extra: A calibração externa rotineira (ex: termodiluição transpulmonar) fornece dados complementares cruciais, como volumes cardíacos, função contrátil e água pulmonar extravascular.
			- 📎 Refs: 5, 6.
	- **Momento da Recalibração (Red Flag):** Não utilize intervalos de tempo fixos para recalibrar; recalibre sempre que houver *suspeita clínica de mudança no sistema arterial*.
		- Piores cenários para a APWA (exigem recalibração): Choque séptico grave com instabilidade profunda ou introdução/titulação drástica de drogas vasoativas.
		- Melhores cenários (alta acurácia): Avaliação de mudanças isoladas de pré-carga com tônus arterial estável (ex: Elevação Passiva das Pernas, Desafio Hídrico).
			- 📎 Refs: 9-12, 15-17, 18, 19, 23, 24, 25, 26.

## Fatores de Confusão e Qualidade do Sinal (Red Flags)
- **A confiabilidade do DC calculado depende criticamente da qualidade técnica da onda de Pressão Arterial Invasiva (PAI). Um sinal ruim gera dados falsos.**
	- **Excesso de Amortecimento (Damping) e Subamortecimento (Ressonância):** Alteram profundamente a morfologia da onda e a estimativa do VS.
		- Artefatos de subamortecimento/ressonância estão presentes em cerca de 33% dos pacientes críticos.
		- Conduta beira-leito OBRIGATÓRIA: Avaliar periodicamente o sistema de transdução utilizando o Teste de Lavagem Rápida (*Fast-Flush Test* / Teste da Onda Quadrada). Garantir zero e calibração do transdutor.
			- 📎 Refs: 27, 28, 29.
	- **Contraindicações Absolutas da APWA:** Cenários de distorção artificial ou patológica do pulso.
		- Uso de Balão Intra-Aórtico (BIA).
		- Insuficiência Aórtica severa.
	- **Limitações em Sistemas Não-Invasivos (Método de Clamp de Volume - ex: Nexfin/ClearSight):**
		- Dependem de boa perfusão capilar no dedo.
		- São imprecisos em pacientes com uso de altas doses de vasopressores ou hipoperfusão periférica por anormalidades microcirculatórias (sepse). O uso ideal restringe-se a pacientes menos graves ou no perioperatório.
			- 📎 Refs: 18, 30, 31, 32.

## Aplicações Práticas Beira-Leito e Tomada de Decisão
- **A interpretação da APWA depende do objetivo da monitorização: Valor Absoluto, Tendência (Trending) ou Variação Dinâmica.**
	- **1. Para medir o Valor Absoluto do DC (Acurácia):** É o maior calcanhar de Aquiles da técnica.
		- Em sistemas de calibração interna: Cuidado. Os valores absolutos só são confiáveis se a hemodinâmica do paciente se assemelhar à população usada para criar o algoritmo.
		- Em sistemas de calibração externa: Confiável, desde que as condições hemodinâmicas do momento em que a calibração foi feita permaneçam estáveis.
	- **2. Para rastrear Mudanças no DC (Trending):** É uma das principais aplicações práticas.
		- Permite detectar se o paciente está melhorando ou piorando.
		- Funciona muito bem desde que o tônus arterial não mude drasticamente.
		- *Red Flag:* Se você notar uma alteração colossal do DC detectada pelo monitor e o paciente não teve uma mudança clínica óbvia, o "Fator X" do sistema arterial provavelmente mudou. Faça uma recalibração externa (se o monitor permitir).
	- **3. Para medir Índices Dinâmicos (VPP, VVS):** É o cenário onde a APWA brilha como ferramenta funcional e pragmática.
		- Ferramenta altamente confiável para rastrear mudanças do VS em curtíssimo prazo (batimento a batimento) para avaliar responsividade a fluidos.
		- *Cuidado clínico:* Quando os índices dinâmicos baseados na APWA falham, geralmente a culpa não é do algoritmo, mas sim do não cumprimento dos rigorosos critérios fisiológicos para o uso do índice pelo próprio paciente (ex: não estar em ventilação mecânica controlada, ter arritmias, volume corrente < 8ml/kg, etc).
			- 📎 Refs: 13, 33, 34.