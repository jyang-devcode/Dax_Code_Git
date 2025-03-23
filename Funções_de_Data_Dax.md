<b>*TODAY/NOW – Retorna a data ou data e hora atual*</b>
<br>
DataHoje = TODAY()
<br>
HoraAgora = NOW()
<br><br>
<b>*YEAR / MONTH / DAY – Extrai partes da data*</b>
<br>
AnoVenda = YEAR(Vendas[Data])
MesVenda = MONTH(Vendas[Data])
<br><br>
<b>*DATEDIFF – Calcula a o número de dias entre uma data e outra informada*</b>
<br>
DiasEntrega = DATEDIFF(Vendas[DataVenda], Vendas[DataEntrega], DAY)
<br><br>
<b>*EOMONTH – Retorna o último dia do mês com deslocamento*</b>
<br>
FimDoMes = EOMONTH(TODAY(), 0)
