Algoritmo "AUTOESCOLA"


Var

atual,nasc,dirigir:inteiro


Inicio
      escreval ("--------Departamento de transito-------")
      escreva("ANO ATUAL (YYYY):  ")
      leia (atual)
      escreva("ANO DE NASCIMENTO (YYYY):    ")
      leia (nasc)
      escrevaL("------- STATUS -------")
      dirigir <- atual - nasc
      se>=18  entao
            escrevaL ("IDADE",  dirigir, ("Est� apto para dirigir"))
      senao
           escrevaL ("IDADE",dirigir,"Est� inapto para dirigir")
      Fimse
      




Fimalgoritmo