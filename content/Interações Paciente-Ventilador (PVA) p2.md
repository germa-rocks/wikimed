---
publish: true
---

***

# Manejo Avançado de Assincronias Paciente-Ventilador (PVA)

## 1. Assincronias de Disparo (Fase de Transição Expiratória-Inspiratória)
### 1.1 Disparo Atrasado ou Perdido (Missed/Delayed Triggering)
- **Regra de Ouro: Ocorre tipicamente por um *trigger* (disparo) insensível ou pela presença de Hiperinsuflação Dinâmica (Auto-PEEP / PEEP intrínseca).**
  - **Identificação Clínica:** Observar contração do diafragma do paciente sem a entrega correspondente ou imediata do ciclo pelo ventilador (verificar curva de pressão esofágica se disponível).
  - **Manejo do Trigger Insensível:**
    - Ajustar a sensibilidade para o nível máximo possível **sem causar auto-disparo**.
    - *Red Flag:* Cuidado ao usar nebulizadores externos no circuito; eles podem adicionar fluxo contínuo, "cegando" o ventilador para o esforço do paciente. Preferir nebulizadores de malha vibratória (*vibrating mesh*).
  - **Manejo da Auto-PEEP (PEEP intrínseca):**
    - **Aumentar o Tempo Expiratório (Te):** Reduzir a frequência respiratória no ventilador para dar tempo ao pulmão de esvaziar (excelente para DPOC/Asma).
    - **Aplicação de PEEP Extrínseca (Aplicada):** Aumentar a PEEP do ventilador até um valor próximo à PEEP intrínseca (aprox. 80%).
      - *Mecanismo:* Isso não reduz a pressão no tórax, mas aproxima a pressão do circuito basal da pressão alveolar, diminuindo o gradiente de esforço necessário para o paciente atingir o limiar de disparo.
      - *Atenção:* Fazer ajustes lentos e beira-leito. O excesso de PEEP pode causar hiperdistensão pulmonar e colapso hemodinâmico.

### 1.2 Autodisparo (Auto Triggering)
- **Regra de Ouro: O ventilador entrega ciclos não solicitados pelo paciente. Suspeitar imediatamente em casos de alcalose respiratória inexplicada.**
  - **Principais Causas e Condutas:**
    - **Vazamentos (Mais comum):** Checar fuga pelo *cuff* do tubo, dreno de tórax em aspiração contínua ou furos no circuito.
    - **Água no circuito:** O líquido condensado "balançando" gera variações de fluxo/pressão que o ventilador interpreta como esforço. Drenar as traqueias.
    - **Oscilação Cardíaca:** Batimentos cardíacos transmitidos à via aérea.
  - **Manobra Diagnóstica (Teste Beira-Leito):**
    - Reduzir drasticamente a sensibilidade (tornar "mais dura") de forma temporária. Se os disparos cessarem, confirma-se o autodisparo. 
    - *Aviso:* Nunca esquecer de retornar à sensibilidade ideal logo após o teste, sob risco de exaustão muscular do paciente.

### 1.3 Disparo Reverso (Reverse Triggering)
- **Regra de Ouro: Contração diafragmática que ocorre *em resposta* a um ciclo mandatório prévio. Comum em pacientes críticos profundamente sedados.**
  - **Mecanismo:** Desconhecido ao certo, mas a insuflação pulmonar deflagra reflexos neuromusculares que ativam o diafragma.
  - **Estratégias de Manejo (Individualizadas):**
    - **Opção 1 (Desmame de Sedação):** Se o paciente tiver *drive* respiratório apropriado, clarear a sedação e transferir para modo espontâneo (ex: PSV - Pressão de Suporte). Pode ser necessário usar PSV elevada (ex: até 20-25 cmH2O) para suprir a demanda.
    - **Opção 2 (Aprofundamento):** Se o quadro for muito grave e o paciente não tolerar ventilação espontânea, otimizar sedação e iniciar Bloqueio Neuromuscular (BNM) temporário.

---

## 2. Assincronias de Fluxo (Durante a Inspiração)
### 2.1 Fome de Fluxo (Flow Starvation)
- **Regra de Ouro: O paciente puxa o ar mais rápido ou com mais força do que o ventilador fornece. Gráfico clássico: Curva de pressão "escavada" (abaulada para baixo) durante a fase inspiratória.**
  - **Manejo em Ventilação Controlada a Volume (VCV):**
    - **Conduta Inicial:** Aumentar a taxa de fluxo ou mudar para onda de fluxo quadrada.
    - *Efeito Adverso Fisiológico:* Aumentar o fluxo **reduz** o Tempo Inspiratório (Ti). Isso pode fazer com que o ventilador encerre o ciclo muito cedo, causando Ciclagem Prematura e Duplo Disparo. 
  - **Manejo em Ventilação Controlada a Pressão (PCV) ou PSV (Solução Preferencial):**
    - **Conduta:** Mudar do modo VCV para modos pressóricos (PCV/PSV).
    - *Mecanismo:* Modos pressóricos oferecem fluxo livre e variável (desacelerado), permitindo que o paciente dite a demanda de fluxo. Pode-se também ajustar o *Rise Time* (tempo de subida) para mais rápido.
    - *Efeito Adverso Fisiológico:* O Volume Corrente (Vt) aumentará inicialmente porque mais fluxo está sendo entregue à mesma pressão. Geralmente é transitório; assim que a fome de fluxo cessa, o Vt tende a normalizar. Monitorar para não exceder limites de proteção pulmonar.
  - **Atenção em Níveis Baixos de PSV:**
    - Fome de fluxo pode ocorrer se a pressão de suporte estiver muito baixa (ex: PSV de 5 cmH2O).
    - *Solução:* Aumentar o nível de PSV temporariamente ou considerar extubação, visto que o paciente apresenta excelente força muscular e alto *drive*.

---

## 3. Assincronias de Ciclagem (Transição Inspiração-Expiração)
### 3.1 Ciclagem Tardia (Delayed Cycling)
- **Regra de Ouro: O ventilador demora muito para encerrar a inspiração. O paciente contrai a musculatura expiratória ativamente "brigando" para exalar contra a pressão do ventilador.**
  - **Consequências Clínicas:** Reduz o tempo de esvaziamento pulmonar, gera Auto-PEEP, aumenta o trabalho muscular e atrasa o próximo disparo. Comum em pacientes DPOC em PSV devido ao lento decaimento do fluxo.
  - **Manejo por Modo Ventilatório:**
    - **Em VCV:** Aumentar o fluxo inspiratório, usar onda de fluxo quadrada ou diminuir o Volume Corrente (todas essas medidas diminuem o Tempo Inspiratório mecânico).
    - **Em PCV:** Diminuir diretamente o Tempo Inspiratório configurado. Alternativamente, mudar para PSV.
    - **Em PSV (Pérola Clínica):** **Aumentar o Critério de Ciclagem (Ciclagem por fluxo / ESENS).**
      - *Ajuste prático:* Em pacientes com via aérea obstruída (DPOC), a curva de fluxo decai devagar. Se a ciclagem estiver em 15%, o Tempo Inspiratório será enorme. Aumentar o critério para 40% faz o ventilador "desligar" o fluxo mais cedo, permitindo a exalação do paciente de forma sincrônica.

### 3.2 Ciclagem Prematura (Premature Cycling / Duplo Disparo)
- **Regra de Ouro: O ventilador encerra a inspiração de forma precoce, enquanto o tempo neural inspiratório do paciente ainda está ativo. Pode gerar imediatamente um segundo disparo (Duplo Disparo ou *Breath-Stacking*).**
  - **Manejo por Modo Ventilatório:**
    - **Em VCV:** Diminuir o fluxo inspiratório ou aumentar o Volume Corrente (medidas que prolongam o Tempo Inspiratório).
      - *Red Flag:* Cuidado ao aumentar o Volume Corrente para não ferir protocolos de ventilação protetora (manter estritamente ≤ 6 a 8 mL/kg peso predito).
    - **Em PCV:** Aumentar diretamente o Tempo Inspiratório configurado.
    - **Em PSV (Pérola Clínica):** **Reduzir o Critério de Ciclagem (Ciclagem por fluxo / ESENS).**
      - *Ajuste prático:* Em pacientes com padrão restritivo ou caixa torácica rígida, o fluxo decai vertiginosamente rápido. Se o corte for alto (ex: 35%), a máquina encerra muito rápido e o paciente puxa o ar novamente (duplo disparo). Reduzir a ciclagem para 5% prolonga o Tempo Inspiratório mecânico, acoplando-o ao neural.