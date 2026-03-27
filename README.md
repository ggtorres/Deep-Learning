O DESAFIO:
A QuantumFinance está desejando construir um fundo de ações baseado em
modelos de Deep Learning. A ideia é desenvolver um modelo que tenha como
saída a compra ou venda de um determinada ação baseado na movimentação
do mercado nos últimos 15 dias.
Inicialmente 4 ações foram selecionadas para análise:
• VALE3 – Vale do Rio Doce
• PETR4 – Petrobras
• BBAS3 – Banco do Brasil
• CSNA3 - Companhia Siderúrgica Nacional

O DESAFIO:
A empresa deseja um modelo de Deep Learning que seja um ‘perseguidor de
tendencia’, ou seja, se o papel sobe o modelo deve comprar, se o papel desce o
modelo deve vender.
Para isso a QuantumFinance contratou economistas que fizerem a rotulagem
dos dados baseado no valor de fechamento dos ativos. Inicialmente foi feita
uma suavização dos preços de fechamento, e por se tratar de um assunto
sigiloso, não foi informada a técnica de suavização utilizada. O próximo passo
foi realizar a rotulagem dia a dia, para verificar qual devemos comprar e qual
devemos vender como segue a imagem a seguir:

O DESAFIO:
Observe que na imagem anterior que as tendencias de alta estão rotuladas em
verde enquanto as tendencias de baixa em vermelho.
Com isso é possível gerar uma predição de compra ou venda para o dia
seguinte baseado nos últimos 15 dias de comportamento do mercado.

COMO RESOLVER O PROBLEMA:
Para cada um dos ativos listados será fornecido dois arquivos no formato csv,
um para treino e outro para testes. Todos conjuntos de treino começam em
janeiro de 2000 e o teste em meados de 2019 até dezembro de 2023.
Também será fornecido um arquivo no formato html mostrando a série de
preços, a suavização realizada bem como os rótulos de forma iterativa, como na
imagem anterior, apenas para facilitar a interpretação do problema.
