# MODELO DE PRECIFICAÇÃO HEDÔNICA ESPACIAL PARA TERRENOS COMERCIALIZADOS PELA COMPANHIA IMOBILIÁRIA DE BRASÍLIA

## 🏠 Resumo do Projeto

A precificação de imóveis, uma atividade antes restrita a especialistas, tem sido transformada pela tecnologia de sistemas autônomos com aprendizado de máquina. O projeto apresentado aqui utiliza regressão linear múltipla e um modelo de precificação hedônica para prever os preços prováveis de terrenos, levando em consideração múltiplas variáveis.

Este modelo foi desenvolvido especificamente para ajudar a Terracap, a Companhia Imobiliária de Brasília, a determinar valores para terrenos ofertados em licitação pública. Os resultados mostraram-se extremamente próximos dos valores efetivamente transacionados, provando ser uma ferramenta confiável e inovadora.

## 💻 Detalhes Técnicos

Abaixo, você encontrará alguns detalhes técnicos do projeto, que mostram o nível de complexidade e a diversidade de técnicas aplicadas:

### Configurações e Importações Iniciais

O código começa definindo configurações locais e formatos numéricos específicos. É feita a importação de bibliotecas relevantes como `pandas`, `numpy`, `matplotlib`, e outras que são essenciais para manipulação de dados e visualizações.

### Análise e Processamento dos Dados

Os dados são carregados a partir de um arquivo CSV, seguido de uma série de operações de limpeza e transformação. Algumas colunas são excluídas com base na alta correlação, enquanto outras são convertidas em categorias para facilitar o processamento.

### Visualização

Um histograma é gerado para visualizar a distribuição da variável dependente, `valor_oferta`. O código utiliza várias configurações de exibição para tornar o gráfico mais informativo, como escalas logarítmicas e formatação personalizada dos rótulos.

### Modelos Utilizados

O projeto inclui uma variedade de modelos de aprendizado de máquina e técnicas de pré-processamento, tais como `HistGradientBoostingRegressor`, `RandomizedSearchCV`, `xgboost`, e `lightgbm`. Isso destaca a complexidade e o cuidado na escolha de métodos para alcançar os melhores resultados.

## 🏢 Aplicação na Terracap

A precisão do modelo no período avaliado demonstrou o potencial na predição de valores de terrenos para a Terracap. Isso representa uma inovação notável no setor imobiliário, especialmente na licitação pública, minimizando distorções e perdas econômicas.

## 🎓 Contribuição Acadêmica

Este projeto foi desenvolvido como parte de uma dissertação de mestrado e contribui para a compreensão e aplicação de modelos hedônicos na precificação de imóveis. É um exemplo brilhante de como a ciência de dados pode ser aplicada em contextos práticos e de grande impacto.

## Conclusão

Com a combinação de análise de dados, aprendizado de máquina e visão estratégica, este projeto oferece uma nova abordagem na precificação de terrenos. Ele não apenas fornece insights valiosos para especialistas do setor imobiliário, mas também demonstra como a tecnologia pode transformar práticas tradicionais, tornando-as mais eficientes e precisas. 🚀
```

Espero que isso seja útil! Por favor, me avise se você precisa de mais ajuda. 😊
