---
publish: true
---

# OpenEvidence: Ferramenta de Suporte à Decisão Clínica e Atualização Médica

## O Problema Clínico: Sobrecarga e Validade da Informação
- **A utilidade da informação médica individual (quanta) está diminuindo em tempo de validade e abrangência populacional.**
	- O volume e a velocidade de novas descobertas médicas aceleraram drasticamente nas últimas décadas.
	- Ensaios Clínicos Randomizados (RCTs) tendem a focar em nichos populacionais cada vez menores.
		- *Implicação Prática:* O padrão de ouro atual (standard of care) torna-se obsoleto em um período muito mais curto do que no passado, exigindo atualização constante do clínico que possui tempo limitado beira-leito.

## A Solução (OpenEvidence): Mecanismo de Ação e Confiabilidade
- **O sistema utiliza a abordagem de "Jardim Murado" (Walled Garden) para mitigar alucinações (evitando o ciclo "Garbage in / Garbage out").**
	- O modelo restringe a busca unicamente a fontes validadas e de alta autoridade científica.
		- Bases de dados incluídas: PubMed, Diretrizes de Sociedades Médicas, FDA (bulas e regulações) e conteúdo licenciado (textos completos, imagens radiológicas, gráficos e vídeos cirúrgicos).
- **A recuperação da informação (Retrieval) é baseada em algoritmos específicos para a lógica médica, não apenas em correlação de linguagem natural.**
	- A seleção das evidências dentre mais de 40 milhões de citações obedece a quatro critérios estritos:
		- *Relevância:* Pertinência clínica exata à pergunta formulada.
		- *Recência:* Priorização das evidências mais contemporâneas que superam práticas antigas.
		- *Autoridade:* Reputação da fonte/jornal.
		- *Força da Evidência:* Robustez metodológica que sustenta a conclusão.

## Casos de Uso na Prática Clínica (Indicações)
- **A principal utilidade a beira-leito confirmada por médicos americanos é para Tratamento, Manejo e Farmacoterapia.**
	- Clinicamente, a ferramenta é mais utilizada para confirmar se o tratamento planejado para casos complexos está alinhado com a literatura mais recente, superando o uso para diagnósticos diferenciais.
- **Outras aplicações integradas ao fluxo de trabalho (Workflow):**
	- Revisão de diretrizes e dosagens/segurança de medicamentos.
	- Geração de materiais educativos para o paciente e resumos de alta.
	- Elaboração de cartas e justificativas para autorização de convênios/seguradoras.
	- Transcrição de consultas clínicas (ferramenta *Visits/Scribe*) com embasamento de evidências acoplado ao plano terapêutico.
	- Obtenção de créditos CME (Educação Médica Continuada) integrados às buscas.
- **Continuidade do Cuidado e Trabalho em Equipe (*OE Rounds / Care Teams*).**
	- Permite a criação de coleções de buscas atreladas a um paciente específico (Leito/Quarto).
	- O raciocínio clínico e as evidências levantadas durante a madrugada ficam disponíveis para o plantonista seguinte ou para o médico assistente (evitando retrabalho e perda de informações nos handoffs/passagens de plantão).

## Dicas de "Prescrição" (Prompting) para Extração de Evidências
- **A qualidade e a especificidade da resposta dependem diretamente da formulação estruturada da pergunta (4 Pilares).**
	- **1. Adicione Contexto Clínico Completo:**
		- Quanto mais restrições e dados, mais precisa é a resposta.
		- *Mandatório incluir:* Idade, comorbidades relevantes, achados principais e restrições fisiológicas/farmacológicas (alergias, função renal/hepática, gestação).
		- *Exemplo de Alto Rendimento:* "Quais as opções alternativas de tratamento para otite média aguda em criança de 4 anos (17 kg) com asma persistente leve e eczema, febre de 39.1°C, membrana timpânica abaulada, com alergia prévia a penicilina, cefalosporinas e macrolídeos?"
	- **2. Seja Específico no Objetivo (Endpoint):**
		- Diferencie claramente se busca um diagnóstico diferencial, opções de tratamento de primeira linha ou tratamentos alternativos/resgate.
	- **3. Especifique a Fonte ou o Tipo de Informação Desejada:**
		- Determine de onde o modelo deve extrair a resposta para mudar o foco do resultado.
		- *Exemplos:* Solicite explicitamente "diretrizes da sociedade X", "literatura mais recente", "ensaios clínicos randomizados (RCTs)" ou "análise do ensaio clínico Y apontando vieses".
	- **4. Molde o Formato da Saída (Output):**
		- Adapte a formatação para leitura rápida (scanning) durante o atendimento.
		- *Estratégias:* Solicite tabelas comparativas, listas ou visualizações lado a lado (Ex: "Crie uma tabela comparando GDMT com colunas para ajuste renal, efeito no potássio e contraindicações").

## Pérolas Clínicas e Atualizações de Diretrizes (Casos Citados)
- **Rinite Alérgica (Atualização de Conduta sobre Diretriz da AAO-HNS de 2015):**
	- **Tratamento:** Anti-histamínicos intranasais são agora suportados por evidências recentes (revisões sistemáticas e meta-análises) como opções de *primeira linha* para doença leve, superando o status antigo de "terapia adicional opcional".
	- **Diagnóstico (Testes Alérgicos):** Evidências recentes suportam o uso de diagnósticos resolvidos por componentes. 
		- *Red Flag:* Pacientes com sintomas sugestivos, mas com IgE sistêmica (sangue/pele) negativa, podem ter rinite alérgica local, requerendo *teste de provocação nasal especializado*.
- **Rouquidão / Disfonia (Validação da Diretriz da AAO-HNS de 2018):**
	- **Imagem:** **NÃO** solicitar Tomografia Computadorizada (TC) ou Ressonância Magnética (RM) para queixa primária de voz *antes* da visualização direta da laringe. Evidências atuais continuam a demonstrar ausência de benefício diagnóstico inicial e preponderância de dano.
	- **Tratamento (Disfonia Espasmódica):** Injeção de Toxina Botulínica mantém-se suportada por RCTs recentes, demonstrando melhora sustentada na qualidade de vida com efeitos adversos apenas transitórios.
- **Saúde Pública e Surtos (Informação "Just-in-Time"):**
	- **Suspeita de Hantavírus:** O foco primário em áreas de surto (geograficamente rastreadas) deve ser voltado a Precauções de Isolamento/EPIs adequados, modos de transmissão pessoa-a-pessoa e sinais/sintomas precoces (não em virologia básica).
	- **Rastreio de Tuberculose:** Em áreas de alta incidência local (ex: crescimento de casos em NYC), queixas de "tosse crônica, perda de peso ou sudorese noturna" devem engatilhar imediata consideração de TB no diferencial e notificação clínica.
	- **Profilaxia Pós-Exposição (PEP) HIV:** Tempo-dependente. A PEP deve ser iniciada estritamente dentro da janela de **72 horas** após a exposição potencial. (Uso de linhas diretas regionais de saúde pública é encorajado para acesso imediato a medicamentos).