---
publish: true
---
# Princípios Gerais da Ventilação Mecânica

- **O ajuste e a compreensão de qualquer modo ventilatório dependem do domínio de três variáveis operacionais fundamentais: Disparo (Trigger), Limite e Ciclagem.**
	- **Variável de Disparo (Trigger):** O que inicia a fase inspiratória. Pode ser o tempo (controlado pela máquina) ou o esforço do paciente (pressão ou fluxo).
	- **Variável Limite:** O valor máximo (de pressão ou volume) que o ventilador atinge e não ultrapassa durante a fase inspiratória.
	- **Variável de Ciclagem:** O critério que o ventilador usa para encerrar a inspiração e abrir a válvula expiratória (pode ser tempo, volume ou queda de fluxo).

---

# Modos Assisto-Controlados

## Ventilação Controlada a Volume (VCV / VC-AC)
- **Modo onde o Volume Corrente (Vt) é garantido. A Pressão nas vias aéreas é a variável dependente (livre), determinada pela complacência e resistência do sistema respiratório.**
	- **Mecanismos de Controle:**
		- **Disparo:** Tempo (se puramente controlado) ou Paciente (se assistido).
		- **Ciclagem:** Tempo/Volume.
		- **Limite:** Volume.
	- **Ajustes Clínicos Principais:**
		- **Volume Corrente (Vt):** Geralmente ajustado em 6 mL/kg de peso ideal predito (estratégia protetora).
		- **FiO2 e PEEP:** Ajustados conforme oxigenação e mecânica do paciente.
		- **Frequência Respiratória (FR):** Define a ventilação minuto mínima e o tempo do ciclo total.
		- **Fluxo Inspiratório (Velocidade/Rampa):** É a velocidade com que o gás entra para atingir o volume alvo.
			- **Ajuste Indireto do Tempo:** Alterar o fluxo modifica o Tempo Inspiratório (Ti) e a relação I:E. Aumentar o fluxo reduz o Ti e aumenta o Tempo Expiratório (Te).
	- **Análise Gráfica (Morfologia das Curvas no VCV):**
		- **Curva de Pressão x Tempo:** Ascensão contínua e retilínea a partir da PEEP, assumindo formato de triângulo retângulo ("barbatana de tubarão") até atingir o pico de pressão necessário para acomodar o volume.
		- **Curva de Fluxo x Tempo (Clássica):** Onda quadrada (fluxo constante). O fluxo entra em velocidade fixa até que todo o volume seja entregue, caindo a zero e cruzando a linha de base para iniciar a expiração (fluxo expiratório desacelerado passivo).
		- **Curva de Volume x Tempo:** Subida linear, oblíqua e constante até o pico exato do volume configurado. Retorna ao zero de forma arredondada na expiração.

## Ventilação Controlada a Pressão (PCV / PC-AC)
- **Modo onde a Pressão Inspiratória é fixa. O Volume Corrente (Vt) é a variável dependente, oscilando a cada incursão conforme a mecânica (complacência/resistência) do sistema respiratório.**
	- **Mecanismos de Controle:**
		- **Disparo:** Tempo ou Paciente.
		- **Ciclagem:** Tempo (Tempo Inspiratório pré-ajustado).
		- **Limite:** Pressão.
	- **Ajustes Clínicos Principais:**
		- **Pressão Inspiratória:** O alvo de pressão.
			- **Atenção à Nomenclatura (Pérola Prática):** Alguns ventiladores (como Dräger Savina) referem-se à "Pinsp" absoluta (Delta de Pressão + PEEP). Outros referem-se estritamente ao Delta de Pressão (ΔP) acima da PEEP. Exemplo Prático (Pinsp absoluta): Se Pinsp = 14 e PEEP = 8, o ΔP real gerado pelo ventilador é 6 mbar.
		- **Tempo Inspiratório (Ti):** Ajustado diretamente. Mexer no Ti afeta inversamente o Tempo Expiratório (Te) para uma mesma FR.
		- **Rampa de Fluxo (Rise Time):** Ajusta a velocidade de pressurização inicial das vias aéreas.
	- **Análise Gráfica (Morfologia das Curvas no PCV):**
		- **Curva de Pressão x Tempo (Clássica):** Onda quadrada. Sobe abruptamente da PEEP até o alvo pressórico, formando um platô reto e constante durante todo o Ti ajustado.
		- **Curva de Fluxo x Tempo:** Fluxo livre e desacelerado (rampa descendente). Atinge um pico instantâneo máximo e cai exponencialmente ao longo da inspiração conforme a pressão alveolar se iguala à pressão proximal.
		- **Curva de Volume x Tempo:** Ascensão abaulada (convexa). O gás entra mais rápido no início e mais devagar no fim. O valor do pico (Vt final) varia conforme a mecânica.

---

# Modos Espontâneos

## Pressão de Suporte (PSV / SPN-CPAP)
- **Modo puramente espontâneo. O ventilador apenas fornece suporte pressórico a um esforço gerado obrigatoriamente pelo paciente. Não há FR ou Ti fixos impostos pela máquina.**
	- **Mecanismos de Controle:**
		- **Disparo:** Paciente (Trigger de Fluxo ou Pressão).
		- **Limite:** Pressão (Pressão de Suporte).
		- **Ciclagem:** Queda de Fluxo Inspiratório (Ciclagem a Fluxo).
	- **Ajustes Clínicos Principais:**
		- **Trigger (Sensibilidade):** Quão fácil é para o paciente iniciar o ciclo. Preferir fluxo (ex: 2.0 L/min) por ser mais fisiológico e rápido que disparo a pressão.
		- **Ciclagem (Term. Insp. / % de Fluxo de Ciclagem):** Determina quando o ventilador abre a válvula expiratória com base na queda percentual do pico de fluxo.
			- **Manejo da Ciclagem a Fluxo:** Quanto *maior* a porcentagem configurada, *mais cedo* a máquina cicla (menor será o Ti do paciente). Essencial para ajustar assincronias de ciclagem (ex: DPOC exige % maior para tempo expiratório mais longo; SARA exige % menor).
	- **Manejo de Riscos: Ventilação de Resgate (Apneia)**
		- **Red Flag Absoluta:** É obrigatório configurar os parâmetros de resgate em qualquer modo espontâneo, pois o paciente pode rebaixar o sensório ou fatigar.
		- **Tempo de Apneia (Tapn):** Geralmente ajustado para 20 segundos.
		- **Conduta:** Se não houver disparo dentro do Tapn, a máquina soa o alarme e entra automaticamente num modo controlado (PCV ou VCV) previamente configurado pelo médico (mantendo FiO2 e PEEP originais, mas assumindo Vt/Pressão e FR de segurança).
	- **Análise Gráfica (Morfologia das Curvas na PSV):**
		- **Curva de Pressão x Tempo:** Presença de deflexão negativa (abaixo da PEEP) marcante no início de cada ciclo (a "cavada" de esforço do paciente), seguida pela manutenção da Pressão de Suporte.
		- **Curva de Fluxo x Tempo:** Desacelerada. Característica chave: a curva é interrompida (sobe para a linha zero) *antes* de finalizar o fluxo inspiratório fisiológico, exatamente no momento em que atinge o percentual configurado para a ciclagem.
		- **Curva de Volume x Tempo:** O volume corrente entregue é altamente variável ciclo a ciclo, dependendo do esforço da musculatura respiratória do paciente.

---

# Alarmes e Limites de Segurança Sistêmicos

- **Os alarmes não são meros avisos; são ferramentas de segurança ativa. No VCV, por exemplo, o limite pressórico superior funciona como um mecanismo de aborto inspiratório.**
	- **Pressão Máxima de Vias Aéreas (Pmax):**
		- **Mecanismo Ativo:** Se a Pmax for ajustada para 40 cmH2O no modo VCV, e a via aérea do paciente atingir esse valor, o ventilador **não entregará o restante do volume**. A válvula inspiratória fecha prematuramente e cicla para a expiração, prevenindo barotrauma agudo.
	- **Alarmes de Volume Minuto (VMe):**
		- Limites superior e inferior. Fundamentais para detectar desconexões (alarme baixo) ou taquipneia excessiva / falha de sedação com risco de alcalose respiratória grave (alarme alto).
	- **Tempo de Apneia (Tapn):**
		- Determina o limiar temporal crítico de inatividade ventilatória permitida antes da máquina sobrepor a fisiologia do doente.