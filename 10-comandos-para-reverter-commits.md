Atenção para estes comandos pois podem ser
destrutivos e todo o trabalho pode ser perdido

Revertendo para um commit anterior usando o hash
do commit
```sh
git reset aad9bfd
```

Reverter usando a tag HEAD
Basicamente ele retorna da HEAD atual n commits atrás
O número após o ~ define a quantidade de passos atrás
o commit será revertido.
```sh
git reset HEAD~1
```

A flag --soft apaga apenas o commit local e as alterações
que haviam sido commitadas voltam para a stage área, bem
ao momento antes do commit.
```sh
git reset --soft HEAD~1
```

A flag --mixed é o default do reset. Se ela for omitida
ainda sim ela seria a executada. Sua diferença é que ao
comando ser rodado retorna ao estado um passo antes do que 
resulta da flag --soft, ou seja vai direto para o working 
directory aguardando ser adicionado ao stage
```sh
git reset --mixed
```