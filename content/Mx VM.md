---
publish: true
---
# 🩺 Monitorização da Ventilação Mecânica (VMI)

## 📋 Fundamentos e Mecânica Respiratória
- **A VMI deve equilibrar a troca gasosa adequada com a prevenção de lesão pulmonar (VILI) e muscular (VIDD).**
	- **Equação do Movimento:** Define a relação entre as pressões aplicadas e a resposta do sistema.
		- $P_{total} = P_{vent} + P_{mus} = P_{el} + P_{res} + PEEP_{total}$
		- **Componente Elástico ($P_{el}$):** Depende da Elastância ($E_{sr}$) e Volume Corrente ($VC$).
		- **Componente Resistivo ($P_{res}$):** Depende da Resistência ($R_{va}$) e do Fluxo ($\dot{V}$).
- **Monitorização em Ventilação Controlada (Sem esforço do paciente):**
	- **Pausa Inspiratória:** Manobra essencial para dissociar os componentes da equação do movimento.
		- **Pressão de Pico ($P_{pico}$):** Reflete a resistência total (vias aéreas + parênquima).
		- **Pressão de Platô ($P_{platô}$):** Reflete a pressão alveolar ao final da inspiração (equilíbrio estático).
		- **Pressão Resistiva ($P_{res}$):** $P_{pico} - P_{platô}$.
	- **Complacência Estática ($C_{sr}$):** Reflete a capacidade de deformação do sistema.
		- Cálculo: $VC / (P_{platô} - PEEP)$.
	- **Driving Pressure ($\Delta P$):** Principal marcador de risco para VILI.
		- Cálculo: $P_{platô} - PEEP$.
		- **Alvo Clínico:** Manter $\le 15 \text{ cmH}_2\text{O}$ na fase aguda.

## 🫁 Pressão Transpulmonar ($P_L$) e Manometria Esofágica
- **A $P_L$ isola o estresse no parênquima pulmonar, subtraindo a influência da caixa torácica.**
	- **Conceito:** Diferença entre a pressão na via aérea e a pressão pleural ($P_{pl}$), estimada via pressão esofágica ($P_{es}$).
	- **Cálculo:** $P_L = P_{via \ aérea} - P_{es}$
- **Alvos de Segurança para Proteção Pulmonar:**
	- **Fase Expiratória (Prevenção de Atelectasia/Colapso):**
		- Manter $P_{L \text{ expiração}} = PEEP - P_{es \text{ final expiração}}$ entre **0 e +2 cmH₂O**.
	- **Fase Inspiratória (Prevenção de Hiperdistensão):**
		- Manter $P_{L \text{ inspiração}} < 20 \text{ a } 25 \text{ cmH}_2\text{O}$.
	- **Variação da Pressão Transpulmonar ($\Delta P_L$):**
		- Reflete o estresse dinâmico no parênquima.
		- **Alvo Clínico:** $\Delta P_L \le 12 \text{ cmH}_2\text{O}$.

## 💪 Avaliação do Esforço Inspiratório e Drive Respiratório
- **O esforço excessivo causa lesão autoinfligida (P-SILI); o esforço insuficiente causa atrofia (VIDD).**
	- **Pressão Muscular ($P_{mus}$):** Medida global do esforço (diafragma + acessórios).
		- **Alvo Clínico:** Manter entre **5 e 10 cmH₂O**.
- **Técnicas de Estimativa (Alternativas ao Cateter Esofágico):**
	- **Pressão de Oclusão da Via Aérea ($\Delta P_{occ}$):** Realizada durante pausa expiratória.
		- Estimativa de $P_{mus} \approx -3/4 \times \Delta P_{occ}$.
		- Estimativa de $\Delta P_{L \text{ dinâmica}} \approx -2/3 \times \Delta P_{occ} - (P_{pico} - PEEP)$.
	- **Índice de Pressão Muscular (PMI):** Realizado durante pausa inspiratória.
		- Cálculo: $P_{platô} - P_{pico}$.
		- Interpretação: Se $P_{platô} > P_{pico}$, há esforço inspiratório significativo. **Alvo: 5-10 cmH₂O**.
	- **P0.1 (Drive Respiratório):** Queda de pressão nos primeiros 100ms de oclusão.
		- **Alvo Clínico:** **1 a 4 cmH₂O**. (Valores > 4 sugerem drive excessivo).
- **Ultrassonografia Diafragmática (Beira-leito):**
	- **Fração de Espessamento ($TF_{di}$):** Avalia o esforço muscular de forma direta.
		- **Alvo Clínico:** **15% a 40%**.
		- **Sucesso no Desmame (TRE):** $TF_{di} > 30\%$ e deslocamento $> 10 \text{ mm}$.
		- 📎 Refs: 6, 12, 13.

## ⚠️ Assincronias Paciente-Ventilador
- **Incidência > 10% dos ciclos está associada a piores desfechos e maior mortalidade.**
- **Tipos e Identificação Visual:**
	- **Ciclagem Precoce:** O ventilador encerra a inspiração antes do paciente terminar o esforço.
		- *Sinal:* Deflexão negativa na pressão durante a fase expiratória inicial.
	- **Ciclagem Tardia:** O ventilador continua insuflando após o paciente iniciar a expiração.
		- *Sinal:* Pico súbito de pressão (*overshoot*) no final da fase inspiratória.
	- **Duplo Disparo:** Dois ciclos seguidos para um único esforço do paciente.
		- *Risco:* Gera volumes correntes somados (alto risco de VILI).
	- **Disparo Reverso:** Ciclo controlado da máquina gatilha uma contração reflexa do diafragma.
		- *Sinal:* Frequentemente evolui para duplo disparo.
	- **Esforço Ineficaz:** O paciente tenta respirar, mas o esforço não atinge o limiar para disparar o ventilador.
		- *Sinal:* Pequena queda na pressão da via aérea sem fluxo subsequente.
	- **Autodisparo:** O ventilador dispara sem esforço do paciente (ex: vazamentos ou oscilações no circuito).
		- *Sinal:* Ciclo assistido sem deflexão negativa prévia na $P_{va}$ ou $P_{es}$.

## 🎯 Resumo de Alvos para Proteção (Beira-Leito)

### ⏹️ Modo Controlado
- **$\Delta P_{va}$ (Driving Pressure):** $\le 15 \text{ cmH}_2\text{O}$
- **$P_{platô}$:** $\le 30 \text{ cmH}_2\text{O}$
- **Volume Corrente:** $4-8 \text{ mL/kg}$ (Peso Predito)
- **$P_{L \text{ expiração}}$:** $0 \text{ a } +2 \text{ cmH}_2\text{O}$
- **$\Delta P_L$ (Estresse):** $10-12 \text{ cmH}_2\text{O}$

### ⏯️ Modo Assistido (Esforço)
- **$P_{mus}$ ou $P_{mus \text{ estimada}}$:** $5-10 \text{ cmH}_2\text{O}$
- **PMI:** $5-10 \text{ cmH}_2\text{O}$
- **P0.1 (Drive):** $1-4 \text{ cmH}_2\text{O}$
- **$\Delta P_{L \text{ dinâmica}}$:** $< 15-20 \text{ cmH}_2\text{O}$
- **$TF_{di}$ (Ultrassom):** $15\%-40\%$