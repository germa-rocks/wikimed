---
publish: true
---

Aqui está a base de conhecimento estruturada e hierarquizada para o manejo do Impella, desenhada com o princípio de divulgação progressiva para Obsidian/Notion.

# Impella: Manejo e Troubleshooting a Beira-Leito

## 1. Monitorização e Avaliação Contínua (LV Impella)
### **A avaliação rotineira exige integração entre laboratório, parâmetros da consola, POCUS e cateter de Swan-Ganz.**
- **Laboratório: O foco primário é a detecção precoce de hemólise, sangramento e perfusão.**
	- **Hemograma:** Quedas de hemoglobina podem refletir hemólise ou hemorragia oculta/sítio de inserção.
	- **Coagulação:** Seguir protocolo institucional de heparina e monitorar plaquetas rigorosamente.
	- **Marcadores de Perfusão:** Avaliar lactato (< 2-3 mM), função renal e transaminases.
- **Configurações e Curvas da Consola do Impella (Waveforms):**
	- **Power Level (P-level): Nunca reduzir abaixo de P2.**
		- Reduzir abaixo de P2 permite fluxo sanguíneo retrógrado através da bomba.
	- **Curva Verde (Corrente do Motor): Deve ser pulsátil.**
		- Mede a resistência ao fluxo. Se estiver não-pulsátil, indica que a entrada (inlet) e a saída (outlet) estão do mesmo lado da válvula aórtica, ou que o VE não está contraindo.
	- **Curva Vermelha (Sinal de Posicionamento): Deve assemelhar-se à curva de pressão aórtica.**
		- Estima a pressão próxima à saída do Impella. *Red Flag:* Não serve como PAI (Pressão Arterial Invasiva) fidedigna para manejo de drogas vasoativas; use uma PAI separada.
	- **Curva Branca (Pressão do VE): Deve assemelhar-se à pressão do VE.**
		- Estima a pressão próxima à entrada do Impella.
- **Ecocardiografia Point-of-Care (POCUS): Confirmação de posição e complicações.**
	- **Posicionamento Ideal (Distância do anel aórtico à entrada do Impella):**
		- Impella CP ou 5.0: 3 cm (± 0,5 cm).
		- Impella 5.5: 4,5 cm (± 0,5 cm).
		- *Dica técnica:* O cateter tem uma angulação intrínseca de 30º e deve afastar-se do aparato mitral.
	- **Color Doppler:** O motor causa um artefato de mosaico amplo que deve estar restrito ao lado aórtico da válvula.
	- **Red Flag (Cavitação): Presença de microbolhas no VE.**
		- Sugere localização subótima causando cavitação, o que gera hemólise, dano valvar e arritmias ventriculares.
- **Hemodinâmica e Cateter de Coração Direito (Swan-Ganz):**
	- **Pressões de Enchimento (CVP e PCWP): Devem ser suficientes para evitar alarmes de sucção.**
		- **CVP Alvo:** < 15 mmHg. Se > 8-12 mmHg, suspeitar de descompensação do VD.
		- **PCWP (Wedge) Alvo:** ~10-15 mmHg (correlaciona com PAD da artéria pulmonar de ~15-20 mmHg). O VE precisa de pré-carga para a bomba funcionar sem "sugar" as paredes.
	- **Índices de Perfusão (CPO e PAPi): Guiam o nível de suporte e a função biventricular.**
		- **CPO (Cardiac Power Output): Alvo > 0,6 Watts.**
			- Fórmula: `[(MAP - CVP) x DC] / 451`
			- Valor < 0,6 Watts indica que o paciente está sub-suportado. (Normal: 0,8 - 1,1).
		- **PAPi (Pulmonary Artery Pulsatility Index): Alvo > 1.**
			- Fórmula: `(PAS Pulmonar - PAD Pulmonar) / CVP`
			- Valor < 1 indica falência significativa do VD (risco de hemólise aumentada se < 1,3).
		- **DC e SvO2:** Alvo de IC > 2 - 2.2 L/min/m² e SvO2 > 50-60%.
	- **Pressão Arterial e Pós-carga (PAM > 60 mmHg, mas sem excessos):**
		- O Impella é sensível à pós-carga. A hipertensão sistêmica diminui o fluxo da bomba. Limite o uso de vasopressores à dose mínima necessária para perfusão.

## 2. Alarmes de Sucção (Suction Alarms)
### **Ocorrem quando a pressão diastólica calculada do VE cai abaixo de -40 mmHg. Diferenciar entre Sucção Diastólica e Contínua é crítico para a conduta.**
- **Sucção Diastólica: A pressão do VE cai na diástole, mas recupera no final; indica baixo enchimento do VE (Pré-carga baixa).**
	- **Causas principais:** Hipovolemia (sangramento, terceiro espaço), Vasoplegia (venodilatação), Falência de VD, Tamponamento, ou Pressão intratorácica excessiva (PEEP alto, AutoPEEP, pneumotórax). O P-level pode estar desnecessariamente alto.
	- **Manejo Passo-a-Passo:**
		1. Reduzir o fluxo/P-level temporariamente até identificar a causa (pode ser necessário aumentar inotrópico/vasopressor para compensar).
		2. Otimizar pré-carga (Cristaloides, Hemoderivados se sangramento).
		3. Tratar vasoplegia (ex: Noradrenalina baixa dose para venoconstrição).
		4. Tratar falência de VD (vasodilatador pulmonar inalatório, inotrópicos).
		5. Ajustar ventilador (reduzir PEEP excessivo).
		6. Após correção, tentar aumentar novamente o P-level.
- **Sucção Contínua: Pressão do VE é negativa e *não* recupera (Curva branca sempre abaixo da vermelha). Indica obstrução anatômica.**
	- **Causas principais:** Mau posicionamento (obstrução da via de entrada) ou Trombose da bomba (sugerido por pressão de purga alta, picos de corrente no motor, ou anticoagulação prévia subótima).
	- **Manejo Passo-a-Passo:**
		1. Reduzir o fluxo do dispositivo (diminui hemólise).
		2. Solicitar ecocardiograma imediato para avaliar posição.
		3. Acionar Cardiologia Intervencionista/Cirurgia Cardíaca. O dispositivo frequentemente precisa ser reposicionado, trocado ou removido.
		- *Nota:* Na ECMO-VA + Impella (Ecpella), o VE pode estar tão vazio/falcido que mimetiza um alarme de sucção contínua.

## 3. Manejo da Pressão de Purga (Purge Pressure)
### **A pressão de purga reflete a patência do sistema; alterações abruptas predizem falência da bomba.**
- **Pressão de Purga ALTA:**
	- Primeira ação: Excluir dobras (kinks) no equipo ou cateter.
	- Se não resolver: Monitorar picos na corrente do motor (indica falência iminente da bomba ou trombo).
- **Pressão de Purga BAIXA:**
	- Primeira ação: Excluir vazamentos (leaks) no sistema de tubulação.
	- Se não resolver: Monitorar a corrente do motor (risco de falência iminente).

## 4. Complicações Hematológicas e Vasculares
### **A hemólise (>40 mg/dL de Hb livre) e o sangramento do sítio são as emergências mais comuns.**
- **Hemólise: Diagnóstico, Causas e Manejo:**
	- **Critérios Diagnósticos:** Hemoglobina livre no plasma > 40 mg/dL exige intervenção (> 100 = grave). Urina rosa/avermelhada (hemoglobinúria sem hemácias no sedimento). *Dica:* Monitorar rotineiramente a cada 6-12h ou diariamente.
	- **Causas associadas ao Impella:** Mau posicionamento (causa #1), Alarmes de sucção diastólica, Obstrução do fluxo de purga, Trombo na bomba, ou P-levels muito altos. (*Anatomia:* Câmaras de VE muito pequenas ou ângulo aorto-mitral < 126º predispõem a hemólise refratária).
	- **Consequências:** Lesão Renal Aguda, Vasoconstrição sistêmica (consumo de óxido nítrico), Trombose (ativação plaquetária).
	- **Manejo:**
		1. POCUS para confirmar posição (corrigir se estiver muito profundo ou direcionado à mitral).
		2. Reduzir P-level se possível (considerar desmame completo se tolerado).
		3. Otimizar pré-carga do VE (Fluidos, tratar VD).
		4. Se trombo (pressão de purga alta): trocar Impella.
		5. Casos refratários: Considerar transição para ECMO-VA.
- **Coagulopatias Múltiplas Induzidas pelo Dispositivo:**
	- **Síndrome de von Willebrand Adquirida:** Ocorre em quase todos os pacientes em até 1 dia por cisalhamento (shearing) da bomba. Resolve rapidamente após remoção.
	- Trombocitopenia, CIVD, e depleção de fatores de contato (XI e XII) devido à superfície plástica (causa alargamento de PTT sem sangramento clínico grave).
	- *Anticoagulação:* Heparina sistêmica é o padrão. Em caso de sangramento grave, pode ser suspensa, mas o P-level deve ser **maximizado** para evitar trombose isquêmica.
- **Sangramento no Sítio de Acesso (Hematoma inguinal / Choque):**
	- Ocorre em ~10% dos casos. Fatores de risco: Idade, Mulher, Obesidade, DAP.
	- **Conduta:**
		1. Compressão manual direta *gentil* preservando o ângulo do cateter.
		2. **Red Flag:** NÃO achate o ângulo do Impella (piora o sangramento) e NÃO coloque sacos de areia ou dispositivos FemStop sobre o Impella.
		3. Avisar Cirurgia Vascular/Cardiologia, reverter anticoagulação e fornecer hemotransfusão.
- **Outras Complicações:**
	- Danos estruturais ou regurgitação funcional da valva aórtica/mitral.
	- Arritmias ventriculares (até 18% dos casos).

## 5. Falência de VD no Contexto de LV Impella
### **O suporte do VE pode aumentar abruptamente a pré-carga do VD, exacerbando a falência de ventrículo direito (BiV failure).**
- **Sinais Clínicos:** Alarmes de sucção (o VD dilata e comprime o VE reduzindo sua pré-carga), queda do Débito Cardíaco, CVP alta (> 8-12 mmHg) e PAPi < 1.
- **Manejo:**
	- Diurese ou diálise para controle de volume.
	- Inotrópicos (Epinefrina, Milrinone).
	- Vasodilatadores pulmonares inalatórios (Óxido Nítrico, Epoprostenol).
	- Reduzir velocidade do Impella (para não "afogar" o VD).
	- Considerar **Impella RP (BiPella)**.
- **Impella RP (Suporte Direto do VD):**
	- **Posicionamento:** Entrada no AD (VCS/VCI); Saída no Tronco da Artéria Pulmonar, acima da válvula pulmonar.
	- Manter fluxo > P-6 (reduzir para P-2 apenas quando manipular cateteres venosos centrais).
	- **Contraindicações:** Hipertensão pulmonar grave (PSAP > 60 mmHg), Trombo em VD/AP ou TEP, bacteremia ativa.

## 6. Desmame do Impella (Weaning)
### **O desmame é baseado na redução gradual do fluxo (0,5 L/min/h) sob monitorização rigorosa hemodinâmica e metabólica.**
- **Critérios para Iniciar (Baseado no DanGer Shock Trial):**
	- Resolução do insulto inicial; pelo menos 48h de suporte.
	- Lactato < 2,5 mM, pH > 7,30.
	- Baixa necessidade inotrópica: Dobutamina ≤ 10, Milrinone ≤ 0,4, Noradrenalina ≤ 0,15, Dopamina ≤ 10 (µg/kg/min). Máximo de 2 inotrópicos.
	- IC > 2 L/min/m²; SvO2 > 55%; Sem edema agudo de pulmão.
- **Protocolo de Redução:**
	- Reduzir o suporte a cada hora em passos de 0,5 L/min (aproximadamente um P-level).
	- Antes de cada redução, checar CVP, PA, SvO2 e Lactato. (É normal precisar aumentar levemente os inotrópicos durante o desmame).
	- **Explante:** Se tolerar fluxo de 1 L/min (ou estável em P2) com parâmetros mantidos, o dispositivo pode ser removido (após suspensão e perda de efeito da anticoagulação).
	- **Falha:** Se o paciente descompensar, retornar ao suporte mecânico anterior e aguardar 24 horas antes de nova tentativa.

## 7. Indicações, Contraindicações e Estratégias Combinadas
### **O Impella tem benefício comprovado (mortalidade a 180 dias) no Choque Cardiogênico pós-IAM (DanGer Shock Trial).**
- **Indicações Principais:** Choque cardiogênico SCAI C-D (SCAI E avaliar ECMO-VA), Descompressão do VE na ECMO (Ecpella) e PCI de alto risco.
- **Contraindicações:**
	- Risco hemorrágico incontrolável ou intolerância à heparina.
	- Insuficiência biventricular severa (Impella LV isolado é insuficiente).
	- Trombo em VE.
	- Doença valvar aórtica severa (Regurgitação AI moderada-severa, Prótese mecânica aórtica). *Nota:* Estenose Aórtica severa pode permitir Impella 5.0/5.5 que substitui o fluxo nativo.
	- Dissecção de Aorta, Tamponamento, Doença Arterial Periférica severa.
- **Ecpella (ECMO-VA + Impella):**
	- Utilizado primariamente para **descompressão do VE** (evitar distensão e edema pulmonar causados pela pós-carga alta da ECMO).
	- O Impella é titulado para manter o VE vazio (não para Débito Cardíaco).
	- Na Ecpella, a ECMO é desmamada primeiro, e o Impella depois.
- **BiPella (LV Impella + RV Impella):**
	- Estratégia experimental para choque biventricular.
	- Vantagens sobre ECMO-VA: Evita hipóxia diferencial, evita dilatação do VE, menor risco de isquemia de membro, descalonamento mais fácil.
	- Desvantagens sobre ECMO-VA: Menor suporte hemodinâmico global, não oferece oxigenação/ventilação. Requer equilíbrio fino (muito fluxo direito causa congestão pulmonar, muito fluxo esquerdo causa falência de VD).