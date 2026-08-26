---
publish: true
---

Aqui está a estruturação de alto rendimento do manual de ECMO, desenhada com a lógica de divulgação progressiva (estilo DynaMed/Notion), focada inteiramente em pérolas clínicas na superfície e fisiopatologia/manejo denso nos níveis inferiores.

***

# 🫀 Manual Prático de ECMO: Suporte de Vida Extracorpóreo

## 1. Parâmetros e Pressões do Circuito (O Básico)
- **O fluxo da ECMO (V̇) deve ser ajustado para a menor taxa possível que garanta oxigenação sistêmica e perfusão adequadas.**
    - Fluxos muito baixos (< 2-3 L/min) aumentam drasticamente o risco de trombose do circuito.
        - Se a anticoagulação for contraindicada, mantenha altos fluxos (ex: 4-5 L/min) para minimizar a estase.
    - Fluxos muito altos aumentam o risco de hematologia adversa (hemólise, perda de fator de von Willebrand, lesão plaquetária).
    - **Metas Iniciais:**
        - **VV ECMO:** Iniciar com fluxo baseado na superfície corporal (BSA * 1.8 L/min/m²). Esperado ~5 L/min. Geralmente, necessita cobrir >60% do Débito Cardíaco (DC) nativo.
        - **VA ECMO:** Iniciar com BSA * 2.4 L/min/m². Falência biventricular exige ~80% do DC (~4-5 L/min). Risco de estase e falência ventricular esquerda associada.
- **Pressão de Drenagem Venosa (Pven): O alvo de segurança é manter > -100 mmHg para evitar hemólise grave e "chugging" (colapso da cânula).**
    - Pven reflete a sucção antes da bomba. Pressões excessivamente negativas geram microcavitação e destroem hemácias.
    - Manejo imediato da Pven <-100 mmHg ou "Chugging" pré-bomba:
        - **Conduta:** Reduzir a velocidade (RPM) em passos de ~100 RPM a cada 10 segundos até estabilizar o fluxo.
        - **Diagnóstico diferencial da Insuficiência de Drenagem:**
            - *Falta de Pré-carga:* Hipovolemia (sangramento, choque distributivo).
            - *Compressão Extrínseca:* Pressão intratorácica alta (pneumotórax, excesso de PEEP, tosse), Hipertensão intra-abdominal, Tamponamento.
            - *Falha Mecânica:* Kink no cateter, cânula mal posicionada (ex: na veia hepática) ou trombose.
- **Pressão Transmembrana (ΔP): O melhor indicador de saúde do pulmão artificial (oxigenador). O basal é ~40-50 mmHg.**
    - Um ΔP > 60 mmHg ou em elevação progressiva (sem aumento de fluxo) sugere disfunção da membrana.
    - Um ΔP > 100 mmHg é um forte indicativo de falha iminente (trombose da membrana) e necessidade de troca do circuito.
    - O diagnóstico exige verificar hemólise paralela, queda de transferência de O2 e aumento inexplicado da necessidade de *Sweep Gas*.

## 2. Oxigenação, Ventilação e Monitoramento
- **SvO2 (Saturação Venosa de Drenagem): Valores < 60% na VV ou < 65% na VA refletem extração de O2 excessiva e perfusão/oxigenação deficientes.**
    - No entanto, SvO2 muito elevada (ex: >75-80%) nem sempre é um bom sinal:
        - **VV ECMO:** Sugere forte recirculação (o sangue oxigenado está sendo sugado de volta pela cânula de drenagem sem ir para o paciente).
        - **VA ECMO periférica:** Se medida em membro inferior, pode refletir hipoxemia diferencial (Síndrome North-South), onde o corpo inferior está hiperoxigenado e o cérebro/coronárias estão hipóxicos.
- **FdO2 (Fração de O2 no Circuito): É fixada em 100% na ECMO VV, mas deve ser titulada na ECMO VA para evitar hiperóxia tecidual.**
    - Na ECMO VV, o sangue hiperoxigenado vai se misturar com o sangue venoso nativo, raramente causando hiperóxia nociva.
    - Na ECMO VA central, o sangue vai direto para os tecidos. Ajustar FdO2 para manter PaO2 pós-membrana em ~150 mmHg.
- **Ventilação Mecânica (Ultra-Lung Rest): A ECMO assume as trocas gasosas; o ventilador serve apenas para manter o pulmão recrutado e prevenir VILI.**
    - **Configurações Alvo Padrão:**
        - Fração Inspirada de O2 (FiO2): 30-50% (evitar toxicidade pelo oxigênio).
        - PEEP: ≥ 10 cmH2O (ideal 10-24 para evitar atelectasia).
        - Pressão de Platô: < 25 cmH2O.
        - Driving Pressure: ≤ 10 cmH2O.
        - Volume Corrente: ~4 mL/kg de peso ideal.
        - Frequência Respiratória: 5 a 10 ipm (reduz o "mechanical power" aplicado ao pulmão).
- **Sweep Gas (CO2): Inicie com 50-100% do fluxo sanguíneo da ECMO, mas evite quedas abruptas da pCO2 em hipercápnicos crônicos.**
    - Reduções drásticas da pCO2 geram vasoconstrição cerebral aguda e lesão neurológica.
    - Regra prática: Corrigir a pCO2 em não mais que 50% nas primeiras 4 horas.
    - Ajustes subsequentes: O Sweep é inversamente proporcional à pCO2 arterial desejada. Se há assincronia/taquipneia, aumentar o Sweep reduz o drive respiratório do paciente, poupando sedativos.

## 3. Manejo Exclusivo: ECMO Venovenosa (VV)
- **Recirculação (Problema central da ECMO VV): Suspeite quando a SpO2 sistêmica cai, enquanto a SvO2 do circuito sobe paradoxalmente (>75-80%).**
    - Sinais visuais: O sangue na cânula de drenagem pisca vermelho brilhante.
    - Confirmação diagnóstica: Tentar reduzir o fluxo (RPM) em 5-10%; se a saturação periférica *melhorar* paradoxalmente, a recirculação está confirmada.
    - Manejo Passo a Passo:
        - 1. Aumentar o débito cardíaco nativo (volume, reduzir PEEP, etc).
        - 2. Reduzir a velocidade da bomba (diminui a fração de recirculação).
        - 3. Reposicionar cânulas. Cânulas simples devem ter distância >15 cm. Cânulas duplo-lúmen (Avalon) precisam do jato direcionado para a valva tricúspide.
- **Disfunção do Ventrículo Direito (VD): A ECMO VV costuma melhorar indiretamente o VD.**
    - Funciona através da redução da pressão intratorácica (lung rest), correção da acidose e reversão da hipóxia alveolar (reduzindo vasoconstrição pulmonar).
    - ECMO VA é reservada como último recurso se a falência de VD na SDRA persistir apesar da VV.

## 4. Manejo Exclusivo: ECMO Venoarterial (VA)
- **Distensão do Ventrículo Esquerdo (VE): A maior ameaça da ECMO VA periférica. Ocorre pelo aumento da pós-carga imposta pela bomba, impedindo o esvaziamento do VE.**
    - Consequências cataclísmicas: Isquemia coronariana (distensão de parede), EAP hemorrágico severo, estase com trombose massiva no VE/raiz da aorta e tempestade arrítmica.
    - Diagnóstico de falha no esvaziamento do VE:
        - Pressão de Pulso no acesso arterial < 10-15 mmHg.
        - ECO: Ausência de abertura da valva aórtica (pelo menos 1x a cada 3 batimentos), VE dilatado, presença de "fumaça" (estase).
        - etCO2 < 15 mmHg (reflete baixíssimo débito cardíaco nativo).
    - Manejo do "Venting" do VE (Do menos invasivo para dispositivos físicos):
        - 1. Tratar arritmias (garantir ritmo perfusional) e garantir anticoagulação plena imediata (risco absurdo de trombo).
        - 2. Reduzir o fluxo da ECMO (diminui a pós-carga), se a perfusão periférica permitir.
        - 3. Otimizar ventilação: Aumentar PEEP (reduz pré-carga do VE e o afterload).
        - 4. Vasodilatadores arteriais ou inodilatadores (Dobutamina) se MAP >65 mmHg.
        - 5. Suporte de dispositivo mecânico associado: Balão Intra-Aórtico (IABP) ou Impella.
- **Hipoxemia Diferencial (Síndrome Norte-Sul / Harlequin): O coração nativo recupera força, mas o pulmão continua falido, ejetando sangue azul para o arco aórtico.**
    - Diagnóstico: SpO2 radial direita baixa (cérebro e coronárias hipóxicos) + SpO2 normal/alta nas pernas (perfundidas pela ECMO).
    - Manejo:
        - 1. Tentar otimizar função pulmonar (Aumentar PEEP/FiO2 no ventilador, tentar óxido nítrico).
        - 2. Reduzir o inotropismo (diminui o débito cardíaco nativo) - medida temporária, gera distensão de VE.
        - 3. Mudança de configuração: Transição para ECMO V-AV (adiciona retorno de sangue oxigenado para a veia cava superior) ou transição definitiva para ECMO VV se o coração estiver bom.
- **Meta de Pressão Arterial (MAP): Alvo geralmente mantido entre 65-80 mmHg.**
    - MAPs mais altas sobrecarregam demasiadamente o VE.
    - MAP < 65 pode ser tolerada se indicadores de perfusão (Lactato, NIRS, enchimento capilar) estiverem impecáveis, especialmente em portadores de cardiopatia crônica.

## 5. Emergências e Complicações Catastróficas
- **Sangramento: É a complicação mais comum (cânulas > TGI > SNC).**
    - O paciente em ECMO tem hemostasia primária nula por **Síndrome de von Willebrand Adquirida** (alta tensão de cisalhamento destroi multímeros) + disfunção plaquetária + plaquetopenia.
    - Conduta no sangramento ativo:
        - Reduzir ou suspender anticoagulação temporariamente. Manter Fibrinogênio alvo rigoroso > 150-200 mg/dL (com crioprecipitado). Transfundir plaquetas para manter >50.000.
        - Uso de Antifibrinolíticos (Ácido Tranexâmico) é tratamento de resgate extremo (devido ao risco de trombose fatal do circuito).
- **Trombose Induzida por Heparina (HIT): Incidência de ~5%.**
    - Diagnóstico difícil pois plaquetopenia isolada ocorre em quase todos os pacientes. Suspeite se houver queda abrupta + microtromboses no circuito.
    - Conduta: Trocar IMEDIATAMENTE para inibidor direto de trombina (Bivalirudina ou Argatrobana) e suspender transfusões de plaquetas.
- **Hemólise Induzida por Circuito: Manifesta-se com urina escura e Lesão Renal Aguda.**
    - Diagnóstico confirmatório: Hemoglobina livre no plasma > 50 mg/dL (moderada) ou > 100 mg/dL (grave). LDH correlaciona mal.
    - Manejo: Identificar causa física (Pven excessiva, kink, coágulo na bomba). Reduzir a RPM da bomba se possível.
- **Parada no Fluxo do Circuito (Arrest): Risco de morte imediata.**
    - Conduta: Buscar pinças acidentais, torção na cânula. Se falha mecânica da bomba, usar manivela manual.
    - Se entrada maciça de ar: Pinçar (clamp) imediatamente a linha arterial, paciente em Trendelenburg (proteção cerebral), FiO2 100%, de-air no circuito usando seringas (ou troca completa do circuito).

## 6. Farmacologia na ECMO
- **Drogas lipofílicas (alta ligação a proteínas) sofrem sequestro maciço no polímero do circuito. Doses usuais não funcionarão.**
    - **Analgesia e Sedação:**
        - Fentanil, Propofol, Dexmedetomidina e Midazolam têm altíssima ligação proteica (substancialmente absorvidos pelo circuito). Requerem doses de ataque e manutenção muito maiores.
        - Hidromorfona (baixa lipofilicidade) é o opioide de escolha.
    - **Antibioticoterapia:**
        - Drogas hidrofílicas (Beta-lactâmicos, Vancomicina) sofrem impacto pelo enorme volume de distribuição (Vd) do sangue no circuito. Requerem doses de ataque mais altas e intervalos otimizados (extremos da faixa terapêutica).
        - Aminoglicosídeos precisam de monitoramento rigoroso de nível sérico.
    - **Bloqueio Neuromuscular:**
        - Cisatracúrio é o agente ideal. Baixa lipofilicidade (menor sequestro) e farmacocinética não depende de função hepática ou renal (comumente disfuncionais nestes doentes).

## 7. Desmame da ECMO
- **Desmame da ECMO VV:**
    - Teste do Gás (Off-Sweep Challenge): O ventilador do paciente é ajustado para parâmetros "normais" protetores. O fluxo de gás (sweep) da membrana é progressivamente reduzido até ser **totalmente desligado (0 L/min)** por 2h.
    - A bomba de sangue NUNCA é desligada (manter 2-3 L/min para evitar trombose).
    - Critérios de sucesso: SpO2, pCO2 e FR estáveis sem sinais de falência de ventilação nativa.
- **Desmame da ECMO VA:**
    - O desmame exige redução gradual do suporte de sangue para avaliar se o coração aguenta a própria carga.
    - **NUNCA desligue o Sweep Gas da ECMO VA** na fase de desmame.
    - Conduta: Otimizar drogas vasoativas/inotrópicos. Reduzir fluxo para ~1 L/min. Realizar o *Clamp Trial* (pinçar o circuito arterial e venoso temporariamente por 3-5 minutos, mantendo a anticoagulação em dia para não perder o circuito).
    - Critérios de sucesso: MAP mantida >65 mmHg, VTI aórtico no ECO >10-12 cm, manutenção de saturação venosa mista >65%.

## 8. Indicações e Seleção de Pacientes (Checklist Rápido)
- **Candidatos ideais para VV (Falência Pulmonar Isolada):**
    - Hipoxemia refratária (PaO2/FiO2 < 80) após pronação e otimização clínica máxima, com potencial de reversibilidade (SDRA, pneumonia, aspiração) ou como ponte para transplante de pulmão.
    - Limites: Em geral, desencorajada se ventilação mecânica lesiva (Platô >30, FiO2 >90%) por > 7 dias, ou lesão irreversível no SNC.
- **Candidatos ideais para VA (Falência Cardíaca):**
    - Choque cardiogênico fulminante refratário a altas doses de drogas vasoativas/inotrópicas instituídas em **menos de 6 horas** (ex: Miocardite fulminante, TEP maciço, pós-PCR).
    - Contraindicação central: Ausência de perspectiva de recuperação cardíaca SEM chance técnica de ponte para dispositivo de longa duração (LVAD) ou transplante. Doença arterial periférica grave (impossibilita acesso femoral seguro). Risco proibitivo se disfunção neurológica grave ou sangramento incontrolável.