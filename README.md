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
  
############################

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




