<b>*VALUES – Retorna valores distintos de uma coluna*</b>
<br>
ListaProdutos = VALUES(Vendas[Produto])
<br><br>
<b>*RELATED – Obtém valores da tabela informada em medida*</b>
<br>
PrecoProduto = RELATED(Produtos[Preco])
<br><br>
<b>*LOOKUPVALUE – Busca um valor específico em outra tabela*</b>
<br>
PrecoTV = LOOKUPVALUE(Produtos[Preco], Produtos[Nome], "TV")

