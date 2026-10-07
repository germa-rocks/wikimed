---
publish: true
---
[[figuras 2 Mecanica VM MUTI]]
# Mecânica Ventilatória

- Ponto 1: entender e medir complacência e resistência.
- Ponto 2: VILI platô sempre deve ser avaliada e driving pressure cada vez mais parece ser o que de fato importa
- Ponto 3: se possível, estimar a força muscular e a pressão transpulmonar
- Ponto 4: mergulhar em novos conceitos– stress e strain, mechanical power, pendeluft, p-sili, etc.


## Princípios Básicos e o Modelo Bicompartimental
- **O ventilador mecânico precisa vencer duas forças principais do sistema respiratório: a resistência das vias aéreas e a elastância (recolhimento) do tecido.**
	- ![[Pasted image 20261007164804.png]]
	- ![[Pasted image 20261007164818.png]]
	- **Força Resistiva (Movimento dos gases):**
		- Relacionada ao atrito gerado pela passagem do ar nas vias aéreas (movimento canalicular).
		- Consome energia dissipando-a em forma de calor, mas **não** deforma o tecido pulmonar diretamente.
		- Regida pela Lei de Ohm ($R = \Delta P / Fluxo$) e Lei de Poiseuille (resistência é inversamente proporcional à 4ª potência do raio da via aérea).
		- ==O fluxo de ar ideal é laminar. Fluxos turbulentos (ex: secreção, broncoespasmo) aumentam criticamente a resistência.
			- ![[Pasted image 20261007164901.png]]
	- **Força Elástica (Deformação tecidual):**
		- Relacionada à expansão do parênquima pulmonar e da caixa torácica.
		- Acumula energia potencial na inspiração para gerar o recolhimento na expiração (que é predominantemente passiva).
		- A Elastância (E) é o inverso da **Complacência (C)**. Portanto, avaliar complacência é avaliar a complacência elástica do sistema.
		- 
	- **A Equação do Movimento Respiratório:**
		- A pressão total do sistema é a soma da pressão muscular do paciente ($Pmus$) com a pressão do ventilador ($Pvent$).
		- $Pmus + Pvent = (Resistência \times Fluxo) + (Volume / Complacência) + PEEP$.

## Monitorização à Beira-Leito: A Curva de Pressão
- **A manobra de pausa inspiratória (em modo VCV com fluxo quadrado) é essencial para decompor e medir a Resistência e a Complacência.**
	- **Pressão de Pico ($Ppico$):**
		- É o ponto mais alto da curva. Representa a pressão necessária para vencer **ambas** as resistências (vias aéreas + tecido pulmonar).
	- **Pressão de Platô ($Pplatô$):**
		- É a pressão medida durante a pausa inspiratória (fluxo = zero).
		- Reflete **exclusivamente a pressão alveolar** (a distensão do tecido, sem o componente do fluxo de ar).
	- **O "Degrau" ($Ppico - Pplatô$):**
		- A diferença entre o Pico e o Platô reflete a força resistiva.
		- **Degrau grande:** Problema obstrutivo (broncoespasmo, tubo dobrado, rolha de secreção). A $Ppico$ sobe, mas a $Pplatô$ fica normal.
		- **Degrau pequeno com pressões altas:** Problema restritivo (edema, SARA, consolidação). A $Pplatô$ sobe acompanhando a $Ppico$.
		- ![[Pasted image 20261007164958.png]]

## Fórmulas Clínicas e Cálculos
- **Atenção à unidade de medida do fluxo: para o cálculo de resistência, o fluxo deve ser sempre convertido de Litros/minuto para Litros/segundo.**
	- **Resistência de Vias Aéreas ($Rva$):**
		- $Rva = (Ppico - Pplatô) / Fluxo$
		- *Ajuste prático:* Se o fluxo no ventilador for 60 L/min, divida por 60 para obter 1 L/s.
		- ![[Pasted image 20261007165323.png]]
		- *Valor de referência:* Ideal $< 20$ $cmH_2O/L/s$ em pacientes sob VMI.
	- **Complacência Estática ($Cest$):**
		- $Cest = Volume Corrente / (Pplatô - PEEP total)$
		- *Atenção à PEEP:* Deve-se usar a **PEEP Total** (PEEP do aparelho + Auto-PEEP do paciente medida na pausa expiratória).
		- *Valor de referência:* Em ventilação, espera-se uma complacência entre 50 e 80 $mL/cmH_2O$.
	- ![[Pasted image 20261007165046.png]]

## Constante de Tempo e Auto-PEEP
- **A Constante de Tempo (CT) define a velocidade de esvaziamento pulmonar e o risco de desenvolver auto-PEEP (aprisionamento aéreo).**
	- **Cálculo da CT:**
		- $CT = Complacência \times (Resistência / 1000)$ *(o 1000 é para ajuste de unidades de mL para Litros)*.
		- 1 CT é o tempo necessário para esvaziar 63% do volume pulmonar inserido.
		- São necessárias de **3 a 5 Constantes de Tempo** para um esvaziamento pulmonar virtualmente completo.
		- ![[Pasted image 20261007165147.png]]
	- **Avaliação Gráfica da Auto-PEEP:**
		- A auto-PEEP ocorre se a curva de Fluxo x Tempo na fase expiratória **não retornar ao zero** antes de iniciar o novo ciclo.
		- ![[Pasted image 20261007165244.png]]
		- É preciso fazer uma **pausa expiratória** para medir a PEEP Total e quantificar a Auto-PEEP (PEEP intrínseca).
	- **Aplicações Práticas da CT:**
		- **SARA (Restritivo):** Complacência muito baixa + Resistência normal = **CT muito curta** (ex: 0,2s). O pulmão esvazia rápido.
		- **DPOC/Asma (Obstrutivo):** Complacência normal/alta + Resistência altíssima = **CT muito longa** (ex: 1,5s). Exige tempos expiratórios prolongados (ex: > 4,5s) para evitar grave auto-PEEP.
		- ![[Pasted image 20261007165157.png]]
		- *Dica avançada:* A matemática pode ser enganosa na asma, pois a Rva medida na pausa inspiratória é de entrada, mas o grande problema da asma é o colapso expiratório. Confie primordialmente na curva de fluxo-tempo.

## Lesão Pulmonar Induzida pela Ventilação (VILI) e P-SILI
- **O paradigma atual da proteção pulmonar foca na redução do Stress (Driving Pressure), do Strain (deformação) e do Ergotrauma (energia total).**
	- **Evolução dos conceitos de lesão pulmonar:**
		- Barotrauma (pressão excessiva) $\rightarrow$ Volutrauma (volume excessivo) $\rightarrow$ Atelectrauma (abertura/fechamento cíclico) $\rightarrow$ Biotrauma (inflamação sistêmica) $\rightarrow$ **Ergotrauma** (Potência Mecânica/Mechanical Power).
	- **Stress (Força sobre Área) e Driving Pressure:**
		- O estresse alveolar clínico é estimado pela **Driving Pressure** ($\Delta P = Pplatô - PEEP$).
		- É o principal marcador de proteção pulmonar na atualidade.
		- ![[Pasted image 20261007165359.png]]
	- **Strain (Deformação Tecidual):**
		- É a relação entre o Volume Corrente entregue e a Capacidade Residual Funcional (CRF) do paciente ($Strain = VC / CRF$).
		- Um "baby lung" (pulmão com muita área colapsada) tem CRF pequena. Um VC de 500ml nele causa um strain gigantesco em comparação ao mesmo volume num pulmão normal.
		- ![[Pasted image 20261007165418.png]]
	- **Pressão Transpulmonar ($Ptp$) e a Parede Torácica:**
		- A $Ptp$ é a verdadeira pressão de distensão do pulmão ($Ptp = Palv - Ppl$).
		- A pressão alveolar ($Palv$) equivale à $Pplatô$. A pressão pleural ($Ppl$) sofre influência da caixa torácica e abdome.
		- Se o paciente tem a parede torácica muito rígida (ex: grande obeso, ascite grave, hipertensão intra-abdominal), a $Ppl$ é alta. A $Pplatô$ estará alta, mas a $Ptp$ pode estar normal. A lesão alveolar ($VILI$) se correlaciona com a $Ptp$, e não apenas com a $Pplatô$ isolada neste contexto.
		- ![[Pasted image 20261007165444.png]]
	- **P-SILI (Patient Self-Inflicted Lung Injury) e Esforço Inspiratório:**
		- Quando o paciente faz esforço excessivo (ex: não sedado, drive alto), ele gera pressões intrapleurais muito negativas.
		- Essa força, somada à pressão do ventilador, distende excessivamente o alvéolo e gera fluxo regional de ar anormal (**Pendelluft** - ar se movendo entre áreas não dependentes para dependentes do pulmão durante a inspiração).
		- ![[Pasted image 20261007165459.png]]
		- **Manejo:** Nesses casos, manter drive espontâneo pode ser deletério. A indicação é aprofundar sedação/bloqueio neuromuscular para anular o componente muscular na equação do movimento respiratório.
		- *Monitorização do drive:* Na beira leito, estima-se o esforço indiretamente por manobras como oclusão expiratória breve ($P0.1$) ou pressão de oclusão ($Pocc$).
		- ![[Pasted image 20261007165540.png]]