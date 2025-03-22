/*VAR – Declara uma variável*/
MediaVenda = VAR Total = SUM(Vendas[Valor])
RETURN Total / COUNT(Vendas[ClienteID])

/*SUMX – Soma valores com base em uma expressão*/
TotalVendas = SUMX(Vendas, Vendas[Quantidade] * Vendas[Preco])

/*FILTER + SUMX – Combina filtros com soma específica -  Em exemplo a soma é aplicada apenas em valores acima de 1000*/
VendasAltas = SUMX(FILTER(Vendas, Vendas[Valor] > 1000), Vendas[Valor])

