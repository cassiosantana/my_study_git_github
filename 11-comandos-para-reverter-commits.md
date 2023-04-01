Aqui a atenção deve ser total, pois este comando
é totalmente destrutivo. Ele apaga commits e as
suas alterações como se nunca tivessem existido.
```sh
git reset --hard HEAD~1
```

O comando revert ele não tem as flags --soft,
--hard como o reset
O revert literalmente reverte apenas a modificação 
realizada no commit especificado e mantém as 
demais alterações de commits posteriores

Se uma linha de código foi adiciona e 5 commits
depois for revertida, apenas esta linha será removida
os outros commits ficarão intactos, mas deve-se atentar
se esta reversão irá quebrar o código.

Por tag head
```sh
git revert HEAD~1
```
Por hash do commit
```sh
git revert aad9bfd
```