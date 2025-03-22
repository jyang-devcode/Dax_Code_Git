/*IF – Avalia uma condição aplicada na medida*/
Lucro = IF(Vendas[Lucro] > 500, "Alto", "Baixo")

/*SWITCH – Assim como IF, avalia a condição informada, mas para múltiplas condições*/
CategoriaProduto = SWITCH(
    Produtos[Tipo],
    "Eletrônico", "Tecnologia",
    "Roupa", "Moda",
    "Outros"
)

