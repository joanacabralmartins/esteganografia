Para desvendar o primeiro caractere:

altere o código do primeiro bloco para #fe0101, converta de hexadecimal para binário e separe os três bits menos significativos de cada byte;
não altere nada no segundo bloco, mas também converta de hexadecimal para binário e separe os três bits menos significativos de cada byte;
altere o código do terceiro bloco para #0100ff, converta de hexadecial para binário e separe apenas os bits menos significativos dos dois primeiros bytes. 
junte todos os bits separados até então e terá o binário do primeiro caractere

Para desvendar o segundo caractere:

altere o código do quarto bloco para #feff01, converta de hexadecimal para binário e separe os três bits menos significativos de cada byte;
altere o código do quinto bloco para #fe01ff, converta de hexadecimal para binário e separe os três bits menos significativos de cada byte;
altere o código do sexto bloco para #01ffff, converta de hexadecial para binário e separe apenas os bits menos significativos dos dois primeiros bytes. 
junte todos os bits separados até então e terá o binário do segundo caractere

Para desvendar o terceiro caractere:

altere o código do sétimo bloco para #000001, converta de hexadecimal para binário e separe os três bits menos significativos de cada byte; 
altere o código do oitavo bloco para #8a0000, converta de hexadecimal para binário e separe os três bits menos significativos de cada byte; 
altere o código do nono bloco para #4a0180, converta de hexadecial para binário e separe apenas os bits menos significativos dos dois primeiros bytes. 
junte todos os bits separados até então e terá o binário do terceiro caractere 

Por último, junte todos os caracteres e terá formado um apelido (nome teria ficado bem extenso)
