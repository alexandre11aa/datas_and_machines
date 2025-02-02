# Aprendendo com Dados e Máquinas

Bem-vindo ao repositório do ebook Aprendendo com Dados e Máquinas! O livro pretende demonstrar conceitos de dados e aprendizado de máquinas da forma mais prática possível. O livro é escrito em cima de [cadernos](https://github.com/alexandre11aa/datas_and_machines/blob/main/notebooks/README.md) (notebooks) desenvolvidos no Jupyter com o uso da linguagem de programação Python.

## Repositório

Clone o repositório para sua máquina local:

```shell
$ git clone https://github.com/<usuario>/https://github.com/alexandre11aa/datas_and_machine.git
```

## Acessando Livro

Com o [Quarto](https://quarto.org/) instalado, renderize o livro:

```shell
$ quarto render
```

Após renderizar o livro, existem algumas formas de abrir ele em seu navegador.

*Server Local:*

```shell
$ quarto preview
```

*Firefox*

```shell
$ firefox _site/index.html                       # Linux
$ open -a "Firefox" _site/index.html             # OS X
$ Start-Process "firefox.exe" .\_site\index.html # Windows (PowerShell)
$ start firefox.exe .\_site\index.html           # Windows (Cmd)
```

*Google Chrome*

```shell
$ google-chrome _site/index.html                 # Linux
$ open -a "Google Chrome" _site/index.html       # OS X
$ Start-Process "chrome.exe" .\_site\index.html  # Windows (PowerShell)
$ start chrome.exe .\_site\index.html            # Windows (Cmd)
```

## Licença

Este repositório é licenciado sob a [GPL-3.0 license](https://github.com/alexandre11aa/notebooks/blob/main/LICENSE). Sinta-se livre para usar e modificar os conteúdos conforme necessário.

Espero que este repositório seja útil para seus estudos e aplicações práticas em Dados!