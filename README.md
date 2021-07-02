# Segui-Linha-sBotics
seguidor de linha do sbotics

Linguagem = rEduc

inicio
	enquanto(verdadeiro) farei{
	se(cor(2)=="PRETO" e cor(4)=="PRETO") entao{
		frente(120)
	}
	se(cor(2)=="BRANCO" e cor(4)=="BRANCO") entao{
		frente(120)
	}
	se(cor(2)=="PRETO") entao {
		direita(800)
	}
	se(cor(4)=="PRETO") entao {
		esquerda(800)
	}
}
	
fim



///////////////////////////////////////////////////////


Linguagem = C#


/*
* wEduc
* https://weduc.natalnet.br
* (C) Copyright 2014-2021
* */

void Main()
{
    while (true) {
    if (bc.ReturnColor((int)(2-1)) ==  "PRETO"  && bc.ReturnColor((int)(4-1)) ==  "PRETO" ) {
    bc.MoveFrontal((float)120, (float)120); 
}

if (bc.ReturnColor((int)(2-1)) ==  "BRANCO"  && bc.ReturnColor((int)(4-1)) ==  "BRANCO" ) {
    bc.MoveFrontal((float)120, (float)120); 
}

if (bc.ReturnColor((int)(2-1)) ==  "PRETO" ) {
    bc.MoveFrontal((float)-(800), (float)(800)); 
}

if (bc.ReturnColor((int)(4-1)) ==  "PRETO" ) {
    bc.MoveFrontal((float)(800), (float)-(800)); 
}


}


}
