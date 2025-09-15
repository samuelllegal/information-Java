# information-Java
Descrição sobre o java e suas funcionalidades

<h1>Tipagem</h1>
<h2>Tipagem Estática</h2>
<p>Não permite alterar o tipo da variável depois de declarada.</p>
<h2>Tipagem Dinâmica</h2>
<p>A mesma variável pode receber valores de tipos diferentes ao longo da execução do código.</p>

<h2>Tipagem Fraca</h2>
<p>Consegue realizar conversões automaticamente entre tipos diferentes de dados.</p>

<h2>Tipagem Forte</h2>
<p>Não realizam conversões automaticamente</p>

<p>public - global</p>
<p>protected -</p>
<p>private - privado</p>
<p>estatico</p>

<h2>Dados</h2>
<p>Byte: -128 até o 127</p>
<p>Char: </p>
<p>Short: -32.768 até o 32.767</p>
<p>Int: -2.147.483.648 a 2.147.483.647</p>
<p>Long: -9.223.372.036.854.775.808 a 9.223.372.036.854.775.807</p>
<p>Boolean: 0 a 1</p>
<p>Float: números quebrados e pode apresentar troca de valor de “0,001” por “0,00100001”</p>
<p>Double</p>


<h2>dados primitivos</h2>
<p>boolean, char, int, short, byte, long, float e double</p>

<h2>dados não primitivos</h2>
<p>String, Array</p>

<h2>type casting</h2>
<p>Para fazer a converção dos dados precisa informar para qual dado está sendo transformado</p>
<p>String teste = (char) ("testando");</p>

<h2>Escopo</h2>
<p>Onde variáveis e dados começa e termina</p>

<h1>Classes</h1>

<h2>Herança</h2>
<p>Recebe os atributos e os métodos</p>
<p>extends: para informar que a classe X é filha da classe Y</p>
<p>public class X extends Y{}</p>

<h2>Reescrita de método</h2>
<p>A classe mãe possui um método e a classe filho pode repetir o método e fazer alterações</p>
<p>public teste(){ "aaaaaaa"} // método mãe</p>
<p>public teste(){"bbbbbbbb" // método filho</p>

<h2>Sobrecarga</h2>
<p>na mesma classe pode haver mais de um método repetido pois são diferenciados pela quantidade ou tipos de parâmetros</p>
<p>public teste(int A){}</p>
<p>public teste(int A, int B){}</p>
<p>public teste(int A, double C){}</p>
<p>public teste(String D, char E){}</p>

<h2>Polimorfismo</h2>
<p>classes que possuem o mesmo método mas podem ser diferentes entre si</p>
<p>pessoa pf = new pessoFisica();</p>
<p>public void teste(pessoaFisica X){}</p>

<h2>Abstrata</h2>
<p>A classe existe mas não pode ser criada</p>
<p>Os métodos támbem precisa ser abstratos pois não pode ser criada pois a classe não pode ser criada.</p>
<p>Por conta disso, a classe filho precisa implementar os métodos da mãe.</p>
<p>public abstract class teste{
  public abstract void teste(){--código aqui--}
}</p>


<h2>Interface</h2>
<p>Toda interface é abstrata e por conta disso não pode ter nada concreto.</p>
<p>não possui variáveis.</p>
<p>os métodos ficam vazios, não podendo escrever nenhuma linha de código dentro do método.</p>
<p>public abstract intarface teste{} //interface</p>
<p>public class X inplements teste{}</p>


variável global
<h3>variável estática</h3>
<p>static: </p>
<p>final</p>
variável local



class
<h3>Construtores</h3>
<p>Toda classe tem um construtor usando o próprio nome e toda vez que é instanciado(criado) é usado esse construtor para criação.</p>
<p>public class teste(){
  public teste(){} //Construtor
}</p>

herança
polimorfismo
interface

extends

<h3>Lista de Arrays</h3>
import java.util.ArrayList;
ArrayList<String> lista = new ArrayList<>();
