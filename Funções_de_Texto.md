<b>*CONCATENATE – Junta strings ou values*</b>
<br>
NomeCompleto = CONCATENATE(Clientes[Nome], " " & Clientes[Sobrenome])
<br><br>
<b>*LEFT / RIGHT / MID – Extrai partes de uma string ou valor*</b>
<br>
PrimeiraLetra = LEFT(Clientes[Nome], 1)
<br><br>
<b>*SEARCH – Encontra a posição de um texto - Em exemplo a medida procura a letra A na culuna Nome*</b>
<br>
PosicaoA = SEARCH("A", Clientes[Nome], 1, 0)
