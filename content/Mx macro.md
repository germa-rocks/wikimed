---
publish: true
---



# Monitorização Hemodinâmica (Macro-hemodinâmica)

## Monitorização Básica e Parâmetros Iniciais
- **A Frequência Cardíaca (FC) é um marcador prognóstico precoce e obrigatório; o aumento da FC é uma resposta adaptativa de alerta inicial.**
	- O *Shock Index* (FC/PA Sistólica) é uma ferramenta útil beira-leito para prever risco de choque antes da queda franca da pressão.
	- Alterações na FC, capnografia (ETCO2 baixo por má perfusão pulmonar) e oximetria de pulso (falha de leitura periférica) são sinais indiretos de baixo débito cardíaco (DC) e má macro-hemodinâmica.

## Pressão Arterial Não Invasiva (PANI) vs. Invasiva (PAI)
- **A PANI (método oscilométrico) é perigosa nos extremos hemodinâmicos: ela subestima a pressão alta e superestima a pressão baixa.**
	- Mecanismo do Método Oscilométrico:
		- O manguito mede diretamente a **Pressão Arterial Média (PAm)**, detectando o ponto de maior oscilação da parede arterial durante a deflação.
		- A PA Sistólica e Diastólica não são medidas diretamente, mas calculadas por algoritmos proprietários de cada monitor (podendo divergir entre marcas).
	- Taxa de Erro no Paciente Crítico:
		- 26% das medidas apresentam erro de 10-20 mmHg em relação à PAI.
		- 6% apresentam erro superior a 20 mmHg.
		- 📎 Refs: *Crit Care Med 2003;31(3):793-9.*
- **Indicações mandatórias para transição para Pressão Arterial Invasiva (PAI):**
	- Uso de drogas vasoativas (DVA).
	- Titulação de vasodilatadores potentes (ex: emergência hipertensiva).
	- Extremos de pressão arterial.
	- PA limítrofe associada a sinais de hipoperfusão (lactato alto, tempo de enchimento capilar lentificado, *mottling score* elevado).
	- *Exceção/Bom Senso:* Paciente com dose baixa e estável de DVA (ex: Noradrenalina 2 mL/h), com PAm alvo atingida na PANI e exame físico normal (bom débito urinário, perfusão periférica, alerta) não exige PAI obrigatória.
- **A PAI só é confiável se o "Teste da Curva Quadrada" (*Flush Test*) atestar a fidelidade do sistema.**
	- Mecanismo de verificação: Tração do *flush* rápido no transdutor (injetando soro pressurizado) para avaliar a resposta e queda da onda.
	- **Curva Normal (Adequada):**
		- Elevação e queda rápidas, gerando apenas 1 ou 2 oscilações (*chicoteamentos*) antes de voltar à leitura normal. Reflete o valor real de PA.
	- **Curva Amortecida / *Damped* (Subestimação da Pressão de Pulso):**
		- Queda atenuada, sem oscilação adequada. A Sistólica e Diastólica convergem (ex: PA real 100x60 lida como 80x70).
		- *Causas:* Coágulo no cateter, dobras no sistema, punho do paciente fletido, tubulação muito flexível.
	- **Curva Subamortecida / *Underdamped* (Superestimação da Sistólica):**
		- Queda com múltiplas reverberações (hachurado). A Sistólica e Diastólica se distanciam (ex: PA real 100x60 lida como 120x50, falso alargamento de pulso).
		- *Causas:* Circuito excessivamente curto ou hiper-ressonância do sistema. Pode simular falsamente insuficiência aórtica ou hipertireoidismo.

## Avaliação do Débito Cardíaco (DC)
- **A pressão arterial isolada é insuficiente no paciente grave instável ou sem resposta; a monitorização do DC impõe-se em cenários de incerteza.**
	- Indicações para monitorizar o DC:
		- Dúvida diagnóstica (choque misto ou etiologia obscura).
		- Evolução inesperadamente ruim (ex: sepse inicial bem tratada que evolui com deterioração hemodinâmica inexplicada).
		- Dúvidas no manejo volêmico (risco de congestão vs. necessidade de expansão).
		- Choque cardiogênico ou hipertensão pulmonar (HP).
		- Prevenção em cirurgias de alto risco.
	- *Red Flag da Sepse:* Disfunção miocárdica induzida pela sepse ocorre em 30-60% dos pacientes. O paciente séptico pode apresentar um choque cardiogênico sobreposto que a PAI isolada não detectará.

## Métodos de Monitorização do Débito Cardíaco
### 1. Ultrassom *Point of Care* (POCUS / Ecocardiograma Beira-leito)
- **O Ecocardiograma é a modalidade inicial preferencial quando a avaliação clínica e pressórica não responde às dúvidas do choque.**
	- Avaliações diretas e indiretas (Não Invasivo):
		- Medida objetiva do DC: Através da técnica de VTI (Integral Tempo-Velocidade).
		- Função cardíaca global: Avaliação subjetiva de contratilidade biventricular.
		- Avaliação de VD e Artéria Pulmonar: Estima a Pressão Sistólica da AP, detectando *Cor Pulmonale* (Tromboembolismo Pulmonar, SARA grave).
		- Diagnósticos diferenciais letais: Tamponamento cardíaco, hipovolemia franca.
		- Avaliação Pulmonar: Ultrassom de pulmão identificando congestão (Linhas B) ou pneumotórax.
	- Limitações: Exame estritamente operador-dependente e limitado por janela acústica ruim (ex: DPOC, obesidade, alta PEEP).

### 2. Análise de Contorno de Pulso (Minimamente Invasivo - Ex: Vigileo, Hemosphere)
- **Estes monitores NÃO servem para medir o valor absoluto do DC no paciente crítico chocado, mas são úteis para avaliar tendência e reposta a volume.**
	- Princípio fisiológico premissa: DC = Pressão de Pulso (PP) x Complacência Vascular. A área sob a curva sistólica da PAI estima o DC.
	- *A Falha Conceitual (Red Flag):* O algoritmo assume que a complacência vascular do paciente é constante. Em pacientes críticos, usando vasopressores (noradrenalina), inotrópicos ou em estados hiperdinâmicos, a complacência muda minuto a minuto, invalidando o número absoluto (método não calibrável).
	- Utilidade Real Beira-leito: Avaliação de métodos dinâmicos (Delta PP, Variação do Volume Sistólico - VVS) ou elevação passiva das pernas. O número absoluto está errado, mas a variação percentual de subida do DC reflete resposta a volume.

### 3. Termodiluição Transpulmonar (Menos Invasivo - Ex: PiCCO, EV1000)
- **É o método de escolha para diferenciar SARA de Edema Pulmonar Hidrostático através do cálculo da Água Extravascular Pulmonar.**
	- Mecanismo (Calibrável):
		- Requer Cateter Venoso Central (com termistor) + PAI específica (artéria femoral ou axilar).
		- Injeta-se 10 mL de soro gelado no CVC. O tempo de transição térmica até o termistor arterial determina o DC absoluto e real.
		- Após a injeção, o monitor passa a calcular o DC continuamente por análise de contorno de pulso.
	- Parâmetros Exclusivos e Red Flags:
		- Água Extravascular Pulmonar: Normal é < 7 a 10 mL/kg. Se aumentado, indica pulmão encharcado (congestão).
		- Índice de Permeabilidade Vascular Pulmonar: Distingue se a água extra é por falha hidrostática (insuficiência cardíaca) ou por permeabilidade (inflamação/SARA).
		- *Fator limitante 1:* Exige recalibração frequente com injeção de soro gelado se houver alteração da instabilidade clínica/complacência.
		- *Fator limitante 2:* Totalmente falho/contraindicado em embolia pulmonar, derrame pleural maciço ou pós-ressecção pulmonar.

### 4. Cateter de Artéria Pulmonar / Swan-Ganz (Altamente Invasivo)
- **Continua sendo o padrão-ouro de medida direta do DC e pressões cavitárias, mas reservado a casos de choque refratário ou HP complexa devido a complicações.**
	- Vias e Medidas Fisiológicas:
		- Via Proximal (Átrio Direito): Mede Pressão Venosa Central (PVC / PAD).
		- Balonete / Via Distal: Na artéria pulmonar com o balão insuflado, a medida da ponta isola o ventrículo direito e reflete a Pressão à frente (Pressão de Átrio Esquerdo / Pressão de Oclusão da AP - POAP).
		- Balonete Desinsuflado: Mede Pressão Sistólica e Diastólica da Artéria Pulmonar (Crucial na Hipertensão Pulmonar).
		- Termistor: Permite medir DC padrão-ouro por injeção térmica proximal.
		- Coleta direta: Saturação Venosa Central Mista (SvO2).
		- Cálculos derivados: Resistência Vascular Sistêmica e Pulmonar.
	- Desvantagens e Armadilhas:
		- Procedimento altamente invasivo com risco de arritmias, ruptura de artéria pulmonar e infecções.
		- Medida intermitente do DC (embora existam cateteres de DC contínuo hoje).
		- Alta variabilidade inter-observador: Leituras incorretas das curvas geram condutas iatrogênicas irreversíveis.

## Algoritmo Prático de Decisão (Consenso ICM)
- **A progressão da monitorização deve ser gradual, acionada APENAS se o exame físico + PAI não esclarecerem o choque (Não usar DC rotineiramente).**
	- 📎 Refs: *Consensus on circulatory shock and hemodynamic monitoring, Intensive Care Med (2014) 40:1795–1815.*
	- Passo 1: Avaliação macro e perfusional (Clínica + PANI/PAI). Paciente respondeu? Manter estratégia.
	- Passo 2: Evolução atípica ou falha? Realizar **Ecocardiograma beira-leito (POCUS)** imediato.
	- Passo 3: Avaliar resultados do POCUS e direcionar a invasão térmica/contínua:
		- Suspeita exclusiva de Disfunção de Ventrículo Esquerdo (VE): Optar por Termodiluição Transpulmonar, Swan-Ganz ou análise de contorno de pulso (somente se a meta for testar volume).
		- Suspeita de Disfunção de Ventrículo Direito (VD) ou Hipertensão Pulmonar (HP): Evitar Termodiluição (não reflete bem o lado direito). Manter-se no Ecocardiograma seriado ou progredir diretamente para Cateter de Artéria Pulmonar (Swan-Ganz).