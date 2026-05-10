---
publish: true
---

# Interações Paciente-Ventilador: Assincronia, PAV e NAVA

## Prevalência e Impacto da Assincronia Paciente-Ventilador (PVA)
* **A assincronia ocorre em cerca de 25% dos pacientes em ventilação mecânica e impacta negativamente a duração do suporte e a morbidade na UTI.**
	* O Índice de Assincronia (AI - *Asynchrony Index*) > 10% define clinicamente um paciente como "assincrônico".
		* Fisiopatologia / Definição de AI: O AI é o número total de eventos assincrônicos dividido pela frequência respiratória total (incluindo esforços não reconhecidos pelo ventilador) multiplicado por 100.
		* As formas mais prevalentes de asssincronia (responsáveis por ~98% dos casos) são os disparos ineficazes (*ineffective triggering*) e o duplo disparo (*double-triggering*).
		* O duplo disparo é estatisticamente mais comum em modos controlados a volume (VCV) do que em modos de pressão de suporte (PSV).
	* O impacto clínico da assincronia grave (AI > 10%) resulta em atraso no desmame ventilatório.
		* Prolonga significativamente o tempo de ventilação mecânica (VM).
		* Aumenta a taxa de traqueostomia.
		* Prolonga o tempo de internação na UTI e no hospital.
		* 📎 Refs: *Thille 2006; De Wit 2009*.
	* **Red Flag (Mortalidade):** Identificar e corrigir assincronias é fundamental para reduzir lesão pulmonar induzida pelo ventilador (VILI) e a necessidade de sedação. Embora alguns estudos observacionais sugiram um benefício de mortalidade para pacientes sincrônicos, os dados ainda carecem de validação randomizada definitiva. *(📎 Refs: Blanch 2015)*.

## Proportional Assist Ventilation (PAV)
* **O modo PAV funciona como uma "direção hidráulica": calcula a mecânica pulmonar do paciente em tempo real e fornece pressão diretamente proporcional ao fluxo inspiratório demandado.**
	* Indicação: Otimização da sincronia e redução do trabalho respiratório em pacientes estritamente espontâneos, com *drive* respiratório intacto e confiável.
		* Mecanismo Contínuo: Diferente do PRVC (que se baseia no fôlego anterior), o PAV monitora a demanda inspiratória e calcula a resistência e complacência (impedância) *durante* a própria incursão respiratória.
		* Fisiologia do suporte: Esforço pequeno = pequeno suporte de pressão. Esforço grande = grande suporte. O tempo inspiratório, fluxo e volume terminam e variam exatamente quando o paciente deseja.
	* Configuração Inicial e Parâmetros (Não há ajuste de volume ou pressão fixa).
		* **Porcentagem de Suporte (% Supp):** É o controle principal. Define qual porcentagem do Trabalho Respiratório (*Work of Breathing* - WOB) o ventilador irá assumir (ex: 50% significa que o ventilador fará metade do trabalho necessário para gerar fluxo e volume).
		* Configura-se sensibilidade a fluxo (geralmente 2 a 3 L/min), PEEP, FiO2, além de inserir o diâmetro e tipo do tubo endotraqueal na máquina.
	* Limitações Práticas e Red Flags na beira-leito.
		* **Vazamentos (*Leaks*) destroem o algoritmo:** Qualquer vazamento no circuito interfere no cálculo da impedância pelo ventilador, resultando em respostas inadequadas.
		* Período de Adaptação: Pacientes recém-transicionados de PSV para PAV podem apresentar taquipneia inicial. Eles "estranham" a perda do "empurrão" fixo de pressão do PSV, e o centro respiratório leva um tempo para recalibrar a nova dinâmica de pressão variável.
		* Equipamento restrito: Disponível primariamente em ventiladores Medtronic (ex: Puritan Bennett 840/980).

## Neurally-Adjusted Ventilatory Assist (NAVA)
* **O modo NAVA utiliza a atividade elétrica do diafragma (Edi) captada via sonda digestiva para disparar e ciclar o ventilador, oferecendo o padrão-ouro teórico de sincronia neuro-ventilatória.**
	* Indicação: Pacientes com asssincronias intratáveis por parâmetros convencionais e em casos de Ventilação Não-Invasiva (VNI) com vazamentos difíceis de controlar. Exige *drive* respiratório.
		* Mecanismo: Uma sonda nasogástrica ou orogástrica especial dotada de múltiplos eletrodos é posicionada distalmente no esôfago, rente ao diafragma.
		* Resposta imediata: O ventilador não aguarda queda de pressão ou fluxo no circuito. Assim que o diafragma dispara eletricamente (em microvolts), o ventilador fornece pressão na mesma proporção e tempo da ativação neural.
	* Configuração Inicial e Parâmetros.
		* **Nível NAVA (*NAVA Level*):** Define quantos centímetros de água (cmH2O) serão entregues para cada microvolt (µV) de atividade diafragmática (ex: 1.6 cmH2O/µV).
		* **Gatilho (*Trigger Edi*):** Define o limiar elétrico para disparar a respiração (ex: 0.5 µV).
		* Configurações de Segurança: É mandatório configurar parâmetros de Pressão de Suporte (PSV) de backup para entrar em ação caso ocorra perda de sinal do cateter, além de parâmetros clássicos de apneia.
	* Monitorização e Vantagens Especiais (Uso em VNI).
		* **Vantagem em VNI:** Como o gatilho vem diretamente do cérebro para o diafragma, o modo NAVA é imune aos vazamentos de máscara que comumente causam auto-ciclagem ou falhas de disparo na VNI tradicional.
		* Avaliação de sincronia offline: A curva do Edi pode ser monitorada na tela *mesmo se o paciente estiver em VCV ou PSV*. Isso ajuda a diagnosticar a causa exata de uma asssincronia em modos convencionais.
	* Limitações Práticas e Red Flags na beira-leito.
		* **Procedimento Invasivo:** Contraindicado em pacientes sem acesso gástrico seguro (ex: cirurgias esofágicas recentes, defeitos septais anatômicos para passagem de sonda).
		* Alto Custo e Exclusividade: Exige insumos descartáveis muito caros (cateter NAVA) e está limitado a ventiladores da marca Maquet/Servo.
		* Evidência de Desfecho: Apesar da redução da necessidade de sedação e clara superioridade em garantir sincronia quando comparado ao PSV, faltam estudos robustos demonstrando redução de mortalidade clínica. *(📎 Refs: Schmidt 2015; Kallio 2015; Liu 2015)*.