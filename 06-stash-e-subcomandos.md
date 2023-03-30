Primeiramente o comando para verificar as branchs existentes e a atual
```sh
git branch
```

Modificar nome da branch atual
```sh
git branch -m novo-nome
```

Modificar nome de qualquer branch
```sh
git branch -m nome-antigo nome-novo
```

Deletar uma branch
```sh
git branch -d nome-da-branch
```

O stash entende-se como uma caixa onde se esconde alterações que não se deseja levar junto
ao se movimentar entre branchs.
Assim guarda-se as alterações no stash e quando desejado é só restaura-las.
O stash funciona como um array podendo ser utilizado várias vezes.
O stash guarda as alterações que se encontram no stage.

Salvar alterações no stash
```sh
git stash save "mensagem identificadora do stash"
```

Listar os stashs
```sh
git stash list
```

Restaurar o guardado
```sh
git stash pop <indice>
git stash pop 1
```

Limpar o stash
```sh
git stash clear
```
