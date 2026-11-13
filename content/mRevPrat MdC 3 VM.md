---
publish: true
---


## Estação Prática: Programação Inicial da Ventilação Mecânica (VCV, PCV e PSV) e Interpretação das Curvas Básicas
**Gatilho Clínico / Tarefa da Estação:** Paciente recém-intubado na UTI aguarda ajuste inicial do ventilador mecânico; no leito ao lado, outro paciente encontra-se em desmame ventilatório. Programe os parâmetros iniciais em VCV e PCV, diferencie as variáveis controladas das dependentes nos 3 modos básicos e defina os ajustes de PSV compatíveis com o Teste de Respiração Espontânea (TRE).

**1. Constructo Técnico-Procedimental (Execução, Setup e Segurança)**
- [ ] **Preparo e Material:** Verificar montagem do circuito ventilatório, filtro trocador de calor e umidade (HME) ou umidificação ativa `[Padrão CTEMI]`, calibração/teste pré-uso do ventilador `[Padrão CTEMI]`, insuflação adequada do *cuff* endotraqueal `[Padrão CTEMI]` e conexão de oximetria de pulso e capnografia.
- [ ] **Posicionamento / Nivelamento / Configuração:** Manter cabeceira elevada ($30^\circ\text{–}45^\circ$) `[Padrão CTEMI]`, calcular o peso predito pela estatura e sexo `[Padrão CTEMI]` e configurar os parâmetros universais pós-IOT em qualquer modo assisto-controlado: **$FiO_2$ inicial de $100\%$** (reduzindo gradativamente para alvo de **$SaO_2\ 92\%\text{–}96\%$** na maioria dos pacientes), **PEEP inicial de pelo menos $5\text{ cmH}_2\text{O}$** e **frequência respiratória (FR) mínima** de segurança (lembrando que, se houver *drive*, o paciente poderá realizar FR superior).
- [ ] **Execução Sequencial:**
  - **No modo VCV (Ventilação Controlada a Volume):** Selecionar diretamente o **Volume Corrente** (**$6\text{–}8\text{ mL/kg}$** se pulmão normal; **$4\text{–}8\text{ mL/kg}$** se SARA) e o **Fluxo inspiratório** (habitualmente **$40\text{–}60\text{ L/min}$**; em alguns aparelhos ajusta-se diretamente o $T_{ins}$ e o fluxo passa a ser calculado). Monitorar a pressão resultante na tela.
  - **No modo PCV (Ventilação Controlada a Pressão):** Selecionar diretamente a **Pressão Inspiratória acima da PEEP** (habitualmente **$10\text{–}20\text{ cmH}_2\text{O}$**) e o **Tempo Inspiratório ($T_{ins}$)** (habitualmente **$0,8\text{ a }1,2\text{ segundos}$**). Monitorar o volume corrente resultante ($VTi$/$VTe$) e configurar alarmes de volume-minuto `[Padrão CTEMI]`.
  - **No modo PSV (Ventilação com Pressão de Suporte — Desmame):** Selecionar **Pressão de Suporte acima da PEEP** (habitualmente **$5\text{–}15\text{ cmH}_2\text{O}$**, reduzindo para **$5\text{ a }8\text{ cmH}_2\text{O}$** para equivalência ao **Teste de Respiração Espontânea — TRE**), **PEEP** (inicialmente **$5\text{ cmH}_2\text{O}$**), **$FiO_2$** titulada pela $SaO_2$ e o **percentual de fluxo para ciclagem**, garantindo ventilação de *backup* de apneia ativa `[Padrão CTEMI]`.

**2. Constructo Cognitivo-Operacional ("Cognição em Movimento")**
- [ ] **Padrão Visual / Curva / Achado Esperado:** Distinguir imediatamente o modo ventilatório pelo formato das ondas escalares na tela:
  - **VCV:** onda de **fluxo quadrada** (constante) e onda de **pressão ascendente** ("barbatana de tubarão");
  - **PCV:** onda de **pressão quadrada** (constante durante o $T_{ins}$ fixo) e onda de **fluxo desacelerado em rampa**;
  - **PSV:** onda de **pressão quadrada**, onda de **fluxo desacelerado** ciclando ao atingir fração do pico de fluxo e todos os ciclos deflagrados pelo paciente (FR espontânea).
- [ ] **Cálculos e Pontos de Corte:** Dominar a matriz de controle das variáveis nos **3 modos ventilatórios básicos**:

| Variável Ventilatória | VCV (Assisto-Controlado) | PCV (Assisto-Controlado) | PSV (Assistido / Espontâneo) |
| :--- | :--- | :--- | :--- |
| **Pressão Inspiratória** | **Não determino** (proporcional ao VC) | **Determino** ($10\text{–}20\text{ cmH}_2\text{O}$ acima da PEEP) | **Determino** ($5\text{–}15\text{ cmH}_2\text{O}$; TRE: **$5\text{–}8\text{ cmH}_2\text{O}$**) |
| **Volume Corrente (VC)** | **Determino** ($6\text{–}8$ ou $4\text{–}8\text{ mL/kg}$) | **Não determino** ($\uparrow$ com $\uparrow \Delta P$ ou $\uparrow T_{ins}$) | **Não determino** (proporcional ao $\Delta P$ + esforço) |
| **Fluxo Inspiratório** | **Determino** ($40\text{–}60\text{ L/min}$) | **Não determino** (livre/desacelerado) | **Não determino** (proporcional ao $\Delta P$ + esforço) |
| **Tempo Inspiratório ($T_{ins}$)** | **Não determino** (inversamente proporcional ao fluxo) | **Determino** ($0,8\text{–}1,2\text{ s}$) | **Não determino** (baseado no % de fluxo de ciclagem) |
| **Frequência Respiratória** | Determino **valor mínimo** | Determino **valor mínimo** | **Paciente determina** integralmente |
| **PEEP e $FiO_2$** | **Sempre determino** ($\ge 5\text{ cmH}_2\text{O}$; alvo $92\text{–}96\%$) | **Sempre determino** ($\ge 5\text{ cmH}_2\text{O}$; alvo $92\text{–}96\%$) | **Sempre determino** ($5\text{ cmH}_2\text{O}$; conforme $SaO_2$) |
| **Tempo Expiratório ($T_{exp}$)** | **NUNCA determino diretamente** | **NUNCA determino diretamente** | **NUNCA determino diretamente** |

- [ ] **Interpretação Fisiopatológica e Diferenciais:** Compreender que em **VCV** o aumento do fluxo inspiratório **encurta o $T_{ins}$** e consequentemente **alarga o $T_{exp}$** (pois o $T_{exp}$ é sempre a fração residual do ciclo definida pela FR e pelo $T_{ins}$); já em **PCV**, para elevar o volume corrente entregue, é obrigatório **elevar a pressão inspiratória OU o tempo inspiratório** (desde que ainda haja fluxo inspiratório positivo ao final do $T_{ins}$ `[Padrão CTEMI]`).
- [ ] **Reconhecimento de Falhas / Alarmes e Correção Imediata:** Identificar hipoventilação ou volutrauma oculto em PCV/PSV quando a mecânica pulmonar se altera (broncoespasmo ou congestão reduzem o VC entregue em PCV), ajustando alarmes estritos de volume corrente/volume-minuto; identificar apneia em PSV (paciente sedado sem *drive*) retornando imediatamente a um modo assisto-controlado (VCV ou PCV).

**3. Constructo Profissional-Subjetivo (Postura e Verbalização Estruturada)**
- [ ] **Script de Verbalização ao Avaliador:** *"Em todos os modos determino PEEP (inicialmente ao menos 5 cmH2O) e FiO2 (iniciando a 100% pós-IOT e titulando para SaO2 entre 92 e 96%), e nunca determino diretamente o tempo expiratório, que é consequência da FR e do tempo inspiratório. Em VCV fixo o volume (6 a 8 mL/kg em pulmão normal) e o fluxo (40 a 60 L/min), sendo a pressão dependente e o tempo inspiratório inversamente proporcional ao fluxo. Em PCV fixo o delta pressórico (10 a 20 cmH2O) e o tempo inspiratório (0,8 a 1,2 s), sendo volume e fluxo variáveis. Já no desmame em PSV, o paciente comanda a FR e ajusto pressão de suporte entre 5 e 8 cmH2O para simular o teste de respiração espontânea."*
- [ ] **Segurança e Controle de Qualidade:** Nunca deixar paciente sob bloqueio neuromuscular ou sedação profunda apneica em modo espontâneo puro (PSV); reduzir prontamente a $FiO_2$ de $100\%$ após estabilização para evitar hiperóxia.

**Armadilhas de Prova & Troubleshooting Rápido**
* **Pegadinha / Erro Pré-Analítico:** Procurar botão de "Tempo Expiratório" no ventilador para corrigir retenção aérea -> **Efeito na Leitura:** Perda de tempo operacional na estação -> **Conduta Corretiva:** Verbalizar que o **$T_{exp}$ nunca é ajustado diretamente**; para aumentá-lo, deve-se **reduzir a FR** ou **reduzir o $T_{ins}$** (aumentando o fluxo em VCV ou reduzindo o $T_{ins}$ direto em PCV).
* **Pegadinha / Erro Pré-Analítico:** Tentar aumentar o volume corrente em PCV mexendo no fluxo -> **Efeito na Leitura:** Ausência de controle direto de fluxo em PCV -> **Conduta Corretiva:** Aumentar a **pressão inspiratória acima da PEEP** ou o **tempo inspiratório ($T_{ins}$)**.

---

## Estação Prática: Aferição da Mecânica Respiratória à Beira-Leito e Ventilação Protetora na SARA
**Gatilho Clínico / Tarefa da Estação:** Paciente com infiltrado pulmonar bilateral agudo e relação $PaO_2/FiO_2 = 118$ encontra-se sedado e sob bloqueio neuromuscular. Demonstre no ventilador como obter as medidas de mecânica respiratória estática e resistiva, calcule complacência, resistência e constante de tempo, e ajuste a ventilação protetora com indicação das terapias de resgate para SARA.

**1. Constructo Técnico-Procedimental (Execução, Setup e Segurança)**
- [ ] **Preparo e Material:** Confirmar paciente acoplado perfeitamente ao ventilador, **sem esforço muscular respiratório ($P_{mus} = 0$, sob bloqueio neuromuscular)**, circuito íntegro sem vazamentos e tubo endotraqueal aspirado/desobstruído.
- [ ] **Posicionamento / Nivelamento / Configuração:** Colocar o ventilador em modo **VCV com onda de fluxo quadrada (constante)** `[Padrão CTEMI]` (ex.: fluxo de **$60\text{ L/min} = 1\text{ L/s}$** para facilitar o cálculo exato de resistência à beira-leito `[Padrão CTEMI]`) e calcular o peso predito.
- [ ] **Execução Sequencial:**
  1. **Medida da Mecânica Respiratória:** Registrar a **Pressão de Pico ($P_{pico}$)** durante o fluxo inspiratório $\rightarrow$ acionar o botão de **Pausa Inspiratória** (habitualmente $0,5\text{ a }2,0\text{ s}$ `[Padrão CTEMI]`, zerando o fluxo de ar) $\rightarrow$ ler no platô estável a **Pressão de Platô ($P_{platô}$)** $\rightarrow$ acionar **Pausa Expiratória** para aferir a PEEP total/intrínseca `[Padrão CTEMI]` $\rightarrow$ calcular *Driving Pressure*, Pressão Resistiva, Complacência Estática, Resistência de Vias Aéreas e Constante de Tempo;
  2. **Ajuste Protetor na SARA:** Ajustar **VC entre $4\text{ e }8\text{ mL/kg}$**, titular PEEP e VC mantendo **$P_{platô} < 30\text{ cmH}_2\text{O}$** e ***Driving Pressure* $< 15\text{ cmH}_2\text{O}$**, ajustar **FR até $35\text{ irpm}$** tolerando hipercapnia permissiva até **$pH = 7,2$**;
  3. **Escalonamento na SARA Grave:** Mantendo **$PaO_2/FiO_2 < 150$ após pelo menos $12\text{ horas}$ de VM otimizada**, indicar **posição prona por pelo menos $16\text{ horas}$**, mantendo bloqueio neuromuscular caso haja assincronias incorrigíveis que impeçam a VM protetora.

**2. Constructo Cognitivo-Operacional ("Cognição em Movimento")**
- [ ] **Padrão Visual / Curva / Achado Esperado:** Identificar na curva Pressão $\times$ Tempo durante a pausa inspiratória: subida até a **$P_{pico}$**, queda súbita ao interromper o fluxo até estabilizar na **$P_{platô}$** (onde o degrau `$P_{pico} - P_{platô}$` representa a **Pressão Resistiva — $P_{resistiva}$**, e a altura `$P_{platô} - PEEP$` representa a **Pressão Elástica — $P_{elástica}$ / *Driving Pressure***). No gráfico exponencial da **Constante de Tempo (CT)**, reconhecer que após $1\ CT$ restam $37\%$ do volume ($63\%$ exalados), após $2\ CT$ restam $13,5\%$ e após **$3\ CT$ exalam-se $95\%$ do ar pulmonar** (restando apenas $5\%$).
- [ ] **Cálculos e Pontos de Corte:** Demonstrar e aplicar todas as equações da mecânica ventilatória e alvos da SARA:
  - **Equação do Movimento:** `$P_{va} = P_{mus} + P_{elástica} + P_{resistiva} + PEEP + \text{Inertância}$` (com inertância $\approx 0$, bloqueio neuromuscular anulando `$P_{mus} = 0$` e pausa inspiratória anulando `$\text{Fluxo} = 0$`);
  - **Pressão Resistiva:** `$P_{resistiva} = P_{pico} - P_{platô} = \text{Resistência} \times \text{Fluxo}$`;
  - **Resistência de Vias Aéreas:** `$R = \frac{P_{pico} - P_{platô}}{\text{Fluxo (em L/s)}}$` (converter $\text{L/min} \div 60 = \text{L/s}$);
  - **Pressão de Distensão (*Driving Pressure* / $P_{elástica}$):** `$\Delta P = P_{platô} - PEEP$` (alvo na SARA: **$< 15\text{ cmH}_2\text{O}$**);
  - **Complacência Estática:** `$C_{est} = \frac{VC}{P_{platô} - PEEP}$` (baixa complacência = pulmão rígido/"duro", típico da SARA);
  - **Constante de Tempo:** `$CT = \text{Complacência} \times \text{Resistência}$` (**$3 \times CT$** = tempo mínimo necessário para exalar **$95\%$** do volume corrente);
  - **Pilares numéricos da SARA:** Diagnóstico = **$PaO_2/FiO_2 < 300$**, agudo, infiltrado bilateral não explicado por congestão cardiogênica; Protetora = **$VC\ 4\text{–}8\text{ mL/kg}$**, **$P_{platô} < 30\text{ cmH}_2\text{O}$**, **$\Delta P < 15\text{ cmH}_2\text{O}$**, **$FR \le 35\text{ irpm}$**, **hipercapnia permissiva até $pH \ge 7,2$**; Prona = **$PaO_2/FiO_2 < 150$** após **$\ge 12\text{ h}$** de VM otimizada, pronando por **$\ge 16\text{ horas}$**.
- [ ] **Interpretação Fisiopatológica e Diferenciais:** Explicar que na SARA a baixa complacência torna a constante de tempo curta, mas exige altas pressões de distensão que geram lesão pulmonar induzida pelo ventilador (VILI); por isso, acidose respiratória leve/moderada ($pH \ge 7,2$) é preferível a elevar o VC ou ultrapassar $P_{platô}$ de $30\text{ cmH}_2\text{O}$ e FR de $35\text{ irpm}$.
- [ ] **Reconhecimento de Falhas / Alarmes e Correção Imediata:** Invalidar qualquer cálculo de complacência estática feito com paciente realizando esforço inspiratório/expiratório ativo ($P_{mus} \neq 0$) ou sem pausa inspiratória efetiva; caso $P_{platô} \ge 30\text{ cmH}_2\text{O}$ ou $\Delta P \ge 15\text{ cmH}_2\text{O}$, reduzir progressivamente o VC até $4\text{ mL/kg}$ ajustando a FR até $35\text{ irpm}$.

**3. Constructo Profissional-Subjetivo (Postura e Verbalização Estruturada)**
- [ ] **Script de Verbalização ao Avaliador:** *
- [ ] "Para aferir a mecânica estática com precisão, 
	- [ ] garanto ausência de esforço muscular sob bloqueio neuromuscular 
	- [ ] em VCV com fluxo quadrado de 60 L/min (1 L/s)
	- [ ] e executo pausa inspiratória: 
		- [ ] pela Equação do Movimento sem Pmus e sem fluxo, a queda da Ppico para a Pplatô fornece a pressão resistiva e a resistência ($P_{pico} - P_{platô}$ dividido pelo fluxo em L/s), 
		- [ ] enquanto a diferença entre Pplatô e PEEP define a driving pressure e permite calcular a complacência estática ($VC / [P_{platô} - PEEP]$). 
	- [ ] Neste paciente com SARA, 
		- [ ] ajusto VC entre 4 e 8 mL/kg 
		- [ ] buscando Pplatô menor que 30 cmH2O, 
		- [ ] driving pressure menor que 15 cmH2O e
		- [ ] FR até 35 irpm, 
		- [ ] tolerando hipercapnia permissiva até pH de 7,2. 
	- [ ] Persistindo P/F abaixo de 150 após 12 horas de VM otimizada, indico posição prona por pelo menos 16 horas."*
- [ ] **Segurança e Controle de Qualidade:** Converter obrigatoriamente o fluxo de $\text{L/min}$ para $\text{L/s}$ antes de dividir `$P_{pico} - P_{platô}$`; checar ausência de vazamento no circuito durante a pausa inspiratória (vazamento faz a $P_{platô}$ cair continuamente sem formar platô `[Padrão CTEMI]`).

**Armadilhas de Prova & Troubleshooting Rápido**
* **Pegadinha / Erro Pré-Analítico:** Calcular resistência dividindo `$P_{pico} - P_{platô}$` pelo fluxo em $\text{L/min}$ (ex.: dividir por $60$ em vez de $1\text{ L/s}$) -> **Efeito na Leitura:** Valor de resistência $60\text{ vezes}$ menor que o real -> **Conduta Corretiva:** Converter sempre o fluxo para **litros por segundo ($\text{L/s} = \text{L/min} \div 60$)**.
* **Pegadinha / Erro Pré-Analítico:** Elevar o VC para $9\text{ mL/kg}$ ou a FR para $42\text{ irpm}$ para corrigir $PaCO_2$ de $58\text{ mmHg}$ com $pH = 7,26$ na SARA -> **Efeito na Leitura:** Indução de VILI e aprisionamento aéreo -> **Conduta Corretiva:** Manter **hipercapnia permissiva** respeitando os tetos protetores enquanto **$pH \ge 7,2$**.

---

## Estação Prática: Ventilando o Obstruído Crítico, Alarme de Pressão Bloqueando Volume e Manejo da Auto-PEEP
**Gatilho Clínico / Tarefa da Estação:** Paciente asmático grave (ou com rolha no TOT) evolui com dessaturação aguda, volume corrente expirado zerado/mínimo e alarme sonoro contínuo de pressão máxima no ventilador. Execute a conduta salvadora imediata no ventilador, diferencie resistência elevada de baixa complacência e corrija a Auto-PEEP.

**1. Constructo Técnico-Procedimental (Execução, Setup e Segurança)**
- [ ] **Preparo e Material:** Checar imediatamente acoplamento paciente-ventilador, permeabilidade do tubo orotraqueal (sonda de aspiração / laringoscópio e novo TOT caso haja obstrução fixa por rolha), espaçador para broncodilatadores inalatórios, corticoide venoso e drogas para sedação profunda e bloqueio neuromuscular.
- [ ] **Posicionamento / Nivelamento / Configuração:** Diante de paciente **hipoventilando e dessaturando porque o alarme de pressão máxima está ciclagem/abortando a entrada de ar**, **desativar ou elevar imediatamente o limite superior do alarme de pressão até o máximo** no painel do ventilador para garantir que o volume corrente volte a entrar nos pulmões!
- [ ] **Execução Sequencial:** Aplicar sequencialmente as **3 Regras de Ouro do Obstruído Crítico**:
  1. **Garantir entrada imediata de ar (Regra 2 — Emergência Zero):** Elevar/desarmar o alarme de pressão máxima $\rightarrow$ promover **sedação profunda e bloqueio neuromuscular** se houver grande desconforto/dificuldade ventilatória até estabilizar;
  2. **Diagnosticar a mecânica resistiva e tratar a causa de base (Regra 1):** Realizar pausa inspiratória confirmando **$P_{pico}$ muito alta com $P_{platô}$ normal** (aumento isolado de pressão resistiva: broncoespasmo, secreção, dobra no TOT ou mordedura do tubo) $\rightarrow$ administrar **broncodilatadores + corticoides** se broncoespasmo, aspirar secreções ou **trocar imediatamente o tubo orotraqueal se rolha refratária**;
  3. **Prevenir e reverter a Auto-PEEP (Regra 3):** Como a constante de tempo (`$CT = C \times R$`) está muito elevada, prolongar maximamente o **tempo expiratório** (reduzindo a FR para $8\text{–}12\text{ irpm}$ e encurtando o $T_{ins}$ / elevando o fluxo em VCV `[Padrão CTEMI]`) até que a curva de fluxo expiratório retorne a zero antes do ciclo seguinte.

**2. Constructo Cognitivo-Operacional ("Cognição em Movimento")**
- [ ] **Padrão Visual / Curva / Achado Esperado:** Reconhecer dois padrões gráficos patognomônicos na tela do ventilador:
  - **Curva de Pressão na Alta Resistência:** pico inspiratório extremamente elevado ($P_{pico} \uparrow\uparrow$) seguido de queda abrupta na pausa inspiratória para uma **$P_{platô}$ próxima do normal** (`$P_{pico} - P_{platô}$` alargado);
  - **Curva de Fluxo na Auto-PEEP:** o ramo expiratório (negativo) **não retorna à linha de base zero ($0\text{ L/min}$)** antes do início do próximo ciclo inspiratório, formando um degrau truncado de fluxo expiratório persistente.
- [ ] **Cálculos e Pontos de Corte:** Relacionar o aumento da resistência à fórmula `$CT = \text{Complacência} \times \text{Resistência}$`: o aumento acentuado de $R$ multiplica as **$3\text{ Constantes de Tempo}$** necessárias para exalar $95\%$ do ar; se o $T_{exp}$ disponível for menor que $3 \times CT$, instala-se aprisionamento aéreo ciclo a ciclo. Quantificar a Auto-PEEP estática realizando manobra de **pausa expiratória** (`$PEEP_{total} - PEEP_{extrínseca}$` `[Padrão CTEMI]`).
- [ ] **Interpretação Fisiopatológica e Diferenciais:** Listar ao examinador todas as causas de **alarme de pressão alta no ventilador**:
  - **Aumento da Pressão Resistiva (`$P_{pico} \uparrow$`, `$P_{platô}$` normal):** broncoespasmo/asma, rolha/excesso de secreção no TOT, dobradura (*kinking*) do tubo/circuito, paciente mordendo o tubo ou tossindo;
  - **Aumento da Pressão Elástica / Queda da Complacência (`$P_{pico} \uparrow$`, `$P_{platô} \uparrow$`):** pneumotórax hipertensivo, intubação seletiva, atelectasia lobar, edema pulmonar/SARA, síndrome compartimental abdominal, **hiperinsuflação dinâmica por Auto-PEEP** ("efeito bola de neve") `[Padrão CTEMI]`.
  Compreender que a Auto-PEEP não corrigida evolui de forma catastrófica para **barotrauma, pneumotórax hipertensivo e choque obstrutivo** (queda abrupta do retorno venoso).
- [ ] **Reconhecimento de Falhas / Alarmes e Correção Imediata:** Reconhecer que em VCV o limite superior do alarme de pressão funciona como válvula de segurança que **interrompe imediatamente a inspiração** ao ser atingido, zerando o volume entregue; em caso de hipotensão grave súbita no obstruído crítico, desconectar transitoriamente o paciente do ventilador por alguns segundos para esvaziamento completo do ar aprisionado e afastar pneumotórax hipertensivo `[Padrão CTEMI]`.

**3. Constructo Profissional-Subjetivo (Postura e Verbalização Estruturada)**
- [ ] **Script de Verbalização ao Avaliador:** 
- [ ] *"O paciente está dessaturando por 
	- [ ] hipoventilação grave porque o alarme de pressão máxima está abortando a fase inspiratória e bloqueando a entrada de volume! 
	- [ ] Não há emergência maior que um paciente que não ventila: 
- [ ] minha primeira ação imediata é
	- [ ] elevar ao máximo (ou desarmar) o limite do alarme de pressão para garantir a entrada do ar, 
	- [ ] associando sedação profunda e bloqueio neuromuscular. 
- [ ] Pela pausa inspiratória confirmo que o alarme decorre de aumento isolado da pressão resistiva (Ppico alta com Pplatô normal): 
	- [ ] checo mordedura, dobras, 
	- [ ] aspiro secreções, troco o TOT se houver rolha 
	- [ ] ou trato broncoespasmo com broncodilatador e corticoide. 
- [ ] Em seguida, reduzo a FR para prolongar o tempo expiratório acima de 3 constantes de tempo, 
	- [ ] eliminando a Auto-PEEP visível na curva de fluxo 
	- [ ] para prevenir barotrauma, pneumotórax e choque obstrutivo."*
- [ ] **Segurança e Controle de Qualidade:** Após resolver a causa resistiva aguda (ex.: troca do TOT obstruído ou reversão do broncoespasmo), **reajustar o alarme de pressão máxima** para faixa segura individualizada `[Padrão CTEMI]` e revalidar a $P_{platô}$ ($<30\text{ cmH}_2\text{O}$).

**Armadilhas de Prova & Troubleshooting Rápido**
* **Pegadinha / Erro Pré-Analítico:** Reduzir o volume corrente a níveis incompatíveis com a vida ou apenas silenciar o som do alarme sem subir o limite de pressão máxima em VCV -> **Efeito na Leitura:** Ventilador continua cortando a inspiração no teto pressórico, mantendo hipoventilação asfíxica -> **Conduta Corretiva:** **Elevar o limite do alarme de pressão ao máximo** imediatamente para garantir entrada de volume e tratar a resistência elevada.
* **Pegadinha / Erro Pré-Analítico:** Ignorar curva de fluxo expiratório que não toca o zero -> **Efeito na Leitura:** Efeito "bola de neve" de hiperinsuflação progressiva levando a PCR em AESP/choque obstrutivo -> **Conduta Corretiva:** Prolongar o tempo expiratório (reduzir FR e $T_{ins}$) até o fluxo expiratório zerar completamente antes de cada disparo.

---

## Estação Prática: Diagnóstico Visual e Correção de Assincronias Paciente-Ventilador, Secreção e Vazamento Aéreo
**Gatilho Clínico / Tarefa da Estação:** Durante visita à UTI, o examinador apresenta telas de ventiladores mecânicos exibindo desconforto e alterações gráficas nas curvas de pressão, fluxo e volume (incluindo um paciente drenado de tórax com perda súbita de volume expirado). Identifique visualmente cada assincronia/artefato e execute a correção exata.

**1. Constructo Técnico-Procedimental (Execução, Setup e Segurança)**
- [ ] **Preparo e Material:** Inspecionar simultaneamente o paciente à beira-leito (uso de musculatura acessória, batimento de asa nasal, esforço expiratório abdominal, nível de sedação RASS `[Padrão CTEMI]`), a integridade externa do circuito/*cuff*/drenos torácicos e as 3 curvas escalares sincronizadas na tela (Pressão $\times$ Tempo, Fluxo $\times$ Tempo e Volume $\times$ Tempo).
- [ ] **Posicionamento / Nivelamento / Configuração:** Congelar a tela (`Freeze`) quando necessário para alinhar verticalmente o início do esforço muscular ($P_{mus}$/deflexão pressórica) com as transições de disparo, entrega de fluxo e ciclagem do ventilador.
- [ ] **Execução Sequencial:** Diagnosticar o grupo da alteração (Fluxo, Ciclagem, Disparo ou Artefato de Circuito/Vazamento), realizar o ajuste fino direcionado no ventilador (ou no paciente/circuito: aspiração, re-insuflação de *cuff*, reconexão de dreno de tórax no selo d'água, ajuste de sedação/BNM) e reavaliar as curvas nos ciclos seguintes confirmando resolução completa.

**2. Constructo Cognitivo-Operacional ("Cognição em Movimento")**
- [ ] **Padrão Visual / Curva / Achado Esperado & Conduta Corretiva:** Reconhecer com 100% de acurácia os **10 padrões gráficos obrigatórios da prova prática do TEMI**:

| Assincronia / Achado | Grupo | Padrão Visual Exato nas Curvas (Pressão, Fluxo e Volume) | Fisiopatologia / Causa | Conduta Corretiva Imediata |
| :--- | :--- | :--- | :--- | :--- |
| **Fluxo Insuficiente** | Fluxo | "Escavação" (concavidade negativa) na curva de pressão em VCV por $P_{mus}$ negativa intensa | Ventilador entrega menos fluxo que a fome de ar do paciente | **Aumentar o fluxo** (em VCV) ou **mudar para PCV/PSV** (fluxo livre) |
| **Fluxo Excessivo** | Fluxo | Pico precoce (*overshoot*) de sobrecarga no início das curvas de pressão e de fluxo | Falha de acomodação pulmonar ao jato inicial abrupto de ar | **Reduzir fluxo e/ou pressão**, ou **aumentar o tempo de subida (*slope*/*rise time*)** |
| **Ciclagem Precoce** | Ciclagem | Inflexão positiva (retorno em direção ao zero) logo no **início da curva de fluxo expiratório** | Ventilador cicla antes do fim do esforço inspiratório do paciente | **Aumentar o tempo inspiratório ($T_{ins}$)** (ou reduzir % de ciclagem em PSV `[Padrão CTEMI]`) |
| **Ciclagem Tardia** | Ciclagem | Elevação terminal na curva de pressão no fim da inspiração (***overshoot* de saída**) e platô zero no fluxo | Paciente já força exalação enquanto o ventilador mantém inspiração | **Reduzir o tempo inspiratório ($T_{ins}$)** (ou elevar % de ciclagem em PSV `[Padrão CTEMI]`) |
| **Disparo Ineficaz** | Disparo | Queda negativa na pressão + entalhe positivo no fluxo expiratório **sem gerar ciclo ventilatório** | Limiar de disparo alto, **Auto-PEEP** e/ou ciclagem tardia prévia | **Ajustar sensibilidade** (mais sensível) + **corrigir Auto-PEEP e ciclagem tardia** |
| **Autodisparo** | Disparo | Múltiplos disparos rápidos sem deflexão de esforço do paciente ($P_{mus}=0$) | Toques/mobilização, **batimentos cardíacos**, condensado no circuito | **Ajustar sensibilidade** (menos sensível) e eliminar estímulo/artefato externo |
| **Duplo Disparo** | Disparo | **1º ciclo disparado pelo paciente** seguido imediatamente de 2º ciclo sem exalar (**empilhamento de VC**) | Esforço inspiratório único muito intenso e prolongado | **Aumentar VC** (se seguro) ou **aumentar $T_{ins}$**; se impossível (SARA), **bloqueio neuromuscular** |
| **Disparo Reverso** | Disparo | **1º ciclo controlado (sem esforço)** seguido de 2º ciclo reflexo disparado pelo paciente | Reflexo diafragmático à distensão pulmonar sob **sedação profunda** | **Reduzir a sedação** (se possível); caso contrário, **bloqueio neuromuscular** |
| **Secreção no Circuito** | Artefato | **Oscilações serrilhadas ("dentes de serra")** na linha de base / ramo expiratório do fluxo | Excesso de secreção no TOT ou líquido condensado nas traqueias | **Aspirar o tubo orotraqueal** e drenar líquidos do circuito ventilatório |
| **Vazamento de Ar** | Artefato | **Degrau vertical truncado na curva de volume** retornando a zero ($VTi > VTe$) | Extubação acidental, *cuff* vazio, fístula aérea ou **dreno desconectado** | Checar posição do TOT, pressão do *cuff*, fístula e **reconectar dreno tubular ao selo d'água** |

- [ ] **Cálculos e Pontos de Corte:** Quantificar o vazamento pela diferença `$VTi - VTe$` no painel numérico; observar no **duplo disparo** e no **disparo reverso** que o empilhamento duplica o volume entregue (ex.: $>750\text{ mL}$, violando gravemente os $4\text{–}8\text{ mL/kg}$ da ventilação protetora!).
- [ ] **Interpretação Fisiopatológica e Diferenciais:** Diferenciar cirurgicamente **Duplo Disparo** vs **Disparo Reverso** (cujas curvas se assemelham pelo empilhamento, mas têm condutas opostas quanto à sedação!): no duplo disparo o **1º ciclo nasce de um esforço do paciente** (alto *drive*), enquanto no disparo reverso o **1º ciclo é mandatório do ventilador** em paciente profundamente sedado. Lembrar também que o **disparo ineficaz** frequentemente é secundário à **Auto-PEEP** e à **ciclagem tardia** (corrigir essas duas condições resolve o disparo ineficaz na raiz).
- [ ] **Reconhecimento de Falhas / Alarmes e Correção Imediata:** Diante do degrau de truncamento na curva de volume em paciente com dreno torácico (questão recente do TEMI), inspecionar imediatamente toda a extensão do dreno tubular até o frasco coletor, identificando **desconexão do dreno no selo d'água** que permite fuga maciça do volume inspirado pela fístula broncopleural.

**3. Constructo Profissional-Subjetivo (Postura e Verbalização Estruturada)**
- [ ] **Script de Verbalização ao Avaliador:** *
- [ ] "Na análise sistematizada das curvas, 
	- [ ] identifico um degrau abrupto de reinicialização no final da curva de volume, 
	- [ ] demonstrando que o volume inspirado é maior que o expirado por vazamento fora do circuito. 
- [ ] Além de checar extubação parcial e pressão do cuff, 
	- [ ] inspeciono o sistema de drenagem pleural e identifico desconexão do dreno tubular no selo d'água, procedendo à reconexão imediata. 
- [ ] Quanto ao empilhamento de ciclos na tela ao lado, 
	- [ ] diferencio duplo disparo de disparo reverso olhando o primeiro ciclo: 
	- [ ] como o primeiro ciclo foi deflagrado pelo ventilador sem esforço prévio em paciente sob sedação profunda, trata-se de disparo reverso, 
	- [ ] cuja conduta é reduzir a sedação ou, se houver SARA grave exigindo proteção pulmonar estrita, instituir bloqueio neuromuscular."*
- [ ] **Segurança e Controle de Qualidade:** Nunca tratar fome de fluxo ou ciclagem precoce simplesmente aprofundando sedação sem antes adequar o fluxo, o *slope* ou o $T_{ins}$ do ventilador às demandas fisiológicas do paciente (salvo quando o ajuste violar limites de proteção pulmonar na SARA).

**Armadilhas de Prova & Troubleshooting Rápido**
* **Pegadinha / Erro Pré-Analítico:** Aumentar a sedação diante de Disparo Reverso achando que o paciente está "agitado/brigando" -> **Efeito na Leitura:** Manutenção ou piora do reflexo de aprisionamento (*entrainment*) e do empilhamento lesivo -> **Conduta Corretiva:** Reconhecer que o disparo reverso decorre de **sedação profunda**; **reduzir a sedação** (ou fazer bloqueio neuromuscular se precisar manter proteção estrita).
* **Pegadinha / Erro Pré-Analítico:** Restringir a busca de vazamento na curva de volume apenas ao *cuff* do TOT -> **Efeito na Leitura:** Falha em resolver o vazamento na estação simulada de trauma/pós-operatório torácico -> **Conduta Corretiva:** Checar sistematicamente **extubação acidental, *cuff* desinsuflado, fístula aérea e desconexão do dreno tubular no selo d'água**.

---

## Estação Prática: Ultrassonografia de Diafragma na Decisão do Desmame da Ventilação Mecânica
**Gatilho Clínico / Tarefa da Estação:** Paciente em ventilação mecânica prolongada está apto clinicamente para avaliação de extubação. Explique e demonstre como realizar a ultrassonografia de diafragma (espessamento e excursão), incluindo o ajuste obrigatório no ventilador antes do exame e os pontos de corte preditores de falha de extubação.

**1. Constructo Técnico-Procedimental (Execução, Setup e Segurança)**
- [ ] **Preparo e Material:** Dispor de aparelho de ultrassom equipado com **transdutor linear** (alta frequência, para espessamento) e **transdutor curvilíneo** (baixa frequência, para excursão), gel condutor e monitorização cardiorrespiratória contínua à beira-leito.
- [ ] **Posicionamento / Nivelamento / Configuração:** Posicionar o paciente em decúbito dorsal semi-elevado `[Padrão CTEMI]` e executar o **pré-requisito obrigatório no ventilador mecânico**: **reduzir a Pressão de Suporte (PS) para $0\text{ cmH}_2\text{O}$** antes de realizar as medidas (evitando que a assistência pressórica positiva mascare a disfunção contrátil diafragmática!).
- [ ] **Execução Sequencial:**
  - **Medida 1 — Fração de Espessamento Diafragmático:** Selecionar o **transdutor linear** $\rightarrow$ posicionar nos espaços intercostais inferiores (zona de aposição no **8º a 9º espaço intercostal** entre linhas axilares anterior e média) $\rightarrow$ identificar em Modo B a parede torácica e as três camadas do diafragma (membrana pleural hiperecogênica superior, camada muscular hipoecoica central e membrana peritoneal hiperecogênica inferior) $\rightarrow$ aplicar o **Modo M** e medir a espessura ao final da expiração e no pico da inspiração.
  - **Medida 2 — Excursão Diafragmática:** Selecionar o **transdutor curvilíneo** $\rightarrow$ posicionar na janela subcostal anterior direita (usando o fígado como janela acústica `[Padrão CTEMI]`) apontando cranialmente para a cúpula diafragmática $\rightarrow$ aplicar o **Modo M** alinhado ao movimento vertical ("sobe e desce") do diafragma e medir a amplitude do deslocamento inspiratório em milímetros.

**2. Constructo Cognitivo-Operacional ("Cognição em Movimento")**
- [ ] **Padrão Visual / Curva / Achado Esperado:**
  - **No transdutor linear (zona de aposição):** duas linhas paralelas brilhantes (**membrana pleural** acima e **membrana peritoneal** abaixo) que se afastam na inspiração ativa por encurtamento/espessamento muscular no Modo M (ex.: `A = 0,25 cm` na expiração expandindo para `B = 0,46 cm` na inspiração);
  - **No transdutor curvilíneo (excursão):** linha curva hiperecogênica justa-hepática desenhando onda senoidal de subida e descida no traçado temporal do Modo M.
- [ ] **Cálculos e Pontos de Corte:** Aplicar os dois pontos de corte diagnósticos de **disfunção diafragmática (alto risco de falha de extubação)**:
  - **Variação da espessura (fração de espessamento) na inspiração:** calculada por `$\frac{\text{Espessura}_{insp} - \text{Espessura}_{exp}}{\text{Espessura}_{exp}} \times 100$` `[Padrão CTEMI]` $\rightarrow$ variações **menores que $30\%\text{ a }36\%$** indicam **disfunção diafragmática**;
  - **Excursão diafragmática:** valores **abaixo de $11\text{ mm}$ ($<1,1\text{ cm}$)** indicam **disfunção diafragmática** e alto risco de falha de extubação.
- [ ] **Interpretação Fisiopatológica e Diferenciais:** Explicar ao avaliador que a fraqueza adquirida do diafragma induzida pela ventilação mecânica é causa central de falha de desmame; quando realizada sem assistência inspiratória ($PS = 0\text{ cmH}_2\text{O}$), a ultrassonografia quantifica diretamente a geração de força/encurtamento muscular intrínseco do paciente, orientando otimização clínica, reabilitação muscular ou extubação preventiva diretamente para VNI/CNAF em pacientes de alto risco `[Padrão CTEMI]`.
- [ ] **Reconhecimento de Falhas / Alarmes e Correção Imediata:** Reconhecer erro técnico grave caso a excursão seja medida com o paciente recebendo pressão positiva inspiratória (ex.: $PS\ 10\text{ cmH}_2\text{O}$), pois a insuflação passiva do ventilador empurra o diafragma caudalmente gerando falsa excursão normal mesmo em diafragma paralisado; repetir sempre com **$PS = 0\text{ cmH}_2\text{O}$**.

**3. Constructo Profissional-Subjetivo (Postura e Verbalização Estruturada)**
- [ ] **Script de Verbalização ao Avaliador:** 
- [ ] *"Para que a ultrassonografia de diafragma reflita o esforço real do paciente no desmame, 
- [ ] primeiro reduzo a pressão de suporte do ventilador para 0 cmH2O e Avalio duas variáveis complementares no Modo M: 
	- [ ] primeiro, com o transdutor linear na zona de aposição (8º–9º espaço intercostal), meço a variação da espessura entre as membranas pleural e peritoneal da expiração para a inspiração, 
		- [ ] onde valores menores que 30 a 36% diagnosticam disfunção diafragmática; 
	- [ ] segundo, com o transdutor curvilíneo subcostal, meço o movimento vertical de excursão do diafragma,
		- [ ] onde valores abaixo de 11 mm indicam disfunção diafragmática e alto risco de falha de extubação."*
- [ ] **Segurança e Controle de Qualidade:** Monitorar frequência respiratória, oximetria e sinais de fadiga durante os minutos em $PS = 0\text{ cmH}_2\text{O}$, retornando o suporte ventilatório adequado imediatamente após concluir a aquisição das imagens `[Padrão CTEMI]`.

**Armadilhas de Prova & Troubleshooting Rápido**
* **Pegadinha / Erro Pré-Analítico:** Medir excursão ou espessamento diafragmático mantendo Pressão de Suporte ligada ($8\text{–}12\text{ cmH}_2\text{O}$) -> **Efeito na Leitura:** Deslocamento diafragmático passivo induzido pelo ventilador mascarando paresia diafragmática (falso-negativo) -> **Conduta Corretiva:** Reduzir obrigatoriamente a **Pressão de Suporte para $0\text{ cmH}_2\text{O}$** antes de adquirir as medidas.
* **Pegadinha / Erro Pré-Analítico:** Inverter os transdutores (usar curvilíneo para espessura milimétrica ou linear para excursão profunda da cúpula) -> **Efeito na Leitura:** Falha de resolução axial na zona de aposição ou alcance insuficiente subcostal -> **Conduta Corretiva:** Usar **transdutor linear** para **espessamento ($<30\text{–}36\%$)** e **transdutor curvilíneo** para **excursão ($<11\text{ mm}$)**.