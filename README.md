# <div align="center">ANOTAÇÕES DE PROGRAMAÇÃO FUNCIONAL COM CLOJURE</div>

Anotações para ajudar no meu aprendizado em programação funcional com Clojure

> Fonte do meu aprendizado: [Curso](https://www.udemy.com/course/clojure-introducao-a-programacao-funcional) na plataforma [Udemy](https://www.udemy.com/) oferecido pelo instrutor [Marcio Frayze David](https://www.udemy.com/user/marcio-frayze-david/)

<hr>

## <div align="center">INTRODUÇÃO</div>

### Vantagens da programação funcional

1. Nova forma de pensar a programação
2. Imutabilidade
3. Concorrência e paralelismo

### Vantagens da Clojure

1. Simplicidade
2. Interoperabilidade (conexão) com a Java
3. REPL (Read Eval Print Loop) (poder testar código diretamente no terminal, sem requerer IDE ou editor de texto)
4. Comunidade

### Clojure pertence ao dialeto do Lisp

<hr>

## <div align="center">PRIMEIROS CÓDIGOS</div>

Após a instalação e a configuração da Clojure na máquina, digite o comando "clj" ou "clojure" para iniciar o REPL

Para sair do REPL, basta digitar o comando "(System/exit 0)" ou reiniciar o terminal

### Olá, Mundo!

Printando "Olá, mundo!" no terminal
> (println "Olá, Mundo!")

### Operações aritméticas

Somando 1 ao número 3 (1 + 3)
> (+ 1 3)
> Retorno: 4

Somando 1 ao número 3 somado a -2 somado a 7 (1 + 3 - 2 + 7)
> (+ 1 3 -2 7)
Retorno: 9

Subtraindo 3 ao número 5 (5 - 3)
> (- 5 3)
Retorno: 2

Multiplicando os números 5 e 3 (5 x 3)
> (* 5 3)
Retorno: 15

Dividindo 15 por 3 (15 ÷ 3)
> (/ 15 3)
Retorno: 5

Agora teste a seguinte linha para ver no que vai dar
> (* 2 5 -2)
<details>

   <summary style="color: lightgray">
        Clique aqui para ver o retorno
   </summary>
   <p>-20</p>
</details>

### Mnaipulação de vetores

Contando o número de elementos em um vetor (lista contendo valores armazenados nela)
> (count [1 2 3 4])
Retorno: 4

Adiciondo um valor ao final de um vetor preexistente (retorna o novo vetor)
> (conj [1 2 3 4] 5)
Retorno: [1 2 3 4 5]

Removendo o último elemento de um vetor preexistente 
> (pop [1 2 3 4 5])
Retorno: [1 2 3 4]

Checando o último elemento de um vetor preexistente
> (peek [1 2 3 4 5])
Retorno: 5

### EXECUÇÃO DE MÚLTIPLAS FUNÇÕES EM UMA LINHA SÓ

> (println (+ 2 -1 peek (conj [1 2 3 4 5] 1)))

Sempre visualize o código da parte mais interna (conj) para a mais externa (println)

Retorno: nil (valor nulo da Clojure), pois o println apenas printa na tela e não retorna o valor printado

Saída (valor printado): 2

<hr>

## <div align="center">CRIANDO NOSSAS PRÓPRIAS FUNÇÕES</div>
