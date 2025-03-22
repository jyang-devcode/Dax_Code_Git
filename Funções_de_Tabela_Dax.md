/*VALUES – Retorna valores distintos de uma coluna*/
ListaProdutos = VALUES(Vendas[Produto])

/*RELATED – Obtém valores da tabela informada em medida*/
PrecoProduto = RELATED(Produtos[Preco])

/*LOOKUPVALUE – Busca um valor específico em outra tabela*/
PrecoTV = LOOKUPVALUE(Produtos[Preco], Produtos[Nome], "TV")

