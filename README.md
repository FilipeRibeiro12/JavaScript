# JavaScript

# O que faz o JavaScript?
   interações entre o cliente e o website
# Cliente x Servidor
     JavaScript é uma tecnologia que funciona muito mais para cliente
# Website
    Como fosse um jornal
        jornalista, produção de conteudo responsavel por texto, imagem, video. (HMTL)
        designer, pegar o conteudo e organiza-los, tornar as coisas mais bonitas. (CSS)
        programador, tratar da engenharia da entrega, segurança, interação. (JS)

# Quem usa JavaScript ?
Google
Youtube
Linkedin
Netflix
Facebook

# Identificadores de variaveis

* Podem começar com letra, $ ou _
* Não podem comçar com números
* É possivel utilizar letras ou numeros
* É possivel usar acentos e simbolos
* Não podem conter espaços
* Não podem ser palavras reservadas, por exemplo comandos do JS

# Dicas de identificadores de variaveis

* Maisculas e minusculas fazem diferença
* Utilizar nomes coerentes para as variaveis
* Evite se tornar um "programdor alfabeto" ou um "programador contador"

# Diferenças de variaveis

* 5 18 -12 0.5 -15.9 3.14 8.0 = Number
* "Gooogle" 'JavaScript' `Maria` = String
* True, false = Boolean

# Manipulação de Dados
* Conversão de string para numero:
 * Number.parseInt(n) ➡ numero inteiro
 * Number.parseFloat(n) ➡ numero real
 * Number(n)➡ O proprio JS decide com o valor que é dado se é real ou inteiro

* Conversão de numero para string
 * String(n)
 * n.toString()

# Formatando Strings
 * var s = 'JavaScript'
 'Eu estou aprendendo s' ➡ não faz interpolação
 'Eu estou aprendendo ' + s ➡ usa concatenação
 `Eu estou aprendendo ${s}` ➡ usa template string

* s.length ➡ quantos caracteres tem uma string
* s.toUpperCase() ➡ muda tudo para letras maiusculas
* s.toLowerCase() ➡ muda tudo para letras minusculas

# Formatando Numeros
* n1.toFixed(2)
* n1.toFixed(2).replace ('.', ',')
* n1.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'})

# Operadores 

* Aritmeticos
5 + 2 ➡ 7
5 - 2 ➡ 3
5 * 2 ➡ 10 ➡ Multiplicação
5 / 2 ➡ 2.5 ➡ divisão real
5 % 2 ➡ 1 ➡ Resto da divisão inateira
5 ** 2 ➡ 25 ➡ potencia

* obs: Cuidado!
5 + 3 / 2 ➡ 6.5
(5 + 3) / 2 ➡ 4

* Ordem de Precedendcia dos operadores aritmeticos
⬇ ()
⬇ ** 
⬇ */%
⬇ +-

* Atribuição simples
var a = 5 + 3 ➡ 8
var b = a % 5 ➡ 3
var c = 5 * b ** 2 ➡ 45
var d = 10 - a / 2 ➡ 6
var e = 6 * 2 / d ➡ 2
var f = b % e + 4 / e ➡ 3

* Auto-atribuições
var n = 3 ➡ 3
n = n + 4 ➡ 7
n = n - 5 ➡ 2
n = n * 4 ➡ 8
n = n / 2 ➡ 4
n = n ** 2 ➡ 16
n = n % 5 ➡ 1

* Simplificando atribuições
n = n + 4 ➡ 7 ➡ n+=4
n = n - 5 ➡ 2 ➡ n-=5
n = n * 4 ➡ 8 ➡ n*+4
n = n / 2 ➡ 4 ➡ n/=2
n = n ** 2 ➡ 16 ➡ n**=2
n = n % 5 ➡ 1 ➡ n%=5

* Incremento
var x = 5
x = x + 1 ➡ 6 ➡ x++
x = x - 1 ➡ 5 ➡ x--