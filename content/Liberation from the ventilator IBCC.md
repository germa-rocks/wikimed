---
publish: true
---


Aqui está a estruturação de alto rendimento do capítulo "Liberação do Ventilador", baseada no princípio de divulgação progressiva. O material está formatado em markdown, pronto para ser copiado e colado no Notion, Obsidian ou Roam Research, com a criação automática de *toggles* (listas colapsáveis).

***

# 🌬️ Desmame e Liberação da Ventilação Mecânica (Extubação)

## 1. Checklist Pré-Extubação (Otimização do Paciente)
- **Sedação Otimizada: O paciente deve seguir comandos, mas tolerar o tubo (leve desconforto se a sedação for suspensa).**
	- Transição para Dexmedetomidina: É um excelente agente, pois não suprime o drive respiratório. Considere *cross-tapering* de propofol para dexmedetomidina.
	- Em casos de dor/agitação, considere infusão conjunta de Dexmedetomidina + Cetamina em dose analgésica.
	- 🚩 **Red Flag:** Excesso de conforto. Se o paciente está perfeitamente confortável com o tubo, ele corre risco de sonolência excessiva pós-extubação por falta de estímulo.
	- Suspenda sedativos de longa ação (ex: Fentanil contínuo) várias horas antes da extubação.
- **Status Volêmico: A extubação aumenta a pré-carga e a pressão arterial; garanta balanço hídrico adequado.**
	- Revise tendências de entradas/saídas (I/O) e examine sinais de congestão.
	- Considere diurese profilática/terapêutica antes da extubação se houver sinais de hipervolemia.
- **Equilíbrio Ácido-Base: Corrija qualquer acidose metabólica para reduzir o trabalho respiratório (WOB).**
	- Acidose exige alcalose respiratória compensatória, aumentando o WOB. Trate a causa (ex: Bicarbonato IV para Acidose Metabólica com Anion Gap Normal - NAGMA).
	- Pacientes com hipercapnia crônica (ex: DPOC) devem ter seu bicarbonato restaurado ao seu *nível basal crônico* (alcalose metabólica compensatória) antes do desmame.
- **Radiologia e Via Enteral: Trate derrames/atelectasias e gerencie a nutrição.**
	- **Derrame Pleural:** Drene muito antes da extubação, pois o pulmão leva horas para reexpandir e recuperar a função plena.
	- **Atelectasia:** Realize manobras de recrutamento.
	- **Nutrição/Insulina:** O jejum será iniciado. Reduza ou pause a insulina basal/contínua e faça HGT frequente para evitar hipoglicemia.
	- **Tubo Gástrico:** Antes de extubar, conecte sondas de duplo lúmen (ex: Salem sump) à sucção. Sondas enterais pós-pilóricas de pequeno calibre podem ser mantidas in loco.

## 2. O Teste de Respiração Espontânea (TRE / SBT)
- **Critérios de Prontidão: Realize o TRE diariamente se: PEEP ≤10, FiO2 ≤50%, Hemodinâmica estável e Neurologicamente responsivo.**
	- **Exceção de PEEP:** Obesidade mórbida pode exigir PEEP inicial >10 cmH2O (ver seção de Obesidade). 
	- **Neurológico:** Despertável e idealmente seguindo comandos (embora não seja um requisito absoluto em neurocríticos).
	- **Hemodinâmica:** Frequência Cardíaca <140 bpm, sem isquemia miocárdica ativa, sem vasopressores em altas doses (ex: Noradrenalina < 15 mcg/min).
	- **Ventilatório:** PaCO2 ou etCO2 normais (ou no basal do paciente).
- **Configuração do TRE: Utilize Pressão de Suporte (PS) 5 cmH2O + PEEP 5 cmH2O por 30 minutos.**
	- Objetivo da PS de 5: Cancelar a resistência imposta pelo próprio tubo endotraqueal (TET).
	- **Alternativa (ATC):** CPAP (~5 cmH2O) + *Automatic Tube Compensation* (ATC). Especialmente útil para TET com diâmetros atípicos (ex: #6.0 ou #9.0).
	- **Duração:** Se tolerar por 30 minutos, provavelmente está apto à extubação.
- **Critérios de Sucesso (Aprovação no TRE): Oximetria >88% (com FiO2 ≤50%), ausência de fadiga grave e ventilação adequada.**
	- **Oxigenação:** Necessidade moderada-alta de FiO2 pode não contraindicar extubação se for transicionar direto para Cateter Nasal de Alto Fluxo (CNAF), especialmente em hipoxêmicos crônicos.
	- **Ventilação Oculta:** Cuidado com hipoventilação oculta (comum em DPOC). Sinais: Queda do volume minuto ou aumento do etCO2 > 10 mmHg durante o TRE. Gasometria de rotina é desnecessária se não houver esses sinais. 
		- 📎 *Refs: 8796386*
	- **Fadiga / RSBI (Índice de Respiração Rápida e Superficial - Índice de Tobin):** 
		- Sinais clínicos de falha: Agitação, sudorese, uso de musculatura acessória.
		- 🚩 **RSBI > 105:** É um *red flag* (especificidade ~44% para falha), mas **não é contraindicação absoluta**. Pacientes com doença pulmonar intersticial (DPI) podem ter taquipneia crônica e tolerar a extubação.
		- Volume corrente ALTO com taquipneia sugere *ansiedade*, não falha ventilatória.
		- 📎 *Refs: 35815895*
- **Manejo da Apneia durante o TRE: Apneia de alarme não significa falha automática; investigue e corrija o drive.**
	- Aparelhos modernos são sensíveis e retornam para suporte total rápido.
	- **Causas comuns:**
		- O paciente estava sendo hiperventilado antes do teste (aguarde acúmulo de CO2 para reativar o drive).
		- Padrão de Cheyne-Stokes (não é contraindicação para extubar se for crônico).
		- Excesso de sedação.
	- **Conduta:** Se sedado, suspenda sedação e repita em horas. Se acordado, retorne ao modo padrão, reduza a FR do ventilador (para "provocar" respirações espontâneas) e repita o TRE avaliando o etCO2.

## 3. Manejo da Falha no TRE
- **Após a falha, retorne o paciente para Nível Total de Suporte Ventilatório.**
	- Se a causa for facilmente reversível (ex: sedação residual), pode-se repetir no mesmo dia. Caso contrário, descanse o paciente e repita na manhã seguinte.
- **Diagnóstico Diferencial e Conduta na Falha:**
	- **Hipervolemia / EAP:** Falha na elevação passiva das pernas em aumentar o DC. → *Conduta:* Diurese (ou diálise), redução da pós-carga se hipertenso, mantenha VNI pós-extubação. 📎 *Refs: 30627804*
	- **Angina / Isquemia:** Dor no peito, alt. ECG. → *Conduta:* Betabloqueador, alvo de Hb >8 g/dL, avaliar revascularização.
	- **Ansiedade:** Taquipneia, Vc alto, etCO2 baixo (hiperventilação). → *Conduta:* Repetir TRE sob Dexmedetomidina ou tentar extubar diretamente (julgamento clínico).
	- **Broncoespasmo:** Sibilos, curva capnográfica/ventilatória alterada. → *Conduta:* Corticoide, broncodilatador, atb se DPOC exacerbado.
	- **Atelectasia / Rolha de muco:** → *Conduta:* Aumentar pressão média de vias aéreas (PEEP ou APRV), fisio respiratória, broncoscopia (raro).
	- **Tubo pequeno para o paciente:** → *Conduta:* Trocar tubo (arriscado), usar modo ATC, ou tentar extubar.
	- **Assincronia / Suporte inadequado:** → *Conduta:* Ajustar *driving pressure* ou mudar de modos adaptativos (ex: AutoFlow/PRVC).
- **Investigação Básica após falha:** Eletrólitos (Ca, Mg, Fósforo), POCUS (congestão/pleura), balanço hídrico, Gasometria (comparar bicarb basal). 📎 *Refs: 32166566*

## 4. O Paciente Passou no TRE: Avaliação Pós-Teste (Airway & Leak)
- **O sucesso no TRE avalia apenas a força diafragmática. Deve-se avaliar: (1) Risco de Edema de Laringe e (2) Proteção de Via Aérea.**
- **Prevenção de Edema de Laringe (Teste de Fuga do Cuff / *Cuff Leak*):**
	- **Indicação (Fatores de Risco):** Intubação traumática, >6 dias de TOT, TOT calibroso, mulher, reintubação prévia. Se não houver fatores de risco, proceda para extubação.
	- **Conduta baseada no Teste de Fuga:**
		- **Com fuga (*Leak*):** Extubar.
		- **Sem fuga (*No Leak*):** Administrar Metilprednisolona 60 mg IV (Dose Única) IMEDIATAMENTE. **Extubar após >4 horas (independentemente se houver fuga ou não após o corticoide)**. 
		- *Nota:* Isso é um meio-termo entre extubar às cegas (estilo *cowboy*) e esperar 48h de corticoide. 📎 *Refs: 27762595*
	- **Se Estridor Pós-Extubação:** Prepare intubação (mas evite se possível). Dê Metilprednisolona 60-125 mg IV, Adrenalina inalatória e considere Heliox.
- **Habilidade de Proteger a Via Aérea: Baseado em 4 critérios clínicos fundamentais.**
	- 1. Status mental (acordado/obedecendo?)
	- 2. Quantidade de secreção (exige aspiração em intervalos < 2h?)
	- 3. Tosse forte? (avaliação subjetiva durante aspiração)
	- 4. História de hipercapnia?
	- **Regra Prática:** Se 1-2 fatores desfavoráveis = geralmente seguro. Se 3-4 fatores desfavoráveis = alto risco de reintubação. Se a causa base não vai melhorar com o tempo (ex: sequela neurológica crônica), pode valer a pena arriscar a extubação ("Trial of Extubation").

## 5. Conceitos Práticos de Desmame
- **Extubação é sempre um "Trial" (Tentativa empírica). A taxa de reintubação aceitável é de ~15%.**
	- Se a sua taxa de reintubação for <<15%, você está extubando os pacientes *muito tarde* (aumentando risco de PAV, delirium, fraqueza).
	- Se >>15%, você está extubando *prematuramente*.
	- Pacientes sistematicamente limitrofes (*borderline*) no TRE merecem uma tentativa empírica de extubação (Trial of extubation) após otimização máxima, antes de serem submetidos a uma traqueostomia.
- **Suporte Pós-Extubação: CNAF e VNI.**
	- **CNAF (Cateter Nasal de Alto Fluxo):** Reduz o WOB. Deve ser considerado para QUASE TODOS os extubados, mesmo os de baixo risco (Evidência RCT multicêntrico). Exige fluxo alto (50-60 L/min) por 24-48h. 📎 *Refs: 26975498*
	- **VNI (BiPAP):** Eficácia equivalente ao CNAF, porém com pior adesão (máscara). Ideal para ICC, DPOC e Obesos Mórbidos (IMC >35).
	- **O "Combo" Perfeito para Hipercapnia:** VNI noturna (24h iniciais) + CNAF intercalado durante o dia. 📎 *Refs: 31577036*
- **Extubação Não Planejada (Auto-extubação): Cerca de 50% dos pacientes que se auto-extubam NÃO precisam ser reintubados.**
	- Paciente teve força/consciência para arrancar as contenções. 
	- Conduta: Pare a sedação, coloque em VNI, observe de perto. Reintube apenas se clinicamente indicado.
- **Traqueostomia (Timing): Idealmente entre 1 a 2 semanas, individualizado.**
	- Precoce: Doenças crônicas ou de recuperação arrastada (Síndrome de Hipoventilação da Obesidade, AVE grave).
	- Tardia: Processos com potencial melhora subaguda (Pneumonia severa em resolução).

## 6. O "Pântano" da Obesidade Mórbida
- **Pacientes com obesidade troncular severa possuem fisiologia INCOMPATÍVEL com o desmame tradicional (Decúbito supino + PEEP 5-8).**
	- Podem necessitar de PEEPs de até **25 cmH2O** deitados para evitar colapso basal imposto pelo abdome.
	- **Como desmamar:** Eles DEVEM ser desmamados e extubados a partir de **PEEPs elevadas** (pois nunca tolerarão o protocolo clássico de PEEP 5).
	- **Conduta Pós-Extubação:** Imediatamente para CPAP/BiPAP (para repor a PEEP alta do ventilador) e enfermagem rigorosa em **posição sentada** ou Trendelenburg Reverso (para retirar o peso abdominal do diafragma). 
	- Se gravemente desrecrutados, podem responder bem à APRV (Airway Pressure Release Ventilation). 📎 *Refs: 33797429, 31025221, 32166639*

## 7. O que NÃO Fazer no Desmame Ventilatório (Práticas Obsoletas)
- **Não realize desmame reduzindo "gradualmente" os parâmetros do ventilador em pacientes comuns.**
	- Retirar o suporte lentamente gera trabalho resistivo contínuo, causando fadiga diafragmática que pode durar dias.
	- **O correto:** Suporte TOTAL, interrompido por TREs (tudo ou nada). Se falhou no TRE, volte para suporte TOTAL. (Desmame gradual só tem papel em traqueostomizados de longo prazo).
- **Não utilize o Teste do Tubo T (*T-Piece*).**
	- Retira *todo* o suporte, fazendo o paciente respirar por um "canudo" longo, com esforço extenuante (além de perder a monitorização de volume e etCO2).
	- Se você precisa retornar o paciente para o ventilador "para descansar" após passar no Tubo T, isso é a prova clínica de que o Tubo T é um teste excessivamente difícil e antifisiológico. 📎 *Refs: 28936675, 31184740*

## 8. Monitorização Avançada: P0.1 (Pressão de Oclusão de Via Aérea)
- **A P0.1 é a pressão de oclusão 100 milissegundos após o início da inspiração. É um marcador objetivo do "Drive" e Esforço Respiratório.**
	- Disponível em ventiladores modernos (fazer média de 3 medições).
	- **Interpretação:**
		- **P0.1 < 1 cmH2O:** Drive respiratório excessivamente baixo (oversedação ou fraqueza muscular/falso-baixo).
		- **P0.1 > 4 cmH2O:** Esforço respiratório muito elevado. Alto risco de dispneia, fadiga diafragmática e falha no desmame. 📎 *Refs: 38436722, 38484187*
		- Zona de corte para predição de sucesso: ~3.5 a 4.5 cmH2O (Sensibilidade 86%, Especificidade 58%). 📎 *Refs: 33012587*