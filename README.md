# <div align="center">ANOTAÇÕES DE PROGRAMAÇÃO FUNCIONAL COM CLOJURE</div>

Anotações para ajudar no meu aprendizado em programação funcional com Clojure

> Fonte do meu aprendizado: [Curso](https://www.udemy.com/course/clojure-introducao-a-programacao-funcional) na plataforma [Udemy](https://www.udemy.com/) oferecido pelo instrutor [Marcio Frayze David](https://www.udemy.com/user/marcio-frayze-david/)

<hr><hr>

## <div align="center">INTRODUÇÃO</div>

### Vantagens da programação funcional

1. Nova forma de pensar a programação
2. Imutabilidade
3. Concorrência e paralelismo

### Vantagens da Clojure

1. Simplicidade
2. Interoperabilidade com a Java
3. REPL (Read Eval Print Loop) (poder testar código diretamente no terminal, sem requerer IDE ou editor de texto)
4. Comunidade

### Clojure pertence ao dialeto do Lisp

<hr><hr>

## <div align="center">PRIMEIROS CÓDIGOS</div>

Após a instalação e a configuração da Clojure na máquina, digite o comando "clj" ou "clojure" para iniciar o REPL

Printando "Olá, mundo!" no terminal
> (println "Olá, Mundo!")

Somando 1 ao número 3 (dá 1 + 3 = 4)
> (+ 1 3)

Somando 1 ao número 3 somado a -2 somado a 7 (dá 1 + 3 - 2 + 7 = 9)
> (+ 1 3 -2 7)

Subtraindo 3 ao número 5 (5 - 3 = 2)
> (- 5 3)

Multiplicando os números 5 e 3 (5 x 3 = 15)
> (* 5 3)

Dividindo 15 por 3 (15 ÷ 3 = 5)
> (/ 15 3)

Agora teste a seguinte linha para ver no que vai dar
> (* 2 5 -2)
