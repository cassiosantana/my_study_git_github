Primeiramente vamos definir o VSCode como editor padrão de mensagens do git:

```sh
git config --global core.editor "code --wait"
```
Para desfazer a configuração que definiu o VSCode
```sh
git config --global --unset core.editor
```

O commitar deve ser realizado sem a flag -m
Se salvar e fechar o git entende que a mensagem foi definida
```sh
git commit
```
O editor irá abrir com textos comentados que podem ser apagados
