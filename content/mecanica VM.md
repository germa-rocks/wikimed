---
publish: true
---
Aqui está a estruturação de alto rendimento do capítulo sobre Mecânica Respiratória, otimizada para o princípio de divulgação progressiva (formato *toggle list* aninhada) ideal para Notion, Obsidian ou Anki.

***

# 🫁 Mecânica Respiratória Básica na UTI

## 1. Fisiologia e Pressões Pulmonares
- **A Pressão Transpulmonar é a variável mais importante para avaliar o risco de Lesão Induzida pela Ventilação Mecânica (VILI).**
	- Reflete o "stretch" real (pressão de distensão) sofrido pelo alvéolo.
	- Cálculo: Pressão Alveolar – Pressão Pleural.
- **A Pressão Transtorácica pode superestimar o risco de lesão em pacientes com rigidez torácica.**
	- Cálculo: Pressão Pleural – Pressão na Superfície do Corpo.
	- Red Flags Clínicas (Falsos aumentos da Pressão Alveolar sem aumento da Transpulmonar): Pacientes obesos (ex: mamas/abdome recaindo sobre o tórax) ou com rigidez da musculatura torácica. Nestes casos, a pressão de platô será alta, mas a transpulmonar pode estar segura.
- **A Pressão Intrapleural é fisiologicamente negativa e cai ainda mais durante o esforço inspiratório espontâneo forte.**
	- Red Flag no Desconforto Respiratório: Paciente em ventilação (ex: VNI ou PSV) puxando com muito esforço gera pressão pleural muito negativa (ex: -15 cmH2O). Somada à pressão positiva do aparelho (ex: +10 cmH2O), gera uma Pressão Transpulmonar altíssima (25 cmH2O), causando VILI crasso.

## 2. A Equação do Movimento Respiratório
- **O trabalho total (Paciente + Ventilador) precisa vencer duas forças principais: Elastância (dureza) e Resistência (fricção).**
	- Fórmula base: `Pressão Muscular + Pressão Ventilador = (Volume x Elastância) + (Fluxo x Resistência)`.
	- Para ajustar o suporte do ventilador, é obrigatório entender a mecânica (elastância e resistência) do paciente.

## 3. Complacência Pulmonar (Deformabilidade)
- **A Complacência é o oposto da elastância: mede a capacidade do pulmão se deformar (receber volume) sob uma determinada pressão.**
	- Valores de Referência Normais: 60 a 100 mL/cmH2O.
	- Complacência Ruim (pulmão duro): < 40 mL/cmH2O (ex: 20-30).
	- Fatores que pioram a complacência: SDRA (áreas colapsadas/peso), obesidade, idade avançada, posição supina (melhora no proclive).
- **Complacência Estática (Cest) é o padrão-ouro pois avalia o alvéolo livre da resistência das vias aéreas.**
	- Fórmula: `Volume Corrente (Vt) / (Pressão de Platô - PEEP)`.
	- Como avaliar a Curva P-V: Quanto mais "deitada" (horizontal) a curva Pressão-Volume, pior a complacência. Curvas mais "em pé" indicam melhora.
- **Complacência Dinâmica (Cdin) é uma estimativa rápida, mas sofre interferência da resistência das vias aéreas.**
	- Fórmula: `Volume Corrente (Vt) / (Pressão de Pico - PEEP)`.
	- Uso clínico: Avaliação rápida (sem pausa inspiratória). Pode estimar a complacência estática apenas se o componente resistivo não estiver aumentado.

## 4. Resistência das Vias Aéreas
- **A Resistência avalia a dificuldade gerada pela fricção para a passagem do fluxo de ar nas vias aéreas.**
	- Fórmula: `(Pressão de Pico - Pressão de Platô) / Fluxo`.
	- Valores de Referência Normais: 3 a 10 cmH2O / L/s.
- **O cálculo exige conversão de unidade matemática para o Fluxo (Atenção à beira-leito).**
	- O ventilador fornece o fluxo em Litros/minuto, mas a fórmula exige Litros/segundo.
	- Dica prática: Ajuste o fluxo para 30 L/min (equivale a 0,5 L/s) ou 60 L/min (equivale a 1,0 L/s) para facilitar a conta de cabeça.
- **Análise visual na Curva Pressão-Volume (Loop P-V).**
	- Aumento da resistência "engorda" a curva, deixando-a com aspecto **quadrado** (muita variação de pressão para entrada/saída de volume).

## 5. Algoritmo Prático de Medida à Beira-Leito (O Passo a Passo)
- **Regra de Ouro para aferição correta: Paciente passivo + VCV + Fluxo Quadrado.**
	- 1. Sedação profunda ou bloqueio neuromuscular (esforço do paciente impossibilita leitura de platô).
	- 2. Mudar modo para Volume Controlado (VCV). O cálculo de resistência **não** pode ser feito em PCV, pois o fluxo em PCV é decrescente (não é constante).
	- 3. Escolher formato de onda de Fluxo Quadrada (Constante).
	- 4. Aplicar Pausa Inspiratória de 1 a 2 segundos.
- **Critério de qualidade da curva de Pausa Inspiratória.**
	- O que buscar: Uma queda do Pico para um Platô que se mantenha em uma linha reta horizontal.
	- Red Flag (Fuga de ar): Se a pressão cai continuamente como uma rampa durante a pausa e nunca estabiliza, há escape de ar. O valor numérico dado pelo ventilador será falso e não deve ser usado.
- **Identificação de Hiperdistensão na Curva de Pressão x Tempo (Stress Index).**
	- Se a rampa de ascensão da pressão (fase inspiratória) formar uma "barriga" convexa para cima (Stress Index > 1), indica que o pulmão está sendo hiperdistendido no final da inspiração. Reduzir a PEEP costuma retificar a curva e melhorar a complacência.

## 6. Constante de Tempo (CT) e Prevenção de Auto-PEEP
- **A Constante de Tempo dita a velocidade de esvaziamento pulmonar e guia o ajuste do Tempo Expiratório.**
	- Fórmula: `Constante de Tempo (em segundos) = Resistência x Complacência`.
	- Fisiologia: O esvaziamento pulmonar não é linear, é exponencial.
- **O Tempo Expiratório mínimo obrigatório é de 3x a Constante de Tempo.**
	- 3 Constantes de Tempo garantem que ~95% do ar foi exalado.
	- Impacto clínico: Menos que isso, o paciente fará Auto-PEEP (aprisionamento de ar).
- **Aplicações nos perfis de pacientes:**
	- Paciente com SDRA (Restritivo): CT curta (ex: 0,15s). Esvazia rápido. Exige tempo expiratório mínimo bem curto (ex: 0,45s). Permite usar frequências respiratórias mais altas para lavar CO2.
	- Paciente Obstrutivo (Asma/DPOC): CT longa. Esvazia muito devagar. Exige tempo expiratório prolongado.

## 7. Troubleshooting e Diagnóstico Diferencial Rápido
- **Padrão SDRA (Restritivo).**
	- Resistência: Normal.
	- Complacência: Baixa.
	- Conduta: Titulação de PEEP guiada por melhor complacência (redução progressiva medindo a Driving Pressure); Ventilação protetora (Platô < 30).
- **Padrão Obstrutivo.**
	- Resistência: Alta.
	- Complacência: Normal.
	- Conduta: Aumentar muito o tempo expiratório. Frequência respiratória mais baixa.
- **Red Flags: Mudanças Abruptas da Mecânica.**
	- Alterações súbitas de mecânica nunca são processos patológicos de base (ninguém faz SDRA em 1 minuto).
	- Queda Abrupta de Complacência: Suspeitar de Intubação Seletiva (tubo principal direito) ou Pneumotórax (ex: barotrauma ou pós punção venosa central).
	- Aumento Abrupto de Resistência: Suspeitar de Rolha de secreção obstruindo o Tubo, Filtro HME encharcado de secreção/condensado, ou Broncoespasmo agudo severo.
		- Sinais de tubo obstruído no ventilador: Aumento súbito da Pressão de Pico (sem aumento de Platô), curva de fluxo expiratório que não zera (gerando auto-PEEP), loop P-V com aspecto "quadrado".

## 8. Avaliação em Modos Espontâneos (Pressão de Suporte - PSV)
- **É impossível calcular Complacência e Resistência formalmente em PSV.**
	- Motivo: Fluxo é livre e decrescente, não há pausa inspiratória programada e o esforço do paciente (Pmus) é variável e desconhecido.
	- Avaliação de esforço/mecânica se dá por via indireta clínica: Retração de fúrcula, uso de musculatura acessória, queda de Vt e aumento de FR indicam complacência ruim ou aumento de resistência.
- **A P0.1 é a melhor medida indireta do Drive Respiratório do paciente em PSV.**
	- O que é: Medida da pressão negativa gerada nos primeiros 100 milissegundos (0,1s) de uma inspiração contra as vias aéreas momentaneamente ocluídas.
	- Valores de Referência (1 a 4 cmH2O):
		- > 3,5 a 4,0 cmH2O: Drive muito alto. Indica pouca assistência do ventilador (paciente fazendo muito esforço) ou falência mecânica/SARA agravando.
		- < 1,0 cmH2O: Drive suprimido. Indica assistência excessiva (sobreassistência) ou sedação profunda.
	- Vantagem: Por durar apenas 0,1s, não gera desconforto e não afeta a sincronia ventilatória.