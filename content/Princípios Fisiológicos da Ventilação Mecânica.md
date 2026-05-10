---
publish: true
---


***

# Princípios Fisiológicos da Ventilação Mecânica
## A Equação do Movimento (Base do Entendimento Ventilatório)

- **A ventilação com pressão positiva precisa vencer duas forças principais: a resistência das vias aéreas (fluxo) e o recolhimento elástico do sistema respiratório (volume).**
    - Componentes da Equação do Movimento ($P = P_0 + P_{res} + P_{el}$):
        - Pressão Inicial ($P_0$): PEEP configurada ou Auto-PEEP (pressão residual).
        - Pressão Resistiva ($P_{res}$): Oposição à passagem do ar. Só existe quando há fluxo (condição dinâmica). Depende do diâmetro do tubo, secreções e broncoespasmo.
        - Pressão Elástica ($P_{el}$): Pressão necessária para distender o pulmão e a parede torácica. Existe independentemente do fluxo (condição estática).

## Monitorização à Beira-Leito: Curvas em Volume Controlado (VCV)

- **Utilize sempre uma pausa inspiratória curta (0,2 a 0,3 segundos) no modo VCV para diferenciar a Pressão de Pico (Ppeak) da Pressão de Platô (Pplat).**
    - A pausa interrompe o fluxo subitamente. Sem fluxo, a resistência é anulada, revelando as verdadeiras pressões elásticas do sistema.
        - Pressão de Pico ($Ppeak$): É a pressão máxima medida nas vias aéreas. Sofre influência direta da resistência (tubo + vias aéreas) e da complacência pulmonar.
        - Pressão de Platô ($Pplat$): É a pressão alveolar real. Reflete apenas a distensão do pulmão e da caixa torácica.
    - Manejo de Alarmes de Pressão (Red Flag):
        - Quando o alarme de Ppeak dispara, o ventilador corta o fluxo imediatamente (proteção), impossibilitando a leitura do Platô.
        - Conduta: Aumente temporariamente o limite do alarme de pressão para observar a curva completa e identificar se o problema é Resistivo (Ppeak alta, Pplat normal) ou Elástico (Pplat alta).

## Resistência de Vias Aéreas (RVA)

- **A Resistência reflete a dificuldade de passagem do fluxo de ar e não distende nem causa lesão direta aos alvéolos. O valor normal é < 10 cmH2O.**
    - Cálculo de Resistência: R = (Ppeak - Pplat) / Fluxo.
        - Dica Prática de Cálculo Rápido (Beira-leito):
            - Ajuste o fluxo inspiratório para 60 L/min.
            - Como 60 L/min equivale exatamente a 1 L/segundo, a equação se anula: a diferença exata entre a Pressão de Pico e a Pressão de Platô passa a ser o valor direto da Resistência.
    - Interpretação da Pressão Resistiva Alta (Ppeak alta, Pplat normal):
        - A pressão se dissipa no trajeto e não causa dano alveolar direto.
        - Causas comuns: Tubo orotraqueal estreito (ex: TOT nº 6 em homem adulto), rolha de secreção, broncoespasmo severo ou paciente "mordendo" o tubo.
        - Efeito nos Modos Ventilatórios:
            - PCV (Pressão Controlada): A alta resistência "roubará" a pressão entregue, gerando um Volume Corrente (Vt) baixo.
            - PSV (Pressão de Suporte): Exigirá alto trabalho respiratório do paciente.

## Complacência e o Conceito de "Baby Lung"

- **A Complacência reflete o "tamanho" do pulmão viável (aerado) disponível para ventilação, não apenas a sua rigidez. Em pacientes graves (ex: SARA), o pulmão não é apenas "duro", ele é "pequeno" (*Baby Lung*).**
    - Cálculo da Complacência: C = Volume Corrente / (Pplat - PEEP).
    - Fisiopatologia e Avaliação Clínica:
        - Complacência Normal: ~ 100 mL/cmH2O (Na prática da UTI, valores de 50 mL/cmH2O são tolerados/comuns em pacientes em decúbito dorsal).
        - Impacto da área aerada: Se houver intubação seletiva (ou colapso maciço), a área pulmonar cai pela metade. A complacência cairá de 50 para 25 mL/cmH2O, e a Pressão de Platô irá dobrar instantaneamente para o mesmo Volume Corrente.
    - Parede Torácica x Pulmão (A Importância da Pressão Esofágica):
        - A Pressão de Platô distende o sistema inteiro (Pulmão + Parede). Geralmente a proporção é 80% para o pulmão e 20% para a parede.
        - Exceções críticas: Obesidade mórbida, ascite severa ou Síndrome Compartimental Abdominal. Nesses casos, > 20% da pressão do Platô é absorvida pela parede. O pulmão pode estar sofrendo menos pressão do que o visor indica.
        - Diagnóstico de certeza: Instalação de balão esofágico para medir a pressão pleural e derivar a Pressão Transpulmonar.

## Driving Pressure (Pressão de Distensão)

- **A *Driving Pressure* (DP) é o principal e mais forte preditor de mortalidade e Lesão Pulmonar Induzida pela Ventilação (VILI). Deve ser mantida rigorosamente < 15 cmH2O.**
    - Cálculo da Driving Pressure: DP = Pressão de Platô - PEEP (Também expressa como Vt / Complacência).
    - Significado Clínico:
        - É a relação entre o Volume Corrente que você configurou e o tamanho real do pulmão disponível (Complacência).
        - Valores > 15 cmH2O indicam sobredistensão grave e mandam reduzir o Volume Corrente.
    - Trade-offs e Ajustes Compensatórios (Efeito do Baixo Vt):
        - Baixar o Volume Corrente causa hipercapnia.
        - Red Flag da Hipercapnia Aguda: Aumento abrupto da pCO2 induz vasoconstrição pulmonar grave, podendo precipitar falência de VD/Cor Pulmonale e infecções a longo prazo.
        - Resolução: Aumentar a Frequência Respiratória (FR). 
            - O limite de segurança da FR: Baixar a Driving Pressure é muito mais protetor do que os danos de uma FR alta (Proporção de proteção é de 4:1. Baixar 1 ponto na DP compensa os riscos de aumentar a FR em 4 irpm).
    - Flexibilização do Vt (Elastância Normalizada):
        - Se a Driving Pressure do paciente já estiver em zonas muito seguras (normalizadas), não há benefício adicional em manter o Vt restrito à força (isso gera risco desnecessário de atelectasias e necessidade de sedação profunda). A ventilação pode e deve ser individualizada.

## Auto-PEEP (PEEP Intrínseca) e Retenção de Ar

- **A presença de fluxo no exato momento em que uma nova inspiração vai começar (a curva de fluxo expiratório não zera) é o sinal diagnóstico de Auto-PEEP.**
    - Fisiopatologia Básica: O fluxo expiratório normal deve ser uma curva de decaimento exponencial. Se a curva "corta" antes de zerar, existe gradiente de pressão retido (A pressão alveolar é maior que a pressão medida no ventilador).
    - Mensuração:
        - Requer uma Pausa Expiratória (fechamento das válvulas ao final da expiração) no paciente passivo.
        - O valor medido estabilizado na tela é a PEEP Total. Auto-PEEP = PEEP Total - PEEP configurada.
    - Manifestações Hemodinâmicas Severas:
        - Auto-PEEP alta atua como uma PEEP externa maciça (Ex: 15 cmH2O extras), comprimindo o retorno venoso, causando hipotensão severa, baixo débito cardíaco e oligúria (frequentemente a primeira suspeita que leva ao diagnóstico).
    - Diferenciando as Duas Causas de Auto-PEEP:
        - 1. Aumento da Constante de Tempo (Comum na DPOC/Asma): 
            - Ocorre por alta resistência e alta complacência. O pulmão demora muito para esvaziar (pode precisar de até 3 a 4 constantes de tempo para exalar >96% do ar).
            - Conduta: Aumentar o Tempo Expiratório (Reduzindo a Frequência Respiratória e diminuindo o Tempo Inspiratório).
        - 2. Limitação de Fluxo Expiratório (Colapso Dinâmico):
            - As pequenas vias aéreas colapsam na expiração.
            - Padrão gráfico característico: A curva de fluxo expiratório apresenta um pico inicial alto (esvaziamento das vias grandes) seguido abruptamente por um achatamento quase total e contínuo.
            - Conduta: Ao contrário da primeira causa, dar mais tempo expiratório é ineficaz, porque o fluxo já está quase nulo. É necessário tratar a causa base ou titular PEEP externa cuidadosamente para "stentar" as vias aéreas abertas.