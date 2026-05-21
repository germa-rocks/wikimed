---
publish: true
---
# Mecânica Respiratória na Ventilação Mecânica

## Pré-requisitos Básicos para Medição
- **O paciente deve estar sem esforço respiratório (drive zerado) para garantir a precisão dos cálculos.**
	- Escala de RASS em -5 (sedação profunda).
	- OU sob efeito de Bloqueio Neuromuscular (ex: após Sequência Rápida de Intubação).

## Configuração Inicial do Ventilador
- **O ventilador deve estar ajustado em Volume Controlado (VCV) com fluxo quadrado (constante) a 60 L/min.**
	- **Ajuste do Fluxo de Ar:** Fixar exatamente em **60 L/min**.
		- *Pérola Fisiológica:* 60 Litros por minuto equivalem a **1 Litro por segundo (L/s)**. Fixar este valor anula o denominador na fórmula de resistência, permitindo calcular a resistência mentalmente apenas subtraindo pressões.
	- **Ajuste do Volume Corrente ($V_T$):** 6 a 8 mL/kg do **Peso Corporal Predito**.
		- *Atenção:* O peso predito é calculado obrigatoriamente pela **altura** do paciente, nunca pelo peso real na balança.
		- *Exemplo prático:* Paciente de 50 kg (predito) x 6 mL/kg = $V_T$ de 300 mL.
	- **Outros Parâmetros:** Configurar PEEP fisiológica/alvo (ex: 5 cmH₂O) e Frequência Respiratória adequada (ex: 15 irpm).

## A Manobra: Pausa Inspiratória
- **Aperte o botão de "Pausa Inspiratória" por pelo menos 2 segundos para isolar os componentes elásticos e resistivos do pulmão.**
	- **O que acontece fisiologicamente durante a pausa?**
		- O fluxo de ar é interrompido abruptamente (cai para zero).
		- Ao zerar o fluxo, o componente **resistivo** (atrito do ar nas vias aéreas) desaparece.
		- A pressão nas vias aéreas cai do seu valor máximo (Pressão de Pico) e se estabiliza formando uma linha reta: esta é a **Pressão de Platô** (pressão alveolar).
		- O volume se mantém constante e sustentado até a liberação da expiração.

## Cálculo e Avaliação da Resistência ($R_{aw}$)
- **A Resistência reflete a oposição ao fluxo de ar; é calculada subtraindo a Pressão de Platô da Pressão de Pico.**
	- **Fórmula Oficial:** $R_{aw} = \frac{\text{Pressão de Pico} - \text{Pressão de Platô}}{\text{Fluxo (em L/s)}}$
	- **Regra Prática (Macete Beira-leito):** Como ajustamos o fluxo para 60 L/min (1 L/s), a divisão por 1 não altera o resultado. A fórmula torna-se apenas: **Pressão de Pico - Pressão de Platô**.
	- **Diagnóstico Diferencial de Resistência Aumentada:**
		- *Relacionada ao Paciente:* Broncoespasmo crônico ou agudo, excesso de secreção em vias aéreas inferiores.
		- *Relacionada ao Dispositivo:* Tubo orotraqueal (TOT) dobrado/quincado, TOT de calibre muito pequeno, secreção impactada no tubo.
	- *Exemplo do caso:* Pressão de Pico (23) - Pressão de Platô (14) = Resistência de 9 cmH₂O/L/s. (Valor considerado tranquilo/normal).

## Cálculo e Avaliação da Complacência Estática ($C_{stat}$)
- **A Complacência reflete a distensibilidade pulmonar (a capacidade de acomodar volume em relação à pressão aplicada). Valor normal: 50 a 80 mL/cmH₂O.**
	- **Cálculo da Driving Pressure (Pressão de Distensão Alveolar):**
		- $\text{Driving Pressure (DP)} = \text{Pressão de Platô} - \text{PEEP}$
	- **Fórmula da Complacência Estática:**
		- $C_{stat} = \frac{\text{Volume Corrente (V}_T\text{)}}{\text{Driving Pressure}}$
	- **Padrões Clínicos Beira-leito:**
		- **Pulmão de Alta Complacência (ex: Enfisema):** Pulmão muito flácido. Acomoda altos volumes com baixas pressões. Fácil de distender, mas difícil de esvaziar (recolhimento elástico prejudicado).
			- *Manejo temporal:* Requer tempo expiratório prolongado (evitar auto-PEEP). Tempo inspiratório geralmente é curto.
		- **Pulmão de Baixa Complacência (ex: SARA):** Pulmão "duro". Requer altas pressões (*Driving Pressures* elevadas) para acomodar pequenos volumes.
			- *Manejo temporal:* Difícil para o ar entrar, mas fácil para sair. Pode-se tolerar um tempo inspiratório mais prolongado.
	- *Exemplo do caso:* Platô (14) - PEEP (5) = *Driving Pressure* de 9. Com $V_T$ de 300 mL, a $C_{stat}$ = 300 / 9 = ~33 a 36 mL/cmH₂O.

## Morfologia Padrão das Curvas no Modo VCV (Fluxo Quadrado)
- **A análise visual correta das 3 curvas confirma se a ventilação e as manobras estão ocorrendo conforme o esperado.**
	- **Curva de Pressão x Tempo (P_{aw}):**
		- *Inspiração:* Linha sobe de forma oblíqua e constante (rampa) acompanhando a entrada de volume até atingir o cume (**Pressão de Pico**).
		- *Expiração:* Queda rápida de volta à linha de base, que representa a **PEEP** ajustada.
	- **Curva de Fluxo x Tempo:**
		- *Inspiração:* Ascensão vertical rápida, seguida de uma linha horizontal reta e constante (formato **quadrado** devido ao fluxo de 60 L/min fixo), finalizando com queda vertical a zero.
		- *Expiração:* O fluxo torna-se negativo (ar saindo), formando um triângulo invertido com decaimento exponencial gradativo até cruzar o eixo zero ao final da expiração.
	- **Curva de Volume x Tempo:**
		- *Inspiração:* A curva ascende de forma linear e constante, formando o desenho de um triângulo/barbatana de tubarão, parando exatamente no $V_T$ pré-definido.
		- *Expiração:* Queda passiva (linha descendente) até retornar a zero.

## Utilidade Clínica Longitudinal
- **O cálculo seriado da mecânica respiratória é a base para titular PEEP e avaliar a evolução clínica do paciente intubado.**
	- **Titulação da PEEP Ideal:** Testar diferentes níveis de PEEP e recalcular a mecânica. A "melhor PEEP" é aquela que gera a maior Complacência (menor *Driving Pressure* para o mesmo $V_T$), indicando que unidades alveolares foram recrutadas sem causar hiperdistensão.
	- **Resposta a intervenções:** Medir antes e após broncodilatadores (para ver queda da resistência) ou uso de bloqueadores neuromusculares/posição pronação (para avaliar melhora na complacência e relação V/Q).