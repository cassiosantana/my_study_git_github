Criando uma branch e mudando para ela no mesmo comando
Mas na verdade esse comando checkout é para mudar de branch
E tem essa funcionalidade para poder digitar menos
``` sh
git checkout -b nova-branch
```

Voltando para a branch main
``` sh
git checkout main
```

> Deve-se ter atenção quanto ao movimento entre branchs quando se
tem modificações na ainda não adicionadas ao stage ou no stage
pois ao mudar de branchs essas modificações também serão movimentadas.
Posteriormente veremos como evitar que esta "sujeira" seja também movimentada.

A uma branch nova ela é uma cópia da branch original, ela não apenas carrega novos commits, mas também todo histórico de onde se originou para que posteriormente se unam. Para isso usamos o comando 'merge'.

Estando na branch main e utilizando este comando a
branch nova-branch será unida a main e trará todas as
modificações.
```sh
git merge nova-branch
```

Caso haja algum conflito entre branchs causado por modificações simultâneas no mesmo arquivo, o git irá solicitar que o conflito seja resolvido antes de efetutar o merge.