# Monitoramento_do_Preco_da_Cesta_Basica
O programa solicita ao operador o tipo de produto, bem como os valores anterior e atual, para informar ao cliente se houve aumento, redução ou manutenção no preço de mercado
Inicio
- // Seção de Comandos, procedimento, funções, operadores etc.
- ESCREVAL( "NOME DO PRODUTO: ARROZ, FEIJÃO, OLEO OU AÇUCAR:" ) LEIA(PRODUTO)
- ESCREVAL( "QUAL O PREÇO ANTERIOR:")
- LEIA(PRECO_ANTERIOR)
- ESCREVAL( "QUAL O VALOR ATUAL:")
- LEIA(PRECO_ATUAL) VARIACAO <- ( (PRECO_ATUAL - PRECO_ANTERIOR) / PRECO_ANTERIOR )* 100
- ESCREVAL("VARIAÇÃO FOI DE:", VARIACAO, "%")
- SE VARIACAO > 0 ENTAO SITUACAO <- "AUMENTO"
- SENAO
- SE VARIACAO < 0 ENTAO SITUACAO <-"QUEDA"
- SENAO VARIACAO =0 SITUACAO <- "ESTÁVEL"
- FIMSE
- FIMSE
- ESCREVAL ("NOME DO PRODUTO: ", PRODUTO)
- ESCREVAL ("PREÇO ANTERIOR: ", PRECO_ANTERIOR)
- ESCREVAL ("PREÇO ATUAL: ", PRECO_ATUAL)
- - ESCREVAL ("VARIAÇÃO: ", VARIACAO, "%")
- ESCREVAL ("SITUAÇÃO: ", SITUACAO)
- Fimalgoritmo
