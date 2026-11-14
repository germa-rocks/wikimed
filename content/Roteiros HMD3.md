---
publish: true
---

### 3.1 Débito Cardíaco por Contorno de Pulso e Variação do Volume Sistólico (VVS)

- [ ] *"Para monitorizar o débito cardíaco batimento a batimento pelo contorno de pulso arterial,
    - [ ] executo o fast-flush test validando 1 a 2 oscilações, 
	    - [ ] pois subamortecimento superestima PAS e DC e 
	    - [ ] superamortecimento apaga a incisura dicrótica.
- [ ] Integro a área sistólica considerando 
	- [ ] complacência ($C = dV/dP$) e resistência arterial ($R$) em monitores calibrados externamente (PiCCO/PulsioCare e VolumeView por TDTP; LiDCOplus por lítio/PulseCO), 
	- [ ] internamente (FloTrac $VS = K \times \sigma_{AP}$, atento a extremos biométricos) 
	- [ ] ou PRAM (MostCare), 
	- [ ] evitando sensores digitais no choque,
- [ ] 
    - [ ] caso ocorra vasoplegia grave, mudança rápida na RVS ou condições que distorcem a onda arterial,
        - [ ] recalibro imediatamente por TDTP os sistemas calibrados 
	        - [ ] (desconfiando do FloTrac na sepse e hepatopatia), 
        - [ ] invalido o contorno em BIAC, regurgitação aórtica, CIV pós-IAM, ECMO-VA e arritmias, 
        - [ ] e migro da TDTP para o CAP se houver falência de VD ou hipertensão pulmonar;
    - [ ] caso avalie a VVS automática ($\ge 12\%$, aplicável em menos de 10% dos pacientes de UTI),
        - [ ] exijo 
	        - [ ] VMI controlada sem esforço, $V_t \ge 8\text{ mL/kg}$ PBW, $C_{rs} > 30\text{ mL/cmH}_2\text{O}$, tórax fechado
		        - [ ] ou elevo o $V_t$ de 6 para $8\text{ mL/kg}$ por 1 minuto (positivo se $\Delta VVS \ge 2,5\text{ p.p.}$), retornando a $6\text{ mL/kg}$;
	        - [ ] $FC/FR > 3,6$, 
	        - [ ] ritmo sinusal nem cor pulmonale
	        - [ ] sem HIA , 
    - [ ] ou caso o paciente ventile em pressão de suporte ou apresente hipertensão intra-abdominal,
        - [ ] descarto apenas a VVS — pois o DC contínuo permanece válido — 
        - [ ] e guio o PLR de 60 a 90 segundos ou
        - [ ] o fluid challenge de 200 mL em 10 minutos (positivos se $\Delta DC$ ou $\Delta VS \ge 10\%$), 
        - [ ] travando novos bolus se a PVC subir $> 3\text{ mmHg}$."*

> **Alerta de Banca (Armadilha Psicométrica):** 
> - Esquecer o fast-flush aceitando subamortecimento que superestima o DC, 
> - invalidar o débito contínuo apenas por PSV ou HIA (TEMI 2020), 
> - ignorar complacência e resistência arterial na estimativa do VS (TEMI 2021) 
> - ou usar TDTP em vez de CAP na falência grave de VD reprovam na estação.

### 3.2 Bioimpedância e Biorreatância Elétrica Torácica (Starling)

- [ ] *"Para monitorizar o fluxo de forma não invasiva pela biorreatância elétrica torácica no monitor Starling,
    - [ ] insiro idade, sexo, peso e altura em Start New Session, 
    - [ ] colo 4 sensores duplos (2 supraclaviculares e 2 na base axilar média) e 
    - [ ] confirmo Sensor Placement verde bilateral.
- [ ] Supero a bioimpedância clássica de amplitude ($VS = k \times TEV \times (dZ/dt)_{max}$, erro de 42,9% acima dos 30% de Critchley) medindo o atraso de fase $\Delta\Phi$ a 75 kHz com relação sinal-ruído 100 vezes superior e imunidade a líquido estático,
    - [ ] caso teste fluidoresponsividade à beira-leito (inclusive na ICC séptica ou choque pós-ultrafiltração dialítica),
        - [ ] desligo botas pneumáticas a $45^\circ$, gravo 3 minutos intocados em Start PLR e basculo a cama ($0^\circ/45^\circ$) por 3 minutos: expando 250 a 500 mL repetindo o PLR até o platô se $\Delta SVI \ge 10\%$ (curva verde), inicio vasopressor se $< 10\%$ (vermelha), ou uso Start BOLUS na HIC e fratura pélvica;
    - [ ] caso encontre fatores de interferência elétrica, arritmias ou alterações anatômicas da aorta,
        - [ ] lembro que EAP, derrame pleural e eletrocautério falseiam a bioimpedância, mas mesmo na biorreatância a fibrilação atrial prejudica o TEV, dissecção ou próteses aórticas alteram o fluxo laminar, e obesidade mórbida ou anemia extrema exigem guiar-se apenas pela variação percentual do $\Delta SVI$;
    - [ ] ou caso o paciente evolua com choque séptico refratário complexo ou hipoxemia grave,
        - [ ] reconheço pelo consenso da ESICM que a biorreatância não mensura pressões de enchimento, GEDV, EVLW nem função isolada de VD e VE, escalonando de imediato para ecocardiograma funcional, TDTP ou cateter de artéria pulmonar."*

> **Alerta de Banca (Armadilha Psicométrica):** 
> - Manter a compressão pneumática intermitente ligada ou 
> - tocar no paciente nos 3 minutos basais do PLR, 
> - não repetir o PLR pós-expansão até atingir o platô vermelho ou
> - tentar estimar congestão pulmonar e pressões cavitárias pelo Starling reprovam na estação.

### 3.3 Medida do Débito Cardíaco pelo Ecocardiograma (VTI-VSVE)

- [ ] *"Para aferir o débito cardíaco ecocardiográfico modelando o cilindro hidráulico na VSVE,
    - [ ] no paraesternal longo (probe setorial, marker às 11h) com zoom mesossistólico 
    - [ ] meço borda-interna a borda-interna o diâmetro na inserção aórtica ($Área = 0,785 \times d^2$, ou fixo $2,0\text{ cm}$ evitando 11% de erro quadrático).
- [ ] No apical 5 câmaras (marker às 3h), alinho o Doppler pulsado ($< 20^\circ$) com gate 5 mm proximal à valva aórtica — fugindo do jato na estenose aórtica — e traço 3 a 5 ciclos (5 a 10 na FA) obtendo $DC = Área \times VTI \times FC$,
    - [ ] caso meça VTI reduzida ($< 17\text{–}18\text{ cm}$, normal AMIB 18 a 22 cm), integro contratilidade, VCI e pulmão,
        - [ ] diferenciando hipovolemia (VE hiperdinâmico colabante, VCI fina colapsável $> 50\%$ e linhas A/FAST+), 
        - [ ] choque cardiogênico (hipocinesia, VCI $> 2,1\text{ cm}$ fixa e linhas B difusas) e 
        - [ ] obstrutivo (colapso diastólico direito no tamponamento, $VD/VE > 1$ com septo em D no TEP ou ausência de lung sliding);
    - [ ] caso observe VTI normal ou elevada ($\ge 23\text{ cm}$) em paciente hipotenso,
        - [ ] afasto turbulência local por insuficiência aórtica moderada a grave ou 
        - [ ] obstrução dinâmica da VSVE com SAM mitral em adaga, 
        - [ ] confirmando choque distributivo hiperdinâmico para titular noradrenalina e rastreando apenas a VTI isolada nas séries (precisão de 4%, limiar mínimo de 10%);
    - [ ] ou caso interrogue fluidoresponsividade pela VTI isolada (PLR $\ge 15\%$ em 60 s, mini-challenge de 100 mL $\ge 10\%$ ou variação respiratória passiva sinusal de $10\text{ a }12\%$),
        - [ ] exijo fluidotolerância intacta antes de infundir soro, pois diante de SDRA com linhas B coalescentes difusas e baixa $PaO_2/FiO_2$ 
        - [ ] proíbo prova volêmica, diurético ou dobutamina e
        - [ ] inicio noradrenalina mesmo com PLR francamente positivo."*

> **Alerta de Banca (Armadilha Psicométrica):** 
> - Remedir o diâmetro da VSVE a cada prova propagando erro quadrático, 
> - deixar o gate escorregar para o orifício estenótico aórtico ou
> - prescrever volume apenas por $\Delta VTI \ge 15\%$ no PLR na vigência de SDRA com linhas B coalescentes (TEMI 2025) reprovam na estação.

### 3.4 Monitorização Hemodinâmica com Doppler Esofágico

- [ ] *"Para monitorizar o fluxo na aorta descendente pelo Doppler esofágico afastadas lesões esofágicas, coarctação ou BIAC,
    - [ ] insiro a sonda até o marcador 2 nos incisivos (oral) ou 3 na narina (nasal), rotaciono até obter som sistólico estridente e maior envelope triangular, ajusto ganho/filtro e fixo rigidamente ($VS = Área_{Ao} \times VTI$).
- [ ] Integro nas interfaces de fluxo e pressão a distância sistólica (DS 12–14 cm), o FTc (330–360 ms), o pico de velocidade ajustado à idade (PV: jovens 90–120, idosos 30–60 cm/s) e o $CPO = (PAM \times DC)/451$ ($0,5\text{–}1,5\text{ W}$),
    - [ ] caso encontre FTc encurtado ($< 330\text{ ms}$), cruzo com a PV separando o quadrante A vasoconstrito (PV alta) do C hipovolêmico (DS $< 12\text{ cm}$),
        - [ ] administrando 200 a 250 mL em 5 a 10 minutos (positivo se $\Delta VS$ ou $\Delta DS \ge 10\text{–}15\%$), ciente de que pós-peridural ou em reaquecimento o 1º bolus pode só subir FTc antes do VS no 2º, e associando dobutamina se PV $< 40\text{–}50\text{ cm/s}$;
    - [ ] caso observe FTc prolongado ($> 360\text{–}400\text{ ms}$), diferencio o quadrante B hiperdinâmico do quadrante D cardiogênico,
        - [ ] iniciando noradrenalina sem volume na mangueira aberta vasoplégica (triângulo largo, PV $> 120\text{ cm/s}$ e DS $> 14\text{ cm}$) ou titulando dobutamina sem expandir no motor quebrado (curva romba em domo, PV $< 40\text{–}50\text{ cm/s}$, DS $< 12\text{ cm}$ e $CPO < 0,6\text{ W}$);
    - [ ] ou caso o débito caia após iniciar noradrenalina exibindo PPV de 15% e SVV de 10% na tela integrada,
        - [ ] audito primeiro os pré-requisitos mecânicos: se válidos (VMI controlada passiva, sinusal e $V_t \ge 8\text{ mL/kg}$), o vasopressor desmascarou hipovolemia oculta e expando com cristaloide; se inválidos, a PPV é artefato de vasoplegia refratária e associo vasopressina a $0,01\text{–}0,04\text{ UI/min}$."*

> **Alerta de Banca (Armadilha Psicométrica):** 
> - Inverter os marcadores da sonda (2 oral vs. 3 nasal), 
> - tomar subida isolada do FTc sem ganho de VS/DS como resposta de Starling ou
> - dar volume por PPV de 15% pós-noradrenalina sem validar antes ventilação controlada e ritmo sinusal reprovam na estação.

### 3.5 Princípio de Fick e Termodiluição Pulmonar e Transpulmonar

- [ ] *"Para aferir o débito cardíaco pelos métodos referenciais de Fick e de termodiluição,
    - [ ] distingo Fick direto (espirometria de $\dot{V}O_2$ e $SvO_2$ na AP) do indireto ($SvcO_2$), calculando $DC = (125 \times ASC) / \{[(SaO_2 - SvcO_2) \times Hb \times 1,34] \div 10\}$ (usando 110 no idoso).
- [ ] Na termodiluição de Stewart-Hamilton ($DC = [V_i(T_s-T_i)K_1K_2]/\int\Delta T_b dt$), injeto 10 mL no CAP ou 15 mL na TDTP a $0\text{–}4^\circ\text{C}$ em $< 4\text{ s}$ (3 curvas com variação $< 10\%$), sendo o débito inversamente proporcional à área sob a curva,
    - [ ] caso empregue o cálculo de Fick em choque, audito suas premissas de fluxo equivalente e metabolismo,
        - [ ] invalidando-o em shunts intracardíacos (CIV/CIA), hipertensão pulmonar ou regurgitações graves ($FSS \neq FSP$) e no gradiente $\Delta C(a-v)O_2$ estreito da sepse hiperdinâmica, 
        - [ ] lembrando que no $\dot{V}O_2$ fixo a febre subestima o DC e a hipotermia ou bloqueio neuromuscular o superestimam;
    - [ ] caso interprete curvas térmicas e pressões oclusivas no cateter de artéria pulmonar,
        - [ ] rejeito curvas achatadas por injeção lenta $> 8\text{ s}$ (subestimam o DC) ou picos em martelo $< 2\text{ s}$ (superestimam o DC), 
        - [ ] recordando que insuficiência tricúspide subestima o fluxo por recirculação 
        - [ ] e que fora da Zona 3 de West ($P_a > P_v > P_A$) a POAP lê PEEP;
    - [ ] ou caso deduza os compartimentos volumétricos pela termodiluição transpulmonar ($GEDV = ITTV - PTV$, $ITBV = 1,25 \times GEDV$ e $EVLW = ITTV - ITBV$),
        - [ ] afasto shunts, aneurisma aórtico e pneumectomia, 
        - [ ] pondero que dilatação do VD superestima GEDI e GEF, 
        - [ ] que TEP subestima e derrame pleural superestima a APEV, 
        - [ ] e que na SDRA $ELWI_{max} > 21\text{ mL/kg}$ e $PVPI_{max} > 3,8$ predizem 70% de óbito."*

> **Alerta de Banca (Armadilha Psicométrica):** 
> - Inverter a relação inversa entre área sob a curva térmica e DC (aceitando injeção lenta ou em martelo), 
> - esquecer que a dilatação do VD falseia GEDI e GEF para cima 
> - ou ignorar que TEP subestima ELWI e
> - derrame pleural superestima ELWI reprovam na estação.

### 3.6 Aplicação Prática da Fluidoresponsividade, Fluidotolerância e Matriz de Perfis (A–D)

- [ ] *"Sabendo que após 8 h menos de 15% respondem, o cristaloide dissipa em 90 min, só 56% são $\dot{V}O_2$-responders e hipervolemia lesa o glicocálix reduzindo $PPO = PAM - PVC$,
    - [ ] supero LIMITS do $\Delta PP > 13\%$ e da VCI ($> 18\%$ por $D_{min}$ ou $> 12\%$ por $D_{med}$, inválidas sob $V_t \le 6\text{ mL/kg}$ ou PEEP $> 10$) usando PLR, TOE de 15 s, TVC, PEEP test ou mini-challenge de 200 mL (parando se PVC subir $\ge 3\text{ mmHg}$).
- [ ] Cruzo então fluidoresponsividade com fluidotolerância direita (PVC $< 12$, GEDI $< 800$, VExUS 0–1 e femoral não pulsátil) e esquerda (linhas A, ELWI $< 10\text{ mL/kg}$, POAP $< 18$ e $E/e' < 14$),
    - [ ] caso o paciente seja fluidotolerante em Perfil A (responsivo) ou Perfil B (não responsivo),
        - [ ] no Perfil A (VCI $< 2,0\text{ cm}$ em VExUS 0 e linhas A) infundo alíquotas de 250 a 500 mL monitorando lactato e razão $P(v-a)CO_2/C(a-v)O_2$, e no Perfil B suspendo fluidos preventivamente para não perder tolerância (OR 1,1/L para óbito no SOAP);
    - [ ] caso configure Perfil D (responsivo no PLR ou TOE, porém intolerante por linhas B confluentes, $C_{rs} < 30$, ELWI $\ge 10\text{ mL/kg}$, VExUS 2–3 ou femoral pulsátil),
        - [ ] diante de pulmão branco ou congestão venosa grave (onda S hepática reversa, porta $\ge 50\%$ ou fluxo renal monofásico diastólico), evito expansão liberal e inicio precocemente noradrenalina associada a vasopressina ou dobutamina sob monitorização estrita;
    - [ ] ou caso enfrente Perfil C (não responsivo com SVV $< 10\%$ sem ganho de CI e gravemente congesto com ELWI $\ge 10\text{ a }16,2\text{ mL/kg}$, PVC $\ge 12$ ou VExUS 2–3),
        - [ ] suspendo de imediato soros de manutenção e diluentes, priorizo vasopressores e inotrópicos e instituo derressuscitação ativa com furosemida intravenosa ou ultrafiltração negativa contínua em CRRT para restaurar a troca gasosa e a perfusão renal."*

> **Alerta de Banca (Armadilha Psicométrica):** 
> - Guiar volume pela colapsabilidade da VCI sob $V_t = 6\text{ mL/kg}$, PEEP de 16 ou peritonite, 
> - expandir liberalmente um Perfil D com pulmão branco ou 
> - não derressuscitar imediatamente um Perfil C após salto do ELWI para $16,2\text{ mL/kg}$ reprovam na estação.

### 3.7 Aplicações Clínicas e Sistematização da Termodiluição Transpulmonar (TDTP)

- [ ] *"Em qualquer plataforma de TDTP (EV1000/VolumeView, HemoSphere, PiCCO₂ ou PulsioFlex), afastados BIAC, ECMO-VA e insuficiência aórtica,
    - [ ] acoplo termistor femoral e sensor no CVC, 
    - [ ] insiro altura e sexo para indexar ELWI pelo peso predito (nunca peso real edemaciado),
    - [ ] zero a PVC destravando Start Set e
    - [ ] injeto 15 mL $\le 8^\circ\text{C}$, excluindo outliers em Review.
- [ ] Aplico a leitura sistemática de 1 a 7 nas fases ROSE: 
	1) PAM $\ge 65$, 
	2) CI $2,5\text{–}4,0$, 
	3) GEDI estático $680\text{–}800\text{ mL/m}^2$, 
	4) SVV/PPV $> 13\%$, 
	5) ELWI $< 7\text{–}10\text{ mL/kg}$, 
	6) PVPI ($EVLW/PBV$: $< 2$ hidrostático; $> 3$ SDRA) e 
	7) bomba ($GEF = 4 \times SV/GEDV$, $25\text{–}35\%$; $CFI = CO/GEDV$, $4,5\text{–}6,5\text{ min}^{-1}$),
- [ ] 
    - [ ] caso encontre edema pulmonar ($ELWI \ge 14\text{–}18\text{ mL/kg}$) e SVV $< 10\%$, 
	    - [ ] diferencio congestão cardiogênica ou pós-ressuscitação ($PVPI \le 2,0$, $GEDI\ 820\text{–}900$, $GEF\ 20\text{–}24\%$) de SDRA ($PVPI > 3,0$, $CI\ 3,7$, $GEF\ 29\%$),
	    - [ ] proibindo soro em ambos: 
		    - [ ] no hidrostático ou miocardiopatia séptica peço eco, inicio dobutamina com noradrenalina e evacuo com diurético/CRRT; 
			- [ ] na permeabilidade inflamatória mantenho VM protetora, prona, controle séptico e balanço negativo;
    - [ ] caso observe baixo débito ($CI < 2,5\text{–}3,0\text{ L/min/m}^2$) com pré-carga baixa ($GEDI < 680\text{–}700\text{ mL/m}^2$), contrasto hipovolemia pura ($ELWI\ 6$, $PVPI\ 1,1$, $SVV\ 17\text{–}18\%$, $GEF\ 28\%$) contra choque misto ($GEF < 25\%$, $ELWI\ 9$),
        - [ ] indicando no pós-operatório sangrante prova controlada de fluidos (e hemácias se $Hb \le 7\text{ g/dL}$) vigiando teto de $ELWI < 10$, mas iniciando dobutamina antes de microalíquotas $\le 250\text{ mL}$ no choque misto;
    - [ ] ou caso identifique choque distributivo hiperdinâmico ($PAM\ 55$, $CI\ 5,1$, $SVRI\ 900$, $GEDI\ 720$, $SVV\ 7\%$, $ELWI\ 7$ e $GEF\ 31\% / CFI\ 6,2$),
        - [ ] contraindico expansão volêmica empírica por pré-carga adequada sem resposta, 
        - [ ] escalono noradrenalina associando precocemente vasopressina, 
        - [ ] abordo cirurgicamente o foco abdominal sem atraso e
        - [ ] recalibro frequentemente por TDTP pela vasoplegia."*

> **Alerta de Banca (Armadilha Psicométrica):** 
> - Indexar o ELWI pelo peso real em anasarca, 
> - esquecer de zerar a PVC travando o Start Set, 
> - insistir em cristaloide por hipotensão e oligúria na Estação 5 ($GEDI\ 900$, $ELWI\ 14$, $SVV\ 5\%$) 
> - ou confiar no contorno sem recalibrar na vasoplegia reprovam na estação.