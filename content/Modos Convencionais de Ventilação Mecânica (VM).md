---
publish: true
---

***

# Modos Convencionais de Ventilação Mecânica (VM)

## Princípios Básicos e Interação Paciente-Ventilador
- **A Ventilação Mecânica (VM) atua aplicando pressão positiva às vias aéreas para sobrepujar a resistência e a complacência do sistema respiratório.**
	- **Indicações clássicas:** SARA, pneumonias graves, ICC, DPOC, e pacientes neurológicos (perda de *drive* respiratório ou incapacidade de proteger via aérea).
	- **Equação do Movimento (A regra de ouro da mecânica):** A Pressão Motora total gerada é a soma do esforço contra a resistência + esforço contra a complacência.
		- `Pressão Motora = (Fluxo x Resistência) + (Volume Corrente / Complacência)`

- **Uma "respiração" no ventilador é obrigatoriamente um ciclo de fluxo positivo seguido por fluxo negativo.**
	- **Fase Inspiratória (Ativa):** Máquina aplica pressão (deflexão positiva na curva de fluxo).
	- **Fase Expiratória (Passiva):** Energia potencial elástica do pulmão/tórax retrai o sistema (deflexão negativa na curva de fluxo).
	- **O ciclo respiratório possui 4 fases cronológicas:**
		1. **Disparo:** Fim da expiração e abertura da válvula inspiratória.
		2. **Fase Inspiratória:** Gás flui até atingir metas predefinidas.
		3. **Ciclagem:** Transição (fechamento válvula inspiratória, abertura válvula expiratória).
		4. **Fase Expiratória:** Exalação passiva.

- **O Disparo (início do ciclo) define quem "manda" na ventilação naquele momento: a máquina ou o paciente.**
	- **Disparo a Tempo (Ciclo Controlado):** Inicia independentemente do esforço do paciente. Definido estritamente pela Frequência Respiratória (FR) ajustada na máquina.
	- **Disparo por Sensibilidade (Ciclo Assistido/Espontâneo):** O paciente inicia o esforço.
		- **Sensibilidade a Pressão:** Esforço muscular gera leve queda de pressão no circuito detectada pela máquina.
		- **Sensibilidade a Fluxo:** Esforço gera flutuação no fluxo basal contínuo (*flow bias*) do circuito.

- **As incursões respiratórias dividem-se em 3 categorias clínicas:**
	- **Controlada:** Máquina determina o disparo e a ciclagem. Paciente passivo.
	- **Assistida:** Paciente determina o disparo (esforço inicial); Máquina determina a ciclagem.
	- **Espontânea:** Paciente determina o disparo e a ciclagem.

---

## Avaliação de Mecânica Pulmonar à Beira-Leito (Modo VCV)
- **A pausa inspiratória no modo de Volume Controlado (fluxo constante) é essencial para calcular Resistência, Complacência e Driving Pressure.**
	- **Mecânica da pausa:** Oclusão do circuito ao final da inspiração (método EIOM). O fluxo zera, anulando as forças resistivas.
	- **Interpretação das Pressões:**
		- **Pressão de Pico:** Reflete a superação da Resistência das vias aéreas + Complacência do sistema.
		- **Pressão de Pausa (Platô / Palv):** Reflete apenas a força elástica (Complacência).
	- **Fórmulas e Cálculos na Prática:**
		- **Pressão Resistiva** = `Pressão de Pico - Pressão de Pausa`
		- **Resistência de Vias Aéreas (Rva)** = `Pressão Resistiva / Fluxo em L/s`
		- **Pressão Elástica (Driving Pressure / Pel)** = `Pressão de Pausa - PEEP`
		- **Complacência do Sistema Respiratório (Crs)** = `Volume Corrente / Pressão Elástica`
	- **Utilidade clínica:** Avaliar resposta a broncodilatadores (queda da Rva) ou posição prona/recrutamento (aumento da Crs).

---

## Modos Ventilatórios Básicos: Ajustes e Red Flags

### Ventilação Controlada a Volume (VCV)
- **Garante entrega de um Volume Corrente fixo a cada ciclo, independentemente da mecânica pulmonar do paciente.**
	- **Características do Gráfico:** Fluxo quadrado/constante. Pressão de vias aéreas sobe de forma linear oblíqua.
	- **Ajustes:** Volume Corrente (VT), FR, Fluxo Inspiratório, PEEP, FiO2, Relação I:E.
	- **Vantagem:** Evita hipoventilação se houver mudança de mecânica. Essencial para estabilidade inicial e avaliação mecânica.
	- **🚨 Red Flags e Desvantagens:**
		- **Barotrauma:** Se a complacência piorar (ex: pneumotórax, piora da SARA), o ventilador fará pressões perigosamente altas para entregar o volume.
		- **Manejo:** Obriga ajuste rigoroso do Alarme de Pressão de Pico (a máquina aborta a entrega de volume se atingir o limite para evitar ruptura).

### Ventilação Assistida Controlada (ACV)
- **Modo híbrido onde o paciente pode disparar ciclos extras, mas a máquina garante o suporte (volume ou pressão) programado.**
	- **Dinâmica Clínica:** Intercala ciclos controlados (se o paciente não tiver *drive*) com ciclos assistidos (se o paciente tiver *drive*). Em ambos, o perfil de entrega (volume ou pressão) é o mesmo.
	- **Vantagem:** Evita atrofia muscular por permitir respiração espontânea. Pode exigir menos sedação profunda/bloqueio neuromuscular.
	- **🚨 Red Flags e Desvantagens:**
		- **Auto-PEEP:** Se o paciente ficar taquipneico, dispara muitos ciclos sucessivos, reduzindo o tempo expiratório e aprisionando ar.
		- **Hipo/Hiperventilação:** Depende da adaptação do *drive* neural do paciente aos ajustes da máquina.

### Ventilação Controlada a Pressão (PCV)
- **Garante uma Pressão Inspiratória fixa (platô), mas o Volume Corrente entregue varia conforme a mecânica do paciente.**
	- **Características do Gráfico:** Pressão assume onda quadrada (constante). O fluxo assume perfil decrescente ao longo do tempo. Disparo e ciclagem ocorrem a tempo.
	- **Ajustes:** Pressão Inspiratória, FR, PEEP, FiO2, Relação I:E.
	- **Vantagem:** Pressão limitada é mais segura para proteger o pulmão (reduz risco de barotrauma). Modo de escolha em doenças obstrutivas graves e doença heterogênea.
	- **🚨 Red Flags e Desvantagens:**
		- **Variabilidade do Volume Corrente:** Quedas na complacência ou aumento de resistência reduzem drasticamente o volume entregue.
		- **Manejo:** Obriga ajuste rigoroso dos Alarmes de Volume-Minuto (Mínimo e Máximo) para detectar hipo ou hiperventilação precocemente.

### Ventilação com Pressão de Suporte (PSV)
- **Modo totalmente Espontâneo: O paciente controla o Disparo e a Ciclagem, recebendo um suporte de pressão para diminuir o trabalho respiratório.**
	- **Dinâmica de Ciclagem (A Regra do Fluxo):** A máquina encerra o ciclo quando o fluxo inspiratório decrescente cai até uma porcentagem estipulada do pico de fluxo (geralmente ajustável de 10% a 70%).
		- Ajustar para uma % mais alta corta a inspiração mais cedo.
	- **Rise Time (Aceleração de Fluxo):** Ajuste de quão rápido a máquina atinge a pressão estipulada. Adapta-se ao "tempo neural" do paciente (acelerado ou lentificado).
	- **Vantagens:** Excelente conforto, sincronia, manutenção de massa muscular. Modo padrão para desmame ventilatório.
	- **🚨 Red Flags e Desvantagens:**
		- **Risco de Apneia:** Se o paciente aprofundar sedação ou perder *drive*, não haverá ventilação. Requer "modo backup" configurado (alarmes de apneia curtos).

### CPAP (Continuous Positive Airway Pressure)
- **Manutenção de via aérea continuamente pressurizada em paciente 100% espontâneo. Não há fornecimento de suporte inspiratório adicional.**
	- **Características do Gráfico:** Curva de Pressão forma uma linha reta basal na PEEP estipulada. Fluxo senoidal (natural do paciente).
	- **Vantagem:** Aumenta a Capacidade Residual Funcional (CRF) e melhora a oxigenação. Sem risco de atrofia.
	- **🚨 Red Flags e Desvantagens:**
		- **Não descansa o músculo:** Todo o trabalho ventilatório contra as forças resistivas e elásticas é feito pelo paciente.
		- **Contraindicação:** Pacientes fadigados, uso de sedativos potentes, ou instabilidade de *drive*.

---

## Taxonomia Moderna: Entendendo a "Sequência da Respiração"
- **O Modo Ventilatório é a soma de: Variável de Controle + Sequência da Respiração + Esquema de Alvo.**
	- **Ventilação Mandatória Contínua (VMC - Modos Assisto-Controlados):** Nenhuma respiração puramente espontânea é possível. Todo disparo resulta em uma inspiração ciclada pela máquina.
	- **Ventilação Mandatória Intermitente (VMI - Modos SIMV):** O ventilador entrega ciclos mandatórios sincronizados em frequência fixa, mas permite ao paciente realizar ciclos puramente espontâneos menores entre eles.
	- **Ventilação Espontânea Contínua (VEC - PSV / CPAP):** Todas as incursões são disparadas e cicladas pelo paciente.

---

## Reconhecimento Gráfico Instantâneo (Diagnóstico Visual)
- **Como identificar o esforço do paciente (Ciclo Assistido vs Controlado)?**
	- Olhe para a Curva de Pressão (ou Pmus, se disponível): Uma pequena deflexão "para baixo" (negativa) imediatamente antes da fase inspiratória confirma que o paciente "puxou" o ar e disparou a máquina.
- **Como identificar VCV (Volume Controlado)?**
	- **Fluxo:** Onda quadrada e constante ao longo de toda a inspiração.
	- **Volume:** Ascensão linear ("em triângulo").
- **Como identificar PCV (Pressão Controlada) ou PSV?**
	- **Pressão:** Sobe rápido e forma um platô retangular perfeito durante toda a inspiração.
	- **Fluxo:** É sempre decrescente.
	- **Como diferenciar PCV de PSV graficamente:** Em PSV, a ciclagem do fluxo é cortada abruptamente acima de zero (pelo critério % do pico), e haverá evidência de deflexão negativa (esforço paciente) em 100% dos ciclos.