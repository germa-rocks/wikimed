---
publish: true
---


# Interpretação do Antibiograma e Otimização Farmacocinética/Farmacodinâmica (PK/PD)

## Princípios Básicos do Antibiograma e MIC

- **A Concentração Inibitória Mínima (MIC) é o pilar da classificação de suscetibilidade (Sensível, Intermediário, Resistente), mas não deve ser interpretada de forma isolada do sítio de infecção e da farmacocinética do paciente.**
    - O MIC reflete a menor concentração do antibiótico capaz de inibir o crescimento bacteriano *in vitro*.
    - **Os "Breakpoints" (pontos de corte epidemiológicos/clínicos) são dinâmicos e podem mudar com o tempo.**
        - Bactérias classificadas como "Sensíveis" no passado podem ser consideradas "Resistentes" hoje para o mesmo valor de MIC.
        - Isso ocorre porque as simulações matemáticas (ex: *Simulação de Monte Carlo*) demonstraram que as doses máximas seguras toleradas em humanos não conseguem atingir os alvos no sangue de forma eficaz para MICs mais altos, exigindo a redução do ponto de corte.
    - **A eficácia depende da penetração tecidual: o antibiótico precisa alcançar o MIC no local específico da infecção.**
        - **Infecções do SNC (Líquor):** Antibióticos (como cefalosporinas) penetram mal a barreira hematoencefálica. A concentração liquórica é muito menor que a sérica.
            - *Conduta:* Exige doses venosas significativamente maiores para garantir que a pequena fração que cruza a barreira seja superior ao MIC da bactéria.
        - **Infecções do Trato Urinário (Cistites):** Beta-lactâmicos, por exemplo, concentram-se ativamente na urina.
            - *Pérola Clínica:* Pode-se atingir concentrações urinárias de 1.000 a 5.000 mcg/mL. Portanto, mesmo bactérias com MICs altíssimos (sistemicamente "Resistentes") podem ser erradicadas na urina usando doses habituais.

## Padrões Farmacodinâmicos (A Interação Droga-Bactéria)

- **A escolha da dose e da forma de infusão depende se o antibiótico é "Concentração-Dependente" ou "Tempo-Dependente".**
    - **Drogas Concentração-Dependentes (Alvo: Cmax/MIC):** Exigem um pico de concentração elevado.
        - O pico (Cmax) deve atingir de **8 a 10 vezes o valor do MIC** para garantir morte bacteriana rápida e evitar resistência.
        - A persistência de níveis baixos prolongados não aumenta a eficácia e eleva a toxicidade.
        - *Exemplo Clássico:* **Aminoglicosídeos** (Gentamicina, Amicacina).
    - **Drogas Tempo-Dependentes (Alvo: T > MIC):** Exigem que a concentração sérica se mantenha constante acima do MIC durante a maior parte do intervalo entre as doses.
        - Atingir picos elevadíssimos (Cmax alto) não melhora a eficácia ("dar um soco forte não adianta; precisam ser socos contínuos").
        - O alvo terapêutico exige que o tempo acima do MIC seja de **40% a 60% do intervalo entre as doses** (idealmente chegando perto de 100% em pacientes graves).
        - *Exemplos Clássicos:* **Beta-lactâmicos** (Penicilinas, Cefalosporinas, Carbapenêmicos).
    - **Drogas Área Sob a Curva-Dependentes (AUC/MIC):** Perfil intermediário, onde importa a exposição total à droga (pico e tempo conjugados).

## Otimização de Terapia na Prática Clínica (Beira-Leito)

- **A manipulação da forma de administração pode resgatar a sensibilidade de bactérias com MICs limítrofes, tratar infecções difíceis e reduzir toxicidade e custos.**
    - **Aminoglicosídeos (Gentamicina/Amicacina): Usar preferencialmente em Dose Única Diária.**
        - *Eficácia:* Garante o pico alto necessário (Cmax > 8 a 10x o MIC).
        - *Redução de Toxicidade:* A nefrotoxicidade ocorre por acúmulo da droga nos túbulos renais. Doses fracionadas (ex: 8/8h) mantêm os receptores tubulares saturados o tempo todo.
        - *Red Flag:* Em infusão única diária, a concentração sérica da droga no momento "vale" (imediatamente antes da próxima dose) deve ser muito baixa para permitir que o tecido renal seja "limpo", evitando nefrotoxicidade.
    - **Beta-Lactâmicos (Piperacilina-Tazobactam, Meropenem, Cefepime): Usar em Infusão Prolongada (ex: 3h a 4h) ou Contínua.**
        - *Eficácia:* Aumenta drasticamente o Tempo acima do MIC (T>MIC). Infusões rápidas (30 min) geram um pico inútil seguido de queda rápida, deixando a bactéria livre do antibiótico no fim do intervalo.
        - *Resgate Terapêutico:* Permite tratar bactérias com MICs mais altos (Ex: *Pseudomonas* com MIC 8 ou 16 para Pip-Tazo, ou MIC 4 para Meropenem) que falhariam miseravelmente com a infusão tradicional de 30 min.
        - *Farmacoeconomia:* Permite a cura da infecção com doses totais diárias menores, diminuindo custos e eventos adversos.
            - *Exemplo Prático:* Em vez de Pip-Tazo 4.5g de 6/6h, pode-se usar doses menores (ex: 3.375g) ou intervalos maiores em infusão contínua, atingindo quase 100% de sucesso terapêutico nas simulações preditivas.

## Farmacocinética Clínica: Impacto do Paciente Grave

- **Alterações fisiológicas de pacientes críticos (aumento de Vd ou variação do Clearance) destroem a previsibilidade das doses padrão de bula.**
    - **Aumento do Volume de Distribuição (Vd):** Ocorre em pacientes sépticos, grandes edemaciados ("terceiro espaço").
        - *Impacto:* Antibióticos hidrofílicos (como Beta-lactâmicos e Aminoglicosídeos) fogem do vaso e se diluem na água extravascular.
        - *Consequência:* O pico sérico (Cmax) cai substancialmente.
        - *Conduta:* Para garantir alcance terapêutico imediato, pode ser necessária uma **Dose de Ataque** mais alta, independentemente da função renal, para preencher esse "tanque" maior.
    - **Aumento do Clearance Renal (Hiperfiltração):** Ocorre no paciente séptico hiperdinâmico, politraumatizado ou grande queimado.
        - *Impacto:* A droga é filtrada e eliminada muito rapidamente (Clearance elevado).
        - *Consequência:* O tempo acima do MIC (T>MIC) despenca, gerando falha terapêutica precoce em beta-lactâmicos.
        - *Conduta:* Exige **aumento na frequência das doses** (encurtar o intervalo, ex: de 8/8h para 6/6h) ou o uso mandatório de **Infusões Contínuas/Prolongadas**.
    - **Diminuição do Clearance Renal (Lesão Renal Aguda / Insuficiência Renal):** 
        - *Impacto:* A droga acumula no organismo, facilitando a manutenção do T>MIC, mas aumentando exponencialmente o risco de toxicidade.
        - *Conduta:* **Aumentar o intervalo** entre as doses (ex: de 8/8h para 12/12h ou 24/24h) ou reduzir a dose de manutenção. *Atenção:* A primeira dose (ataque) geralmente não deve ser corrigida para a função renal, para garantir o pico inicial.