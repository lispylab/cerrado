# Aprendendo com lis.py

Este repositório contém variações do
[interpretador lis.py](https://github.com/norvig/pytudes/blob/c33cd6835a506a57d9fe73e3a8317d49babb13e8/py/lis.py)
para um subconjunto de
[Scheme](https://en.wikipedia.org/wiki/Scheme_(programming_language))
criado por Peter Norvig, descrito em seu texto
[(How to Write a (Lisp) Interpreter (in Python))](https://norvig.com/lispy.html).

## Rodando no Colab

Clique no link abaixo para executar o Jupyter Notebook
na plataforma Google Colab sem instalar nada em sua máquina:

https://colab.research.google.com/github/lispylab/cerrado/blob/lispy.ipynb

## Rodando na linha de comando

O notebook `lispy.ipynb` pode ser exportado como um script Python assim:

```bash
$ jupyter nbconvert --to script lispy.ipynb
```

Isso gera o arquivo `lispy.py`, que  precisa ser executado no console `ipython`
devido ao uso de alguns comandos mágicos como `%%script`:

```bash
$ ipython lispy.py
```
 
O script exibe o resultado de alguns experimentos, e afinal exibe o REPL (console interativo):

```
42
9
(12 34 10)(0 1 2 3 4 5 6 7 8 9)
(Este é o lis.py de Norvig)
lis.py> 
```


## Proveniência, Direitos Autorais e Licença

`lis.py` foi
[publicado](https://github.com/norvig/pytudes/blob/c33cd6835a506a57d9fe73e3a8317d49babb13e8/py/lis.py)
no repositório [`norvig/pytudes`](https://github.com/norvig/pytudes) no Github.
O detentor do direito autoral é Peter Norvig e o código é licenciado sob a
[licença do MIT](https://github.com/norvig/pytudes/blob/60168bce8cdfacf57c92a5b2979f0b2e95367753/LICENSE).

A menos que seja observado o contrário,
escrevi as mudanças e adições descritas nos arquivos README em cada diretório.

*Luciano Ramalho*<br/>
São Paulo, 5 de julho de 2024
