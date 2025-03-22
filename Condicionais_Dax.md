<b>*IF – Avalia uma condição aplicada na medida*</b>
<br>
Lucro = IF(Vendas[Lucro] > 500, "Alto", "Baixo")
<br><br>
<b>*SWITCH – Assim como IF, avalia a condição informada, mas para múltiplas condições*</b>
<br>
CategoriaProduto = SWITCH(
    Produtos[Tipo],
    "Eletrônico", "Tecnologia",
    "Roupa", "Moda",
    "Outros"
)

