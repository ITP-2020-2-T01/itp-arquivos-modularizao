# Questão 3

Escreva um programa que leia um arquivo CSV contendo as notas dos alunos de uma turma e calcule a media e o status de aprovação. O aluno é considerado aprovado caso sua média seja maior ou igual a 5 e não possua notas menores que 3.

Seu programa deverá receber como parâmetros de linha de comando:

* -i arquivo\_de\_entrada

* -o arquivo\_de\_saida

## Exemplo:

Linha de execução do código(linux):
```shell
./media -i itp.csv -o itp_media.csv
```
Exemplo de arquivo de entrada:
```
matrícula,nome,nota1,nota2,nota3
20200001,Fulano dos Anzois,4.5,5.1,3.3
20200002,Beltrana das Cachoeiras,6.5,6.6,6.4
20200003,Sicrano Beltrano Jr.,5.0,6.0,4.0
20200004,Beltrano Glorioso,9.0,9.0,3.0
```
Exemplo de arquivo de saída:
```
matrícula,nome,média,status
20200001,Fulano dos Anzois,4.3,reprovado por média
20200002,Beltrana das Cachoeiras,6.5,aprovado
20200003,Sicrano Beltrano Jr.,6.0,aprovado
20200004,Beltrano Glorioso,7.0,aprovado
```
