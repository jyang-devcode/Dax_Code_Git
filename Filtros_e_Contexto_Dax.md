//CALCULATE – Aplica cálculos com contextos informados
<br>
TotalVendasEstado = CALCULATE(SUM(Vendas[Valor]), Vendas[Estado] = "SP")
<br><br>
//FILTER – Aplica filtro em tabela informada
<br>
ClientesVIP = FILTER(Clientes, Clientes[Compras] > 1000)
<br><br>
//ALL – Remove filtros do contexto
<br>
TotalVendasGeral = CALCULATE(SUM(Vendas[Valor]), ALL(Vendas))
<br><br>
//ALLEXCEPT – Mantém filtros com exceções - Em exemplo os filtros são retirados com exceção da coluna Categoria 
<br>
TotalPorCategoria = CALCULATE(SUM(Vendas[Valor]), ALLEXCEPT(Vendas, Vendas[Categoria]))
<br><br>
//KEEPFILTERS – Mantém os filtros aplicados apenas para o contexto
<br>
VendasFiltradas = CALCULATE(SUM(Vendas[Valor]), KEEPFILTERS(Vendas[Produto] = "TV"))
