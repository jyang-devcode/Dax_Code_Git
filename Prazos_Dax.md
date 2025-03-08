Prazo Vigente = 
CALCULATE(
    MAX( 'TabPrazos'[Prazo (dias úteis)]), 
    FILTER( 
            'TabPrazos, 
            'TabelaPrincipal'[Data]>= 'TabPrazos'[PrazoInicioVigente]&& 
                        'TabelaPrincipal' [Data]<= 'TabPrazos' [PrazofimVigente])
    )
