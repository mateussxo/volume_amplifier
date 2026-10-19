📝 Sobre o Projeto

O objetivo deste programa em C é modificar o volume de um ficheiro de áudio no formato WAV. O programa lê o cabeçalho do ficheiro original, copia-o para o novo ficheiro e, em seguida, altera o volume multiplicando cada amostra de áudio por um fator fornecido pelo utilizador.


💻 Como Executar

O programa exige três argumentos na linha de comandos para funcionar corretamente: o ficheiro de entrada, o ficheiro de saída e o fator de escala do volume.

./volume input.wav output.wav 2.0


Parâmetros:

input.wav: O ficheiro de áudio original (que quer alterar).

output.wav: O nome do novo ficheiro que será gerado.

2.0: O fator pelo qual o volume será multiplicado. Por exemplo, 2.0 duplica o volume, enquanto 0.5 reduz o volume para metade.
