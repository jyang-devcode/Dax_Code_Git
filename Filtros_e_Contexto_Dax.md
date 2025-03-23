<b>*CALCULATE – Aplica cálculos com contextos informados*</b>
<br>
TotalVendasEstado = CALCULATE(SUM(Vendas[Valor]), Vendas[Estado] = "SP")
<br><br>
<b>*FILTER – Aplica filtro em tabela informada*</b>
<br>
ClientesVIP = FILTER(Clientes, Clientes[Compras] > 1000)
<br><br>
<b>*ALL – Remove filtros do contexto*</b>
<br>
TotalVendasGeral = CALCULATE(SUM(Vendas[Valor]), ALL(Vendas))
<br><br>
<b>*ALLEXCEPT – Mantém filtros com exceções - Em exemplo os filtros são retirados com exceção da coluna Categoria*</b>
<br>
TotalPorCategoria = CALCULATE(SUM(Vendas[Valor]), ALLEXCEPT(Vendas, Vendas[Categoria]))
<br><br>
<b>*KEEPFILTERS – Mantém os filtros aplicados apenas para o contexto*</b>
<br>
VendasFiltradas = CALCULATE(SUM(Vendas[Valor]), KEEPFILTERS(Vendas[Produto] = "TV"))
