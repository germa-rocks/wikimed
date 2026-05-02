---
publish: true
---



# Monitorização Hemodinâmica Invasiva na UTI

## Princípios Fundamentais e Indicações Clínicas
- **A invasividade da monitorização deve ser diretamente e estritamente proporcional à gravidade do paciente.**
	- Pacientes estáveis ou com choque inicial e responsivo requerem métodos não invasivos.
	- Pacientes em choque refratário ou com síndromes complexas exigem métodos avançados/invasivos.
- **O exame físico e marcadores laboratoriais continuam sendo a triagem inicial padrão-ouro.**
	- Avaliação de perfusão periférica (Tempo de Enchimento Capilar - TEC), Lactato e Gap de CO2 guiam as intervenções precoces com a mesma eficácia de métodos avançados na fase inicial (validado pelo estudo *Andromeda Shock*).

## Pressão Arterial: PANI vs. PAI
### Pressão Arterial Não Invasiva (PANI)
- **A PANI oscilométrica mede diretamente apenas a Pressão Arterial Média (PAM).**
	- PAS e PAD são valores derivados por algoritmos do monitor, tornando a PAM o parâmetro mais fidedigno para guiar condutas à beira-leito.
- **A PANI perde severamente a acurácia em estados de choque grave e uso de altas doses de drogas vasoativas (DVA).**
	- O método tende a superestimar pressões muito baixas e subestimar pressões muito altas.
		- *Red Flag:* Esta discrepância tem margem de erro que afeta até 1/3 dos casos, podendo causar retardo no desmame ou atraso no escalonamento de DVAs.

### Pressão Arterial Invasiva (PAI)
- **A PAI está indicada sempre que houver uso crescente de DVAs, vasodilatadores potentes (ex: Nipride) ou metas neurológicas estritas.**
	- Funciona por sistema mecânico de vasos comunicantes, onde o transdutor reflete a pressão arterial convertendo-a em uma curva de pulso no monitor.
- **A validação da curva através do *Square Wave Test* (Teste da Curva Quadrada/Flush) é obrigatória antes de tomar decisões clínicas.**
	- O teste normal (flush flush) gera uma ascensão retangular imediata seguida de um "repique" (incisura dicrótica) e estabilização na linha de base.
	- ▶ **Sistema Amortecido (Damped):** Curva perde a morfologia e fica "achatada".
		- *Causas:* Obstrução do sistema, coágulos, cateter dobrado ou bolhas de ar.
		- *Impacto Hemodinâmico:* Subestima a PAS e superestima a PAD. A PAM geralmente se mantém próxima do real.
	- ▶ **Sistema Subamortecido (Underdamping):** Curva pontiaguda e hiper-ressonante.
		- *Causas:* Cateter excessivamente curto ou excesso de tubos extensores no circuito.
		- *Impacto Hemodinâmico:* Superestima gravemente a PAS. Pode mimetizar morfologia de insuficiência aórtica falsamente no monitor.

## Monitorização do Débito Cardíaco (DC)
### Indicações de Avaliação do DC
- **Sempre aferir o DC na presença de dúvida diagnóstica, manejo volêmico complexo ou choque refratário/misto.**

### Métodos Não Invasivos
- **O Ecocardiograma Point-of-Care (POCUS) é a ferramenta de primeira escolha na UTI para avaliação hemodinâmica inicial.**
	- Permite medição indireta e não invasiva do DC através do cálculo do *Velocity Time Integral* (VTI).
	- Fornece avaliação morfológica rápida e global: função biventricular, status volêmico (tamponamento), disfunção de VD (ex: Cor Pulmonale/TEP) e congestão (linhas B pulmonares).
		- *Atenção:* É um exame operador-dependente e restrito pela qualidade da janela acústica do paciente.

### Métodos Minimamente Invasivos (Análise de Contorno de Pulso NÃO Calibrada)
- **Dispositivos não calibrados (ex: Vigileo, Lidco Rapid) são contraindicados para guiar débito cardíaco em pacientes com choque instável em UTI.**
	- Estes dispositivos estimam o DC baseados na área sob a curva da PAI (Cálculo: Pressão de Pulso × Complacência Vascular).
		- *Fisiopatologia da Falha:* O algoritmo matemático pressupõe que a complacência vascular do paciente é constante. Em pacientes sépticos ou sob titulação contínua de noradrenalina, o tônus vascular muda minuto a minuto, invalidando a estimativa do DC.

### Métodos Menos Invasivos (Análise de Contorno de Pulso CALIBRADA)
- **O sistema calibrado (ex: PiCCO, VolumeView) é a escolha para pacientes com SARA e choques onde a análise de água pulmonar define a conduta.**
	- Exigem acesso venoso central associado a um cateter arterial específico (geralmente femoral).
	- Utilizam termodiluição transpulmonar (injeção de soro gelado) ou lítio para obter o Débito Cardíaco basal real.
		- *Manejo Prático:* O valor basal real "calibra" a curva de pulso. Se a noradrenalina for aumentada e o tônus vascular mudar, basta o médico injetar novo bolus de soro gelado (recalibração) para corrigir o algoritmo.
		- *Pérolas do PiCCO:* É o único método que fornece a Água Extravascular Pulmonar (EVLW) e o Índice de Permeabilidade Vascular (PVPI). Isso diferencia com precisão a SDRA (edema por permeabilidade capilar) da congestão cardiogênica clássica (edema hidrostático).

### Métodos Invasivos (Cateter de Artéria Pulmonar / Swan-Ganz)
- **O Swan-Ganz é o padrão-ouro hemodinâmico, porém seu uso é estritamente restrito a subgrupos específicos.**
	- Indicações clássicas atuais: Choque cardiogênico refratário, falência aguda de Ventrículo Direito, hipertensão pulmonar primária e choques mistos com dissociação clínico-hemodinâmica grave.
		- *Red Flag:* Não deve ser usado como rotina geral na UTI, pois não provou benefício de sobrevida global em populações não selecionadas.
	- Parâmetros fornecidos de forma contínua ou direta:
		- Pressão de Átrio Direito (PVC).
		- Pressão de Ventrículo Direito.
		- Pressão de Artéria Pulmonar (PAP).
		- Pressão de Oclusão da Artéria Pulmonar (POAP / Capilar Pulmonar / Wedge) — reflete diretamente a pressão do Átrio Esquerdo.
		- Saturação Venosa Mista verdadeira (SvO2).
		- DC contínuo por termodiluição padrão.

## Algoritmo Prático: Abordagem Progressiva (Stepwise)
- **A invasão hemodinâmica deve seguir uma progressão de 4 etapas, baseada na refratariedade do quadro (Consenso ICM 2014).**
	- ▶ **Passo 1: Choque Inicial**
		- Guiar por Exame Físico (TEC) + Lactato/Gap CO2 + PANI. Instalar PAI se houver necessidade de ascensão de DVA.
	- ▶ **Passo 2: Choque Refratário ou Dúvida Diagnóstica**
		- Beira-leito imediato com POCUS (Eco).
	- ▶ **Passo 3: Dúvida Volêmica Complexa / Edema Pulmonar / SARA**
		- Instalar sistema de Termodiluição Transpulmonar Calibrada (PiCCO / LiDCO Plus).
	- ▶ **Passo 4: Choque Cardiogênico Grave / Falência de VD Isolada**
		- Instalar Cateter de Artéria Pulmonar (Swan-Ganz).
	- 🚫 **Nunca Fazer:** Basear tomada de decisão hemodinâmica de fluidos e inotrópicos usando contorno de pulso não calibrado em pacientes com choque vasoplégico ou instabilidade de DVA.