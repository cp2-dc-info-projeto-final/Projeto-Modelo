# Especificação de Requisitos

Este repositório tem por objetivo instruir os alunos de projeto final sobre como deverão realizar sua especificação de requisitos. Toda a documentação do software será deverá ser feita utilizando a linguagem Mark Down, para que ao fim todo o material esteja disponível na página do GitHub do projeto.

Este documento servirá não somente como um exemplo de como os requisitos deverão ser especificados, mas também como referência da linguagem Mark Down e de git.

## Inicializando seu repositório

Primeiramente, inicie um repositório em sua máquina utilizando o mesmo nome do repositório criado no GitHub.

```
git init exemplo-requisitos
```

Entre na pasta criada para seu repositório com o comando

```
cd exemplo-requisitos
```

Feito isso, utilize um editor de texto de sua preferência (pessoalmente gosto do Atom) para criar um arquivo chamada `README.md`, onde você deverá fazer uma breve descrição do seu projeto utilizando a linguagem Mark Down.

## Adicionando ao staging area

O staging area é a área de preparação do seu commit. Para adicionar seu arquivo `README.md` ao staging area utilize o comando

```
git add README.md
```

## Verificando o staging area

Antes de comitar, é sempre aconselhável verificar o que está no staging area, onde todas as alteração a serem comitadas são rastradas. Para verificar seu staging area, utilize o comando

```
git status
```

## Comitando alterações

Salvar as alterações indicadas no staging area é uma operação chamada commit. O commit é como uma fotografia de uma etapa do desenvolvimento do seu código, e uma vez realizado, não poderá ser desfeito. É sempre possível retornar a uma versão anterior de seu código, porém o commit não deixará de fazer parte do histórico de seu projeto. É sempre aconselhável fazer um comentário no commit, para que seja mais fácil identificá-lo futuramente. Para realizar um commit inserindo um comentário, utilize o comando

```
git commit -m 'adicionando arquivo README.md'
```
