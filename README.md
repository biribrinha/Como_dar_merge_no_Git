# Como dar merge no Git

Oie! Vou explicar de forma prática como dar um merge usando o exemplo de gatinhos :) 

## Passo 1: Clonar um repositório


```bash
Git clone (link)
```

## Passo 2: Criar branch pros gatinhos e os brinquedos

```bash
git branch gatinhos
```
```bash
git branch brinquedos
```



## Passo 3: Brincando com os gatinhos

Mudando pra branch dos gatinhos
```bash
git checkout gatinhos
```
Adicionando um novo brinquedo

- Crie um arquivo TXT com o nome do brinquedo (ratinho_de_borracha.txt)

## Passo 4: Mude pra branch dos brinquedos e adicione um novo gatinho.

mudando pra branch brinquedos

```bash
git checkout brinquedos
```

- Crie um arquivo TXT com o nome do gatinho (bibi.txt)

## Passo 5: Dando merge nas branchs

vamos dar merge nos gatinhos e brinquedos pra unir todas as alterações: 

```bash
git checkout gatinhos
```

```bash
git merge brinquedos
```

## Passo 6:  Finalizar o merge
Adicione os arquivos ao commit e finalize o merge.


```bash
git add .
```
ps: Dê git status pra conferir se está tudo ok 

```bash
git commit -m "Merge dos gatinhos e brinquedos"
```

# Refêrencias

Ao iniciar o processo do merge, é preciso ter bastante atenção (cuidado com o dedo nervoso) e tem uma boa chance de dar conflitos, vou deixar aqui algumas referencias boas que podem te ajudar com isso. Mas se lembre: Faça com calma e atenção! 

- https://git-scm.com/book/pt-br/v2 (documentação do git)
- https://blog.betrybe.com/git/git-merge/ (Git merge: mesclando sua branch à branch master!) 
- https://www.youtube.com/watch?v=xAOBQtSVI_k&list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA&index=12 (Git Branches de forma fácil e com exemplo - Curso de Git e GitHub- Curso em Vídeo) 



![Alt Text](https://media.giphy.com/media/GeimqsH0TLDt4tScGw/giphy.gif)


