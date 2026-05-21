---
publish: true
---
Aqui está a base de conhecimento estruturada para o seu Notion/Obsidian, aplicando o princípio da divulgação progressiva. O foco está na consulta rápida à beira-leito e na rápida tomada de decisão, com a fisiopatologia e fórmulas ocultas nos níveis inferiores.

# Monitorização Respiratória: Trocas Gasosas

## 1. Princípios Fisiológicos Básicos e Trocas Gasosas
- **A principal função pulmonar (hematose) depende de três pilares: Ventilação, Perfusão e Membrana Alveolocapilar íntegra.**
	- Se qualquer um destes falhar, ocorre distúrbio na troca de oxigênio (O2) ou gás carbônico (CO2).
	- **A hematose é movida pela diferença de pressão parcial dos gases.** O O2 difunde-se para o capilar; o CO2 difunde-se para o alvéolo.
		- 🧮 **Cálculo da Pressão Inspirada de O2 (PiO2):** Depende da pressão barométrica (Pb) e do vapor de água.
			- Fórmula: `PiO2 = (Pb - PH2O) x FiO2`
			- Exemplo no nível do mar: `(760 - 47) x 0.21 = ~149 mmHg`.
- **O CO2 é 20x mais difusível que o O2.**
	- **Pérola Clínica:** Distúrbios da membrana (ex: espessamento no Edema Agudo ou Fibrose) afetam muito o O2 (hipoxemia), mas raramente retêm CO2 por defeito de difusão. O CO2 é depurado quase normalmente, a menos que haja falha na ventilação.
- **A saturação da Hemoglobina (Hb) limita o transporte de O2; oxigênio livre no plasma é insignificante.**
	- **Pérola Clínica:** Se a Hb já está 100% saturada, aumentar a FiO2 para subir a PaO2 (ex: de 100 para 300 mmHg) quase não aumenta a oferta tecidual de O2 (DO2).
		- 🧮 **Fórmula do Conteúdo Arterial de O2 (CaO2):** `CaO2 = (1.34 x Hb x SaO2) + (PaO2 x 0.003)`
		- Note que o multiplicador da PaO2 livre é apenas `0.003`.
- **O aumento do Espaço Morto (VD) é a principal causa de desperdício ventilatório.**
	- **Sinal de Alarme Clínico:** O paciente compensa o espaço morto aumentando o *volume minuto* (Taquipneia / Esforço respiratório). A retenção de CO2 (hipercapnia) só ocorre quando o paciente exaure e não consegue mais manter o volume minuto.
		- *Fisiologia:* Espaço Morto = Ventilação SEM Perfusão (V/Q tende ao infinito).
		- *Fisiológico* = Anatômico (vias aéreas condutoras) + Alveolar (alvéolos hiperdistendidos ou hipoperfundidos). Corresponde a 25-30% do volume corrente habitual.

---

## 2. Abordagem Diagnóstica: Hipoxemia e Hipercapnia
- **Existem 5 mecanismos fisiopatológicos clássicos de Hipoxemia. O "Shunt" é o único que NÃO responde à suplementação de O2.**
	- **1. Shunt Verdadeiro (V/Q = 0):** Perfusão de áreas não ventiladas (ex: atelectasia maciça, preenchimento alveolar por pus/sangue). O sangue passa desoxigenado. O aumento da FiO2 não corrige a hipoxemia.
	- **2. Distúrbio V/Q (Desequilíbrio Ventilação/Perfusão):** Áreas mal ventiladas, mas não totalmente ocluídas. **Responde à FiO2**. É a causa mais comum na UTI.
	- **3. Hipoventilação:** Baixa renovação de ar no alvéolo. Causa hipoxemia acompanhada obrigatoriamente de hipercapnia.
	- **4. Alteração de Difusão:** Espessamento da membrana alveolocapilar (ex: DPOC, Fibrose).
	- **5. Redução da PiO2:** Baixa FiO2 ou grandes altitudes (incomum na UTI).
- **A Hipercapnia é quase exclusivamente um problema de Hipoventilação Alveolar.**
	- Se a PaCO2 está subindo, o ar não está sendo trocado adequadamente (falência de bomba respiratória, rebaixamento de nível de consciência).
	- *Exceções (Causas raras/secundárias):* Aumento extremo do VD (espaço morto massivo onde a ventilação vira desperdício) ou aumento súbito na produção de CO2 (VCO2) como hipertermia ou *overfeeding*.

---

## 3. Monitorização Não-Invasiva: Oximetria de Pulso (SpO2)
- **A Oximetria reflete o PASSADO recente (Delay de 30-40 segundos). Não tome decisões precipitadas no momento imediato de uma intervenção.**
	- **Pérola da Intubação:** Após intubar e ventilar, a expansão torácica e a ausculta são imediatas. A SpO2 demorará até 40s para subir. **Não extube em desespero achando que o tubo está no esôfago apenas porque a saturação não subiu no segundo 1.** O inverso também é válido (a saturação demora a cair na apneia).
- **A SpO2 é "cega" para Hiperóxia devido ao formato da Curva de Dissociação da Hemoglobina.**
	- Uma saturação de 100% pode corresponder a uma PaO2 de 95 mmHg ou de 300 mmHg. O oxímetro não distingue.
	- A fase inicial da curva é plana (93-100%); a fase descendente é abrupta (pequenas quedas de PaO2 causam quedas bruscas de SpO2).
- **Atenção às Falsas Leituras e Interferências (Red Flags do Oxímetro).**
	- **Hemoglobinas Anômalas:** Monóxido de Carbono (COHb) e Meta-hemoglobina (MetHb) mimetizam a oxi-hemoglobina. O paciente pode estar em hipóxia tecidual grave com SpO2 falsamente a 100%. Necessita de co-oximetria na gasometria.
	- **Falha de Captação:** Extremidades frias, hipoperfusão (choque com pulso filiforme), esmalte escuro e edema reduzem a qualidade do sinal luminoso (vermelho e infravermelho).

---

## 4. Monitorização Invasiva: Gasometria Arterial
- **A Gasometria Arterial NÃO é um exame obrigatório de rotina para todos os pacientes de UTI.**
	- É dolorosa, invasiva e tem risco de sangramento/fístula.
	- **Indicações precisas:** Falta de confiabilidade no oxímetro, suspeita de retenção de CO2 (acidose respiratória não vista no oxímetro) ou para avaliação de distúrbios ácido-base sistêmicos.
- **Valores de Referência Básicos (Beira-leito).**
	- **pH:** 7.35 – 7.45
	- **PaO2:** 60 - 90 mmHg
	- **SaO2:** > 88 - 97%
	- **PaCO2:** 35 - 45 mmHg
	- **HCO3:** 22 - 26 mEq/L
- **Atenção Técnica à Coleta:**
	- Seringa heparinizada (usar a padronizada; se manual, expulsar excesso de heparina para não diluir a amostra).
	- Processamento imediato. Se houver atraso justificado, transportar e armazenar em gelo (ou mala térmica < -8ºC) para evitar consumo contínuo de O2 pelos eritrócitos na seringa.

---

## 5. Índices Analíticos de Oxigenação
- **O Gradiente Alvéolo-Arterial (GA-aO2) ajuda a descobrir a CAUSA da hipoxemia (Normal < 15 mmHg).**
	- Se **AUMENTADO:** O problema está no pulmão profundo (Shunt, Distúrbio V/Q ou Defeito de Difusão).
	- Se **NORMAL:** O pulmão troca bem, mas falta ar chegando (Hipoventilação pura ou Baixa PiO2 em altitude).
		- 🧮 **Algoritmo de Cálculo à beira-leito:**
			1. Calcular a Pressão Alveolar (PAO2) = `PiO2 - (PaCO2 / 0.8)`
				- *Nota:* PiO2 no nível do mar (FiO2 21%) = ~149.
			2. Subtrair a PaO2 da gasometria: `GA-aO2 = PAO2 - PaO2`.
- **Relação P/F (PaO2 / FiO2): Define e gradua a SDRA (Critérios de Berlim).**
	- Normal > 400.
	- SDRA: < 300 (Leve), < 200 (Moderada), < 100 (Grave).
	- *Limitação:* É altamente dependente dos níveis de PEEP e da própria FiO2. Não discrimina o mecanismo etiológico exato.
- **Relação S/F (SpO2 / FiO2): Excelente alternativa não invasiva à P/F, desde que a SpO2 seja < 97%.**
	- **Pérola:** Se SpO2 ≥ 97%, a relação S/F perde a acurácia matemática devido ao platô da hemoglobina. Não utilize.
	- **Equivalências Mentais Rápidas:**
		- P/F de 300 ➔ S/F de ~315
		- P/F de 200 ➔ S/F de ~235

---

## 6. Capnografia (Monitorização Contínua do CO2)
- **O ETCO2 (End-Tidal CO2) é classicamente ~5 mmHg MENOR que a PaCO2 arterial. Esse "Gap" representa o Espaço Morto Alveolar.**
	- **Pérola Clínica:** Doenças que aumentam o espaço morto (DPOC grave, TEP, SARA, baixo débito cardíaco) alargam o Gap (ETCO2 cai, enquanto o PaCO2 no sangue sobe).
	- 🧮 **Fração de Espaço Morto (Equação de Bohr adaptada):** `VD/VT = (PaCO2 - ETCO2) / PaCO2`.
		- Normal: VD/VT entre 0.25 e 0.30.
- **Análise Prática das Fases da Curva de Capnografia:**
	- **Fase Inspiratória (Zero):** Gás livre de CO2 entrando.
	- **Fase Expiratória 1:** Saída do ar do espaço morto anatômico (ainda sem CO2).
	- **Fase Expiratória 2 (Ascensão rápida):** Mistura de ar do espaço morto com ar alveolar.
	- **Fase Expiratória 3 (Platô Alveolar):** Ar puramente alveolar, rico em CO2. O ponto final desse platô (D) é o valor numérico que aparece no monitor (ETCO2).
- **Usos Clínicos da Capnografia:**
	- Confirmação imediata de intubação orotraqueal correta.
	- Ajuste dinâmico de volume minuto na ventilação mecânica sem furar o paciente toda hora.
	- Avaliação de eficácia da RCP (PCR) e Retorno da Circulação Espontânea (ROSC).

---

## 7. A Regra de Ouro: Integração Clínica
- **A Clínica é Soberana: Insuficiência Respiratória Aguda (IRpA) é um diagnóstico CLÍNICO, não gasométrico.**
	- Não espere a gasometria mostrar hipoxemia severa ou hipercapnia para diagnosticar desconforto respiratório ou fadiga.
	- O paciente taquipneico e com uso de musculatura acessória está usando seu esforço mecânico máximo para manter as trocas limítrofes na gasometria. Intervenha antes da falência de bomba (antes dos gases "piorarem" no papel).
- **Individualize os "Valores Normais" pelas Comorbidades.**
	- DPOC retentor crônico ou paciente obeso (Síndrome de Hipoventilação) já possuem gasometrias basais anormais (ex: PaCO2 de 55 mmHg com pH compensado em 7.36). Isso pode ser o alvo terapêutico aceitável para ele. Não tente normalizar valores à força sob risco de iatrogenia (como hiperinsuflação dinâmica ao forçar ventilação).