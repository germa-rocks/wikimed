---
publish: true
---

# Princípios Físicos e Nomenclatura em Ventilação Mecânica

- **Regra de Ouro: Evite os termos ambíguos "mandatório/obrigatório" vs "espontâneo"; utilize a taxonomia moderna baseada em 3 variáveis independentes (Modelo *Trigger-Target-Cycle*).**
	- O paradigma mudou: Atualmente, pacientes podem disparar incursões "mandatórias" e receber suporte de pressão em incursões "espontâneas". A terminologia clássica não descreve com precisão a ventilação moderna.
	- Da mesma forma, evite o termo "Controle" como sinônimo geral; prefira "Alvo" (Target) para descrever o que o ventilador manipula e guarde "Controle" estritamente para respirações iniciadas pela máquina.
	- Independentemente da marca do ventilador (que utilizam nomenclaturas comerciais confusas), todos operam sob princípios mecânicos seculares (análogos ao fole de lareira).

# O Modelo de 3 Componentes (*Trigger - Target - Cycle*)

- **1. TRIGGER (Disparo): É a variável que inicia a fase inspiratória.**
	- Pode ser disparado pelo **Tempo** (Incursão Controlada - timer da máquina) ou por **Esforço** (Incursão Assistida/Suportada).
	- **Tipos de Disparo por Esforço do Paciente:**
		- Disparo a Pressão (*Pressure trigger*): O esforço inspiratório gera uma queda de pressão no circuito fechado. A sensibilidade é ditada pelo valor de pressão negativa configurado.
		- Disparo a Fluxo (*Flow trigger*): Há um fluxo contínuo basal no circuito. O esforço do paciente desvia parte desse gás, e a máquina lê essa variação de fluxo. A sensibilidade é ditada pela quantidade de fluxo desviado (método mais comum atualmente; a maioria das máquinas lê pressão e fluxo simultaneamente e responde ao primeiro detectado).
	- **Sensores Avançados de Disparo (para superar *Trigger Delays*):**
		- Medição de Pressão Esofágica (Pes).
		- Eletromiografia Diafragmática (Edi / NAVA): Um cateter esofágico capta a atividade elétrica do diafragma. Apresenta resposta e sensibilidade superiores aos métodos pneumáticos.

- **2. TARGET (Alvo/Limite): É a variável primária que governa o fluxo de gás durante a inspiração.**
	- **Alvo de Fluxo (*Set Flow*):** Garante a entrega de um fluxo constante e, por consequência, um Volume Corrente (Vc) exato.
		- *Variável Dependente:* Pressão em vias aéreas (aumenta ou diminui conforme mecânica pulmonar, complacência, resistência e esforço do paciente).
		- *Indicação Clínica:* Uso prioritário quando o controle rigoroso do volume corrente e da ventilação minuto é inegociável.
	- **Alvo de Pressão (*Set Pressure*):** Garante uma pressão inspiratória fixa (em formato de onda quadrada).
		- *Variável Dependente:* Fluxo e Volume Corrente. O fluxo torna-se desacelerado e adapta-se à mecânica do paciente.
		- *Indicação Clínica:* Facilita a sincronia paciente-ventilador. O fluxo variável atende melhor aos picos de demanda inspiratória do paciente.

- **3. CYCLE (Ciclagem): É a variável que encerra a inspiração e abre a válvula expiratória.**
	- **Ciclagem a Volume:** A inspiração cessa quando o volume predefinido é entregue (Típico do *Set Flow*).
	- **Ciclagem a Tempo:** A inspiração cessa após decorrido o Tempo Inspiratório (Ti) predefinido em segundos (Típico da Pressão Controlada).
	- **Ciclagem a Fluxo:** A inspiração cessa quando o fluxo inspiratório cai para uma porcentagem predeterminada do pico de fluxo (Ex: 25%). Característico da Pressão de Suporte.
	- **Ciclagem a Pressão (Mecanismo de Segurança):** Raramente usada como ciclagem primária, atua como limite de alarme de pico de pressão para encerrar o ciclo preventivamente e evitar barotrauma.

# Avaliação e Manejo Beira-Leito: Atrasos de Disparo e Auto-PEEP

- **A presença de Auto-PEEP (aprisionamento aéreo crônico/agudo) é a causa principal de grave assincronia de disparo e esforço ineficaz (*missed trigger*).**
	- **Fisiopatologia do Atraso:** Em cenários de obstrução de via aérea (ex: DPOC, Asma grave), o tempo expiratório é insuficiente e o pulmão retém pressão positiva ao final da expiração (Auto-PEEP). Para acionar o sensor do ventilador (que está calibrado na linha de base da PEEP ajustada), o paciente precisa gerar um esforço inspiratório excessivo para, primeiro, vencer e "zerar" o Auto-PEEP e, somente depois, atingir o limiar do *trigger*.
	- **Diagnóstico Físico Rápido (Sem cateter esofágico): Técnica Mão-Tórax + Olho-Tela.**
		- Coloque a mão no tórax do paciente e palpe a contração da musculatura inspiratória.
		- Olhe para a curva de fluxo/pressão no monitor.
		- *Achado:* Se você sente o esforço muscular, mas o ventilador apresenta um claro atraso na entrega do fluxo ou ignora a incursão completamente, o diagnóstico clínico de Auto-PEEP atrapalhando o disparo está feito.
	- **Manejo Clínico de Primeira Linha: Titulação de PEEP Extrínseca.**
		- *Conduta:* Aumentar cautelosamente a PEEP configurada no ventilador em incrementos de 3 a 5 cmH2O (80% a 90% do valor do Auto-PEEP medido, se disponível).
		- *Mecanismo:* A PEEP extrínseca eleva a pressão basal das vias aéreas, "fechando o fosso" de pressão que o paciente precisava vencer. Isso reduz o trabalho muscular necessário para acionar o disparo, restaurando a sincronia sem necessariamente piorar a hiperinsuflação (na doença obstrutiva).

# Os 5 Tipos Básicos de Incursões Respiratórias (*Breaths*)

- **Ao combinar as variáveis de Trigger, Target e Cycle, fisiologicamente, existem apenas 5 tipos de incursões possíveis:**
	- **1. Volume Control (VC):** Disparo por *Tempo* | Alvo de *Fluxo* | Ciclagem a *Volume*. (100% máquina).
	- **2. Volume Assist (VA):** Disparo por *Esforço* | Alvo de *Fluxo* | Ciclagem a *Volume*.
	- **3. Pressure Control (PC):** Disparo por *Tempo* | Alvo de *Pressão* | Ciclagem a *Tempo*.
	- **4. Pressure Assist (PA):** Disparo por *Esforço* | Alvo de *Pressão* | Ciclagem a *Tempo*.
	- **5. Pressure Support (PS):** Disparo por *Esforço* | Alvo de *Pressão* | Ciclagem a *Fluxo*. (Única respiração puramente espontânea suportada).

# Os 5 Modos Ventilatórios Básicos (e o APRV)

- **Cuidado com nomes comerciais (Proprietários): Os modos são os mesmos, mas os rótulos mudam conforme a marca (ex: PB840, Avea, Servo I). Baseie a sua interpretação na fisiologia dos 5 Modos Básicos:**
	- **Volume Assist/Control (VACV):** Combina *Volume Control* e *Volume Assist*. A FR de backup dita os ciclos controlados; esforços adicionais do paciente geram ciclos assistidos com o mesmo volume fixo.
	- **Pressure Assist/Control (PACV):** Combina *Pressure Control* e *Pressure Assist*. Semelhante ao VACV, mas todas as incursões entregam uma pressão inspiratória (Pi) predefinida e ciclam a tempo.
	- **Volume SIMV / Pressure SIMV:** Mistura respirações mandatórias sincronizadas (a Volume ou a Pressão) com janelas onde o paciente pode fazer respirações 100% espontâneas (com ou sem Pressão de Suporte). O seu uso clínico tem decaído pela inferioridade adaptativa em comparação a modos mais modernos.
	- **Pressure Support Ventilation (PSV/CPAP):** Modo totalmente espontâneo. Todas as respirações são *Pressure Support* (disparo a esforço, pressão de alvo, ciclagem a fluxo).

- **APRV (Airway Pressure Release Ventilation): Não é um modo independente, mas sim uma variação da engenharia do modo Pressure SIMV.**
	- *Fisiologia e Configuração:* É um SIMV a Pressão configurado com uma relação Inspiração:Expiração (I:E) altamente invertida (ex: tempos inspiratórios até 10-12 vezes maiores que os expiratórios).
	- *Efeito Alvo:* O longo tempo inspiratório (*T High*) aumenta substancialmente a Pressão Média das Vias Aéreas, garantindo um potente recrutamento alveolar sem necessidade de aumentar Volume Corrente de pico ou PEEP.
	- *Por que o paciente tolera?* Porque a válvula do APRV permite que o paciente realize ciclos espontâneos (ou respire com Pressão de Suporte) a qualquer momento, *mesmo durante a fase de alta pressão inspiratória*, melhorando a mistura de gases e o conforto anatômico.
	- *Nomenclaturas Comerciais Confusas do APRV:* Pode ser encontrado como BiLevel (Puritan Bennett), BiPhasic (Avea) ou Bi-Vent (Servo).