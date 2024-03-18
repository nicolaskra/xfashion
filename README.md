# Xfashion
* Dashboard comercial - desafio Xperium Case:
 ![image](https://github.com/nicolaskra/xfashion/assets/144272226/617f093e-2519-4cfa-b3f4-75978575181f)

# Link dashboard https://app.powerbi.com/view?r=eyJrIjoiMGQzMGYyMjgtODczZi00MzA5LWExNDUtNGE3NWI5NTAyYzMzIiwidCI6IjM1ZmZkMDk1LTM4MWQtNDA3MC1hOGM1LTIwOGJhYzgzNTMwOSJ9&pageName=ReportSection

* Ápos importar os arquivos que estavam em formato CSV, foi observado que estavam praticamente todos prontos para serem utilizados, já com uma tabela Fato e as dimensões bem organizadas, apenas sendo necessário alguns ajustes na dCalendario para criar o contexto de TriAno e MêsAno.

* Verificando os relacionamentos e por os arquivos estarem bem estruturados teve o reconhecimento automático do Power Bi.

![image](https://github.com/nicolaskra/xfashion/assets/144272226/39267b55-f874-475a-9436-99a99e5b2229)

* Também criei novas tabelas manuais para criar seletor de medidas dinamicos permitindo assim uma análise mais completa e totalmente dinamica.

  ![image](https://github.com/nicolaskra/xfashion/assets/144272226/21d5f43a-4e36-476b-9c1d-0166069acc7f)




# Medidas DAX
* Foram utilizadas várias fórmulas e combinações para alcançar resultados e criar contextos. Todas organizadas por pastas para facilitar a identificação

![image](https://github.com/nicolaskra/xfashion/assets/144272226/7e736390-bc8a-4418-83f0-f385a8780021)

# Faturamento - Fórmula CALCULATE
![image](https://github.com/nicolaskra/xfashion/assets/144272226/51c729eb-f43c-4dc1-9bdb-a2ffdf766ae2)

# Formatação Fórmulas IF, NOT, ISBLANK 
![image](https://github.com/nicolaskra/xfashion/assets/144272226/a2aebe68-0717-470d-846f-f9244fb6c081)

# Percentuais Fórmulas CALCULATE, DIVIDE, ALL e VÁRIAVEIS.
![image](https://github.com/nicolaskra/xfashion/assets/144272226/194784aa-4149-4f55-b795-663bd271b7c8)

# Quantidade - Fórmulas DISTINCTCOUNT, COUNT, CALCULATE, SAMEPERIODLASTYEAR, DATEADD
![image](https://github.com/nicolaskra/xfashion/assets/144272226/e544b9dc-9ee3-4173-8aaa-660cca7958dd)

# Ranking - Fórmulas IF, HASONEVALUE, RANKX, RANKXX, FILTER, ALL, VALUES, SELECTEDVALUE, MAX, TOPN, SUMMARIZE, FORMAT
![image](https://github.com/nicolaskra/xfashion/assets/144272226/d7bc4386-414e-4ec3-815d-2ec6f56840b1)

# Temporais - Fórmulas MAXX, VALUES, CALCULATE , DATEADD, DATESQTDE, SAMEPERIODLASTYEAR
![image](https://github.com/nicolaskra/xfashion/assets/144272226/a3b11dfd-147b-4651-9f53-13962364ddbe)

# Ticket Médio - Fórmulas DIVIDE, AVERAGEX
![image](https://github.com/nicolaskra/xfashion/assets/144272226/8a1d1f8c-d524-4f2e-9b9c-a61489182242)

# Seletor de medidas foram criados 4 tipos de seletores para deixar a análise mais dinamica e detalhada.

# Seletor tipo de comparação, como foi solicitado uma análise detalhada sobre o trimestre atual e o anterior foram criados 3 opções para análise, vs LY, vs LQ e vs NQ.
![image](https://github.com/nicolaskra/xfashion/assets/144272226/76aceef3-88ac-42bd-ba98-a5253dc9e7cc)
![image](https://github.com/nicolaskra/xfashion/assets/144272226/a784d77a-51db-4051-8146-7ab27ce525b8)
![image](https://github.com/nicolaskra/xfashion/assets/144272226/b19d831d-304b-4f0d-bf00-9500f7a04a7f)
* Na página 1 temos uma segmentação com seleção única a onde existem as opções de análise e também cartões com o contexto selecionado para ficar claro o que está sendo observado.


![image](https://github.com/nicolaskra/xfashion/assets/144272226/f4ab60c3-3b14-43d9-b7f0-c248a94712a5)
![image](https://github.com/nicolaskra/xfashion/assets/144272226/313bc436-6179-43ce-9e91-ba9263cfa9a0)![image](https://github.com/nicolaskra/xfashion/assets/144272226/75b0ed78-24ed-4f1c-a7e8-3a4c5db6e69e)

# Seletor Gênero diferente do seletor de comparação esse foi criado para conseguir uma análise geral ou escolher apenas um genero e analisar mais especificamente.
![image](https://github.com/nicolaskra/xfashion/assets/144272226/34b92a01-8b73-4268-98d7-ee0f0a9617bb)
![image](https://github.com/nicolaskra/xfashion/assets/144272226/3d59020c-b797-4a14-8eb6-25edb0ca934d)![image](https://github.com/nicolaskra/xfashion/assets/144272226/f29b23ce-3bbb-4f3c-8ae0-b44bc776d008)![image](https://github.com/nicolaskra/xfashion/assets/144272226/cee36dd9-2f73-40c6-99ed-720e8b46295e)
![image](https://github.com/nicolaskra/xfashion/assets/144272226/62813413-1748-4aef-b179-a377ae1272a6)


# Descrição Análise
# Pág 1 - Análise Temporal
![image](https://github.com/nicolaskra/xfashion/assets/144272226/40e443e3-965e-4883-93fd-ad02ae0fc738)


* Menu Retrátil com opção de escolha Trimestre/Ano, Categoria e Vendedor.
* Cards com o Faturamento e Vendas vs LY, LQ e NQ. Todos formatados de acordo com o valor, negativo = vermelho, positivo = verde.
* Abaixo dos cards gráfico com a variação percentual em relação ao mesmo período do LY. ToolTip com o melhor dia do contexto e pior dia, com o valor de venda e faturamento total atual e vs LY. O Mesmo para Vendas.
* Gráfico de Faturamento e Vendas por categoria, ambos com seletor de medidas como dito a cima.
* Gráfico de linhas por dia da semana para observamos a tendência de compra durante os dias. Também com ToolTip para observar melhor os detalhes.

# Pág 2 - Análise Gênero 
![image](https://github.com/nicolaskra/xfashion/assets/144272226/9a851a81-055a-4206-98fc-6e733161d689)

* Botão para escolha de análise por genero ou ambos
* Cards informativos com a quantidade de clientes de cada gênero e sua representividade dentro dos dados. Também trazendo qual o cliente que mais comprou em termos de valor.
* Gráfico de Fatumento, vendas por categoria e produtos(com ToolTipo para mais informações)

# Pág 3 - Análise produtos
![image](https://github.com/nicolaskra/xfashion/assets/144272226/d4ea2f30-bb29-4b17-996d-51bb38463133)

* Cards com as categorias e sua representatividade. Produtos de destaque dentro da categoria, Top 5 melhores produtos, Top5 piores produtos, quantidade de clientes por sexo e marca.

# DrillThrough  
* Neste aba que está oculta, podendo só ser acessada pelo campo onde tem Faturamento, temos matrizes que permitem observar bem mais especificamente o que aconteceu para o Faturamento cair tanto, e existe anotações com recomendações para o time comercial e DBA. Podemos análisar vários contextos diferentes e sempre com a infomração de qual contexto estamos.
![image](https://github.com/nicolaskra/xfashion/assets/144272226/0c3e10ad-9372-4ad4-81f0-7d64d7017bb0)


# Insights e respostas 
 Como estamos no Trimestre atual?

	◽ E se eu comparar o Trimestre atual com o Trimestre anterior? E com o mesmo Trimestre no ano passado?
  ◽ Estou no caminho certo para superar o Trimestre passado e o mesmo Trimestre no ano passado?
* R: vs LastQuarter - Atualmente por faturamento estamos menos de 1% positivo, mas vale ressaltar que não chegamos ao fim de fevereiro ainda então com certeza iremos superar tranquilamente o LastQuarter, em termos de quantidade estamos 2% abaixo.
* R: vs LastYear - Já em relação ao ano passado em faturamento estamos -13% e em vendas -16,26% porém como dito anterior faltam mais de uma mês para acabar o trimestre, comparando janeiro atual vs ly obtivemos um crescimento de 19% no faturamento e 16% em quantidade, já em fevereiro uma redução de -42% Faturamento e -46% em Vendas, vale observar o por que dessa variação tão alta?
	
	 ◽ O que causou a queda do faturamento no Trimestre anterior?
* R: Nota-se que Calçados teve a pior a variação totalizando -20,15%,  principalmente com a Marca2 que teve a pior perfomance com uma variação de -49,82% na receita, sendo mais preciso no Produto 33 uma redução de -81,63% saindo de R$2.127 para uma receita de R$390,85 também vale ressaltar que a Marca3 obteve uma variação de 316,67% com o Produto73, saindo de R$287,61 para R$1.198 Tivemos 7 marcas com variação negativa.
Já em Acessórios tivemos uma variação de -13,97% liderada por uma variação de -54,58% para a Marca9 reduzindo a receita de R$10.581 para R$4.806.
Temos 9 marcas dentro do contexto que tiveram variação negativa.
Já em Roupas tivemos uma variação positiva de 11,28% com 
destaque para a Marca2 liderando com um total de 100,52% com 5 marcas positivas destacando Produto59 com um crescimento de 255,56%.








