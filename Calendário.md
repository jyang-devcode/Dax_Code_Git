Calendario = 
ADDCOLUMNS(
    CALENDAR(DATE(2020, 1, 1), DATE(2025, 12, 31)),
    "Ano", YEAR([Date]),
    "Mês", MONTH([Date]),
    "Trimestre", QUARTER([Date]),
    "Dia da Semana", WEEKDAY([Date]),
    "Nome do Mês", FORMAT([Date], "MMMM")
)