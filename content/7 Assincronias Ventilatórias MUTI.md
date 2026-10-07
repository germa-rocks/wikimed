---
publish: true
---


Aqui está a estruturação de alto rendimento do material, desenhada para plataformas como Notion ou Obsidian, utilizando o princípio da divulgação progressiva.



# Assincronia Paciente-Ventilador

## Sistematização Inicial: A "Escalação 4-3-3"
- **A identificação da assincronia baseia-se na fase do ciclo ventilatório em que o "desencontro" ocorre.**
	- **O Goleiro (Problema basal):** Vazamento.
	- **A Defesa (Fase de Disparo - 4 tipos):** Auto disparo, Disparo ineficaz, Duplo disparo e Disparo reverso.
	- **O Meio-Campo (Fase de Fluxo - 3 tipos):** Fluxo insuficiente, Fluxo excessivo e Flow Index.
	- **O Ataque (Fase de Ciclagem - 3 tipos):** Ciclagem precoce, Ciclagem tardia e Autopeep.

---

## Assincronias de Fundo / Circuito
- **O Vazamento no circuito impede o retorno da curva de fluxo à linha de base, sendo a principal causa de Autodisparo.**
	- **Identificação Gráfica:** Na curva de Fluxo x Tempo, o fluxo expiratório não atinge o zero antes de iniciar o próximo ciclo.
	- **Fisiopatologia:** O ventilador interpreta a perda contínua de fluxo/pressão do vazamento como se fosse o paciente "puxando" o ar (esforço inspiratório), deflagrando um ciclo.
	- **Mnemônico Visual:** A curva cortada no final lembra a máscara do "V de Vingança" (V = Vazamento).

---

## Assincronias de Disparo (Início da Inspiração)

- **Auto Disparo (Autotriggering): O ventilador é acionado sem que haja real esforço do paciente.**
	- **Quadro Clínico:** Frequência respiratória lida no monitor é muito maior que a ajustada no ventilador. Paciente calmo, sem esforço visível. Risco de hiperventilação iatrogênica e alcalose respiratória.
	- **Causas Principais:**
		- Ajuste excessivamente sensível do *trigger*.
		- Vazamento no sistema ou fístula pleural.
		- Condensado (água) no circuito gerando oscilação.
		- Transmissão de batimentos cardíacos (comum em pacientes hiperdinâmicos ou com morte encefálica).
	- **Manejo Sequencial:**
		- 1. Checar e corrigir vazamentos ou água no circuito.
		- 2. Reduzir a sensibilidade do ventilador (aumentar o valor numérico do *Flow Trigger*).
		- 3. Se falhar, mudar a sensibilidade de Fluxo para Pressão (menos suscetível a artefatos cardíacos).

- **Disparo Ineficaz: O paciente faz esforço inspiratório, mas a máquina não reconhece ou o esforço não atinge o limiar.**
	- **Identificação Gráfica:** Queda na curva de pressão associada a uma deflexão positiva na curva de fluxo, mas **sem** o fornecimento de um ciclo mecânico subsequente.
	- **Causas Principais:**
		- **Auto-PEEP / Aprisionamento Aéreo:** O paciente precisa vencer a PEEP intrínseca antes de conseguir negativar a pressão do circuito. Causa clássica no DPOC.
		- Fraqueza muscular (doença neuromuscular ou fadiga).
		- Excesso de sedação / depressão do drive.
		- Assistência excessiva do ventilador ou tempo inspiratório mecânico muito longo.
	- **Manejo Sequencial:**
		- Deixar o ventilador mais sensível (reduzir o valor numérico do *trigger*).
		- Tratar a Auto-PEEP (aumentar tempo expiratório, broncodilatador).
		- Reduzir níveis de pressão de suporte (se estiverem suprimindo o drive do paciente).

- **Duplo Disparo: O ventilador entrega dois ciclos consecutivos sem intervalo expiratório adequado, gerando perigoso "empilhamento" de volume.**
	- **Variante 1: Ciclagem Precoce (Tempo Neural > Tempo Máquina)**
		- **Fisiopatologia:** O ventilador termina de mandar o ar, mas o paciente (com drive exacerbado) continua inspirando. Esse esforço forte imediato dispara um segundo ciclo.
		- **Manejo:** O objetivo é **aumentar o tempo inspiratório** da máquina.
			- Modo PCV: Aumentar o Tempo Inspiratório diretamente.
			- Modo PSV: Fazer o "BURPPE" (Aumentar a Pressão de Suporte, prolongar/deitar o *Rise Time* e **reduzir** a % da sensibilidade de ciclagem exalatória).
			- Modo VCV: Aumentar o Volume Corrente (mudar apenas o fluxo sem mudar o volume pode agravar a "fome de fluxo").
	- **Variante 2: Disparo Reverso (Contração Diafragmática Reflexa)**
		- **Fisiopatologia:** O ciclo mecânico imposto pelo ventilador estira os pulmões e gera um reflexo vagal que contrai o diafragma do paciente, disparando a máquina logo em seguida. Ocorre em pacientes sedados.
		- **Manejo:**
			- Ideal: Reduzir a sedação e permitir ventilação espontânea.
			- Se grave/intratável (ex: SARA): Aprofundar sedação e instituir Bloqueio Neuromuscular (curarização).

---

## Assincronias de Fluxo (Durante a Inspiração)

- **Fluxo Insuficiente (Fome de Fluxo / Work Shifting): O ventilador entrega fluxo mais devagar do que o paciente necessita.**
	- **Identificação Gráfica:** Mais comum e visível no modo VCV. A curva de Pressão x Tempo fica **distorcida e com aspecto côncavo** ("barriga para baixo") durante a inspiração.
	- **Fisiopatologia:** O paciente faz força ativa para sugar o ar, reduzindo ativamente a pressão dentro do circuito.
	- **Manejo:**
		- Modo VCV: Aumentar o Fluxo Inspiratório ou o Volume Corrente.
		- Conduta de Ouro: Mudar para modos pressóricos (PCV ou PSV), onde o fluxo é livre, desacelerado e se adapta à demanda do paciente.
		- Investigar/tratar a causa do drive exacerbado (febre, dor, acidose).

- **Fluxo Excessivo ("Overshoot" de Entrada): O ventilador entrega o fluxo de forma muito rápida ou abrupta contra uma resistência.**
	- **Identificação Gráfica:** Presença de uma **espícula (pico agudo)** logo no início da fase inspiratória na curva de Pressão x Tempo.
	- **Manejo:**
		- Modo VCV: Reduzir o fluxo inspiratório.
		- Modos PCV/PSV: Aumentar o *Rise Time* (tempo de subida) para que a pressurização seja mais lenta ("deitar a curva").

- **Flow Index**
	- **O que é:** Parâmetro não invasivo e contínuo para avaliar o grau de esforço do paciente em modo PSV, analisando matematicamente a concavidade da curva de fluxo. Avalia se o suporte está excessivo ou deficiente.

---

## Assincronias de Ciclagem (Transição Inspiração -> Expiração)

- **Ciclagem Precoce: O ventilador encerra a inspiração antes do paciente.**
	- **Identificação Gráfica:** O fluxo expiratório apresenta uma "barriga" ou deflexão positiva logo após o início da expiração. Se o esforço for muito intenso, vira o *Duplo Disparo*.
	- **Manejo:** Idêntico ao Duplo Disparo por ciclagem precoce. Aumentar o tempo inspiratório em PCV/VCV ou **diminuir** o limiar de ciclagem em PSV (Ex: baixar de 25% para 10%).

- **Ciclagem Tardia (Overshoot de Saída): O ventilador continua mandando ar quando o paciente já começou a expirar ativamente.**
	- **Identificação Gráfica:** Presença de um **pico de pressão no final** do ciclo inspiratório (o paciente contrai o abdome contra a máquina que ainda está insuflando).
	- **Fisiopatologia:** Tempo inspiratório do ventilador > Tempo neural. Muito comum em pacientes com aumento de resistência (ex: DPOC/Asma).
	- **Manejo:**
		- Modo PCV: Reduzir o tempo inspiratório.
		- Modo VCV: Aumentar o fluxo (pois fluxo maior entrega o volume mais rápido, encurtando o tempo inspiratório).
		- Modo PSV: **Aumentar** o limiar de ciclagem exalatória (Ex: subir de 25% para 50%, fazendo a máquina "desligar" mais cedo).

---

## Pérolas Clínicas Práticas (Baseado em Provas - SIBA 2024)

- **Vazamento e Fuga Aérea geram Autodisparo.**
	- **Conduta de prova:** Se o paciente tem fístula pleural e apresenta autodisparo, a conduta inicial ideal é **trocar a sensibilidade de fluxo para pressão**. (Diminuir o valor da sensibilidade a fluxo pioraria o quadro, pois a deixaria mais sensível).

- **Paciente com DPOC + deflexões na curva de fluxo = Disparo Ineficaz por Auto-PEEP.**
	- **Fisiopatologia de prova:** O paciente tenta respirar, há variação no fluxo, mas a curva de pressão não sobe (o ciclo não entra). A causa mortis na DPOC é a hiperinsuflação dinâmica (Auto-PEEP).
	- **Conduta de prova:** Tratar a Auto-PEEP aumentando o tempo expiratório, evitando volumes altos e tratando o broncoespasmo.

















-------------
# 🫁 ASSINCRONIA VENTILATÓRIA: Manejo Prático à Beira-Leito

## ⚽ A Metáfora do Time de Futebol (O Mapa Mental 4-3-3)
- **Para organizar o raciocínio beira-leito, dividimos as assincronias em 11 componentes estruturados como um time de futebol.**
  - **O Goleiro:** Vazamento (a base que afeta as demais).
  - **A Defesa (4 - Disparo):** Autodisparo, Disparo Ineficaz, Duplo Disparo (Ciclagem Precoce) e Disparo Reverso.
  - **O Meio-Campo (3 - Fluxo):** Fluxo Insuficiente, Fluxo Excessivo e Flow Index.
  - **O Ataque (3 - Ciclagem/PEEP):** Ciclagem Precoce, Ciclagem Tardia e Auto-PEEP (o "artilheiro").

---

## 🧤 O GOLEIRO: Vazamento do Circuito
- **A identificação do vazamento é mandatória antes de avaliar qualquer outra assincronia, pois falseia a mecânica e gera autodisparos.**
  - **Identificação Gráfica (O "V" de Vazamento):**
    - Observar a curva de **Volume x Tempo**.
    - A curva expiratória não retorna à linha de base (zero).
    - O Volume Corrente Inspirado (VTi) é maior que o Expirado (VTe) (Ex: VTi 500mL / VTe 350mL = 150mL perdidos).
    - ![[Pasted image 20261007170928.png]]
  - **Impacto Clínico:**
    - Contaminação do ambiente (risco biológico).
    - Impossibilidade de avaliar mecânica (queda contínua na pausa inspiratória).
    - Principal causa de autodisparo.

---

## 🛡️ A DEFESA: Assincronias de Disparo (Início do Ciclo)

- **1. Autodisparo: O ventilador dispara sem esforço do paciente (FR alta, mas sem drive).**
  - **Identificação Clínica e Gráfica:**
    - Frequência respiratória maior que a ajustada em paciente sedado/sem drive.
    - Ausência de *P-trigger* (deflexão negativa na curva de pressão antes do fluxo).
    - Curva de Fluxo com "rabiscos" ou serrilhados.
  - **Causas Principais:**
    - Vazamentos (o aparelho lê a perda de volume como esforço).
    - Presença de condensado/água no circuito.
    - Artefato de batimento cardíaco sendo lido pelo sensor.
    - Sensibilidade excessivamente "leve".
  - **Manejo e Resolução:**
    - 1º Passo: Checar e corrigir vazamentos ou água no circuito.
    - 2º Passo: **Ajustar Sensibilidade** (deixar mais "dura").
      - Se a fluxo: Aumentar o valor (ex: de 1.5 L/min para 3 L/min).
      - Se a pressão: Diminuir o valor (ex: de -1 cmH2O para -2 cmH2O).
      - *Nota: Na maioria dos ventiladores, aumentar o valor numérico dificulta o disparo (exceto padrão Maquet).*

- **2. Disparo Ineficaz: O paciente faz esforço, mas a máquina não reconhece.**
  - **Identificação Clínica e Gráfica:**
    - Observação de esforço muscular (tórax/abdome) sem entrega de ciclo pelo ventilador.
    - Curva de fluxo com deflexão positiva (solavanco) na fase expiratória.
    - **Red Flag:** Esforço que ocorre longe da inspiração anterior (não confundir com ciclagem precoce).
    - 
    - ![[Pasted image 20261007171106.png]]
		  -  "queda na curva de pressão associada a uma deflexão positiva na curva de fluxo, mas sem o fornecimento de um ciclo". O gráfico deste slide ilustra exatamente isso, mostrando o esforço muscular do paciente (linha vermelha) não sendo suficiente para disparar a máquina.
  - **A Causa Oculta (O Gatilho Mental):**
    - **Auto-PEEP / Hiperinsuflação Dinâmica:** É a principal causa. O paciente precisa vencer a PEEP intrínseca + a sensibilidade ajustada para conseguir disparar a máquina.
    - Outras causas: Fraqueza muscular extrema, depressão do comando neural.
  - **Manejo e Resolução:**
    - **Foco principal:** Reduzir a Auto-PEEP (Diminuir energia/tempo).
    - Em PSV: Reduzir a Pressão de Suporte (P). *Menos volume = menos aprisionamento.*
    - Em PCV: Reduzir o Tempo Inspiratório.
    - Em VCV: Aumentar o Fluxo Inspiratório (para reduzir o Tempo Ins).
    - Ajuste de sensibilidade: Deixar mais sensível (geralmente não é a solução primária).

- **3. Duplo Disparo (O grande desafio diagnóstico): Dois ciclos consecutivos com exalação incompleta (empilhamento de volume).**
  - **A Chave do Diagnóstico:** Diferenciar se a causa é Ciclagem Precoce (drive ativo) ou Disparo Reverso (drive suprimido).
  - ▶ **Variante A: Por Ciclagem Precoce (Paciente quer mais tempo)**
    - **Diagnóstico:** O tempo neural do paciente é maior que o tempo inspiratório da máquina. A máquina fecha a válvula, mas o paciente continua puxando e gera um novo ciclo.
	    - ![[Pasted image 20261007171210.png]]
		    - mostra que o tempo neural do paciente é maior que o da máquina, evidenciando o paciente "puxando" o ar e gerando o empilhamento de volume.
    - **Achados:** *Drive Ativo*. Existe *P-trigger* inicial. O esforço muscular começa junto com a máquina.
    - **Manejo (Adequar o Tempo Inspiratório):**
      - Em PCV: Aumentar o Tempo Inspiratório.
      - Em VCV: Aumentar o Volume Corrente (Atenção: reduzir o fluxo em VCV piora o drive).
      - Em PSV (Mnemônico **BURPPE** para aumentar T.ins):
        - Aumentar a **P**ressão.
        - Deitar a curva (Aumentar *Rise Time*).
        - Reduzir o **E-sens** (Ciclagem). Ex: de 25% para 5%.
  - ▶ **Variante B: Por Disparo Reverso (O "Soluço" diafragmático)**
    - **Diagnóstico:** Insuflação passiva pela máquina gera um reflexo neuromuscular tardio.
	    - ![[Pasted image 20261007171224.png]]
		    - "soluço diafragmático" descrito no seu texto: a insuflação passiva pela máquina (sem P-trigger inicial) gera um esforço muscular reflexo e tardio.
    - **Achados:** *Drive Suprimido/Abolido no início*. Acontece em modos Controlados. É rítmico/cíclico (ex: a cada 2 ciclos passivos, 1 reverso). Não há *P-trigger* inicial. A deflexão de pressão ocorre no meio/fim da insuflação.
    - **Manejo:**
      - Despertar o paciente: Permitir ventilação espontânea (PSV) com redução de sedação (remove a "insuflação passiva" da jogada).
      - Se quadro clínico grave (ex: SARA): Bloqueio Neuromuscular (Curarização) ou ajuste de FR/variáveis.

---

## 🏃 O MEIO-CAMPO: Assincronias de Fluxo (Fase de Insuflação)

- **1. Fluxo Insuficiente (Fome de Fluxo / Work Shifting)**
  - **Identificação:** Típica do modo **VCV** (fluxo fixo).
    - O paciente demanda mais fluxo do que a máquina entrega.
    - **Gráfico (Pressão x Tempo):** A curva de pressão "desaba", formando uma "barriga" (aspecto côncavo), indicando esforço ativo roubando pressão do sistema.
    - Presença de *P-trigger* nítido.
    - ![[Pasted image 20261007171317.png]]
    - ![[Pasted image 20261007171329.png]]
    - ![[Pasted image 20261007171342.png]]
  - **Manejo:**
    - Em VCV: Aumentar o Fluxo Inspiratório e/ou Volume.
    - **Conduta Ouro:** Mudar para modos de fluxo livre/variável (PCV ou PSV).
    - Avaliar e tratar a causa do drive exacerbado (dor, febre, acidose, delírio).

- **2. Fluxo Excessivo (Overshoot de Entrada)**
  - **Identificação:** Típica de modos pressóricos (**PCV ou PSV**). *Não ocorre em VCV.*
    - O ventilador entrega o fluxo muito rápido para uma via aérea com resistência aumentada.
    - **Gráfico (Pressão x Tempo):** Espícula inicial ("chifrinho") logo na entrada da insuflação, ultrapassando o limite de pressão ajustado.
    - ![[Pasted image 20261007171420.png]]
    - ![[Pasted image 20261007171426.png]]
  - **Manejo:**
    - Deitar a curva: **Aumentar o Tempo de Subida (Rise Time / Rampa)**. Ex: passar de 0ms para 150-200ms.
    - Tratar a causa base (broncoespasmo, secreção - alta resistência).

- **3. Flow Index (A assincronia oculta do PSV)**
  - **Identificação:** Ocorre no modo **PSV**.
    - **Gráfico (Fluxo x Tempo):** A curva inspiratória descendente (que deveria ser reta ou levemente côncava) fica **convexa** (abaulada para cima).
    - ![[Pasted image 20261007171524.png]]
  - **Significado Clínico:**
    - Indica esforço ativo mantido do paciente durante toda a fase inspiratória (sub-assistência). A energia fornecida pelo PSV está inadequada para a demanda.
    - ![[Pasted image 20261007171513.png]]
  - **Manejo:**
    - Avaliar necessidade de aumentar o suporte pressórico (PS) ou tratar a causa do aumento de demanda.

---

## ⚔️ O ATAQUE: Assincronias de Ciclagem (Fim da Inspiração)

- **1. Ciclagem Tardia (Overshoot de Saída)**
  - **Identificação:** O tempo inspiratório da máquina é maior que o tempo neural do paciente. O paciente quer expirar, mas a máquina continua insuflando.
    - **Gráfico (Pressão x Tempo):** Aumento abrupto (espícula / "barrigada" para cima) no **final** da fase inspiratória.
    - ![[Pasted image 20261007171700.png]]
    - ![[Pasted image 20261007171709.png]]
  - **Manejo:**
    - O objetivo é **reduzir o tempo inspiratório**.
    - Em PCV: Reduzir o tempo inspiratório no botão.
    - Em VCV: Aumentar o fluxo inspiratório (para o volume entrar mais rápido).
    - Em PSV: Aumentar o E-sens (Limiar de Ciclagem). Ex: passar de 25% para 40% ou 50%.

- **2. Ciclagem Precoce**
  - *Detalhada acima, no módulo de Defesa, como principal causadora do "Duplo Disparo".*
  - ![[Pasted image 20261007171629.png]]
	  o fluxo expiratório apresenta uma "barriga ou deflexão positiva logo após o início da expiração". O gráfico do slide 24 aponta explicitamente para essa deflexão positiva, mostrando a tentativa do paciente de continuar inspirando.
	  ![[Pasted image 20261007171643.png]]

---

## 🛠️ FERRAMENTA PRÁTICA: O Segredo da Pausa Expiratória
- **Como descobrir se o Drive está ativo quando as curvas estão confusas?**
  - Acione a **Pausa Expiratória** no ventilador.
  - **Drive Suprimido:** A curva de pressão durante a pausa se manterá plana/linear.
  - **Drive Ativo:** A curva de pressão sofrerá deflexão negativa.
  - **Utilidade:** Permite quantificar a força muscular do paciente medindo o Delta Pocc (*Pressure Occlusion*), diferenciando instantaneamente um Disparo Reverso (sem drive) de uma Ciclagem Precoce (com drive forte).