---
publish: true
---

# Princípios Gerais da Ventilação Mecânica
## **Regra dos 4 Passos para Análise Inicial a Beira-Leito**
### Sistematização da avaliação do ventilador para tomada de decisão rápida.
- **Passo 1: Identificar as curvas (Reconhecer quem é quem)**
	- **Curva de Fluxo:** É a única curva com componente positivo (fase inspiratória) e negativo (fase expiratória).
	- **Curva de Volume:** Possui aspecto triangular, sai do zero e retorna ao zero absoluto.
	- **Curva de Pressão:** Sai do nível da PEEP e volta para a PEEP (nunca toca o zero, a menos que PEEP = 0).
- **Passo 2: Definir o modo ventilatório**
	- Identificar a variável limite (ex: pressão no PCV/PSV, fluxo/volume no VCV).
- **Passo 3: Ajustar os alarmes**
	- Adequar os alarmes às variáveis que não controlamos no modo escolhido (ex: alarme de pressão no VCV, alarme de volume no PCV).
- **Passo 4: Análise MDC**
	- Avaliar Mecânica, Drive respiratório e Contexto clínico do paciente.

# Modos Ventilatórios: Ajustes e Características
## **PSV (Pressão de Suporte): Modo Limitado a Pressão e Ciclado a Fluxo**
### O fluxo é livre/variável (depende do paciente) e não há controle direto de FR ou relação I:E.
- **Volume Corrente gerado:** Depende da Pressão de Distensão (*Driving Pressure*, que é PSV - PEEP) somada ao esforço muscular do paciente.
	- Aumentar apenas a PEEP sem ajustar o PSV diminui a força motriz, reduzindo o volume corrente.
- **Mecanismo de Ciclagem (Transição Ins-Ex):**
	- Ocorre quando o fluxo inspiratório cai para um **percentual do pico de fluxo máximo** (Ciclagem Expiratória / E-Sens), geralmente 25%.
	- **NÃO** ocorre quando o fluxo atinge zero.
- **Como diminuir o Tempo Inspiratório (Ti) no modo PSV:**
	- **1. Diminuir a Pressão de Suporte:** Alvo menor é atingido mais rápido.
	- **2. Reduzir o *Rise Time* (Rampa/Slope):** Um tempo de rampa menor (ex: 0 ms) faz a pressão subir verticalmente, atingindo a meta mais rápido, encurtando o Ti.
	- **3. Aumentar o % da Ciclagem Expiratória (E-Sens):** Passar a ciclagem de 25% para 50% faz a válvula abrir mais cedo, encurtando a inspiração. *(Atenção: diminuir a ciclagem de 50% para 20% aumenta o tempo inspiratório)*.

## **Mecânica Comparativa: VCV x PCV**
### A Pressão Alveolar (Platô) depende exclusivamente de Volume e Complacência, não do modo escolhido.
- **Equação do Movimento:** `Pressão = (Fluxo x Resistência) + (Volume / Complacência) + PEEP`
- **Fórmula da Pressão Alveolar:** `P. Platô = (Volume / Complacência) + PEEP`
- **Troca de VCV para PCV (mantendo o mesmo Volume Corrente):**
	- A **Pressão Alveolar atingida será exatamente a mesma**, pois a complacência pulmonar e o volume administrado não mudaram.
- **Impacto do Fluxo Inspiratório (em VCV):**
	- Aumentar o fluxo aumenta o componente resistivo, o que **aumenta a Pressão de Pico**.
	- Aumentar o fluxo **NÃO** altera a Pressão Alveolar (Platô), pois esta depende apenas do elemento elástico.
- **Pico de Pressão:**
	- Geralmente é maior no VCV (devido ao fluxo quadrado mantendo a força resistiva até o final da inspiração) do que no PCV (que tem fluxo decrescente).

# Fisiologia Respiratória Aplicada à Clínica
## **Resistência Vascular Pulmonar (RVP) e Pós-Carga de Ventrículo Direito**
### A RVP possui um comportamento de curva em "U" em relação ao volume pulmonar (distensão).
- **Pulmão Colabado (Volume Residual):**
	- **RVP Alta.** Os alvéolos murchos não sustentam a arquitetura, colabando/comprimindo os vasos extra-alveolares.
	- **Recrutamento Alveolar:** Ao abrir esses alvéolos, a resistência extra-alveolar diminui, causando **queda** na RVP.
- **Pulmão Normodistendido (próximo à Capacidade Residual Funcional - CRF):**
	- É o ponto mais baixo da curva, onde a RVP é mínima. Objetivo da titulação ideal de PEEP.
- **Pulmão Hiperdistendido (Capacidade Pulmonar Total):**
	- **RVP Alta.** Alvéolos hiperinsuflados (ex: Volume Corrente alto e PEEP elevada) comprimem diretamente os capilares alveolares.
	- **Consequência hemodinâmica grave:** Aumento súbito da RVP com falência de VD e queda do Débito Cardíaco (*Cor Pulmonale* agudo).
- **Outros Fatores que Alteram a RVP (Tríade da Intubação Difícil):**
	- **Hipoxemia e Hipercapnia:** Causam vasoconstrição pulmonar hipóxica (aumentam RVP). A melhora da oxigenação promove queda da RVP.
	- **Tônus Simpático:** Aumenta a RVP por vasoconstrição direta. (A diminuição do tônus leva à queda da RVP).

## **Manejo da SDRA (Síndrome do Desconforto Respiratório Agudo)**
### Volume Corrente maior gera maior Pressão Alveolar; maior Driving Pressure aumenta a mortalidade.
- **Metas da Ventilação Protetora:**
	- Volume Corrente baixo (6 mL/kg de peso predito) para evitar excesso de pressão alveolar (volutrauma/barotrauma).
	- Pressão de Platô (Alveolar) < 30 cmH2O.
	- **Driving Pressure (Pressão de Distensão) < 15 cmH2O.** *Relação direta comprovada com sobrevida (maior driving pressure = maior mortalidade).*

# Análise Gráfica Avançada e Assincronias
## **Auto-PEEP (Retenção Aérea)**
### Identificação: Curva de fluxo expiratório se encerra precocemente antes de chegar ao zero absoluto.
- **Manejo da Auto-PEEP no paciente com DPOC em modo PSV:**
	- **Alvo fisiológico:** Fornecer mais tempo para a expiração (Te). Para isso, deve-se **diminuir o tempo inspiratório (Ti)**.
	- **Condutas no ventilador:**
		1.  **Diminuir a Pressão de Suporte:** Atinge o limite mais rápido, liberando a exalação precoce.
		2.  **Reduzir o Rise Time (Rampa):** Pressão sobe rápido (ex: 0 ms), encurtando a ins.
		3.  **Aumentar a Ciclagem (E-sens):** Mudar de 25% para 40-50% força a válvula a abrir mais cedo na queda do fluxo.

## **Índice de Pressão Muscular (PMI) / Avaliação de Esforço**
### Deflexão negativa profunda na curva de pressão durante pausa inspiratória indica esforço excessivo.
- **Interpretação da Pausa Inspiratória (Oclusão):**
	- Quando a válvula é ocluída no final da inspiração, oscilações que caem abruptamente abaixo do platô previsto refletem a Pressão Muscular (Pmus) transmitida pelo diafragma.
	- Um PMI > 5 cmH2O sugere que o paciente está com *esforço excessivo* (Drive alto), sendo um alerta crítico no processo de desmame.

## **Fuga Aérea (Vazamento no Sistema)**
### Na curva Fluxo-Volume (Loop), a perna expiratória não retorna ao eixo zero do volume.
- **Interpretação Gráfica:**
	- A curva de fluxo positivo (inspiração) cumpre seu trajeto, mas na fase negativa (expiração), o traçado é interrompido abruptamente cortando o eixo Y antes de fechar o loop no ponto zero.
- **Significado Clínico:**
	- O volume de ar entra, mas uma parte é perdida e não passa pelo sensor expiratório da máquina.
	- Causas comuns: Cuff do tubo endotraqueal desinsuflado, fístula broncopleural ou desconexão/furo no circuito.

# Capnografia na Parada Cardiorrespiratória (PCR)
## **ETCO2 é o padrão-ouro para confirmar via aérea e guiar a RCP.**
### Aplicações imediatas a beira-leito durante a PCR:
- **1. Confirmação do Tubo:** Curvas regulares e ETCO2 detectável a cada ventilação garantem posição endotraqueal. (Extubação acidental leva o ETCO2 a zero imediatamente).
- **2. Qualidade da Massagem Cardíaca:** Manter ETCO2 **> 10 a 15 mmHg** reflete débito cardíaco adequado gerado pelas compressões. Variações refletem a qualidade da compressão torácica.
- **3. Retorno da Circulação Espontânea (ROSC):** Elevação súbita e sustentada do ETCO2 (ex: salto de 15 para 40 mmHg) sinaliza o retorno do metabolismo e perfusão pulmonar.
- **4. Prognóstico:** Valores consistentemente < 10 mmHg após 20 minutos de RCP otimizada predizem altíssima mortalidade, embasando a decisão de cessar esforços.

----

Aqui está a base de conhecimento estruturada com foco em alto rendimento para a prática clínica e consulta rápida, utilizando o princípio da divulgação progressiva da informação.

# 🫁 Monitorização Ventilatória e Assincronias

## 🛑 Auto-PEEP (PEEP Intrínseca) e Resistência Aumentada
- **A Auto-PEEP ocorre por constante de tempo elevada (ex: DPOC/Asma) e é diagnosticada quando o fluxo expiratório não retorna a zero antes do próximo ciclo.**
	- Sinais gráficos associados:
		- Curva de fluxo expiratório truncada (não zera).
		- No modo PCV, pode ocorrer *overshoot* de entrada (pico inicial de pressão) e o fluxo inspiratório demora a cair, refletindo a alta resistência.
		- Curva de pressão ruidosa/rabiscada na inspiração e expiração sugere a presença de fluidos/secreção (necessidade de aspiração).
	- Consequências Hemodinâmicas e Mecânicas:
		- **Ventrículo Direito (VD):** O aumento da pressão intratorácica diminui o retorno venoso (↓ pré-carga do VD) e aumenta a resistência vascular pulmonar (↑ pós-carga do VD).
		- **Ventrículo Esquerdo (VE):** A disfunção do VD reduz o sangue que chega ao VE (↓ pré-carga do VE).
		- **Fadiga Muscular:** Exige alto esforço do paciente para negativar a pressão e conseguir disparar o ventilador. É a principal causa de **disparo ineficaz**.
	- ▶ Manejo da Auto-PEEP:
		- Aumentar o tempo expiratório (reduzindo a frequência respiratória ou aumentando o fluxo inspiratório).
		- **Não** aumentar volume corrente ou pressão de platô (piora o quadro).
		- Em DPOC: Adequar a PEEP extrínseca (cerca de 80% do valor da Auto-PEEP lida) para atuar como *stent* pneumático nas vias aéreas colapsadas, facilitando a exalação.

## 📉 Fome de Fluxo (Fluxo Insuficiente)
- **A fome de fluxo é caracterizada por uma concavidade ("barriga para baixo" / escavamento) na alça inspiratória da curva Pressão-Volume.**
	- Fisiopatologia: O paciente possui *drive* ativo e puxa o ar com uma velocidade/demanda maior do que a máquina está configurada para entregar.
	- Consequência: Pode gerar duplo disparo ou fluxo inspiratório contínuo, em que o paciente continua inspirando mesmo após a ciclagem do ventilador.
	- ▶ Manejo imediato: 
		- Aumentar o fluxo inspiratório (se em modo VCV) ou transitar para modo PCV/PSV para fornecer fluxo livre de acordo com a demanda.

## ⏱️ Ciclagem Tardia
- **Ocorre classicamente no DPOC em modo PSV, quando o fluxo inspiratório demora a atingir o critério de ciclagem, forçando o paciente a usar musculatura expiratória contra o ventilador ainda insuflando.**
	- Sinais no gráfico: Elevação abrupta (pico) da pressão no final da fase inspiratória.
	- ▶ Manejo imediato:
		- Aumentar o percentual do critério de ciclagem (ex: passar de 25% para 50%), encurtando o tempo inspiratório da máquina.
		- **Reduzir a Pressão de Suporte (PS):** Um delta de pressão menor atinge o pico de fluxo mais rápido, permitindo que a queda percentual para ciclagem aconteça precocemente.

## 🎈 Hiperdistensão e Alterações de Complacência
- **Na curva Pressão-Volume, alças mais verticalizadas indicam melhor complacência; o surgimento de "bico de pássaro" no limite superior indica hiperdistensão alveolar.**
	- Queda da Complacência (A "Bela Adormecida"):
		- A curva deita (fica mais horizontal). Ex: Edema Agudo de Pulmão (EAP), SDRA.
		- **No modo PCV:** A pressão nas vias aéreas não muda (já é controlada). O que cai é o volume corrente e o fluxo inspiratório. O alarme de pressão alta não é disparado.
	- Sinais de Hiperdistensão ("Bico de Pássaro"):
		- O volume não aumenta mais, porém a pressão sobe vertiginosamente.
		- **Stress Index > 1** (curva de pressão no tempo com convexidade superior).
		- **Consequências fisiológicas:** Compressão de capilares alveolares gera aumento da razão ventilatória (> 2) por aumento do espaço morto (gradiente elevado entre PaCO2 e EtCO2) e eleva o risco de Cor Pulmonale (hipertensão pulmonar).

## ⚠️ Disparo Ineficaz vs. Autodisparo
- **Autodisparo não requer esforço do paciente; Disparo Ineficaz ocorre quando o paciente faz esforço, mas a máquina não lê.**
	- Causas de Autodisparo: Vazamentos no circuito, oscilação por fluido/secreção, ou oscilações cardíacas (muito comum em pós-operatório de cirurgia cardíaca).
	- *Red Flag:* Auto-PEEP é a principal causa de **disparo ineficaz**, e NÃO de autodisparo.


# 🚨 Manejo de Vias Aéreas e Parada Cardiorrespiratória

## 📊 Capnografia (EtCO2) na PCR
- **A capnografia é o padrão-ouro para confirmar a posição do tubo, guiar a eficácia das compressões e definir o retorno da circulação espontânea (ROSC).**
	- Qualidade da RCP: EtCO2 > 10 a 15 mmHg indica compressões de alta qualidade.
	- Sinal de ROSC: Elevação súbita do EtCO2 (ex: salto abrupto para > 35 mmHg).
	- Fim de esforços: EtCO2 permanentemente < 10 mmHg após 20 a 30 minutos de RCP otimizada autoriza a interrupção das manobras por futilidade.
	- Fatores de confusão: O uso de epinefrina causa vasoconstrição pulmonar transitória, alterando a relação V/Q e, consequentemente, afetando momentaneamente a leitura do EtCO2.

## 🆘 Algoritmo de Via Aérea Falha
- **Diante de 2 tentativas frustradas de IOT com paciente evoluindo com hipoxemia, a conduta primária é tentar resgatar a ventilação com Dispositivo Supraglótico (Máscara Laríngea) ou Máscara Facial, e solicitar ajuda.**
	- *Red Flag (Cenário CICO):* A via aérea cirúrgica de emergência (cricotireostomia) no trauma com colar cervical apenas está indicada de forma imediata se houver caracterização de "Não Intubo e Não Ventilo" (CICO), após falha do resgate supraglótico/facial.


# 🧠 Doenças Neuromusculares na UTI

## 📏 Critérios de Intubação (Ex: Guillain-Barré, ELA)
- **Pacientes neuromusculares não devem aguardar hipoxemia para intubação eletiva; a decisão é baseada na deterioração da mecânica ventilatória (Regra do 20 / 30 / 40).**
	- Capacidade Vital (CV) < 20 mL/kg (Normal é 60-70 mL/kg).
	- Pressão Inspiratória Máxima (PImax) mais fraca (menos negativa) que -30 cmH2O.
	- Pressão Expiratória Máxima (PEmax) < 40 cmH2O.


# 🌬️ Suporte Respiratório Não Invasivo e SDRA

## 👃 Cateter Nasal de Alto Fluxo (CNAF)
- **O CNAF é a terapia de escolha (superior à VNI e ao O2 convencional) em pacientes com Insuficiência Respiratória Aguda Hipoxêmica Moderada (Relação P/F entre 100 e 200).**
	- Configurações e Benefícios:
		- Fornece gás aquecido e umidificado a um fluxo de até 60 L/min, com FiO2 de até 100%.
		- Gera pressão positiva expiratória final (efeito *PEEP-like*), especialmente se o paciente mantiver a boca fechada.
		- Reduz significativamente o trabalho muscular pulmonar e o *drive* respiratório.
		- Impacto Clínico: Em pacientes com P/F < 200, altera desfechos e reduz necessidade de intubação.
	- Limitações / Contraindicações relativas:
		- Em DPOC descompensado, a VNI (BiPAP) ainda é a primeira linha inquestionável.
		- Em SDRA grave (P/F < 100), o uso de CNAF tem altíssima taxa de falha; a IOT não deve ser postergada.

## 🛌 Posição Prona na SDRA
- **Além de melhorar a oxigenação, o principal ganho hemodinâmico e mecânico extrapulmonar da posição prona é a melhora da função do Ventrículo Direito (VD).**
	- Mecanismo protetor do VD: A SDRA impõe alto estresse ao VD por hipoxemia, hipercapnia e altas pressões de vias aéreas (*Cor Pulmonale* agudo). A prona reverte a vasoconstrição hipóxica e desobstrui leitos capilares, diminuindo drasticamente a pós-carga do VD.
	- Mecânica Pulmonar: Melhora a relação V/Q homogeneizando a ventilação para as zonas dorsais dependentes (mais bem perfundidas).
	- O que NÃO ocorre: A prona não aumenta a complacência da caixa torácica (o paciente fica apoiado sobre o tórax, podendo até reduzi-la levemente) e tende a aumentar (ou não alterar) a pressão intra-abdominal.

----

