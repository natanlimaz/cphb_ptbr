# Manual do Programador Competitivo (Tradução Completa)

Este é o projeto de tradução do livro "Competitive Programmer's Handbook" para o português. A tradução inicial foi concluída e está disponível para a comunidade. O objetivo deste projeto é fornecer um recurso acessível e compreensível para a comunidade de programação competitiva de língua portuguesa, especialmente para aqueles que só podem, ou preferem, ler em português.
 
#### 💾 Você pode baixar a versão mais recente do PDF na seção de [**releases**](https://github.com/natanlimaz/cphb_ptbr/releases) 💾
  

## Importante: Revisão Contínua

A tradução de um livro técnico é um processo complexo e trabalhoso. Apesar do empenho e da boa intenção dos colaboradores, é natural que alguns erros ou imprecisões possam ter passado despercebidos durante o processo inicial de tradução.

Por isso, enfatizamos a importância da revisão contínua por parte da comunidade. Seu feedback e contribuições são essenciais para aprimorar e refinar esta tradução ao longo do tempo. Encorajamos todos os leitores a reportarem quaisquer erros encontrados, sugerirem melhorias na clareza ou precisão do texto, e participarem ativamente no processo de revisão.

Juntos, podemos garantir que esta tradução se torne um recurso cada vez mais valioso e confiável para a comunidade de programação competitiva de língua portuguesa.

## Sobre o Livro

"Competitive Programmer's Handbook" é uma introdução moderna à programação competitiva. O livro aborda truques de programação e técnicas de design de algoritmos relevantes na programação competitiva.

## CSES Problem Set

O CSES Problem Set contém uma coleção de problemas de programação competitiva.
Você pode praticar as técnicas apresentadas no livro resolvendo esses problemas.

https://cses.fi/problemset/
(Apenas em inglês)

## Licença

A licença do livro é Creative Commons BY-NC-SA 4.0.

## Outros livros

"Guide to Competitive Programming" é um livro impresso publicado pela Springer, baseado no "Competitive Programmer's Handbook". Há também uma edição em russo chamada "Олимпиадное программирование" (Programação Olímpica) e uma edição em coreano chamada "알고리즘 트레이닝: 프로그래밍 대회 입문 가이드" (Treinamento de Algoritmos: Guia de Introdução às Competições de Programação).

https://cses.fi/book/

## Contribuição

Apesar da tradução inicial estar completa, sempre há espaço para melhorias, seja na correção de erros, revisão de termos técnicos ou aprimoramento da fluidez do texto. Sua contribuição é bem-vinda!

### Como Contribuir

1. **Fork do Repositório**: Faça um fork deste repositório para sua conta do GitHub.

2. **Clone o Fork**: Clone o fork para sua máquina local.

3. **Edição**:
   - Para iniciantes no LaTeX, recomendamos usar o Overleaf, um editor LaTeX online:
     1. Baixe o repositório como um arquivo .zip
     2. No Overleaf, crie um novo projeto e faça upload do arquivo .zip
     3. Você pode então editar os arquivos diretamente no Overleaf
   - Se você já está familiarizado com LaTeX, pode editar os arquivos localmente com seu editor preferido.

4. **Tradução**: Traduza o texto, mantendo as estruturas LaTeX inalteradas. Foque apenas no conteúdo textual.

5. **Teste**: Se estiver usando o Overleaf, você pode compilar o documento para ver o resultado em PDF. Isso ajuda a verificar se não há erros de formatação.

6. **Commit e Push**: Faça commit das suas alterações e push para o seu fork no GitHub.

7. **Pull Request**: Abra um Pull Request para que suas alterações sejam revisadas e incorporadas ao projeto principal.

### Dicas

- Mantenha a formatação e estrutura originais do LaTeX.
- Preste atenção especial à tradução de termos técnicos.
- Se tiver dúvidas sobre algum termo ou trecho, deixe um comentário no PR para discussão.
- Para iniciantes: No arquivo `book.tex`, há a inclusão dos capítulos. Para incluir um capítulo específico no PDF compilado, remova o comentário da linha correspondente. Por exemplo:
  - Para incluir o Capítulo 1, mude `%\include{chapter01}` para `\include{chapter01}`
  - Isso permite que você trabalhe e visualize capítulos específicos sem precisar compilar o livro inteiro.
