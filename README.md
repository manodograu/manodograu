programa {
  funcao inicio() {
    inteiro ano =0;

    escreva ("informe seu ano de nascimento\n")

    leia (ano)

    se (ano <= 2005){
      escreva ("Você pode votar esse ano")
    } senao {
      escreva ("Você não pode votar esse ano")
    }
  }
}








programa {
  funcao inicio() {
    inteiro x =0;
    inteiro y=0;

    escreva ("Por favor, informe um numero inteiro\n")

    leia (x)

    escreva ("Por favor, informe um numero inteiro\n")

    leia (y)

    se (x%y==0){
      escreva ("x é divisivel por y")
    } senao{
      escreva ("x não é divisivel por y")
    }
  }
}









programa {
funcao inicio() {
real produto_1 =0;
real produto_2 =0;
real produto_3 =0;

escreva ("por favor informe o valor do produto 1\n")

leia (produto_1)

escreva ("por favor informe o valor do produto 2\n")

leia (produto_2)

escreva ("por favor informe o valor do produto 3\n")

leia (produto_3)

se (produto_1 < produto_2 e produto_1 < produto_3) {
escreva ("O produto 1 é o mais barato")
} se (produto_2 < produto_1 e produto_2 < produto_3) {
escreva ("O produto 2 é o mais barato")
} se (produto_3 < produto_1 e produto_3 < produto_2) {
escreva ("O produto 3 é o mais barato")
}

}
}






programa {
 
     
    
  funcao inicio() {
    inteiro a = 0;
  

    escreva ("por favor informe um numero inteiro:\n")

   leia (a)
   

  se (a%7==0){
     escreva ("É multiplo de 7\n")
  }senao{
     escreva ("Não é multiplo de 7\n")
  }
    
    

  }
}








programa {
  funcao inicio() {
    real a = 0;
     real b = 0;

    escreva ("por favor informe um número:\n")

    leia (a)

    escreva ("por favor informe um número:\n")

    leia (b)

    escreva (a + b)

  


    
    

  }
}











programa {
  funcao inicio() {
    inteiro a = 0;
     inteiro b = 0;

    escreva ("por favor informe um numero inteiro:\n")

    leia (a)

    escreva ("por favor informe um numero inteiro:\n")

    leia (b)

    escreva (a * b)

  


    
    

  }
}
