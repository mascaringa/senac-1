# senac
Curso de Desenvolvimento de Aplicativos Móveis 

Usando **DART** e **FLUTTER**

## Aula 1 - variáveis 

Espaço reservado em memória para armazenar um valor temporiamente

### Tipos de Variáveis

- **string** - textos
- **int** - números inteiros
- **double** - números decimais

### Variáveis
   
   * Um valor armazenado na memoria ram do computador,
   * que perde seu valor sempre que o PC é desligado.
   *  Seu valor pode ser modificado a qualquer momento.
   * 
   * Resumindo, a variavel é como uma caixa, onde eu guardo
   * um determinado valor, este valor podendo ser um numero,
   * um texto,um valor lógico (sim/nao), etc.

### Exemplo 1 - tipos de Variáveis
```

void(){
String nome = "Nathan";
int idade = 17;
double altura = 1.75;
}
```

### Exemplo 2 - Cálculo Simples
```
void main() { 
String nome, sobrenome, email;

nome = "Nathan" ;
sobrenome = "Bazon" ;
email = "nanabazon@gmail.com" ;
print("eai $nome $sobrenome seu email é $email" );


int anonasc;
anonasc = 2002;
int idade;
idade = 2019 - anonasc;
print(idade) ;

eai erik seu email é urangutango666@gmail.com
17
```

## aula 2 

**${renda_pessoa.toStringAsFixed(3)}**



```dart



String nome, sobrenome, email, senha, cpf, data_nasc, endereco, sexo, celular, curso;
 
 int ano_nasc, idade, qtd_moradores;
  
 double renda_familiar, renda_pessoa;
  
 nome = "Erik gabriel";
 sobrenome = "zanetti";
 email = "urangutango666@gmail.com";
 senha = "ter************";
 cpf = "42436-63536";
 data_nasc = "01/02/2002" ;
 endereco = "amelia lise";
 sexo = "masculino"; 
 celular = "567688.756768";
 curso = "lixeiro";

 idade = 17;
 qtd_moradores=5;
 renda_familiar = 2500;
 renda_pessoa = renda_familiar / qtd_moradores;
   
   print("           ###########################");
   print("           CONFIRMAÇÃO DE CADASTRO"); 
   print("Nome: $nome $sobrenome");
   print("E-MAIL: $email");
   print("SENHA: $senha");
   print("CPF: $cpf");
   print("DATA_NASC: $data_nasc");
   print("ENDERECO: $endereco");
   print("SEXO: $sexo");
   print("CELULAR: $celular");
   print("CURSO: $curso");
   print("RENDA: $renda_familiar");
   print("IDADE: $idade");
   print("RENDA_PESSOA: R\$ ${renda_pessoa.toStringAsFixed(3)}");
   print("          ############################");


o IF serve para determinar se um bloco de instruções **deve** ou **não**
 ser execultado, pode-se dizer que senpre que for necessario 
**testar** algum valor usaremos o *if*

###OPERADORES LOGICOS

== igual
!= diferente
>= maior ou igual
<= menor ou igual
> maior 
< menor

###SINTAXE

```dart
if(teste_logico)
{
     //faz isso se o teste for verdadeiro 
}
else
{
    //fas isso se o teste for falso
}
```
### EXENPLO IF

```dart
string curso = "progamador android";

if(curso == "progamador android")
{
       print("parabens vc fes otima escolha");
}
else
{
      print("vacilão aposto que faz adm");
}
```
double  nota1, nota2, media;

nota1 = 3;
nota2 = 2;

media = (nota1 + nota2) / 2;
  
   
if(media >= 5)
{  
     print("PASSOU DE BIMESTRE BURRO FINALMENTE UM $media");
}
else
{
     print("REPITIU TROXA TOMA AI SEU $media");
} 
### AULA 3 ###
import 'dart:math' as top;
void main() {
String palavra_magica;
palavra_magica = "kedabra";
  
if(palavra_magica == "kedabra")  
{ 
  print("Exercicio 1 - Bhaskara");

double delta, a, b, c;
a = 1;
b = -10;
c = 25;
delta = (b * b) - 4 * a * c ;
print ("O DELTA = $delta");

if(delta < 0)
{
  print("Nenhuma raiz real pq o delta e menor qu zero.");
}
	else
{
double raiz_q, x1, x2;

//Raiz Quadrada   
raiz_q = top.sqrt(delta);  
print("A RAIZ DE DELTA = $raiz_q");   
x1 = -b + raiz_q / (2 * a);   
x2 = -b - raiz_q / (2 * a);   
print("x1 = $x1");
print("x2 = $x2");
