---
publish: true
---


# Tromboelastografia (TEG)
## Princípios Gerais e Escolha do Cartucho
- **A TEG (e outros métodos viscoelásticos) é superior aos exames tradicionais para guiar hemotransfusão, pois avalia a hemostasia de forma global (sangue total).**
	- Permite avaliação funcional das plaquetas (e não apenas a contagem numérica) e da fibrinólise.
	- Evita o foco cego no INR, reduzindo o uso abusivo e desnecessário de Plasma Fresco Congelado (PFC).
	- Indicações principais: Coagulopatias complexas e dinâmicas (Cirrose, CIVD, Trauma, ECMO, Pós-operatório cardíaco).
	- Limitações da TEG: Insensível a anticoagulantes orais diretos (DOACs), Doença de von Willebrand, hipotermia (teste roda a 37ºC na máquina) e deficiências de fatores raros isolados.
- **Na UTI, o cartucho "Hemostasia Global com Neutralização de Heparina" (TEG 6S) deve ser o padrão ouro para pacientes críticos.**
	- Racional: Pacientes graves costumam sofrer dano no glicocálice endotelial, liberando heparan sulfato ("auto-heparinização"). O uso de um cartucho sem heparinase (que anula esse efeito) pode induzir a erros.
	- Nomenclaturas do TEG 6S:
		- CK (*Citrated Kaolin*): Avaliação nativa (com heparina, se presente).
		- CKH (*Kaolin with Heparinase*): Anula a heparina.
		- FFH-MA (*Functional Fibrinogen with Heparinase*): Isola a função exclusiva do fibrinogênio na formação do coágulo.

## Algoritmo Guiado por TEG 6S para Sangramento Ativo
- **Passo 1: Investigar e tratar Efeito Residual de Heparina (Exógena ou Endógena).**
	- Critério: Tempo R (R-time) do cartucho nativo (CK) é > 1,25 a 2 vezes maior que o Tempo R do cartucho com heparinase (CKH).
	- Conduta: Considerar Protamina (ex: 50 mg).
		- *Red Flag*: Individualizar a decisão devido aos riscos da protamina. Frequentemente o efeito hepariníco se dissipa espontaneamente sem necessidade de reversão.
		- 📎 Refs: 40016048
- **Passo 2: Investigar e tratar Deficiência de Fatores de Coagulação (Via enzimática).**
	- Critério: Tempo R do CKH significativamente prolongado (Valor normal: 4.3 a 8.3 minutos).
	- Conduta baseada no prolongamento do CKH R-time:
		- 10 a 12 minutos: Fazer 12-15 U/kg de Complexo Protrombínico (PCC) ou ~2 U de Plasma (PFC).
		- 13 a 15 minutos: Fazer 15-20 U/kg de PCC ou ~3 U de Plasma (PFC).
		- > 15 minutos: Fazer 20-25 U/kg de PCC ou ~4 U de Plasma (PFC).
- **Passo 3: Investigar e tratar Deficiência de Fibrinogênio.**
	- Critério: FFH-MA baixo (Valor normal: 15 a 34 mm). *Nota: Um limite de < 15 mm reflete um fibrinogênio sérico < 150 mg/dL.*
	- Conduta baseada no valor do FFH-MA:
		- 15 a 20 mm: *Considerar* reposição, principalmente se o alvo for mais rigoroso (ex: cirurgia grave onde se deseja fibrinogênio > 200 mg/dL).
		- 10 a 14 mm: Administrar 4-6 gramas de concentrado de fibrinogênio ou 5-10 unidades de crioprecipitado.
		- < 10 mm: Considerar doses mais elevadas.
		- 📎 Refs: 33141779
- **Passo 4: Investigar e tratar Disfunção ou Deficiência Plaquetária.**
	- Critério: FFH-MA está normal (> 15-20 mm) E a amplitude máxima geral (CRT-MA) está baixa (Normal do CRT-MA: 53-69 mm).
	- *Atenção*: Se o fibrinogênio (FFH-MA) e a amplitude global (CRT-MA) estiverem *ambos* baixos, reponha o fibrinogênio primeiro (Passo 3) e repita a TEG antes de transfundir plaquetas.
	- Conduta baseada na Amplitude Máxima (MA):
		- 48 a 50 mm: DDAVP (Desmopressina) 0,3 mcg/kg.
		- 43 a 47 mm: DDAVP 0,3 mcg/kg + 1 Unidade de plaquetas por aférese.
		- ≤ 42 mm: DDAVP 0,3 mcg/kg + 2 Unidades de plaquetas por aférese.
- **Passo 5: Investigar e tratar Hiperfibrinólise.**
	- Critério: LY-30 aumentado (Normal: < 2.6 a 3%).
	- Conduta: Inibidores fibrinolíticos (Ácido Tranexâmico ou Ácido Aminocapróico).

## TEG 5000 (Geração Anterior) e Platelet Mapping
- **Na TEG convencional, o Ângulo Alfa reflete a função COMBINADA de plaquetas e fibrinogênio, e NÃO apenas a função do fibrinogênio (Mito Clínico).**
	- Para isolar a real força e função do fibrinogênio, você precisa do teste TEG 6S com inibição química de plaquetas.
	- Amplitude Máxima (MA) Baixa: Reflete falha combinada. Na dúvida, e sem exames específicos, repor fibrinogênio primeiro gera benefícios imediatos, é menos consumido que a plaqueta pelo doente crítico e apresenta menos riscos transfusionais.
	- Tempo R normal e sangramento + INR largo: É um dado valiosíssimo na Cirrose ou CIVD. Um R-time normal contraindica plasma fresco, pois prova que a cascata enzimática *in vivo* funciona, independente do INR alterado.
- **O estudo de *Platelet Mapping* (Mapeamento) é mandatório para avaliar uso de AAS e Clopidogrel na TEG.**
	- Fisiologia: A TEG nativa gera um excesso de trombina (Thrombin Burst) tão grande no tubo de ensaio que ativa as plaquetas por vias alternativas, atropelando e mascarando o efeito do AAS/Clopidogrel.
	- Como funciona o Mapeamento:
		- Ácido Araquidônico (AA): Avalia a via inibida pelo AAS.
		- ADP: Avalia a via inibida pelos bloqueadores P2Y12 (Clopidogrel).
		- *Pérola:* Inibição com ADP menor que ~35% indica baixo risco de sangramento perioperatório no uso prévio de clopidogrel.

---

# Testes Tradicionais de Coagulação (Enzimáticos)
## Prolongamento Isolado do INR (PTT Normal)
- **Reflete uma deficiência do Fator VII (Via Extrínseca) ou uma deficiência muito sutil da Via Comum.**
	- O INR longo se correlaciona bem com risco de sangramento apenas no uso de Varfarina. NÃO tem correlação clínica com sangramento na Cirrose ou CIVD, pois estas doenças afetam também os anticoagulantes naturais (Proteínas C e S), causando um reequilíbrio da hemostasia não mensurado pelo INR.
- **O Desafio com Vitamina K Venosa (10mg IV) ajuda a diferenciar a etiologia na UTI.**
	- Nunca usar via oral em pacientes críticos (risco de má-absorção invalidando o teste).
	- Correção do INR após 24h: Confirma deficiência nutricional de Vitamina K ou uso de varfarina.
	- Ausência de correção: Sugere insuficiência hepática severa, Inibidores do Fator Xa (Rivaroxabana/Apixabana), Anticoagulante lúpico grave ou CIVD.

## Prolongamento Isolado do PTT (INR Normal)
- **Reflete um acometimento na Via Intrínseca (Fatores XII, XI, IX ou VIII).**
	- *Red Flag*: Deficiências dos fatores de contato (XII ou XI) podem alargar substancialmente o PTT laboratorial, mas raramente causam sangramento clínico *in vivo*.
	- Fator de confusão: Níveis muito elevados de Fator VIII (ex: em respostas inflamatórias agudas e gestação) encurtam falsamente o PTT, mascarando o alcance do alvo terapêutico na anticoagulação com Heparina não fracionada ("pseudo-resistência" à heparina).
- **O "Teste da Mistura" (Mixing Study) é mandatório para diferenciar deficiência de fator versus presença de inibidor circulante.**
	- Mecânica: Mistura-se 1:1 o plasma do paciente com plasma normal (que contém 100% de todos os fatores).
	- PTT CORRIGE na mistura: Significa deficiência de fator (Basta ~50% do fator para o PTT normalizar). Causas: Hemofilias (A ou B), deficiência de von Willebrand grave.
	- PTT NÃO CORRIGE: Significa presença de Inibidor circulante "destruindo" ou inativando também o plasma normal. Causas: Heparina não fracionada, Anticoagulante Lúpico (corrige se fosfolipídeo exógeno for adicionado) ou inibidor adquirido. *Nota: HBPM geralmente não altera o PTT.*

## Prolongamento Conjunto (INR e PTT alargados)
- **Indica agressão global à hemostasia ou bloqueio na Via Comum (X, V, II ou Fibrinogênio).**
	- Causas Frequentes: Efeito supraterapêutico grave de Varfarina, falência hepática severa, Inibidor Direto de Trombina (Dabigatrana), intoxicação por heparina, CIVD e hipofibrinogenemia extrema (< 80 mg/dL).
	- Abordagem Inicial: Revisar lista de drogas (DOACs/Heparinas), solicitar Fibrinogênio de Clauss, D-dímero e testes de função hepática.

---

# Fibrinogênio e Tempo de Trombina
## Fibrinogênio Convencional (Método de Clauss)
- **É um teste plasmático hiperdiluído que mede a polimerização da fibrina sob altas doses de trombina bovina, superando a maioria dos inibidores.**
	- Fisiologia do Teste: Por usar plasma diluído e excesso de trombina, ele consegue avaliar a presença e função de fibrinogênio sem que concentrações terapêuticas de heparina atrapalhem a medição.
	- Falsos resultados (Clauss baixo indevidamente): Presença de Inibidores Diretos da Trombina (ex: Dabigatrana) inibem diretamente o reagente do ensaio.
	- Falsos resultados (Clauss "normal", mas função ruim in vivo): Disfibrinogenemia adquirida na sepse, trauma ou cirrose. A molécula defeituosa funciona na diluição artificial do laboratório, mas cria coágulos fracos no paciente.

## Fibrinogênio Funcional Viscoelástico (TEG 6S - FFH-MA)
- **Prevê a necessidade transfusional e o risco de sangramento com mais eficácia que o fibrinogênio de Clauss tradicional.**
	- Como opera: Isola a força do fibrinogênio ao inibir quimicamente as plaquetas no tubo, usando sangue total.
	- Situações onde o TEG-Fibrinogênio se altera, mas o Clauss está normal:
		- Disfibrinogenemia adquirida (moléculas disfuncionais expostas no sangue total).
		- Falha da máquina em neutralizar doses maciças de heparina (heparinase tem um limite basal de ~5 UI/mL).
		- Trombocitopenia ou falha na inibição química completa do sistema plaquetário no cartucho.

## Tempo de Trombina (TT)
- **É um teste de plasma puro e NÃO-diluído, altamente sensível a inibidores, ideal para detectar heparina residual.**
	- Fisiologia: É irmão gêmeo do Clauss, mas sem as diluições que protegem a amostra. Consequentemente, frações minúsculas de heparina ou dabigatrana alargarão drasticamente o TT.
	- Se o TT vier prolongado, mas o Fibrinogênio (Clauss) estiver normal: A culpa é de um inibidor da trombina circulante, e não de falta de fibrinogênio.

---

# Testes Plaquetários: PFA-100 e ACT
## Analisador de Função Plaquetária (PFA-100)
- **O PFA é um exame "global" de triagem de função plaquetária, altamente dependente de Hematócrito (mínimo de 30%) e Contagem de Plaquetas (mínimo de 80.000/µL).**
	- Se houver anemia ou plaquetopenia severa, o aparelho falha em ocluir o orifício e acusa "disfunção" falsamente.
- **Interpretação Baseada nos Dois Cartuchos (COL/EPI e COL/ADP):**
	- AMBOS normais: Ausência de disfunção grave. (Nota: não exclui totalmente o uso de AAS, pois níveis compensatórios altos de Fator de von Willebrand mascaram o efeito).
	- EPI longo + ADP normal: Efeito exclusivo de AAS ou AINEs (ou disfunção/von Willebrand de grau leve).
	- AMBOS prolongados: Efeito de droga P2Y12 potente, uremia, Doença de von Willebrand grave, síndromes genéticas (Glanzmann, Bernard-Soulier) ou violação das regras de hematócrito/plaquetas.
	- *Dica Prática*: No cenário de neurocirurgia na UTI, um PFA EPI/ADP prolongado prediz alto risco de ressangramento e sugere uso de profilático de DDAVP pré-incisão.

## Tempo de Coagulação Ativado (ACT)
- **Teste restrito ao centro cirúrgico (especialmente cirurgia cardíaca) para monitorar altas doses de heparina à beira-leito.**
	- Usa ativadores de contato (vidro/caulim) para disparar intensamente a via intrínseca (análogo ao PTT).
	- Alvos comuns:
		- Normal basal: ~105 a 167 segundos.
		- Heparinização plena padrão: ~250 a 300 segundos.
		- Circulação extracorpórea (CEC cardíaca): > 450 segundos.

---

# Conceito Avançado: Modelo Celular da Coagulação
## Substituindo a Cascata Tradicional Linear
- **O modelo tradicional linear em vias (intrínseca/extrínseca/comum) explica apenas os exames de laboratório, mas falha em explicar a fisiologia do sangramento real, pois ignora o ambiente celular.**
	- No laboratório, descarta-se a célula por centrifugação. No leito do paciente, a coagulação acontece *obrigatoriamente* na membrana de plaquetas e fibroblastos.
## As 3 Fases do Modelo Celular
- **Fase 1: Iniciação**
	- Ocorre fora da circulação sistêmica. Células portadoras de Fator Tecidual (FT), como fibroblastos subendoteliais ou células endoteliais inflamadas, disparam a cascata (via VIIa e Xa), gerando uma pequena quantidade local de Trombina.
- **Fase 2: Amplificação**
	- A pequena quantidade de trombina inicial migra para as plaquetas próximas, ativando-as. A plaqueta muda sua superfície membranar (expondo fosfolipídios pró-coagulantes) e o Fator von Willebrand é liberado.
- **Fase 3: Propagação**
	- As plaquetas recrutadas servem como uma superfície massiva de montagem para os complexos enzimáticos. A via intrínseca local acelera violentamente, gerando o fenômeno de "Explosão de Trombina" (*Thrombin Burst*), que consolida rapidamente o coágulo de fibrina estável.