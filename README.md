<!-- Título -->
# Includes em C

***Conteúdo da Aula:***

Nas aplicações que formos desenvolver, inclusive neste curso, precisaremos de recursos **“estendidos”** da linguagem, além dos recursos-padrão.

Um exemplo é se precisarmos ler informações a serem fornecidas pelo usuário através do console...

Para conseguirmos realizar esta operação, precisaremos do comando `scanf` da linguagem **C**, porém, ele só está disponível em uma biblioteca externa, a **STDIO** (Standard I/O).

Para conseguirmos utilizar esta biblioteca externa, nós precisamos **“incluí-la”** em nossa aplicação, para fazermos corretamente o link entre nossa aplicação e a biblioteca externa (link esse chamado também de **“referência”**).

Nós fazemos isso com o comando `#include` no começo de nossa aplicação.

Veja os exemplos abaixo:

```c
#include <stdio.h> // Inclusão dos comandos da biblioteca Standard I/O.
#include <math.h> // Inclusão dos comandos da biblioteca matemática do C.
```

O `#include` também é chamado de diretiva.

Na verdade, para o **C**, qualquer declaração que comece com **“#”** é chamada de diretiva.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-inc-c-est-bas-sof-c-log-par-pro-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-inc-c-est-bas-sof-c-log-par-pro-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-inc-c-est-bas-sof-c-log-par-pro-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-inc-c-est-bas-sof-c-log-par-pro-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-inc-c-est-bas-sof-c-log-par-pro-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-inc-c-est-bas-sof-c-log-par-pro-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
