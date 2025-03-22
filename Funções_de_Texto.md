/*CONCATENATE – Junta strings ou values*/
NomeCompleto = CONCATENATE(Clientes[Nome], " " & Clientes[Sobrenome])

*/LEFT / RIGHT / MID – Extrai partes de uma string ou valor*/
PrimeiraLetra = LEFT(Clientes[Nome], 1)

/*SEARCH – Encontra a posição de um texto - Em exemplo a medida procura a letra A na culuna Nome*/
PosicaoA = SEARCH("A", Clientes[Nome], 1, 0)