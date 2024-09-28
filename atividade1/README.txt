Interpretação dos Resultados e Conclusão

1) AIC (Akaike Information Criterion) é uma medida que ajuda a comparar diferentes modelos de regressão logística, equilibrando a qualidade do ajuste do modelo e sua complexidade. Um valor de AIC mais baixo indica um modelo melhor, isto é, um modelo robusto, equilibrando a precisão das previsões com a simplicidade do modelo, tornando-o mais adequado para aplicações práticas, pois é mais fácil de interpretar na prática clínica. Com base nas variáveis incluídas no modelo abordado, um AIC de 712.7357 sugere que ele é adequado para prever a presença ou ausência da doença cardíaca. Como ele não foi comparado com outros, pode-se concluir que o modelo atual é apropriado, devido ao equilíbrio que o AIC sugere entre simplicidade e ajuste, o que o torna uma escolha razoável para a previsão de doenças cardíacas.

2) Identificação de Fatores de Risco Mais Relevantes:
Os fatores de risco mais relevantes são aqueles cujos coeficientes na regressão logística apresentam maior magnitude (positiva ou negativa) e são estatisticamente significativos. Vamos revisar os fatores que foram incluídos no modelo:

Idade (age): Geralmente, à medida que a idade aumenta, o risco de doença cardíaca também aumenta. Isso se reflete em um coeficiente positivo para a idade, indicando uma maior probabilidade de diagnóstico de doença cardíaca em indivíduos mais velhos, ou seja, idosos pois são mais propensos a desenvolver doenças cardíacas devido à degeneração natural das artérias e outros fatores relacionados ao envelhecimento.

Sexo (sex): O coeficiente associado ao sexo pode indicar diferenças de risco entre homens e mulheres. Geralmente, homens têm um risco maior de desenvolver doença cardíaca em várias faixas etárias, o que pode ser explicado por fatores hormonais e de estilo de vida, o que se reflete em um coeficiente positivo para o sexo masculino.

Tipo de dor no peito (cp): Este é um dos fatores mais importantes. Tipos de dor no peito associados a angina (tipicamente 1 ou 2 no dataset) tendem a ser indicativos fortes de risco de doença cardíaca, o que deve resultar em coeficientes significativos.

Colesterol (chol): Níveis elevados de colesterol são um conhecido fator de risco para doença cardíaca, pois estão associados ao acúmulo de placas nas artérias, um fator de risco primário para doenças cardiovasculares. Se o coeficiente for positivo e significativo, isso reforça a necessidade de controle do colesterol em pacientes.

Frequência cardíaca máxima (thalach): A frequência cardíaca máxima pode ter uma relação inversa com a probabilidade de doença cardíaca (ou seja, coeficiente negativo), indicando que indivíduos com frequências cardíacas máximas mais baixas podem ter maior risco, isso porque uma frequência cardíaca maior pode ser um sinal de boa aptidão cardiovascular.

Número de vasos principais (ca): O número de vasos principais coloridos por fluoroscopia é um importante preditor de doença cardíaca, porque indica a extensão e a gravidade da obstrução nas artérias coronárias. Coeficientes significativos aqui indicam que esse fator tem forte influência no diagnóstico.

3) Insights que podem ser usados em prática clínica:
Identificação de Pacientes de Alto Risco: O modelo pode ser utilizado para identificar pacientes com maior probabilidade de desenvolver doença cardíaca com base nos fatores como idade, sexo, e resultados de exames, permitindo uma triagem mais precisa.

Intervenção Precoce: Com a identificação dos principais fatores de risco, médicos podem recomendar mudanças no estilo de vida (como controle do colesterol e aumento da atividade física) para reduzir o risco antes que a doença se manifeste.

Foco em Educação e Prevenção: Campanhas de saúde pública podem ser direcionadas aos fatores mais relevantes, como incentivar exames regulares de colesterol e promover o tratamento precoce para sintomas como dor no peito.

4) Insights que podem ser usados em futuros estudos:
Exploração de Novos Fatores: Embora variáveis como colesterol e idade sejam bem estudadas, futuros estudos podem investigar variáveis adicionais ou comportamentais, como níveis de atividade física e fatores socioeconômicos.

Esses insights fornecem uma base para melhorar tanto a prática clínica (prevenção/tratamento da doença e monitoramento do paciente) quanto para orientar pesquisas futuras na prevenção e tratamento da doença cardíaca, como o fator genêtico que não deve ficar de fora, pois há casos que pacientes jovens quando têm o índice de colesterol alto e são orientados inicialmente a fazer atividade física, sem medicação, o índice não diminui e pacientes que sofrem um grande impacto emocional (ou que possuem hipertiroidismo) desenvolvem frequência cardíaca descontrolada (arritmia cardíaca) e precisam tomar medicamento para o resto da vida.
