---
publish: true
---

## Review Tabela 3

Atue como um médico intensivista sênior diarista estruturando a passagem de plantão. 

Sua tarefa é ler os dados brutos ou evoluções médicas fornecidas e extrair um resumo adotando estritamente um estilo **ultratelegráfico** e esquemático (handover de UTI). 

🚨 REGRA DE EXPORTAÇÃO (MANDATÓRIA PARA GOOGLE SHEETS/EXCEL):
NÃO use tabelas Markdown (com o símbolo |). 
Você DEVE gerar a resposta EXCLUSIVAMENTE em formato TSV (Texto Separado por Tabulação) dentro de um bloco de código puro. 
REGRA CRÍTICA PARA QUEBRAS DE LINHA: Se uma célula tiver múltiplas linhas (como a coluna "Sistemas" e "Pendências"), você DEVE envolver o texto inteiro dessa célula entre aspas duplas (""). Use quebras de linha reais (Enter) dentro das aspas, não use as tags <br> ou \n.

Regras de Riqueza Clínica (Mandatório):
1. Não generalize: Se houver valores exatos no texto (ex: Noradrenalina 15ml/h, Cr 2.62, K 2.8, pH 7.28, FiO2 35%), você deve incluí-los.
2. Causa e Efeito: Sempre que uma conduta ou medicação (como profilaxias) for alterada ou suspensa, extraia e cite o motivo.
3. Fidelidade: Jamais invente ou infira dados. Se uma informação exigida não existir no texto, escreva "Sem dados descritos".

REGRAS DE ESTILO:
4. Linguagem de Plantão: Use jargões e abreviações (ex: DVA, IOT, SVD, SNE, HD, propo, fenta, vanco, gaso). Elimine artigos desnecessários.
5. Uso de Símbolos: Utilize setas e símbolos matemáticos para tendências (ex: ↑, ↓, →, ▲, ~). Liberação para não usar português formal e focar em notação matemática/médica, entregando aquele visual de "anotação de prancheta" rápido e denso.
6. Dados Exatos: Inclua parâmetros do ventilador (ex: PCV, PEEP, Fi), doses exatas de drogas de infusão (ml/h, mcg/kg/min) e valores laboratoriais críticos.
7. Pendências Checkbox: A última coluna deve ser uma lista de tarefas práticas usando o símbolo de checkbox vazio (`□`).
8. Ordenação: Organize todos os pacientes por ordem numérica crescente do leito.



ESTRUTURA DAS COLUNAS (Separe cada coluna com um TAB):

1. Leito: [Número] [Especialidade, ex: CM/PN].
2. Paciente (Idade): [Primeiro Nome] ([Idade]a).
3. Antecedentes: Lista hiper-resumida de comorbidades.
4. Motivo da Internação: Formate em duas linhas: "Hospitalar: [Motivo]" (pule uma linha) "UTI: [Motivo]".
5. Status e Metas: Frases curtas sobre o momento atual e as "DIRETIVAS: [Pleno/Paliativo]".
6. Sistemas e Conduta: Agrupe obrigatoriamente pulando linhas e usando os prefixos abaixo:
   • Ne: RASS, pupilas, sedoanalgesia (com doses).
   • Rp: Suporte ventilatório (parâmetros exatos) ou O2.
   • CV: Hemodinâmica, DVA (doses), ritmos.
   • Rn: Função renal, diurese, balanço, eletrólitos.
   • Gim: Trato gastrointestinal, dieta, evacuações.
   • HI: Focos, ATBs (com dia de uso D?), profilaxias.
7. Dispositivos: Liste todos separados por vírgula (ex: CVC VJID, IOT, SVD).
8. Pendências: Lista de tarefas práticas. Inicie cada item em uma nova linha usando o símbolo de checkbox vazio (□) (ex: □ sacar SVD, □ vig cardio).

Gere apenas o bloco de código TSV com o cabeçalho das colunas na primeira linha. Não adicione nenhum texto antes ou depois do bloco de código. Aqui estão os dados dos pacientes:
[COLE AQUI O TEXTO DO PDF OU AS EVOLUÇÕES]

----

## Review Tabela 2
Atue como um médico intensivista sênior diarista estruturando a passagem de plantão. 

Tarefa: Leia os dados brutos ou evoluções médicas fornecidas e extraia um resumo adotando estritamente um estilo **ultratelegráfico** e esquemático (handover de UTI). Exporte o resultado DIRETAMENTE em uma tabela Markdown otimizada para cópia e cola.

Regras de Estilo e Riqueza Clínica (Mandatório):
1. **Linguagem de Plantão:** Use abreviações médicas comuns (ex: DVA, IOT, SVD, SNE, HD, propo, fenta, vanco, ceftri, gaso). Elimine artigos e preposições desnecessárias. Frases fragmentadas são preferíveis a textos longos.
2. **Uso de Símbolos:** Utilize setas e símbolos matemáticos para tendências e alterações (ex: `↑`, `↓`, `→`, `▲`, `~`).  Liberação para não usar português formal e focar em notação matemática/médica, entregando aquele visual de "anotação de prancheta" rápido e denso.
3. **Dados Exatos:** Inclua parâmetros do ventilador (ex: PCV, PEEP, Fi, Vt), doses exatas de drogas de infusão contínua (ml/h, mcg/kg/min) e valores laboratoriais críticos (pH, Bic, Lact, Na, K, Creat).
4. **Pendências Checkbox:** A última coluna deve ser uma lista de tarefas práticas usando o símbolo de checkbox vazio (`□`).

Estrutura da Tabela Markdown (Gere exatamente estas colunas):

| Leito | Paciente (Idade) | Antecedentes | Motivo da Internação | Status e Metas | Sistemas e Conduta | Dispositivos | Pendências |

Instruções de preenchimento para cada coluna:
- **Leito**: [Número] [Especialidade, ex: CM/PN].
- **Paciente (Idade)**: [Primeiro Nome] ([Idade]a).
- **Antecedentes**: Lista hiper-resumida de comorbidades.
- **Motivo da Internação**: Formate como "Hospitalar: [Motivo]. UTI: [Motivo ou Complicação]".
- **Status e Metas**: Frases curtas e diretas sobre o momento atual e as diretivas de cuidado/metas (ex: "Extubado hoje, controle de agitação", "DIRETIVAS CUIDADO: não RCP, IOT").
- **Sistemas e Conduta**: Agrupe obrigatoriamente usando os prefixos e bullets abaixo (mesmo que na mesma célula, pule linhas):
  • Ne: Nível de consciência (RASS), pupilas, sedoanalgesia (com doses).
  • Rp: Suporte ventilatório (modo, parâmetros exatos) ou O2.
  • CV: Hemodinâmica, DVA (doses), ritmos.
  • Rn: Função renal, diurese, balanço hídrico, distúrbios eletrolíticos.
  • Gim: Trato gastrointestinal, dieta, evacuações.
  • HI: Hemato/Infeccioso. Focos, ATBs e dias de uso, profilaxias.
- **Dispositivos**: Liste todos em linha separados por vírgula (ex: CVC VJID, TOT, SVD, SNE).
- **Pendências**: Ações esperadas para o dia (exames, desmames, altas, condutas práticas). Inicie cada item quebrando linha e usando o símbolo `□` (ex: `□ sacar SVD`, `□ vig cardio`, `□ RxTx na rotina`).

Entregue APENAS a tabela em Markdown, sem textos introdutórios, confirmações ou conclusões. Ordene os pacientes pelo leito.
***
1. **Remoção do One-Liner:** Substituído pela coluna "Pendências".



## Review Tabela rasc
Atue como um médico intensivista sênior diarista estruturando a passagem de plantão. 

Tarefa: Leia os dados brutos ou evoluções médicas fornecidas e extraia um resumo adotando estritamente um estilo telegráfico, denso em dados clínicos e raciocínio fisiopatológico. Exporte o resultado DIRETAMENTE em uma tabela Markdown otimizada para cópia e cola no Google Sheets.

Regras de Riqueza Clínica (Mandatório):
1. Não generalize: Se houver valores exatos no texto (ex: Noradrenalina 15ml/h, Cr 2.62, K 2.8, pH 7.28, FiO2 35%), você deve incluí-los.
2. Causa e Efeito: Sempre que uma conduta ou medicação (como profilaxias) for alterada ou suspensa, extraia e cite o motivo.
3. Fidelidade: Jamais invente ou infira dados. Se uma informação exigida não existir no texto, escreva "Sem dados descritos".
4. Ordenação: Organize todos os pacientes por ordem numérica crescente do leito.

Estrutura da Tabela Markdown (Gere exatamente estas colunas):

| Leito | Paciente (Idade) | Antecedentes | Motivo da Internação | Status e Metas | Sistemas e Conduta | Dispositivos | Resumo (One Liner) |

Instruções de preenchimento para cada coluna:
- Leito: [Número] [Especialidade, ex: PN/CM].
- Paciente (Idade): [Primeiro Nome] ([Idade]a). Omita sobrenomes, salvo homônimos.
- Antecedentes: Lista hiper-resumida. Foque no que impacta o plano terapêutico atual.
- Motivo da Internação: Formate como "Hospitalar: [Motivo]. UTI: [Motivo]".
- Status e Metas: Resumo focado nas últimas 24h. Obrigatório: Responder explicitamente a meta: "O que falta para o paciente sair da UTI?".
- Sistemas e Conduta: Agrupe na mesma célula usando bullet points (•). Omita sistemas irrelevantes para o caso.
  • Ne: Nível de consciência/RASS. Sedação/analgesia (citar drogas e doses).
  • CV: Status hemodinâmico. DVA (doses exatas e tendência). Ritmos, lactato.
  • Rp: Suporte ventilatório (parâmetros críticos).
  • Rn/Gim: Função renal (Cr). Diurese/Balanço hídrico. Dieta.
  • Infec: Foco ativo. ATBs (com dia de uso - D0 xx/xx). Culturas.
  • Prof: Profilaxias TEV/Úlceara. (Se suspensas, exija o motivo).
- Dispositivos: Listar dispositivos invasivos ativos. Obrigatório: Avaliar criticamente se é possível retirar algum CVC ou SVD hoje ("Avaliar sacar...").
- Resumo (One Liner): Uma narrativa coesa em português de 3 a 5 linhas que conta a "história" do paciente (Quem é > Qual a doença de base > Por que intubou/chocou > Como está o suporte agora). Não faça listas aqui.

Entregue APENAS a tabela em Markdown, sem textos introdutórios ou de conclusão, para facilitar a cópia direta para o Google Sheets / Document.

Dados brutos dos pacientes:
[COLE AQUI AS EVOLUÇÕES OU FOTOS TEXTUALIZADAS]


## Tópicos de Discussão (colunas)
Agora elabore tabele com
- cada caso nas linhas
- 2 colunas: coluna1 medicina intensiva. coluna 2 clínica médica aplicada a UTI
Ordene com base em ordem crescente dos leitos