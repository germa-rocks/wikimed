---
publish: true
---



# Monitorização de Débito Cardíaco Minimamente Invasiva

## Racional Clínico e Fisiopatologia Básica
- **A monitorização hemodinâmica não reduz mortalidade por si só; ela funciona como um "Waze" clínico para guiar intervenções e reavaliações.**
	- Indicação principal: Avaliação de pacientes em choque que não respondem à terapêutica inicial (expansão volêmica, baixas doses de vasopressores) com persistência de sinais de má perfusão (ex: lactato elevado, oligúria, enchimento capilar alentecido).
	- Princípios da variável hemodinâmica ideal: Deve ser objetiva (sem variabilidade interpessoal), mensurável (quantificável numericamente) e reprodutível ao longo do tempo.
	- *Red Flag Clínica:* Obter o dado hemodinâmico e não intervir (ou não ter um protocolo de ação atrelado) anula completamente o benefício do uso do monitor.

- **O choque circulatório é definido pela Disóxia (desbalanço agudo entre a oferta e o consumo de oxigênio celular).**
	- Meta terapêutica: Restaurar a Oferta de Oxigênio (DO2) para suprir a Demanda (VO2).
	- Fisiologia do Fornecimento (DO2): `DO2 = CaO2 x Débito Cardíaco (DC)`
		- **Conteúdo Arterial de O2 (CaO2):** Definido primariamente por Hemoglobina e Saturação de O2. `CaO2 = (1,34 x Hb x SaO2) + (0.0031 x PaO2)`. Na prática, foca-se em manter SatO2 > 90% e níveis de Hb toleráveis.
		- **Débito Cardíaco (DC):** É a variável de maior manipulação na beira-leito para otimizar o choque.
			- *Pré-carga:* Manipulada com expansão volêmica.
			- *Contratilidade:* Manipulada com inotrópicos (Dobutamina, Milrinona/Amrinona).
			- *Pós-carga:* Manipulada com vasopressores (Noradrenalina, Adrenalina) ou vasodilatadores (Nitroprussiato).

## Mensuração do Débito Cardíaco: Do Padrão-Ouro ao Minimamente Invasivo
- **A mensuração de referência do Débito Cardíaco baseia-se no Princípio de Fick através da Termodiluição.**
	- Mecanismo: Injeção de um marcador (bolus de soro gelado) que percorre o fluxo sanguíneo até ser lido por um sensor de temperatura à distância. 
	- Interpretação da Curva de Termodiluição: O Débito Cardíaco é **inversamente proporcional** à área sob a curva térmica.
		- Curva pequena/passagem rápida do marcador = Alto fluxo = Débito Cardíaco Alto.
		- Curva grande/demorada = Baixo fluxo = Débito Cardíaco Baixo.
	- Limitações do método: Requer alta invasividade, como o Cateter de Artéria Pulmonar (Swan-Ganz) ou um cateter arterial femoral/central específico (termodiluição transpulmonar).

- **A Monitorização Minimamente Invasiva utiliza a Linha Arterial (PAI) pré-existente para calcular o DC através da "Análise de Contorno de Pulso".**
	- Mecanismo fisiológico: O formato, a área sob a curva da fase sistólica e a incisura dicrótica do traçado da PAI refletem o Volume Sistólico (Stroke Volume).
	- Desafio algorítmico: A curva da PAI deforma-se não apenas por variações de volume sistólico, mas também por flutuações na Resistência Vascular Sistêmica (RVS) e na Complacência arterial (ex: entrada de dose alta de vasopressor).
	- Solução tecnológica: Para diferenciar o que é variação de volume sistólico do que é variação de tônus vascular, os monitores exigem **Calibração**.

## O Calcanhar de Aquiles: Calibração dos Dispositivos
- **Dispositivos com Calibração Externa são mais precisos em pacientes com grande instabilidade do tônus vascular (choque vasoplégico grave/séptico).**
	- Como funciona: O monitor analisa continuamente o contorno do pulso, mas exige que o médico faça injeções periódicas de um marcador para "ensinar" ao algoritmo qual é o DC real naquele exato nível de tônus vascular.
	- Dispositivos e marcadores utilizados:
		- PiCCO® e VolumeView®: Utilizam injeção de soro gelado central e leitura por termodiluição transpulmonar (sensor na aorta descendente/artéria femoral).
		- LiDCOplus®: Utiliza injeção em bolus de Lítio (dispensa cateter femoral específico, usa veia periférica/central e a própria linha arterial radial).

- **Dispositivos com Calibração Interna (Auto-calibrados) não exigem injeções, são 100% focados no algoritmo matemático e ideais para avaliar Tendência Temporal.**
	- Como funciona: O software ajusta a curva baseando-se em dados biométricos demográficos (Idade, Peso, Altura, Sexo) para inferir a complacência aórtica média.
	- Dispositivos comuns: Flotrac/Vigileo® (Edwards), ProAQT/Pulsioflex® (PiCCO), LiDCOrapid®.
	- ▶ *Pérola Clínica:* A Tendência Temporal é superior ao valor absoluto.
		- Como o aparelho infere a complacência por dados populacionais, o DC absoluto (ex: 4.0 L/min) pode carregar uma margem de erro. 
		- O valor real da ferramenta é acompanhar a **Tendência Temporal**. Se após um *fluid challenge* (prova de volume) o DC subir rapidamente para 5.5 L/min no monitor, a tendência garante que o paciente é responsivo a fluidos, independentemente se o número base exato era 4.0 ou 4.2.

## Evidências Clínicas e Desfechos (UTI vs. Centro Cirúrgico)
- **O uso destas ferramentas melhora drasticamente a sobrevida e desfechos no Perioperatório de alto risco, mas frequentemente falha nos estudos de UTI por inércia médica.**
	- Cenário Cirúrgico (Perioperatório): A Terapia Guiada por Metas (*Goal-Directed Therapy*) baseada na PAI e análise de pulso reduz uso desnecessário de catecolaminas, complicações orgânicas e tempo de internação. A intervenção é imediata frente à variação temporal.
	- Cenário de UTI: Ensaios clínicos demonstram que apenas instalar a monitorização minimamente invasiva não reduz mortalidade ou tempo de estabilização do choque.
	- *Por que falha na UTI?* Falha comportamental. A presença do dado na tela não se traduz em mudança de conduta terapêutica pelos intensivistas plantonistas. O dispositivo não trata a doença celular; ele exige que o médico utilize o dado para otimizar os determinantes do DO2 de forma ativa e protocolar.