# Compilador-C-Sharp-UFMT-2021-1
O compilador foi feito usando C# e utilizei o Visual Studio 2019


Nome: José Henrique S. Rodrigues     

O compilador foi feito usando C# e utilizei o Visual Studio 2019 para a parte de programação, já o autómato do analisador léxico e a gramática com as regras semânticas eu fiz no papel e tirei fotos que irei deixar disponível aqui junto ao trabalho e no GitHub.

O código usado nos testes foi o exemplo.lalg.txt mais que deve ser inserido de forma dinamica ao iniciar o programa ou copiando para a janela do trabalho:

program teste
	var a, b : real;
	var c, d : integer;
begin 
	read(a);
	read(c);
  b := a * a + a;
  d := 2*c + c;
  if a > b then
  	write(a)
  else
  	write(b)
  $;
  if d < c then
  	write(d)
  else
  	write(c)
  $
end.
