# Trabalho-Java-2-

##Diagrama de classes UML
                            _____________________________________
```Java                     |                                    
 __________________________ |     _________________    _________________________________
|           Gasto          |    |      Ganho      |    |           Relatório             |
|__________________________|    |_________________|    |_________________________________|
| - tipo                   |    | - tipo          |    | - gerarRelatorioDeGastos()      |
| - data                   |    | - data          |    | - gerarRelatorioDeGanhos()      |
| - valor                  |    | - valor         |    | - gerarRelatorioDeSaldoMensal() |
| - formaPagamento         |    |                 |    |                                 |
|__________________________|    |_________________|    |                                 |
                                         ⬇️            |_________________________________|
```                                      ⬇️                               ⬆️
                                         ⬇️                               ⬆️
                                         ⬇️➡️➡️➡️➡️➡️➡️➡️➡️➡️➡️➡️➡️➡️➡️⬆️
                                       
