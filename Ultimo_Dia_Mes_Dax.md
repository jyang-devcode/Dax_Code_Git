/*Último dia do mês da data atual*/
EOMONTH(TODAY(), 0)

/*Último dia do mês seguinte*/
EOMONTH(TODAY(), 1)

/*Último dia do mês anterior*/
EOMONTH(TODAY(), -1)

/*Usando em uma coluna calculada*/
Último Dia do Mês = EOMONTH('Tabela'[DataVenda], 0)
