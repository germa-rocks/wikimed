---
publish: true
---

## 1. Atualização SOFA-2 (JAMA 2025)
- **O SOFA-2 moderniza a avaliação de disfunção orgânica incorporando suportes avançados, equivalência de vasopressores em $\mu\text{g/kg/min}$ e delirium.**
  - **Principais Mudanças Conceituais (*Singer M, et al. JAMA 2025*):**
    - *Respiratório:* Novos cortes de $PaO_2/FiO_2$ (`300`, `225`, `150`, `75 mmHg`); permite $SpO_2/FiO_2$ se gasometria indisponível; inclui formalmente **VNI, CNAF e ECMO**.
    - *Cardiovascular:* Estratificação pela soma de `Norepinefrina + Epinefrina` ($\mu\text{g/kg/min}$), equivalência com outros vasopressores/inotrópicos (vasopressina, angiotensina -> fim da dependência da dopamina) e inclusão de **suporte circulatório mecânico**.
    - *Neurológico:* Mantém Glasgow (GCS), adiciona **equivalentes motores/gestuais** para sedados/intubados e pontua formalmente **delirium / fármacos para delirium**.
    - *Renal, Hepático e Coagulação:* Débito urinário ajustado ao peso (`mL/kg/h`), inclusão explícita de **TRS** (em uso ou com critério), e refinamento dos cortes de bilirrubina e plaquetas (discrasias/induções medicamentosas).
  - **Tabela Oficial de Pontuação SOFA-2:**

| Sistema | 0 pontos | 1 ponto | 2 pontos | 3 pontos | 4 pontos |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Neurológico** | GCS `15` (ou sinal de positivo, punho fechado ou paz) | GCS `13–14` (ou localiza dor) **OU** uso de drogas p/ tratar delirium | GCS `9–12` (ou retirada à dor) | GCS `6–8` (ou flexão anormal à dor) | GCS `3–5` (ou extensão à dor, arreativo ou mioclonia generalizada) |
| **Respiratório** ($PaO_2/FiO_2$) | `> 300 mmHg` (`> 40 kPa`) | `<= 300 mmHg` (`<= 40 kPa`) | `<= 225 mmHg` (`<= 30 kPa`) | `<= 150 mmHg` (`<= 20 kPa`) + suporte ventilatório avançado (VNI/CNAF/VMI) | `<= 75 mmHg` (`<= 10 kPa`) + suporte ventilatório avançado **OU** `ECMO` |
| **Cardiovascular** (Soma Nora + Epi em $\mu\text{g/kg/min}$) | PAM `>= 70 mmHg`, sem vasopressor/inotrópico | PAM `< 70 mmHg`, sem vasopressor/inotrópico | Dose baixa (`<= 0,2`) **OU** qualquer dose de outro vasopressor/inotrópico | Dose média (`> 0,2 a <= 0,4`) **OU** dose baixa (`<= 0,2`) + outro vasopressor/inotrópico | Dose alta (`> 0,4`) **OU** dose média (`> 0,2 a <= 0,4`) + outro vasopressor/inotrópico **OU** `suporte mecânico` |
| **Hepático** (BT em mg/dL [$\mu\text{mol/L}$]) | `<= 1,20` [`<= 20,6`] | `<= 3,0` [`<= 51,3`] | `<= 6,0` [`<= 102,6`] | `<= 12,0` [`<= 205`] | `> 12,0` [`> 205`] |
| **Renal** (Cr mg/dL [$\mu\text{mol/L}$] ou DU) | Cr `<= 1,20` [`<= 110`] | Cr `<= 2,0` [`<= 170`] **OU** DU `< 0,5 mL/kg/h` por `6–12h` | Cr `<= 3,50` [`<= 300`] **OU** DU `< 0,5 mL/kg/h` por `>= 12h` | Cr `> 3,50` [`> 300`] **OU** DU `< 0,3 mL/kg/h` por `>= 24h` **OU** anúria (`0 mL`) por `>= 12h` | Em **TRS** ou preenche critérios p/ TRS (inclui uso crônico) |
| **Hemostasia** (Plaquetas $\times 10^3/\mu\text{L}$) | `> 150` | `<= 150` | `<= 100` | `<= 80` | `<= 50` |

---

## 2. Neurointensivismo: AVCI (2026), AVCH e TCE (ATLS 11)

### AVCI: Reperfusão, Complicações e Anticoagulados (Diretriz 2026)
- **Tenecteplase em bolus único consolida-se como Classe I, e a trombectomia mecânica expande-se para grandes núcleos isquêmicos.**
  - **Protocolo de Fibrinólise e Trombectomia (2026):**
    - *Tenecteplase (TNK):* Classe I (equivalente/superior à alteplase em logística) -> **`0,25 mg/kg` EV em bolus único** (máx `25 mg`). Dose de `0,4 mg/kg` **contraindicada** (risco de sangramento).
    - *Neuroimagem:* **TC sem contraste imediata** -> nunca atrasar trombólise aguardando TC de perfusão.
    - *Janelas de Fibrinólise:* Clássica até `4h30min`; Estendida / *Wake-up stroke* até `9h` se selecionada por imagem avançada (TC perfusão ou RM com *mismatch* `DWI-FLAIR`).
    - *Trombectomia Mecânica:* Expandida entre `6–24h` para incluir casos de **grande núcleo isquêmico (`ASPECTS 3–5`)**.
  - **Conduta na Transformação Hemorrágica Pós-Fibrinólise (2026):**
    - *Ação imediata:* **Suspender infusão** de Alteplase/TNK imediatamente + **TC de crânio sem contraste STAT** (confirmar e cubicar volume).
    - *Reversão da coagulopatia:* **Crioprecipitado** `10 U` inicial (repor fibrinogênio) + **Ácido Tranexâmico (TXA)** `1–2 g EV` +/- **Complexo Protrombínico (CCP)** (pode ser considerado).
    - *Suporte e Cirurgia:* Controle de PA (alvo **PAS `< 140–160 mmHg`**) + proteção de via aérea/prevenção de herniação + avaliação neurocirúrgica (**craniotomia descompressiva** se volumoso/efeito de massa).
- **No AVCI em anticoagulados, checar droga, hora da última dose e função renal; anticoagulação NUNCA contraindica trombectomia mecânica.**
  - **Manejo do AVCI em Uso de Anticoagulantes:**

| Anticoagulante | Avaliação Laboratorial STAT | Critério para Trombólise EV | Reversão (Se Transformação Hemorrágica) |
| :--- | :--- | :--- | :--- |
| **Varfarina** | Coletar **RNI** imediatamente | Permitida apenas se **`RNI <= 1,7`** (`> 1,7` contraindicada) | **CCP** (*Beriplex/Prothromplex*) + **Vitamina K EV** |
| **Dabigatrana** (Inibidor IIa) | **Tempo de Trombina (TT)** ou TTPa | Contraindicada se última dose `< 48h` (função renal normal). Permitida se `> 48h` + coagulograma específico normal.<br>*Exceção:* Reversão imediata com **Idarucizumabe** seguida de trombólise (centros experientes) | **Idarucizumabe** (*Praxbind*) |
| **Rivaroxabana / Apixabana / Edoxabana** (Inibidores Xa) | **Atividade Anti-Xa** (se disponível), TAP e TTPa *(normais não excluem efeito total)* | Contraindicada se última dose `< 48h` (função renal normal). Permitida se `> 48h` + testes específicos normais | **Andexanet Alfa** (se disponível) **OU** **CCP de 4 fatores** em altas doses |

  - *Oclusão de Grande Vaso (Angio-TC):* Priorizar **Trombectomia Mecânica** dentro da janela (linha principal quando trombólise química é proibida).

### AVCH (Prognóstico) e TCE na UTI (ATLS 11)
- **O ICH Score estratifica mortalidade em 30 dias no AVCH, enquanto o ATLS 11 eleva metas pressóricas e prioriza reversão antitrombótica no TCE.**
  - **Escore ICH (*Hemphill et al., Stroke 2001* — Total `0–6 pontos`):**
    - *Componentes:* **Glasgow admissão:** `3–4` (2 pts), `5–12` (1 pt), `13–15` (0 pt) | **Idade:** `>= 80 anos` (1 pt), `< 80` (0 pt) | **Local:** Infratentorial (1 pt), Supratentorial (0 pt) | **Volume:** `>= 30 mL` (1 pt), `< 30 mL` (0 pt) | **Hemoventrículo:** Sim (1 pt), Não (0 pt).
    - *Mortalidade em 30 dias:* 0 pts (`0%`) -> 1 pt (`13%`) -> 2 pts (`26%`) -> 3 pts (`72%`) -> 4 pts (`97%`) -> 5 e 6 pts (`100%`).
  - **5 Mudanças do ATLS 11 no TCE com Impacto na UTI:**
    1. *Alvos de PAS mais elevados p/ neuroproteção (TCE moderado/grave):* **PAS `> 100–110 mmHg`** (ajustado por idade: `> 100 mmHg` em adultos; ainda mais alto em idosos).
    2. *Ácido Tranexâmico (TXA):* Dose maior no TCE (comparado ao padrão de hemorragia traumática maior de `1 g bolus + 1 g em 8h` dentro de `3h`).
    3. *Reversão rápida de antitrombóticos:* Protocolos enfatizados para varfarina, DOACs (apixabana, rivaroxabana) e antiplaquetários.
    4. *Manejo de HIC em camadas (tiered approach):* Abordagem estruturada escalonada (embora menos detalhada que a *Brain Trauma Foundation*).
    5. *Ressuscitação balanceada e peri-intubação:* Conceito **`xABCDE`** + *damage control* (menos cristaloides, transfusão precoce, hipotensão permissiva seletiva) + prevenção estrita de hipotensão peri-intubação.

---

## 3. Choque, Monitorização Hemodinâmica e Trauma

### Choque Séptico, Refratário e Incoerência Hemodinâmica
- **A ressuscitação guiada pelo Tempo de Enchimento Capilar (TEC) reduz mortalidade/suporte vital, sendo superior ao cuidado convencional.**
  - **Estudo ANDROMEDA-2 (2025):** `1467` pacientes com choque séptico precoce (`19` países) -> protocolo personalizado de `6 horas` baseado no **TEC** (integrando pressão de pulso, fluido-responsividade e ecocardiografia beira-leito p/ guiar fluidos e vasopressores) -> melhora estatisticamente significativa no desfecho composto (mortalidade + tempo de suporte vital).
  - **Manejo do Choque Séptico Refratário:**
    - *Definição:* Doses elevadas de Noradrenalina (**`> 0,5 mcg/kg/min`**) + lactato persistentemente alto ou hipoperfusão tecidual.
    - *Vasopressores e Alvos:* Associar **Vasopressina** ou **Epinefrina** (2ª linha); manter **PAM `>= 65 mmHg`** (aceitável **`60–65 mmHg` em idosos `>= 65 anos`** pelo *Surviving Sepsis Campaign*).
    - *Adjuvantes:* **Dobutamina** (se disfunção miocárdica / baixo DC com hipoperfusão) + **Hidrocortisona EV** (doses crescentes de vasopressores).
    - *Restrição de Bicarbonato:* Evitar uso rotineiro na acidose lática leve/moderada -> **restrito a `pH <= 7,2` + Lesão Renal Aguda associada**.
  - **Incoerência Hemodinâmica:**
    - *Conceito:* Perda de acoplamento entre macro-hemodinâmica sistêmica restaurada e microcirculação tecidual hipoperfundida -> piora prognóstica.
    - *Diagnóstico Multimodal:* **Clínica** (balanço hídrico, PEEP, PIA elevada, edema intersticial, dependência de vasopressor) + **USG** (`SBRI`, `VExUS`, contratilidade) + **Sistêmica/Termodiluição** (FC, PAI, PVC, POAP, VPP, DC, VVS, IRVS, `EVLW`, `PVPI`, `GEVD`) + **Microcirculação sublingual** (`MFI`, `PPV`, `TVD`, `PVD`, velocidade de hemácias, `PBR`) + **Laboratório** (Hb, $SvO_2$, $\Delta P_{(v-a)}CO_2$, lactato, marcadores inflamatórios/coagulação/lesão endotelial).

### Monitorização Hemodinâmica e Choque Hemorrágico (ATLS 11)
- **A monitorização classifica-se pelo grau de invasividade, e o choque hemorrágico no ATLS 11 adota 3 estágios e o conceito de Diamante Letal.**
  - **Classificação dos Métodos de Monitorização Hemodinâmica:**

| Nível de Invasividade | Definição Técnica | Dispositivos e Variáveis Captadas |
| :--- | :--- | :--- |
| **1. Não Invasiva** | Sem dispositivos intravasculares ou intracardíacos | **PANI** (oscilométrica), **Oximetria** ($SpO_2$), **ECG/Telemetria**, **ETT** (estrutural/funcional beira-leito), **Bioimpedância / Bioreactância torácica** (DC estimado) |
| **2. Minimamente Invasiva** | Punções periféricas/centrais + análise de contorno de pulso ou US esofágico | **PAI** (radial/femoral/braquial + gasometrias), **PVC** (volume/função VD), **Contorno de pulso / Termodiluição transpulmonar** (*FloTrac/Vigileo, PiCCO, LiDCO, EV1000* -> DC contínuo, VVS, água pulmonar extravascular), **Doppler esofágico** (aorta descendente), **ETE** |
| **3. Invasiva (Avançada)** | Cateter posicionado no coração direito e artéria pulmonar | **Cateter de Artéria Pulmonar (*Swan-Ganz*)** -> medida direta de pressões de enchimento esquerdo (**POAP**), DC por termodiluição clássica, **$SvO_2$** e resistências vasculares |

  - **4 Pilares do Choque Hemorrágico no ATLS 11:**
    1. *Nova Classificação:* Reduzida de 4 para **3 estágios** (`leve`, `moderado` e `grave`).
    2. *Protocolo **`xABCDE`**:* Priorização absoluta do controle de hemorragia exsanguinante antes da via aérea.
    3. *Ressuscitação Hemostática:* Ressuscitação balanceada, uso precoce de **sangue total (*Whole Blood*)**, hipotensão permissiva e TXA.
    4. ***Diamante Letal*:** Expansão da antiga tríade da morte (`acidose` + `hipotermia` + `coagulopatia`) incluindo a **Hipocalcemia**.

---

## 4. Cardiointensivismo e Tromboembolismo Pulmonar (2025/2026)

### Tromboembolismo Pulmonar (Diretriz 2026)
- **A trombólise sistêmica segue 1ª linha no TEP de alto risco, enquanto trombectomia e terapias por cateter ganham Classe 2a em selecionados.**
  - **Estratificação e Organização (2026):** Gravidade reorganizada pela **função de VD + estabilidade hemodinâmica**; forte recomendação para **PERTs** (*Pulmonary Embolism Response Teams*). *Pegadinha:* **POCUS não diagnostica TEP**, mas é fundamental para estratificar disfunção de VD.
  - **Conduta Terapêutica por Cenário:**
    - *TEP de Alto Risco (choque obstrutivo / hipotensão persistente):* **Trombólise sistêmica** = 1ª linha (**Alteplase** ou **Tenecteplase** EV).
    - *Falha da Trombólise ou Alto Risco de Sangramento:* **Terapia Dirigida por Cateter (TDC)**, **Trombectomia Mecânica** ou **Embolectomia Cirúrgica**.
    - *TEP de Risco Intermediário-Alto (estável + disfunção de VD):* Individualizar trombólise vs. sangramento. **TDC e Trombectomia Mecânica são Classe 2a** para evitar piora clínica/mortalidade em selecionados (categorias **`E1` e `D1–D2`**).
      - *Evidências:* Estudo **`PEERLESS`** (trombectomia mecânica -> menor deterioração clínica e uso de UTI) e estudo **`HI-PEITHO`** (TDC -> reduziu eventos clínicos precoces).

### Emergência Hipertensiva (Diretriz 2025)
- **Exige redução rápida mas controlada com fármacos EV tituláveis em UTI, evitando queda abrupta (exceto dissecção de aorta e eclâmpsia).**
  - *Conceito:* Emergência (lesão aguda de órgão-alvo) = **UTI/Sala Vermelha + EV titulável** + monitorização contínua de sinais vitais/diurese (antiga "urgência" = manejo VO + observação).
  - **Metas Cronológicas de Redução Pressórica (Regra Geral):**
    - *1ª hora:* Reduzir PAM ou PAS em **até `20–25%`** -> *2 a 6 horas:* Estabilizar em **`~160/100–110 mmHg`** -> *24 a 48 horas:* Redução gradual até basal / **`< 130/80 mmHg`** e transição para VO.
  - **Escolha do Anti-Hipertensivo EV por Órgão-Alvo:**
    - *Maioria (EAP, Encefalopatia Hipertensiva):* **Nitroprussiato de Sódio** (1ª escolha pela rapidez). Outras opções EV: `Nicardipina`, `Labetalol`, `Hidralazina`.
    - *Síndrome Coronariana Aguda (SCA):* **Nitroglicerina** (preferencial).
    - *Dissecção Aguda de Aorta:* **Betabloqueadores (`Esmolol` / `Metoprolol`)** -> meta imediata em **minutos**: **`PAS < 120 mmHg` e `FC < 60 bpm`**.
    - *AVCI:* Reduzir apenas se **`PA >= 220/120 mmHg`** ou se candidato a trombolítico (AVCH e Eclâmpsia possuem metas específicas rápidas).

### Nova Definição de IAM e Síndrome BRASH
- **A nova definição de IAM extingue os Tipos 1–5, exige cortes de troponina por sexo e redefine MINOCA como lesão miocárdica.**
  - **Critérios e Nova Classificação Clínica do IAM:**
    - *Diagnóstico Obrigatório:* **Injúria miocárdica aguda** (curva de troponina com `>= 1` valor acima do **percentil 99 específico por sexo** -> evita subdiagnóstico em mulheres) **+** **Isquemia objetiva** (sintomas, novas alterações ECG, alteração segmentar no eco/imagem ou lesão coronariana). Inclui novos critérios p/ morte súbita e protocolos acelerados com troponina ultrassensível em baixo recurso.
    - *3 Categorias Clínicas (Fim dos Tipos 1–5):* **1. Infarto Primário** (ruptura/erosão de placa, dissecção espontânea, embolia, vasoespasmo); **2. Infarto Secundário** (desequilíbrio oferta/consumo de $O_2$ -> agora exige evidência rigorosa de lesão obstrutiva ou alteração segmentar em exames, não apenas troponina isolada); **3. Infarto Relacionado a Procedimento** (ICP ou CRM em janela de `30 dias`).
    - *MINOCA atualizado:* Passa a significar **lesão miocárdica** com coronárias não obstrutivas (diagnóstico de trabalho que exige investigação etiológica).
- **A Síndrome BRASH é um ciclo vicioso sinérgico entre hipercalemia e bloqueadores do nó AV desencadeado por disfunção renal.**
  - **Pentade:** **B**radycardia + **R**enal failure + **A**V blockade + **S**hock + **H**yperkalemia.
  - **Fisiopatologia em Cascata:** Gatilho (ex: IECA/BRA, hipovolemia) -> **LRA** -> acúmulo de bloqueadores AV de excreção renal (`atenolol, nadolol, digoxina`) + **Hipercalemia** (agravada por BB não seletivo) -> sinergismo gera **Bradicardia grave e BAV** (agravados por acidemia/uremia) -> **Choque** -> hipoperfusão hepática acumula bloqueadores de metabolismo hepático (`metoprolol, diltiazem, verapamil`) + piora da LRA -> retroalimenta o ciclo.

---

## 5. Ventilação Mecânica, VILI e Desmame Guiado por USG

### Mecânica Ventilatória, Curva P/V e Mechanical Power
- **A mecânica à beira-leito exige pausas estáticas sequenciais, buscando $\Delta P \le 14\text{ cmH}_2\text{O}$ e *Mechanical Power* $< 17\text{ J/min}$.**
  - **5 Passos da Avaliação da Mecânica no Paciente Intubado:** `1. Pressão de Pico` -> `2. Oclusão da Valva Inspiratória` ($P_{\text{platô}}$) -> `3. PEEP ajustada` -> `4. Oclusão da Valva Expiratória` -> `5. PEEP Total` (identifica Auto-PEEP).
  - **Interpretação da Curva Pressão-Volume (Loop P/V):**
    - *Morfologia e Histerese:* Elipse / "bola de rugby" (ramo inferior = inspiração; superior = expiração). **Histerese** (ramos não se sobrepõem) é fisiológica -> exige mais pressão para abrir alvéolos do que para mantê-los abertos.
    - *Inclinação (Complacência):* Deitada / desviada p/ **direita** = **baixa complacência** ("pulmão duro", pneumonia, edema); Vertical / desviada p/ **esquerda** = **alta complacência**.
    - *Pontos de Inflexão:* **PII (Inferior)** = início da abertura alveolar (definir PEEP ligeiramente acima p/ evitar colapso; PII muito baixo = risco de colapso -> aumentar PEEP); **PIS (Superior)** = início da sobredistensão (PIS muito baixo = risco de hiperdistensão -> reduzir $V_C$ ou pressão).
  - **Força / Potência Mecânica (*Mechanical Power* — Ergotrauma):**
    - *Conceito:* Energia total/minuto (`J/min`) transferida ao sistema respiratório (derivada da equação do movimento $\times V_C \times FR$), unificando **$V_C$, $\Delta P$, $P_{\text{platô}}$, fluxo inspiratório, PEEP e FR**.
    - *Alvo de Segurança:* Manter **`< 17 J/min`** (ou **`< 13 J/min`** em pulmões já doentes/SDRA) para reduzir VILI e mortalidade na UTI.

### Fenótipos de VILI, P-SILI, TIE e USG no Desmame
- **O volutrauma é o mecanismo mais deletério da VILI, enquanto esforços espontâneos intensos induzem P-SILI e *pendelluft* oculto.**
  - **Mecanismos Fisiopatológicos de Lesão Pulmonar Associada à VM:**

| Mecanismo | Determinante Físico / Gatilho | Fisiopatologia e Consequências Clínicas |
| :--- | :--- | :--- |
| **Volutrauma** *(Mais deletério)* | $V_C$ excessivo p/ o *"baby lung"* ($\Delta P = P_{\text{platô}} - \text{PEEP} > 14\text{ cmH}_2\text{O}$) | Deformação excessiva (*strain*) -> hiperpermeabilidade alveolocapilar, edema pulmonar e infiltração inflamatória. **Alvo: $\Delta P \le 14\text{ cmH}_2\text{O}$** |
| **Barotrauma** | Pressão transpulmonar excessiva (`> 20–22 cmH2O`) *(não $P_{va}$ isolada)* | Ruptura alveolar + fragmentação da matriz -> pneumotórax, pneumomediastino, pneumoperitônio, enfisema subcutâneo |
| **Atelectrauma** | PEEP subótima + disfunção de surfactante | Fenômeno **RACE** (abertura e colapso cíclicos) -> cisalhamento (*shear stress*). Prevenção: PEEP acima da pressão crítica de fechamento (*open lung*) |
| **Biotrauma** | Mecanotransdução | Hiperdistensão/cisalhamento -> liberação de citocinas -> lesão pulmonar (SDRA, fibrose) + **disfunção orgânica extrapulmonar** |
| **Rheotrauma** | Fluxo inspiratório excessivo | *Shear stress* nas bifurcações brônquicas e interfaces heterogêneas (independente de $V_C$/pressão; integrado ao *Mechanical Power*) |
| **P-SILI** | Esforço espontâneo intenso ($P_{\text{mus}}$ elevada) | 1) *Swings* pleurais negativos -> $\uparrow$ pressão transpulmonar e $V_C$ oculto em PSV; 2) $\uparrow$ pressão transmural vascular -> **edema pulmonar de baixa pressão**; 3) Assincronias (*breath stacking*, duplo disparo, *pendelluft*) |
| **Pendelluft** | Drive alto / contração diafragmática violenta | Pressão pleural muito negativa nas bases -> suga ar das regiões **não dependentes p/ as dependentes (basais)** antes do fluxo do ventilador -> superdistensão local maciça **invisível nas pressões do ventilador** |

  - **Tomografia de Impedância Elétrica (TIE) na UTI:** Guia ventilação em tempo real -> 1) Titulação de PEEP (colapso vs. hiperdistensão); 2) Assincronias e distribuição regional de ar (D/E, dependente/não dependente); 3) Detecção aguda de **pneumotórax**; 4) Resposta a manobras (prona, aspiração); 5) Perfusão pulmonar regional (contraste com salina hipertônica).
  - **Protocolo `ABCDEF-Ultrasound` no Desmame da VM:**
    - **A** (*Airway/Breathing* - Pulmonar): *Aeration score*, atelectasias, consolidações -> **B** (*Below diaphragm* - Abdominal): PIA, ascite -> **C** (*Circulation* - Cardíaco): função ventricular e sobrecarga hídrica -> **D** (*Diaphragm*): fração de espessamento (**`TFdi`**) e excursão diafragmática -> **E** (*Extra-diaphragmatic*): ativação compensatória de musculatura acessória.

---

## 6. Infectologia Crítica, Multirresistência (MDR) e IRAS

### Resistência Bacteriana, Escolha de ATB e Infecções de Partes Moles
- **O manejo de germes MDR exige culturas pré-ATB, conhecimento da microbiota local e otimização PK/PD com infusão prolongada de beta-lactâmicos.**
  - **5 Mecanismos de Resistência em UTI:** 1) *Inativação enzimática* (ESBL, carbapenemases `KPC`, `OXA-48`, `NDM`); 2) *Alteração do sítio de ligação* (`PBPs`/transpeptidases p/ penicilinas; `DNA girase` p/ quinolonas); 3) *Redução de porinas* (membrana externa de Gram-negativos); 4) *Bombas de efluxo* (comum em *P. aeruginosa*); 5) *Biofilmes* (matriz em cateteres/dispositivos -> aumenta resistência em até **`1000x`**).
  - **Fatores de Risco para MDR:** ATB prévio de amplo espectro (últimas semanas), internação prolongada, dispositivos invasivos (VM, CVC, SVD), colonização prévia, alta gravidade (`APACHE II`), comorbidades (imunossupressão, transplante, neoplasia hematológica, DM, DRC, idosos) e transmissão cruzada (leito anterior/proximidade).
  - **Estratégia de Prescrição:** Mapear perfil local + coletar culturas antes do ATB -> buscar menores **CIMs** no antibiograma (categoria **"I" = sensível aumentando exposição** com doses altas) + **infusão prolongada** de beta-lactâmicos (tempo > CIM).
  - **Terapia Antimicrobiana Direcionada (MDR e Partes Moles Graves):**

| Patógeno / Síndrome | Esquema de Primeira Escolha | Alternativas / Observações Técnicas |
| :--- | :--- | :--- |
| **Enterobactérias MDR (ex: KPC)** | **Ceftazidima-Avibactam** **OU** Polimixina B/E (colistina) + Aminoglicosídeo (amicacina/gentamicina) | Associar Meropenem/Doripenem se CIM não for extremamente alta |
| ***Acinetobacter baumannii* MDR** | **Polimixina B**, **Ampicilina-Sulbactam** (altas doses), Amicacina | **Tigeciclina** (com ressalvas em bacteremias devido a baixo nível sérico) |
| ***Pseudomonas aeruginosa* MDR** | **Ceftolozana-Tazobactam** | Associações com polimixinas, aminoglicosídeos ou carbapenêmicos |
| **MRSA** | **Vancomicina**, **Linezolida** ou **Daptomicina** | Evitar daptomicina em foco pulmonar (inativada pelo surfactante) |
| **Erisipela** (*S. pyogenes* A, C, G) | **Penicilina Cristalina** `0,5–4 milhões U EV 4/4h` **OU** Amoxicilina `500 mg VO 8/8h` | **Clindamicina** |
| **Celulite** (*S. aureus* + *S. pyogenes*) | **Oxacilina** `2–3 g EV 6/6h` **OU** Cefalotina `1–2 g EV 6/6h` **OU** Cefalexina `1 g VO 6/6h` | **Clindamicina** |
| **Fasceíte Necrotizante** *(Polimicrobiana / anaeróbios / Clostridium)* | **Limpeza cirúrgica ampla STAT** + **Ampicilina-Sulbactam** `1,5–3 g EV 6/6h` **OU** **Piperacilina-Tazobactam** `4,5 g EV 8/8h` **OU** **Ertapenem** `1 g EV 1x/dia` | **Clindamicina + Ciprofloxacina** *(Etiologia: Strep A/C/G, S. aureus, E. coli, Klebsiella, Proteus, Enterobacter, Bacteroides, Peptostreptococcus, C. perfringens)* |

### IRAS, Prevenção de PAV e Hipertermia em UTI
- **O bundle de PAV previne a principal IRAS ventilatória, e toda hipertermia não infecciosa grave exige exclusão imediata de síndromes malignas.**
  - **4 IRAS Mais Frequentes na UTI:** **PAV** (ventilação mecânica), **IPCS** (cateter central), **ITU** (sonda vesical) e **ISC** (sítio cirúrgico).
  - **Bundle de Prevenção de PAV (6 Medidas):** 1) Cabeceira elevada **`30°–45°`**; 2) Higiene oral rotineira (reduz biofilme); 3) **Aspiração subglótica** contínua/intermitente; 4) Pressão do *cuff* entre **`20 e 30 cmH2O`**; 5) Despertar diário + Teste de Respiração Espontânea (extubação precoce); 6) Higiene rigorosa das mãos.
  - **Diagnóstico Diferencial da Hipertermia em UTI:**
    - *Infecciosas (mais comuns):* Sepse, PAV, IPCS, ITU, pancreatite.
    - *Síndromes Malignas (Emergências):* **Hipertermia Maligna** (halogenados/succinilcolina -> rigidez muscular + hipercapnia); **Síndrome Neuroléptica Maligna** (antipsicóticos -> rigidez em *"cano de ferro"*); **Síndrome Serotoninérgica** (antidepressivos -> tremores + **hiperreflexia**).
    - *Outras Não Infecciosas:* **Farmacológicas** (reação transfusional, febre por drogas: ATBs/anticonvulsivantes); **Neurogênicas** (HSA, AVCH, TCE, tumores); **Endócrinas** (tempestade tireoidiana, feocromocitoma).

---

## 7. Nefrologia, TRS e Distúrbios Hidroeletrolíticos

### Hiponatremia Sintomática e ECG nos Distúrbios Eletrolíticos
- **Na hiponatremia grave sintomática, a NaCl 3% visa cessar sintomas (convulsão/coma) respeitando o teto máximo de 8 a 10 mEq/L em 24h.**
  - **Protocolo Seguro de NaCl 3%:**
    - *Indicação:* Hiponatremia aguda (`< 48h`), grave (`< 120 mEq/L`) e sintomática (convulsão, coma, PCR).
    - *Diluição Prática (`1:9` de NaCl 20% + SF 0,9%):* **`10 mL NaCl 20% + 90 mL SF 0,9%`** (bolus) **OU** **`50 mL NaCl 20% + 450 mL SF 0,9%`** (bomba).
    - *Posologia:* **Aguda** (maratona, *ecstasy*, drogas) -> `100 mL` (`1 amp + 90 mL`) EV até `3x`; **Crônica agudizada** -> infusão contínua `1–2 mL/kg/h` (dosar $Na^+$ de `4/4h`). *Meta:* Controle de sintomas (não normalizar $Na^+$), limite máximo **`8–10 mEq/L em 24h`**.
  - **Padrões Eletrocardiográficos nos Distúrbios Hidroeletrolíticos:**

| Eletrólito | Hiper (Elevação Sérica) | Hipo (Redução Sérica) |
| :--- | :--- | :--- |
| **Potássio ($K^+$)** | Onda **T apiculada em "tenda"** (alta, simétrica, base estreita) -> perda de onda P -> alargamento QRS -> padrão sinusoidal -> assistolia | Achatamento/inversão de T + infra de ST + **onda U proeminente** -> arritmias ventriculares |
| **Cálcio ($Ca^{2+}$)** | **Encurtamento do QT** (diminuição/desaparecimento do segmento ST) | **Prolongamento do QT** (alongamento do segmento ST) -> arritmias graves |
| **Magnésio ($Mg^{2+}$)** | Prolongamento de PR + alargamento de QRS + prolongamento de QT | Semelhante à hipoK: QRS alargado, T apiculada e **QT longo** -> alto risco de ***Torsades de Pointes*** |

### Terapia de Substituição Renal (TRS e Mecanismos da CVVHDF)
- **Pacientes hemodinamicamente instáveis requerem CRRT (24h), onde a CVVHDF alia difusão para solutos pequenos e convecção para moléculas médias.**
  - *Modalidades:* **HD convencional** (intermitente), **Diálise Peritoneal** (CAPD manual diurna ou DPA cicladora noturna), **Transplante Renal** (melhor terapia definitiva) e **CRRT** (métodos contínuos 24h na instabilidade hemodinâmica).
  - **Física da CVVHDF (Hemodiafiltração Venovenosa Contínua):**
    - *Difusão (gradiente de concentração — como na HD):* Depura **solutos pequenos** -> Ureia (`60 Da`), Creatinina (`113 Da`).
    - *Convecção (arraste por água / ultrafiltrado — como na hemofiltração):* Depura **moléculas médias** -> $\beta_2$-microglobulina (`11,8 kDa`), Mioglobina (`17 kDa`).

---

## 8. Hepatologia, Nutrição Crítica e Grande Queimado

### Encefalopatia Hepática (EH) no Paciente Crítico
- **Graus III e IV exigem intubação precoce mandatória, rastreio agressivo de fatores precipitantes e dieta normoproteica sem restrição.**
  - **5 Pilares do Tratamento Intensivo da EH:**
    1. *Via Aérea e Neuroproteção:* **IOT precoce obrigatória em EH grau III ou IV** (torpor profundo/coma); controle rigoroso de **PIC** na Insuficiência Hepática Aguda (IHA).
    2. *Redução/Eliminação de Amônia:* **Lactulose/lactitol** VO/SNE (alvo `2–3 evacuações/dia`); **Polietilenoglicol (PEG)** em quadros graves na UTI (superior à lactulose p/ limpeza rápida do cólon e redução do tempo de coma); **Rifaximina** (1ª escolha; alternativa: `Metronidazol`); **LOLA EV** (L-ornitina-L-aspartato -> estimula detoxificação).
    3. *Controle de Precipitantes:* Rastrear/tratar **infecções** (culturas + ATB empírico precoce p/ PBE), controlar **HDA** (carga proteica luminal) e corrigir **hipocalemia, hiponatremia e alcalose metabólica** (alcalose facilita entrada cerebral de $NH_3$).
    4. *Suporte Nutricional:* **Proibido restringir proteína** de forma severa/prolongada (evita catabolismo muscular) -> ofertar **`30–35 kcal/kg/dia`** e **`~1,2 g/kg/dia` de proteína** (priorizar aminoácidos de cadeia ramificada — **AACR**).
    5. *Substituição/Resgate:* **Transplante Hepático** (cura definitiva na IHA/cirrose refratária); diálise com albumina (**`MARS`**) como ponte em centros de excelência.

### Oligoelementos e Nutrição no Grande Queimado
- **A nutrição parenteral exige adição diária de oligoelementos, e o grande queimado demanda dieta enteral em até 12h com alta carga proteica.**
  - **Manejo de Oligoelementos na UTI:** Adição diária **mandatória na Nutrição Parenteral (NP)** (bolsas padrão não contêm); necessidades aumentadas em sepse, queimados, fístulas e **CRRT** (reposição extra); **risco de toxicidade/acúmulo** na disfunção renal ou colestase/biliar (especialmente **Cobre e Manganês**).
  - **Protocolo Nutricional do Grande Queimado:**
    - *Via e Tempo:* **Nutrição Enteral precoce em até `12 horas`** (protege mucosa e reduz infecções); NP restrita a falência intestinal/ílio grave.
    - *Metas Macronutrientes:* Gasto energético elevado (estimar por calorimetria indireta ou **fórmula de Toronto**); oferta hiperproteica (**`1,5–2,5 g/kg/dia`**); controle estrito de carboidratos (evitar hiperglicemia e esteatose hepática).
    - *Imunonutrientes e Micronutrientes:* **Glutamina** (trofismo intestinal / reduz translocação) + reposição redobrada de **Zinco, Vitamina C, Vitamina A e Cobre** (cicatrização).

---

## 9. Hematologia e Toxicologia Intensiva

### Anemia Hemolítica Microangiopática (AHMA) e Antídotos
- **Esquizócitos no sangue periférico com Coombs Direto negativo e plaquetopenia definem microangiopatia trombótica até prova em contrário.**
  - **Perfil Laboratorial da AHMA / MAT:** **Esquizócitos** (hemácias em "capacete"/triangulares -> achado definitivo) + hemólise intravascular (**DHL elevado**, **haptoglobina muito baixa/indetectável**, **BI aumentada**, queda Hb/Ht) + **reticulocitose** + **Teste de Coombs Direto (TAD) NEGATIVO** + **plaquetopenia (`< 150.000`)**.
  - **9 Principais Etiologias:** **PTT** (deficiência congênita/autoimune da **`ADAMTS-13`**); **SHU** (toxina *Shiga*/*E. coli* ou SHU atípica/complemento); **Obstétricas** (pré-eclâmpsia grave, HELLP, eclâmpsia); **Neoplasias** (adenocarcinomas, metástase medular); **HAS maligna**; **Sepse**; **Drogas** (quimioterápicos, `ciclosporina`, `tacrolimus`, antiplaquetários); **Autoimunes** (LES, esclerodermia); **Mecânicas** (próteses valvares, malformações vasculares).
  - **Guia Rápido de Antídotos em Intoxicações Agudas na UTI:**

| Toxina / Fármaco | Antídoto Específico | Toxina / Fármaco | Antídoto Específico |
| :--- | :--- | :--- | :--- |
| **Paracetamol** | **N-acetilcisteína** | **Cianeto** | **Hidroxocobalamina** ou **Tiossulfato de Sódio** |
| **Opiáceos** | **Naloxona** | **Varfarina** | **Vitamina K** (+ CCP se sangramento grave) |
| **Benzodiazepínicos** | **Flumazenil** *(cuidado: convulsão)* | **Digoxina** | **Anticorpo Fab anti-digoxina** |
| **Organofosforados** | **Atropina + Pralidoxima** | **Monóxido de Carbono** | **$O_2$ a 100% / Câmara Hiperbárica** |
| **Metanol / Etilenoglicol** | **Fomepizol** ou **Etanol + Ácido Folínico** | **Betabloqueadores** | **Glucagon** |
| **Ferro** | **Deferoxamina** | **Bloqueadores Canal $Ca^{2+}$** | **Cálcio + Insulina Euglicêmica (altas doses)** |

---

## 10. Gestão, Qualidade e Segurança do Paciente em UTI (AMIB / OMS)
- **A triagem de vagas baseia-se em 5 níveis de prioridade prognóstica, integrando protocolos rígidos de segurança e liderança multiprofissional.**
  - **Critérios de Prioridade de Admissão em UTI (Níveis 1 a 5):**
    - *Prioridade 1:* Necessita suporte de vida + grande chance de recuperação, **sem limitações terapêuticas**.
    - *Prioridade 2:* Necessita monitorização intensiva (alto risco de instabilidade), **sem restrições de tratamento**.
    - *Prioridade 3:* Necessita suporte avançado, mas com **prognóstico reservado ou limitações terapêuticas**.
    - *Prioridade 4:* Prognóstico desfavorável / doença terminal avançada (benefício limitado na UTI).
    - *Prioridade 5:* Estado terminal irreversível ou Morte Encefálica -> **não admitidos, exceto potenciais doadores de órgãos**.
  - **6 Metas Internacionais de Segurança do Paciente (OMS):**
    1. *Identificação correta:* Mínimo `2 identificadores` em pulseira (ex: nome completo + data de nascimento).
    2. *Comunicação efetiva:* Padronizar passagem de plantão e ordens verbais/telefônicas críticas.
    3. *Segurança em medicamentos:* Protocolos de medicamentos de alta vigilância (prescrição, dispensação, administração).
    4. *Cirurgia segura:* *Checklist* (paciente, sítio e procedimento corretos) antes, durante e após o ato.
    5. *Higiene das mãos:* Adesão monitorada aos `5 momentos` (prevenção de IRAS).
    6. *Prevenção de quedas e LPP:* Avaliação individual de risco + barreiras físicas/monitoramento.
  - **Segurança na Mobilização / Pronação (Prevenção de Perda de Dispositivos):**
    - *Equipe e Via Aérea:* Dimensionamento adequado com **1 profissional exclusivo para proteger TOT/TQT** e coordenar o giro -> checar fixações/cadarços/suturas antes -> liberar linhas/circuitos/drenos deixando **"folga" sobre o leito** -> pausar dieta enteral e fechar drenos temporariamente.
  - **Funções do Coordenador de UTI (AMIB):** 1) *Gestão de equipes* (escalas, liderança multiprofissional, treinamentos); 2) *Qualidade e protocolos* (rotinas assistenciais, indicadores, normas ANVISA/Conselhos); 3) *Apoio clínico-administrativo* (discussão de casos complexos, auditoria de prontuários, alinhamento com diretoria).