<b>*Último dia do mês da data atual*</b>
<br>
EOMONTH(TODAY(), 0)
<br><br>
<b>*Último dia do mês seguinte*</b>
<br>
EOMONTH(TODAY(), 1)
<br><br>
<b>*Último dia do mês anterior*</b>
<br>
EOMONTH(TODAY(), -1)
<br><br>
<b>*Usando em uma coluna calculada*</b>
<br>
Último Dia do Mês = EOMONTH('Tabela'[DataVenda], 0)
