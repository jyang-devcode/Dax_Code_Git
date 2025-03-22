/*SUM - Soma os valores de uma coluna*/
TotalVendas = SUM(Vendas[Valor])

/*AVERAGE - Calculos de média de uma coluna*/
MediaVendas = AVERAGE(Vendas[Valor])

/*MIN / MAX – Menor ou maior valor de uma coluna*/
MenorPreco = MIN(Produtos[Preco])
MaiorPreco = MAX(Produtos[Preco])

/*COUNT / COUNTA – Contagem de valores em uma coluna*/
TotalClientes = COUNT(Clientes[ID])

/*DISTINCTCOUNT – Conta valores distintos em uma coluna*/
ClientesDistintos = DISTINCTCOUNT(Vendas[ClienteID])