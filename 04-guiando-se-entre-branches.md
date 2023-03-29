Adicionando um repositório remoto ao projeto local caso ainda não possua
``` sh
git remote add origin https://algum-repositorio/algo/algo
```

Verificar o repositório remoto do projeto atual.
``` sh
git remote -v
```

Puxando alterações do repositório remoto
Deve ser efetuado antes de iniciar os trabalho e push
``` sh
git pull
```

Verificar as branchs do repositório
``` sh
git branch
```
Push é enviar as alterações locais para o repositório remoto
Origin é o repositório origem e main é a branch do origin para onde
as alterações estão sendo enviadas
``` sh
git push origin main
```

Criando uma branch e mudando para ela no mesmo comando
``` sh
git checkout -b nova-branch
```

Tag HEAD é onde estamos atualmente. Ela aponta para onde etamos localizados no fluxo do git