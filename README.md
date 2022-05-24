# projetoportugolmediafinal
Média final cálculo - no portugol studio

programa
{
	
	funcao inicio()
	{
	 real nota1, nota2, nota3, nota4, mediaFinal
          
	 
		escreva("digite sua priemira nota do semestre\n")
		leia(nota1)
		escreva("digite sua segunda nota do semestre\n")
		leia(nota2)
		escreva("digite sua terceira nota do semestre\n")
		leia(nota3)
		escreva("digite sua quarta e última nota do semestre\n")
		leia(nota4)

		mediaFinal=(nota1+nota2+nota3+nota4)/4
		limpa()

	  

		se(mediaFinal>=7)
		{
			escreva("parabéns você foi aprovado")
		}

		se(mediaFinal<7)
		{
			escreva("infelizmente você foi reprovado")
			
		}

         
		
		
		
	}
}
/* $$$ Portugol Studio $$$ 
 * 
 * Esta seção do arquivo guarda informações do Portugol Studio.
 * Você pode apagá-la se estiver utilizando outro editor.
 * 
 * @POSICAO-CURSOR = 378; 
 * @PONTOS-DE-PARADA = ;
 * @SIMBOLOS-INSPECIONADOS = ;
 * @FILTRO-ARVORE-TIPOS-DE-DADO = inteiro, real, logico, cadeia, caracter, vazio;
 * @FILTRO-ARVORE-TIPOS-DE-SIMBOLO = variavel, vetor, matriz, funcao;
 */
