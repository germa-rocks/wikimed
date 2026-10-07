---
publish: true
---

Aqui está a base de conhecimento estruturada em Markdown, focada no formato de listas aninhadas (toggles) para o princípio de divulgação progressiva, completamente livre das tags de formatação do texto original e voltada para a aplicação clínica beira-leito e provas de residência/título.

# Modos Ventilatórios Básicos

## O Ciclo Ventilatório e a Janela Respiratória
* **A "Janela Respiratória" representa o tempo total de um ciclo ventilatório (Inspiração + Expiração), sendo estritamente dependente da frequência respiratória (FR).**
	* O tempo não é uma grandeza que o operador manipula livremente de forma direta; ele é consequência matemática da FR configurada.
	* ==Cálculo da Janela: 60 segundos divididos pela FR.
		* *Exemplo prático:* Se a FR está ajustada para 20 irpm, a janela respiratória é de 3 segundos (60 / 20 = 3).
	* **Relação I:E (Tempo Inspiratório : Tempo Expiratório):** 
		* ==Em uma ventilação fisiológica padrão, a relação I:E é de cerca de 1:2 (a expiração dura o dobro do tempo da inspiração). 
		* No cenário de uma janela de 3 segundos, teríamos 1 segundo de inspiração e 2 segundos de expiração.
	* 🚨 **Red Flag Clínica: Risco de Auto-PEEP em Padrões Obstrutivos.**
		* ==Pacientes com alta resistência das vias aéreas (ex: asma grave, DPOC) possuem tempo expiratório prolongado.
		* Fisiopatologia: Se a mecânica do paciente exige 4,5 segundos para exalar todo o volume, mas a janela respiratória configurada no ventilador só oferece 3 segundos totais, o ar ficará aprisionado no tórax.
		* ==Conduta: Em perfis obstrutivos, exige-se uma Frequência Respiratória baixa para alargar a janela respiratória e fornecer mais tempo para a expiração, evitando a hiperinsuflação dinâmica (auto-PEEP).

## Perspectiva do Ventilador e Variáveis de Fase
* **Todo ciclo inspiratório obrigatoriamente possui três fases: Começo (Disparo), Meio (Alvo/Limite) e Fim (Ciclagem). O modo ventilatório levará o nome da variável que domina o "Meio" da história.**
	* **1. Fase de Disparo (Gatilho / Trigger):** É o COMEÇO. Momento de abertura da válvula inspiratória.
		* Disparo a Tempo: Determinado puramente pelo ventilador, independentemente do paciente. Define os ciclos *Controlados*.
		* Disparo a Pressão ou a Fluxo: Ocorre quando a máquina percebe o ==esforço== do paciente. Define os ciclos *Assistidos*.
	* **2. Fase de Limite ou Alvo:** É o MEIO. É a variável que se mantém **CONSTANTE** durante a entrada do ar.
		* "Procure a variável alvo e o modo dirá seu nome".
		* Se o Fluxo é constante/quadrado: o limite é o Fluxo (Modo VCV).
		* Se a Pressão é constante/quadrada: o limite é a Pressão (Modo PCV ou PSV).
		* ![[Pasted image 20261007170538.png]]
	* **3. Fase de Ciclagem:** É o FIM. Momento em que a válvula inspiratória fecha e a expiratória abre.
		* Pode ocorrer ao se atingir um Volume pré-determinado, um Tempo pré-determinado ou uma queda de Fluxo pré-determinada.

## Ajuste Fino: Sensibilidade e Fluxo Base (Bias Flow)
* **A regra de ouro da sensibilidade: O ajuste deve ser "o mais sensível possível, desde que não gere autodisparo" (falsas respirações não iniciadas pelo paciente).**
	* **Sensibilidade a Fluxo (Flow Trigger):** O ventilador lê a mudança no fluxo gerada pelo esforço do paciente.
		* É a métrica mais recomendada e utilizada.
		* Interpretação: ==Na unidade Litros/minuto (L/min), um **menor valor numérico revela maior sensibilidade**.
		* Alvo usual: Entre 1,5 e 3,0 L/min (considerando que o fluxo de uma respiração espontânea normal gira em torno de 15 L/min).
		* *Exceção de equipamento:* Em ==ventiladores mais antigos (ex: linha Servo), o ajuste pode ser em porcentagem (%). Nesses casos, reduzir o valor o torna menos sensível.
	* **Sensibilidade a Pressão:** O paciente precisa gerar uma pressão negativa para abrir a válvula.
		* Valores comuns: -1 a -2 cmH2O. 
		* ==Valores muito baixos (ex: -5 cmH2O) tornam o respirador "pesado" e impõem alto trabalho respiratório.
	* **Bias Flow:** É o fluxo contínuo mantido no circuito para permitir a leitura do trigger a fluxo.
		* Conduta: Dificilmente necessita ajuste pelo operador. Em equipamentos como o Servo, é fixo em 2 L/min.

## Os 3 Modos Ventilatórios Básicos (VCV, PCV e PSV)
* **VCV (Ventilação Controlada a Volume): Alvo no FLUXO | Ciclada a VOLUME.**
	* Variável limitante (constante no meio do ciclo) é o fluxo inspiratório. A curva de fluxo é quadrada.
	* O fim da inspiração ocorre exatamente quando o Volume Corrente estipulado é entregue ao paciente.
	* ==A pressão nas vias aéreas é uma variável dependente (livre), e mudará de acordo com a complacência e resistência do paciente.
* **PCV (Ventilação Controlada a Pressão): Alvo na PRESSÃO | Ciclada a TEMPO.**
	* ==A pressão programada é atingida rapidamente e mantida constante durante toda a inspiração. O fluxo é desacelerado.
	* 🚨 **Pegadinha Clássica:** Apesar do nome, ==o modo PCV **NÃO** cicla a pressão. Ele cicla a **Tempo**==. O ciclo encerra porque o Tempo Inspiratório (Ti) pré-definido pelo médico no painel acabou.
* **PSV (Pressão de Suporte): Alvo na PRESSÃO | Ciclada a FLUXO.**
	* É o modo estritamente espontâneo. O paciente dita o início (disparo a fluxo/pressão) e o fim da respiração. Não existe ajuste de Frequência Respiratória neste modo.
	* O ventilador apenas garante uma pressão positiva de ajuda (Suporte) constante.
	* A ciclagem ocorre quando o fluxo inspiratório cai para um percentual do pico de fluxo máximo alcançado no início do ciclo (geralmente fixado em 25% de fábrica, mas ajustável na função *Cycling Off*).

## Ajustes Específicos nos Modos Pressóricos (Rise Time e Cycling Off)
* **Entendendo a dinâmica do fluxo: Fluxo é igual a Volume dividido por Tempo. Logo, mais veloz significa menos tempo.**
	* **Rise Time (Fluxo de ataque / Tempo de retardo):** É o tempo que a máquina leva para atingir a pressão alvo no PCV ou PSV.
		* Como ajustar:
			* ==Aumentar o "Rise Time" em milissegundos (ex: de 0ms para 200ms) deita a curva, tornando a entrega inicial de fluxo mais lenta e confortável.
			* Baixar o "Rise Time" (ex: 0ms) cria uma curva perfeitamente vertical, entregando a pressão imediatamente.
	* **Ciclagem a Fluxo (E-Sens / Cycling Off / % de Ciclagem):** Exclusivo do modo PSV. Define o momento exato em que a máquina "desliga" o suporte e abre a válvula expiratória.
		* Funciona como um percentual do fluxo inspiratório máximo (pico).
		* **Aumentar o E-Sens (Ex: 50%):** A máquina cicla precocemente (quando o fluxo ainda está alto). O resultado é um **Menor Tempo Inspiratório**. Útil em DPOC para dar mais tempo de expiração.
		* **Reduzir o E-Sens (Ex: 10%):** A máquina espera o fluxo cair quase a zero para ciclar. O resultado é um **Maior Tempo Inspiratório**.
		* *Dica de memorização ==(Analogia do Burpee):* Quanto mais baixo você vai (10%), mais tempo demora a execução (Maior Ti).

## Questões e Casos de Raciocínio Clínico (Pérolas de Prova - TEMI)
* **Compreender as variáveis fixas vs. dependentes é a chave para provas de terapia intensiva.**
	* **Caso 1 (Conceito VCV):** Se um paciente está em VCV e você aumenta o fluxo inspiratório, o que ocorre com o volume corrente?
		* *Resposta:* Permanece **absolutamente igual**. No VCV o volume corrente é o alvo ditatorial final. Se você aumentar a velocidade do fluxo, os mesmos 500mL entrarão, porém de forma mais rápida (encurtando o tempo inspiratório e aumentando a pressão de pico), mas o volume total não se altera.
	* **Caso 2 (Ajustes Iniciais VCV):** Quais os três parâmetros centrais que o médico deve ajustar no painel ao colocar alguém em Volume Controlado?
		* *Resposta:* Fluxo inspiratório (que define a variável constante), Volume corrente (que define a ciclagem) e a PEEP (fase expiratória). Pressões de via aérea e pressão de distensão (driving pressure) são *consequências* observadas na mecânica, não parâmetros ajustados diretamente no painel no modo VCV.