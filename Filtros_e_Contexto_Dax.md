/*CALCULATE – Aplica cálculos com contextos informados*/
TotalVendasEstado = CALCULATE(SUM(Vendas[Valor]), Vendas[Estado] = "SP")

/*FILTER – Aplica filtro em tabela informada*/
ClientesVIP = FILTER(Clientes, Clientes[Compras] > 1000)

/*ALL – Remove filtros do contexto*/
TotalVendasGeral = CALCULATE(SUM(Vendas[Valor]), ALL(Vendas))

/*ALLEXCEPT – Mantém filtros com exceções - Em exemplo os filtros são retirados com exceção da coluna Categoria */
TotalPorCategoria = CALCULATE(SUM(Vendas[Valor]), ALLEXCEPT(Vendas, Vendas[Categoria]))

/*KEEPFILTERS – Mantém os filtros aplicados apenas para o contexto*/
VendasFiltradas = CALCULATE(SUM(Vendas[Valor]), KEEPFILTERS(Vendas[Produto] = "TV"))
