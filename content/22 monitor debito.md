---
publish: true
---



# Monitorização do Débito Cardíaco na UTI

## Introdução e Princípios de Monitorização
- **O Débito Cardíaco (DC) é a principal variável macro-hemodinâmica na avaliação do paciente crítico instável.**
	- A sua medição frequentemente determina o rumo ou a mudança das intervenções terapêuticas.
	- Deve ser sempre interpretado dentro do contexto clínico geral, avaliando outros parâmetros hemodinâmicos e metabólicos simultaneamente (ex: lactato, perfusão periférica).
- **O monitor ideal à beira-leito deve equilibrar precisão com usabilidade e segurança.**
	- Critérios de utilidade clínica para a escolha do método:
		- Confiabilidade: Alta exatidão das medidas (baixo viés e alta precisão).
		- Inocuidade: Ser o mais não-invasivo possível para não agregar risco.
		- Tempo real: Fornecer medidas contínuas.
		- Praticidade: Ser automatizado ou minimamente dependente do operador para reduzir falhas e poupar recursos humanos.
		- Aceitação: Fácil implementação na prática diária.

## Métodos de Mensuração e Tecnologias Disponíveis

### Diluição de Indicador (Termodiluição)
- **A Termodiluição é o "Padrão Ouro" clínico para medir valores absolutos, porém é invasiva e fornece medidas intermitentes.**
	- Princípio Fisiológico:
		- Injeta-se um *bolus* de quantidade conhecida de um indicador (solução fria ou corante) na circulação.
		- Um sensor mais adiante (downstream) mede a alteração de concentração/temperatura ao longo do tempo.
		- Regra: Quanto mais rápido for o fluxo sanguíneo (alto débito), mais rápida é a elevação e a queda da curva do indicador.
	- Cateter de Artéria Pulmonar (Swan-Ganz):
		- Fornece parâmetros hemodinâmicos exclusivos: Fração de Ejeção do Ventrículo Direito (FEVD) e Volume Diastólico Final do Ventrículo Direito.
		- Red Flag: Altamente invasivo, depende da presença de equipe com excelente treinamento técnico. Não é um dispositivo "plug and play".
		- 📎 Refs: 5, 6, 7
	- Termodiluição Transpulmonar:
		- Menos invasivo que o Swan-Ganz; utiliza um cateter venoso central comum e um cateter arterial específico com sensor (femoral, axilar ou braquial).
		- Fornece parâmetros avançados: Volume Diastólico Final Global (GEDV) e Água Pulmonar Extravascular (EVLW).
		- 📎 Ref: 2
	- Limitação do Grupo: Como exige a injeção em *bolus*, trata-se de um método inerentemente intermitente e descontínuo.

### Análise da Onda de Pulso (Pulse Contour)
- **A Análise da Onda de Pulso oferece monitorização contínua (tendência), mas tem precisão limitada em números absolutos e sofre artefatos com arritmias.**
	- Princípio Fisiológico:
		- Baseia-se no mecanismo de Frank: se as propriedades elásticas da parede arterial permanecerem constantes, a integral da porção sistólica da curva de pressão arterial correlaciona-se com o volume sistólico (VS) do ventrículo esquerdo.
		- 📎 Refs: 3, 4, 11
	- Formas de Captação:
		- Invasiva: Através de pressão arterial invasiva (PAI) central ou periférica.
		- Não Invasiva: Através da tecnologia de "volume clamp" ou sinal fotopletismográfico no dedo.
		- 📎 Refs: 10, 12
	- Vantagens:
		- Automatizado, batimento a batimento, contínuo e independente do operador.
	- Red Flags e Limitações:
		- Limitada exatidão para valores absolutos (comparado à termodiluição); é excelente para guiar **tendências** de resposta a terapias.
		- Contraindicação relativa: Inadequado para pacientes com arritmias (como fibrilação atrial).
		- Altamente sensível a erros de medição gerados por artefatos no sinal bruto da curva de pressão.

### Fluxometria Derivada de Doppler
- **A Ecocardiografia / Doppler é excelente, não-invasiva e em tempo real, mas exige operador treinado e não serve como "monitorização prolongada".**
	- Princípio Fisiológico:
		- Usa o efeito Doppler para medir o perfil de fluxo dos eritrócitos e quantificar a Integral Velocidade-Tempo (VTI).
		- VTI multiplicado pelo diâmetro do vaso (via de saída do VE ou VD, ou aorta descendente) fornece o Volume Sistólico (VS).
	- Formas de Obtenção:
		- Ecocardiografia Transtorácica (ETT) ou Transesofágica (ETE).
		- Sonda Esófagica de Doppler (miniaturizada e transnasal): Mais adequada para uso perioperatório contínuo de curto prazo.
		- 📎 Refs: 8, 9
	- Limitações Práticas na UTI:
		- Com exceção do Doppler esofágico mantido, o ecocardiograma gera apenas uma "fotografia" do momento (snapshot temporário).
		- Alta dependência do operador e grande consumo de tempo, impedindo seu uso como um monitor real contínuo no leito.

### Bioimpedância e Biorreatância
- **Totalmente não invasivos, fáceis de instalar, porém apresentam a menor precisão comparada aos padrões ouro em pacientes críticos.**
	- Princípio Fisiológico:
		- Aplica-se uma corrente de alta frequência e baixa magnitude no tórax por eletrodos na pele.
		- O volume sistólico serve como um "meio de contraste elétrico": a ejeção de sangue altera o volume intratorácico, o que por sua vez altera a condutividade elétrica.
		- 📎 Ref: 13
	- Vantagens:
		- Uso puramente não invasivo, em tempo real, contínuo e automatizado.
	- Limitação:
		- Exatidão muito limitada em pacientes complexos de UTI frente à termodiluição.
		- 📎 Ref: 10

## Aplicação Clínica e Individualização (Pérolas do Dia a Dia)
- **A escolha do monitor deve equilibrar a "Invasividade" vs "Exatidão" dependendo da gravidade e do cenário do paciente.**
	- Perfil de Paciente Eletivo / Perioperatório:
		- Objetivo: Evitar de forma preemptiva fases de instabilidade hemodinâmica e guiar reposição volêmica padrão.
		- Estratégia preferencial: Métodos não invasivos ou minimamente invasivos (Automatização supera a necessidade de exatidão estrita absoluta). Análise da onda de pulso e Doppler são opções clássicas.
	- Perfil de Paciente de UTI (Alta Complexidade / Choque / Hemodinâmica Instável):
		- Objetivo: Ressuscitação volêmica complexa e uso criterioso de inotrópicos e vasopressores.
		- Estratégia preferencial: Necessidade absoluta de exatidão e precisão associada a outros parâmetros da mecânica pulmonar/cardíaca (GEDV, EVLW, FEVD). Prioriza-se a Termodiluição Transpulmonar ou o Cateter de Artéria Pulmonar (Swan-Ganz).
		- 📎 Ref: 1