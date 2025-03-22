//IF – Avalia uma condição aplicada na medida
<br>
Lucro = IF(Vendas[Lucro] > 500, "Alto", "Baixo")
<br><br>
//SWITCH – Assim como IF, avalia a condição informada, mas para múltiplas condições
<br>
CategoriaProduto = SWITCH(
    Produtos[Tipo],
    "Eletrônico", "Tecnologia",
    "Roupa", "Moda",
    "Outros"
)

