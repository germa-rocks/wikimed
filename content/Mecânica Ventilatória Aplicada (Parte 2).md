---
publish: true
---
# Ventilação Mecânica: Mecânica Aplicada na Prática Clínica (Parte 2)

## Parâmetros Pressóricos e Cálculos Respiratórios
- **A Pressão Transpulmonar é a verdadeira pressão de distensão do parênquima pulmonar e deve ser monitorada em casos complexos.**
	- Representa a diferença de pressão entre o interior dos alvéolos e o espaço pleural.
	- Cálculo: `Pressão Transpulmonar = Pressão Alveolar - Pressão Pleural`
	- Estimativa à beira-leito:
		- Pressão Alveolar (Fim da Inspiração) ≈ Pressão de Plateau.
		- Pressão Pleural ≈ Pressão Esofágica (medida via balão esofágico).
		- *Exemplo prático:* Plateau de 30 cmH2O e Pressão Esofágica de 10 cmH2O = Pressão Transpulmonar de 20 cmH2O.
- **A Complacência Dinâmica e a Resistência das Vias Aéreas são extraídas diretamente das pressões de pico e plateau.**
	- **Complacência do Sistema Respiratório:** Avalia a elasticidade do sistema apenas durante a entrega do volume corrente.
		- Cálculo: `Volume Corrente / Driving Pressure`.
		- *Exemplo:* VC de 1000 mL / Driving Pressure de 30 cmH2O = 33 mL/cmH2O.
	- **Resistência das Vias Aéreas:** Avalia a pressão gasta exclusivamente para gerar fluxo de ar.
		- Cálculo: `(Pressão de Pico - Pressão de Plateau) / Fluxo Inspiratório`.
		- *Atenção:* O fluxo deve estar convertido para a unidade correta na fórmula para um resultado exato (ex: L/segundo).

## Curvas de Pressão-Volume (P-V)
- **A Curva Estática P-V reflete com precisão a pressão intra-alveolar; a Curva Dinâmica pode ser enganosa se o fluxo for elevado.**
	- **Curva Estática:** Obtida com múltiplas pausas (plateaus) graduais durante a insuflação e desinsuflação (até a Capacidade Pulmonar Total).
		- **Histerese Pulmonar:** O pulmão precisa de menos pressão para se manter aberto na deflação do que para abrir na insuflação. Isso ocorre porque, ao atingir a capacidade total, o surfactante é distribuído pelo sistema, estabilizando os alvéolos na descida.
		- O ramo deflatório da curva estática é o que melhor representa o estado real do pulmão.
	- **Curva Dinâmica:** Medida continuamente sem pausas. Sofre forte influência da resistência ao fluxo.
		- Com fluxos normais/altos (ex: 60 L/min), a curva desvia para a direita (falsa impressão de piora da complacência por causa da pressão de vias aéreas).
		- Para aproximar a curva dinâmica da curva estática inspiratória, é necessário usar um fluxo extremamente lento (ex: 10 L/min), o que exige tempo inspiratório longo e, frequentemente, sedação profunda ou bloqueio neuromuscular.
- **Os Pontos de Inflexão (Inferior e Superior) mapeiam o colapso e a superdistensão global, mas têm utilidade prática limitada beira-leito.**
	- **Ponto de Inflexão Inferior (Ramo Inspiratório):** Curvatura na base da lina que indica a pressão onde os alvéolos colapsados começam a se abrir (recrutamento).
	- **Ponto de Inflexão Superior:** Ponto no topo da curva onde o sistema respiratório começa a sofrer superdistensão (aumento de pressão sem ganho proporcional de volume).
	- *Pérola Clínica:* O autor sugere não focar nos extremos da curva (acima ou abaixo do volume corrente), mas sim na mecânica *durante* a entrega do volume corrente (usando Driving Pressure e Stress Index).

## Driving Pressure e Índice de Estresse (Stress Index)
- **A *Driving Pressure* (Pressão de Distensão) é a principal métrica para avaliar a complacência durante o ciclo e guiar ventilação protetora.**
	- Cálculo: `Pressão de Plateau (fim da inspiração) - PEEP (fim da expiração)`.
	- É a pressão efetivamente gasta para expandir o pulmão a cada incursão respiratória.
	- **Red Flag Clínica:** Manter a *Driving Pressure* abaixo de 15 cmH2O. Valores superiores estão fortemente associados a Lesão Pulmonar Induzida pela Ventilação (VILI) e pior prognóstico em insuficiência respiratória.
- **O *Stress Index* permite o ajuste fino do PEEP e Volume Corrente analisando o formato da onda de pressão-tempo.**
	- **Pré-requisito obrigatório:** Deve ser avaliado *apenas* em Ventilação Controlada a Volume (VCV) com fluxo inspiratório **constante (onda quadrada)**. Isso elimina a variação de pressão relacionada ao fluxo, tornando a subida da pressão um reflexo puro da complacência.
	- **Interpretação dos 3 Padrões do Stress Index:**
		- **Perfil 1 - Linha Reta Diagonal:** É o cenário ideal. O pulmão infla de forma linear, indicando que não há colapso (derecrutamento) nem superdistensão. Os parâmetros estão corretos. *(Nota: O texto refere-se a este perfil matemático como índice 0, embora muita literatura o chame de 1).*
		- **Perfil 2 - Concavidade para baixo (Abaulamento superior):** A curva sobe rápido no início e depois achata/melhora a inclinação.
			- Fisiopatologia: Indica recrutamento tardio durante a inspiração (e consequentemente derecrutamento na expiração).
			- Conduta: O PEEP está muito baixo. **Aumentar o PEEP** até que a curva se torne uma linha reta.
		- **Perfil 3 - Concavidade para cima (Abaulamento inferior):** A curva começa subindo devagar e fica abruptamente íngreme no final da inspiração.
			- Fisiopatologia: O pulmão está ficando progressivamente mais rígido no final da insuflação (superdistensão).
			- Conduta: O PEEP ou o Volume Corrente estão muito altos. **Reduzir o PEEP ou o Volume Corrente**.

## Interações Cardiopulmonares na Ventilação Mecânica
- **A ventilação com pressão positiva altera fundamentalmente a hemodinâmica por funcionar como uma câmara de pressão ao redor do coração.**
	- O coração e os pulmões compartilham a caixa torácica, enquanto o resto do corpo (cérebro, abdome, membros) não está submetido a essa pressão positiva.
	- A Pressão Pleural elevada atua diretamente sobre as paredes cardíacas, aproximando-se do efeito da Pressão Pericárdica.
- **Efeitos Benéficos da Pressão Intratorácica Elevada (Pacientes Hipervolêmicos / Insuficiência Cardíaca Esquerda):**
	- **Reduz a pré-carga (retorno venoso):** O aumento da pressão no tórax dificulta a entrada de sangue das veias cavas, o que é terapêutico no manejo do edema agudo de pulmão.
	- **Reduz a pós-carga do Ventrículo Esquerdo (VE):** A pressão positiva "espreme" o coração, ajudando a empurrar o sangue do VE para o resto do corpo (que está em menor pressão). Atua como um assistente ventricular mecânico.
	- **Red Flag (Desmame/Extubação):** A retirada súbita da pressão positiva (ex: teste de respiração espontânea ou extubação) retira essa assistência ao VE e aumenta o retorno venoso de supetão, podendo precipitar *Edema Agudo de Pulmão Flash* em pacientes cardiopatas.
- **Efeitos Maléficos da Pressão Intratorácica Elevada (Pacientes Hipovolêmicos / Cor Pulmonale):**
	- **Queda drástica do Débito Cardíaco:** Se o paciente estiver com baixo volume intravascular, a restrição ao retorno venoso causada pela pressão intratorácica levará a hipotensão grave.
	- **Aumento da Pós-carga do Ventrículo Direito (VD):** A superdistensão alveolar esmaga a vasculatura capilar pulmonar, aumentando a resistência vascular pulmonar e sobrecarregando o VD (risco de falência de VD).