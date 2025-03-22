//SUM - Soma os valores de uma coluna
<br>
TotalVendas = SUM(Vendas[Valor])
<br><br>
//AVERAGE - Calculos de média de uma coluna
<br>
MediaVendas = AVERAGE(Vendas[Valor])
<br><br>
//MIN / MAX – Menor ou maior valor de uma coluna
<br>
MenorPreco = MIN(Produtos[Preco])
MaiorPreco = MAX(Produtos[Preco])
<br><br>
//COUNT / COUNTA – Contagem de valores em uma coluna
<br>
TotalClientes = COUNT(Clientes[ID])
<br><br>
//DISTINCTCOUNT – Conta valores distintos em uma coluna
<br>
ClientesDistintos = DISTINCTCOUNT(Vendas[ClienteID])
