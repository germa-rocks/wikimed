---
publish: true
---
Aqui está a estruturação de alto rendimento baseada nos princípios de divulgação progressiva, otimizada para o Notion, Obsidian ou Anki. O conteúdo foi rigorosamente hierarquizado para uso a beira-leito.

# Ventilação Mecânica: Interpretação de Curvas e Modos Básicos

- **Ajustes Universais Pós-Intubação (Fase Aguda): FiO2 e PEEP são ajustados independentemente do modo ventilatório escolhido.**
	- **Fração Inspirada de Oxigênio (FiO2):** Iniciar sempre a 100% imediatamente após a intubação (paciente instável, sob bloqueador neuromuscular).
		- **Desmame da FiO2:** Após estabilização, titular para baixo mantendo alvo de Saturação Periférica (SpO2).
		- **Alvos:** > 92% em pacientes gerais; > 88% em pacientes com SARA (Síndrome de Angústia Respiratória do Adulto).
	- **PEEP (Pressão Expiratória Final Positiva):** Impede o colapso alveolar (atelectrauma) na expiração e melhora a oxigenação através do recrutamento/manutenção de unidades alveolares abertas.

---

## 1. Modo Volume Controlado (VC-AC)
- **Modo limitado a fluxo e ciclado a volume. A Pressão é a variável livre (dependente da mecânica do paciente).**
	- **Parâmetros Setados pelo Médico (Variáveis Independentes):**
		- **Volume Corrente (Vt):** É o alvo rígido da ciclagem. 
			- **Ajuste beira-leito:** 6 a 8 mL/kg do **Peso Corporal Predito** (calculado pela altura do paciente).
			- **Red Flag:** O pulmão não engorda! Nunca calcule o Vt pelo peso real em pacientes com obesidade.
		- **Fluxo Inspiratório:** Determina a velocidade de entrada do ar e afeta diretamente o Tempo Inspiratório (Ti). Ex: Fluxo de 60 L/min = 1 L/seg. Para entregar 300 mL (0,3 L), o Ti será de 0,3 segundos.
			- **Manejo do Fluxo:** Se aumentar o fluxo, o Ti reduz. Se reduzir o fluxo, o paciente precisará de mais tempo para receber o mesmo volume.
		- **Frequência Respiratória (FR):** Modo Assistido-Controlado garante uma FR mínima (ex: 20 irpm = 1 ciclo a cada 3 segundos), mas permite que o paciente faça *triggers* (disparos) adicionais assistidos.
	- **Análise das Curvas no Ventilador (A História do Ciclo no VC-AC):**
		- **Curva de Fluxo (Gráfico Central): Padrão de Onda Quadrada (Fluxo Constante).**
			- Fisiologia: O fluxo sobe rapidamente até o limite ajustado (ex: 60 L/min) e se mantém numa linha reta horizontal. Ao atingir o volume setado, cai abruptamente para zero. A fase expiratória apresenta curva negativa decaindo à linha de base.
		- **Curva de Volume (Gráfico Inferior): Padrão de "Barbatana de Tubarão" (Constante).**
			- Fisiologia: Ascende gradativamente a partir do zero até o pico exato do Volume Corrente ajustado. Desce simetricamente na expiração. O pico é rigorosamente o mesmo em todos os ciclos.
		- **Curva de Pressão (Gráfico Superior): Padrão Variável e Ascendente.**
			- Fisiologia: Parte do valor da PEEP (linha de base não é zero). Sobe de forma ascendente até a **Pressão de Pico** (pressão máxima para vencer resistência das vias aéreas e complacência pulmonar).
			- ▶ **Pausa Inspiratória e Pressão de Platô:**
				- Se aplicar uma pausa inspiratória (fluxo cai a zero), a pressão decai levemente do Pico para formar um platô horizontal.
				- A Pressão de Platô reflete a **Pressão Alveolar** pura (exclui o componente resistivo do ar em movimento), demonstrando a complacência elástica do pulmão.

---

## 2. Modo Pressão Controlada (PC-AC)
- **Modo limitado a pressão e ciclado a tempo. O Fluxo é livre e o Volume Corrente é a variável livre (dependente do esforço e da mecânica).**
	- **Características Clínicas Principais:**
		- Reduz o risco imediato de barotrauma, pois a pressão máxima nas vias aéreas é "travada" e constante durante toda a inspiração.
		- Modo Assistido-Controlado: Garante ciclos baseados na FR mínima ajustada, mas permite disparos do paciente.
	- **Parâmetros Setados pelo Médico:**
		- **Pinsp (Pressão Acima da PEEP):** Determina o limite pressórico do ciclo.
		- **Tempo Inspiratório (Ti):** Como não ajustamos o fluxo, precisamos definir exatamente quanto tempo a pressão será mantida.
	- **Análise das Curvas no Ventilador (A História do Ciclo no PC-AC):**
		- **Curva de Pressão (Gráfico Superior): Padrão de Onda Quadrada.**
			- Fisiologia: Sobe rapidamente da PEEP até o valor alvo (ex: PEEP + Pinsp) e mantém-se constante (plana) durante todo o Ti. A Pressão de Pico é geralmente igual à Pressão de Platô.
		- **Curva de Fluxo (Gráfico Central): Padrão Livre e Descendente (Desacelerado).**
			- Fisiologia: É o fluxo mais fisiológico. Apresenta um pico muito alto no início da inspiração (maior gradiente de pressão entre ventilador e pulmão). Conforme o pulmão enche e as pressões se igualam, a velocidade do fluxo desacelera até zero. Gera muito **menos assincronia de fluxo** comparado ao VC.
		- **Curva de Volume (Gráfico Inferior): Padrão Variável.**
			- Fisiologia: Curva em barbatana, mas a altura (Pico de Volume Corrente) varia a cada respiração. A variação depende diretamente do esforço (drive diafragmático) do paciente e da complacência/resistência do sistema respiratório.

---

## 3. Modo Pressão de Suporte (PSV / SPN-CPAP)
- **Modo estritamente espontâneo. Exige "drive" respiratório ativo do paciente. Usado para transição e desmame ventilatório.**
	- **Red Flag de Segurança (Alarme de Apneia):** Se o paciente parar de respirar (ausência de esforço) por 20 a 30 segundos, não haverá ciclo. O ventilador obrigatoriamente aciona o alarme de apneia e entra em **ventilação de resgate (backup)**, retirando o paciente do modo espontâneo para evitar óbito. Ocorre frequentemente se o paciente ainda estiver sob efeito residual de sedativos/opióides.
	- **Parâmetros Setados pelo Médico:**
		- **Pressão de Suporte (PS):** Nível de pressão ofertado em cima da PEEP para ajudar a vencer o trabalho respiratório.
		- *Nota Clínica:* A titulação da PS é feita observando a capacidade do paciente em gerar um Volume Corrente adequado e confortável com aquele esforço.
	- **Análise das Curvas no Ventilador (A História do Ciclo em PSV):**
		- **Curva de Pressão (Gráfico Superior): Padrão de Onda Quadrada.**
			- Fisiologia: Sobe da PEEP e mantém-se constante enquanto o esforço inspiratório do paciente for sustentado e efetivo.
		- **Curva de Fluxo (Gráfico Central): Padrão Livre e Descendente.**
			- Fisiologia: Semelhante à Pressão Controlada (rápida aceleração seguida de desaceleração).
			- ▶ **Ciclagem (A grande diferença da PSV):** A ciclagem é feita a **fluxo**. O ventilador corta a inspiração e abre a válvula expiratória quando o fluxo inspiratório em desaceleração atinge um limiar específico do pico de fluxo máximo (critério de ciclagem, geralmente configurado de fábrica em 25%).
		- **Curva de Volume (Gráfico Inferior): Totalmente Variável.**
			- Fisiologia: A altura da curva (Vt atingido) é inteiramente dependente do quão forte e sustentado foi o esforço diafragmático do paciente contra a complacência pulmonar naquele ciclo específico.