<b>*VAR – Declara uma variável*</b>
<br>
MediaVenda = VAR Total = SUM(Vendas[Valor])
RETURN Total / COUNT(Vendas[ClienteID])
<br><br>
<b>*SUMX – Soma valores com base em uma expressão*</b>
<br>
TotalVendas = SUMX(Vendas, Vendas[Quantidade] * Vendas[Preco])
<br><br>
<b>*FILTER + SUMX – Combina filtros com soma específica -  Em exemplo a soma é aplicada apenas em valores acima de 1000*</b>
<br>
VendasAltas = SUMX(FILTER(Vendas, Vendas[Valor] > 1000), Vendas[Valor])

