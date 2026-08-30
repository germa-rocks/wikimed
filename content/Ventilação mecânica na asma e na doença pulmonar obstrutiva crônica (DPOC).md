---
publish: true
---

# Ventilação Mecânica em DPOC e ASMA
*Base de Conhecimento Rápido (Beira-Leito)*

# 1. Identificação Clínico-Epidemiológica
* **Indicação de UTI e IOT em Broncoespasmo: Presença de critérios de gravidade extrema ou risco iminente de óbito.**
	* Gravidade Clínica: Fala entrecortada, agitação, uso de musculatura acessória, taquipneia (FR > 30), taquicardia (FC > 120), SatO2 < 90% ou PEF < 50% do predito.
	* Risco Iminente (Indicação Imediata de IOT): Rebaixamento do nível de consciência (sonolência) e ausculta com pulmão silente.
	* Epidemiologia e Mortalidade: 
		* Asma: ~30% dos pacientes em UTI necessitam de IOT; mortalidade de 8%.
		* DPOC: Mortalidade atinge até 30% em pacientes de UTI (frequentemente associado a comorbidades sistêmicas).
		* 📎 Refs: JAMA 1995; 274: 1852-1857 / Am J Resp Crit Care Med 2003; 168(7):740-59.

# 2. Fisiopatologia e Mecânica Respiratória
* **Asma x DPOC: A Asma apresenta obstrução fixa com parênquima normal, enquanto a DPOC apresenta colapso expiratório com parênquima destruído.**
	* Asma: 
		* Dificuldade do ar entrar e sair (constrição + edema + hipersecreção + remodelamento).
		* Tolera pressão de pico mais alta ("difícil de entrar").
		* Risco de Auto-PEEP significativo.
	* DPOC: 
		* Obstrução não-fixa predominantemente expiratória (destruição de septos alveolares e colapso dinâmico das vias aéreas). O ar entra, mas não sai.
		* Complacência pulmonar inicialmente aumentada/variável.
		* Altíssimo risco de Auto-PEEP.
* **Mecânica Básica e Constante de Tempo (CT): Mínimo de 3 a 4 CTs são necessárias para o esvaziamento pulmonar seguro e prevenção de Auto-PEEP.**
	* Resistência (R): Fricção ao fluxo nas vias aéreas. `R = (Pressão de Pico - Pressão de Platô) / Fluxo`. (Normal: 3-10 cmH2O/L/s).
	* Complacência (C): Deformabilidade pulmonar. `C = Volume Corrente / (Pressão de Platô - PEEP)`. (Normal: 60-100 mL/cmH2O).
	* Constante de Tempo (CT): `CT = R x C`. O esvaziamento ocorre de forma exponencial.
		* 1 CT: Esvazia 63% do volume (resta 37%).
		* 3 CTs: Esvazia 95% do volume (resta 5%).

# 3. Estratégia Ventilatória e Modos 
* **Modos Controlados (VCV ou PCV) são a escolha na fase aguda; VCV com fluxo descendente é preferível para garantir lavagem de CO2.**
	* Volume Controlado (VCV):
		* Garante Volume Corrente (Vt) estável independente das variações de resistência.
		* Diferenciação clara entre Pressão de Pico e Pressão de Platô.
		* ▶ **Setup preferencial:** Curva de fluxo descendente (distribui o fluxo, encurta o Ti e gera menor pressão de pico comparado à onda quadrada).
		* 🚨 **Red Flag:** Risco de pressões de pico inadvertidamente altas se o alarme não for bem ajustado (barotrauma).
	* Pressão Controlada (PCV):
		* Garante limite pressórico de segurança.
		* 🚨 **Red Flag:** Se a resistência subir, o Vt cai drasticamente, gerando hipoventilação letal (hipercapnia).
* **Pressões Alvo: Pressão de Pico > 50 cmH2O é tolerável na Asma, desde que a Pressão de Platô permaneça < 30 cmH2O.**
	* Na asma, a alta resistência dissipa a pressão nas vias aéreas centrais. Essa energia pressórica elevada não atinge o alvéolo, poupando o parênquima (se o Platô estiver controlado).

# 4. Ajuste de Parâmetros à Beira-Leito
* **Volume Corrente (Vt): Alvo inicial de 6 a 8 mL/kg de peso ideal; tolerável até 10 mL/kg para lavagem agressiva de CO2.**
	* O problema principal em pacientes obstrutivos intubados não é oxigenação, é **Hipercapnia**.
	* Fisiologia: `Ventilação Alveolar = FR x (Vt - Espaço Morto)`. Vt elevado diminui a PaCO2.
	* Limite de segurança: Em pacientes sem SDRA, Vt de até 10 mL/kg demonstrou-se seguro para lavagem de CO2.
	* 📎 Refs: PReVENT Trial. JAMA. 2018;320(18):1872-1880.
* **Relação I:E (FR e Ti): O objetivo central é maximizar o Tempo Expiratório (TE) mantendo o Volume Minuto, porém o limite útil do TE é 4 a 5 segundos.**
	* Como maximizar o TE:
		* 1º Passo: Reduzir o Tempo Inspiratório (Ti). Em VCV: aumentar o fluxo (monitorando a P. Pico). Em PCV: ajustar Ti para 0,5 a 0,6 s.
		* 2º Passo: Reduzir a Frequência Respiratória (FR). 
	* Titulação da FR (A busca do Ponto Ótimo):
		* Aumente a FR o máximo possível (para lavar CO2) até o limite onde a curva de fluxo expiratório quase toca a linha de base (zero).
		* Frequências habituais ficam baixas: 10 a 16 irpm.
	* 🚨 **Red Flag (O Limite do TE):** Aumentar o TE infinitamente abaixando a FR para 6-8 irpm diminui drasticamente o Volume Minuto, agravando severamente a hipercapnia, com ganho irrisório na redução da Auto-PEEP. Tempos > 5 segundos são fúteis.
	* 📎 Refs: Intensive Care Med (2006) 32:501–510 / CHEST 2018; 154(4):948-962.
* **Manejo de PEEP: Utilize PEEP baixa (< 5 cmH2O) como regra. Na DPOC, PEEP pode ser titulada a 80% da Auto-PEEP para aliviar o esforço de disparo.**
	* Cálculo da Auto-PEEP: Realizar pausa expiratória prolongada (paciente sedado/curarizado, sem drive). Auto-PEEP = PEEP Total medida.
	* Na DPOC (Doença Dinâmica com colapso): 
		* A presença de Auto-PEEP cria uma "carga limiar" (ex: Auto-PEEP 10 + Trigger -2 = Esforço necessário de 12).
		* PEEP extrínseca empurra a linha de base. Se PEEP = 8, o esforço de disparo cai de 12 para 4. Melhora disparo ineficaz e reduz trabalho respiratório.
	* Na Asma: 
		* Em geral, manter PEEP de 0 a 5 cmH2O. Pode piorar o esvaziamento.
	* 🚨 **Red Flag:** Avalie a Auto-PEEP de forma rotineira, pois o broncoespasmo é dinâmico e cede com a terapia.
* **Ajuste de FiO2: Alvos de saturação diferem radicalmente: Asma (90-94%) vs. DPOC (88-92%).**
	* Na DPOC, hiperoxigenação agrava a retenção de CO2 e causa rebaixamento severo (Carbonarcose).
	* Tríade fisiopatológica do malefício do O2 na DPOC:
		1. Piora aguda do distúrbio V/Q (Principal mecanismo): O oxigênio inibe a Vasoconstrição Pulmonar Hipóxica (VPH), desviando sangue para alvéolos destruídos e anulando a troca de CO2.
		2. Efeito Haldane: O2 desloca CO2 da hemoglobina para o plasma.
		3. Inibição do drive respiratório periférico.

# 5. Otimização Mecânica e Terapia Inalatória
* **Redução de Espaço Morto Instrumental: Remova extensores, traqueias ou filtro HME se houver hipercapnia refratária.**
	* Fisiopatologia: Tudo que se encontra entre a peça em "Y" do ventilador mecânico e o tubo orotraqueal do paciente representa espaço morto (ventilado, mas não perfundido). 
	* Uma simples traqueia ("cateter mount") combinada a um filtro HME pode roubar até 75 mL do seu Volume Corrente estabelecido.
* **Terapia Inalatória na VM: Utilize MDI (Puff) ou espaçador a 20-30 cm da peça em Y, no ramo inspiratório.**
	* Nebulizadores comuns de copinho geram macrogotas que não penetram na via aérea distal intubada.
	* Dosagens escalonadas: Utilize doses dobradas/triplicadas do Beta-2 (ex: 4 a 8 puffs por ciclo).
	* Acionamento: Administre o puff no final da expiração / transição para a inspiração.
	* 🚨 **Red Flag:** Remover obrigatoriamente o filtro HME antes da administração. Caso contrário, todo o fármaco será retido pelo filtro.

# 6. Cuidados Globais Não-Ventilatórios
* **O manejo transcende o ventilador: Hemodinâmica, Sedação e Balanço metabólico são essenciais.**
	* Sedação: Indução profunda inicial (ou bloqueador neuromuscular) para acoplamento e redução do consumo de O2. Realizar protocolo de despertar diário assim que houver alívio do broncoespasmo.
	* Hemodinâmica: Vigiar hipotensão grave. Auto-PEEP severa comprime a veia cava e diminui drasticamente o retorno venoso e débito cardíaco.
	* Nutrição: Início precoce, mas evite hiperalimentação (excesso calórico e de carboidratos eleva o Quociente Respiratório e a produção endógena de CO2).
	* Função Renal: Monitorar e tratar rapidamente acidoses metabólicas sobrepostas, que colapsam ainda mais o pH sistêmico no paciente hipercápnico.

# 7. Resumo (Checklist de Setup Inicial à Beira-Leito)
* **Checklist de Prescrição Rápida (Asma / DPOC):**
	* **Modo:** VCV preferencial (ou PCV).
	* **Vt:** 6 a 10 mL/kg (Visar o maior limiar seguro para lavar CO2).
	* **Tempo Insp (Ti):** Curto. Ajustar fluxo entre 60-80 L/min (curva descendente).
	* **Tempo Exp (Te):** Maximizável até 4 a 5 segundos, guiado pela curva de fluxo.
	* **Frequência Respiratória:** 10 a 16 irpm.
	* **PEEP:** Asma (0 a 5 cmH2O) / DPOC (5 cmH2O ou até 80% da Auto-PEEP).
	* **Alvo de SatO2:** Asma (> 90%) / DPOC (88 a 92%).
	* **Pressão de Platô Alvo:** < 30 cmH2O.