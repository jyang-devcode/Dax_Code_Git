/*TODAY/NOW – Retorna a data ou data e hora atual*/
DataHoje = TODAY()
HoraAgora = NOW()

/*YEAR / MONTH / DAY – Extrai partes da data*/
AnoVenda = YEAR(Vendas[Data])
MesVenda = MONTH(Vendas[Data])

/*DATEDIFF – Calcula a o número de dias entre uma data e outra informada*/
DiasEntrega = DATEDIFF(Vendas[DataVenda], Vendas[DataEntrega], DAY)

/*EOMONTH – Retorna o último dia do mês com deslocamento*/
FimDoMes = EOMONTH(TODAY(), 0)