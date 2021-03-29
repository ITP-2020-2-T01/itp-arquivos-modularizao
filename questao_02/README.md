#Questão 2

Um arquivo CSV (comma-separated-values) é um arquivo de texto que normalmente é utilizado para armazenar dados e importá-los/exportá-los a programas como Excel, Google Sheets, etc. Segue um exemplo simples desse tipo de arquivos:

```
CPF,nome,snome,endereço,telefone
11111,João,Pimentel,Av Salgado Filho 222,999 1234
22222,Maria,Silva,Av Roberto Freire 555,999 4321
33333,Augusto,Xavier,Av Tirol 222,999 2222
```

1. Crie um tipo estruturado para armazenar os dados de uma pessoa (CPF, nome, sobrenome, endereço e telefone)

2. Seu programa deve ler do usuário um número inteiro n e depois ler as informações de n pessoas:

* CPF
* Nome
* Sobrenome
* Endereço (sem vírgulas)
* Telefone

3. Depois, seu programa deve armazenar esses dados em um arquivo CSV.

4. A seguir, leia o conteúdo do arquivo criado no item anterior e imprima-o linha por linha.


#Exemplos de entrada / saída

Exemplo 1
```
3
11111
João
Pimentel
Av Salgado Filho 222
999 1234
22222
Maria
Silva
Av Roberto Freire 555
999 4321
33333
Augusto
Xavier
Av Tirol 222
999 2222
```
```
CPF,nome,snome,endereço,telefone
11111,João,Pimentel,Av Salgado Filho 222,999 1234
22222,Maria,Silva,Av Roberto Freire 555,999 4321
33333,Augusto,Xavier,Av Tirol 222,999 2222
```

Exemplo 2

```
4
1234
Camila
Gomes
Rua Praia de Ponta Negra
999 0000
4321
Rodrigo
Medeiros
Av Salgado Filho 111
999 2222
101010
Pedro
Oliveira
Rua Potengi 123
999 1212
556655
João
Pinheiro
Rua do Sol 10
999 4444
```
```
CPF,nome,snome,endereço,telefone
1234,Camila,Gomes,Rua Praia de Ponta Negra,999 0000
4321,Rodrigo,Medeiros,Av Salgado Filho 111,999 2222
101010,Pedro,Oliveira,Rua Potengi 123,999 1212
556655,João,Pinheiro,Rua do Sol 10,999 4444
```
