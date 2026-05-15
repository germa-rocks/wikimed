---
publish: true
---
Aqui está a base de conhecimento estruturada e otimizada para Notion/Obsidian, aplicando o princípio da divulgação progressiva de informação (pérolas clínicas na superfície, fisiologia e detalhes profundos nos níveis aninhados).

# Fisiologia Aplicada da Ventilação Mecânica (VM)

## Princípios Básicos e Monitorização de Pressões
- **A VM inverte a fisiologia da respiração espontânea: o ventilador empurra o ar (pressão positiva proximal) em vez de o diafragma o puxar (pressão pleural negativa).**
	- Na VM, o painel do ventilador monitoriza a *Pressão de Vias Aéreas Proximal (Paw)*, e NÃO a pressão pleural.
		- A pressão hemodinamicamente relevante é a Pressão Pleural (intratorácica). Na VM passiva (paciente sedado/curarizado), a pressão pleural torna-se uma "vítima" (variável dependente) das complacências do sistema.
		- O pulmão e a parede torácica movem-se como uma unidade única guiada pela máquina. Logo, a análise gráfica é feita baseada na Complacência do *Sistema Respiratório* (Crs = Pulmões + Parede Torácica).
		- Qualquer tentativa de estimar com precisão as pressões intratorácicas em um paciente com *esforço ativo* apenas olhando para o ventilador é falha; isso exige monitorização avançada (ex: balão esofágico).

## Análise da Curva de Pressão (Pico vs. Platô)
- **A Pressão de Platô (Pplat) representa a pressão alveolar (estática) e traduz o risco de barotrauma; a Pressão de Pico (Ppeak) soma a Pplat ao componente de resistência das vias aéreas (dinâmica).**
	- **Pressão de Platô (Estática):**
		- Obtida através de uma pausa inspiratória (condição de fluxo zero no ventilador).
		- Reflete a pressão necessária para manter o volume corrente no alvéolo.
		- Como o fluxo é zero, forma-se uma coluna estática de gás do tubo endotraqueal até o alvéolo, logo: *Pressão na Válvula = Pressão Alveolar*.
		- É o componente principal para o cálculo da Complacência Estática do Sistema Respiratório:
			- *Cálculo:* Complacência = Volume Corrente / (Pplat - PEEP).
	- **Pressão de Pico (Dinâmica):**
		- Representa o somatório: Pressão Alveolar (Estática) + Pressão para vencer a resistência das vias aéreas (Dinâmica).
		- O aumento isolado da Pressão de Pico (com Platô normal) significa aumento de resistência (broncoespasmo, secreção, tubo dobrado/mordido).
			- Este aumento de pressão se dissipa nas vias aéreas de condução e não atinge o alvéolo e nem a pleura. Portanto, *não* causa barotrauma alveolar nem compromete o retorno venoso (não choca o paciente).
		- *Cálculo da Resistência de Vias Aéreas (Raw):* Raw = (Ppeak - Pplat) / Fluxo Constante.
	- **Regra de Ouro da Análise Gráfica:** 
		- A análise visual confiável do gradiente Pico-Platô para inferir resistência *só é possível em modos com fluxo inspiratório constante* (Onda Quadrada / VCV). Em fluxos decrescentes (PCV), a pressão resistiva cai à medida que o fluxo desacelera, impossibilitando essa análise matemática direta na tela.

## Impacto Hemodinâmico: A Regra da Partição da Pressão
- **Nem toda Pplat ou PEEP gerada pelo ventilador atinge o espaço pleural e afeta a hemodinâmica; isso depende unicamente da proporção entre a complacência do pulmão e da parede torácica.**
	- A Pressão Pleural dita os efeitos circulatórios (queda do retorno venoso, hipotensão).
	- **Cenário 1: Pulmão muito rígido (Baixa Complacência Pulmonar)**
		- *Exemplos:* SARA/ARDS, Edema Agudo de Pulmão severo.
		- *Impacto:* < 50% da Pplat/PEEP é transmitida à pleura. 
		- *Fisiopatologia:* O pulmão rígido atua como uma "carapaça de chumbo" (ou balão de Kevlar). Ele absorve a pressão para tentar se distender e não consegue empurrar a parede torácica. A pressão pleural sofre pouca elevação, protegendo a hemodinâmica. O paciente tem alta pressão transpulmonar.
	- **Cenário 2: Complacências Iguais (Pulmão normal, Parede normal)**
		- *Impacto:* Cerca de 50% da pressão das vias aéreas é transmitida à pleura.
	- **Cenário 3: Parede Torácica Rígida (Baixa Complacência da Parede)**
		- *Exemplos:* Obesidade mórbida, ascite volumosa, hipertensão intra-abdominal, cifoescoliose.
		- *Impacto:* > 50% da Pplat/PEEP é transmitida à pleura.
		- *Fisiopatologia:* O pulmão é complacente, mas ao expandir, bate numa "parede de concreto". A pressão no espaço pleural dispara. Estes são os pacientes com alto risco de choque obstrutivo (redução severa de retorno venoso) ao receberem altos níveis de PEEP ou volume.

## Trabalho Respiratório (Work of Breathing - WOB) no Ventilador
- **Na VM com fluxo constante (VCV), a curva de Pressão-Tempo pode ser usada diretamente para visualizar o Trabalho Respiratório Resistivo e Elástico.**
	- Como o volume e o tempo variam de forma linear (devido ao fluxo constante), a área sob a curva representa o Trabalho Respiratório.
	- **Trabalho Resistivo:** É a área da curva demarcada entre a Pressão de Pico e a rampa que leva até a Pressão de Platô (se visualizarmos o fluxo interrompido).
	- **Trabalho Elástico:** É a área preenchida abaixo do nível da Pressão de Platô.

## O Paciente com Esforço Espontâneo sob VM
- **A presença de esforço respiratório ativo sob VM mascarada a verdadeira pressão intratorácica, podendo gerar pressões pleurais intensamente negativas.**
	- Em modos assistidos (ou sob Pressão de Suporte), o ventilador mostra pressões positivas na via aérea, mas o recrutamento da musculatura inspiratória do paciente está puxando a pressão pleural para baixo.
	- *Armadilha Clínica:* Aferir complacência ou pressões hemodinâmicas através do painel do ventilador em pacientes que interagem ativamente com a máquina produzirá dados incorretos e ilusórios.
	- **O papel da Pressão de Suporte (PSV / VNI):**
		- Melhora a complacência efetiva do sistema respiratório.
		- Descarrega o trabalho dos músculos respiratórios (reduz tanto o WOB resistivo quanto o elástico).
		- Mitiga variações extremas da pressão pleural (evitando, por exemplo, pressão pleural hiper-negativa que piora edema pulmonar ou causa falha de desmame por fadiga/isquemia miocárdica).