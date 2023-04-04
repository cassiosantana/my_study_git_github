Exemplo de corpo de commit:

>Esse commit possui comandos para configurar o
editor padrão de commits do git
>
>- Aceita Markdown
>
>Closes #13 Ref #123


Desta forma as informações ficam muito bem atreladas dando
para saber mais informações sobre a tarefa efetuada e sua
issue, podemos usar markdown para ficar mais elegante.


Commits semânticos

Primeiramente saber o que é semantic versioning
https://semver.org/
3.2.7
O '3' - referencia uma alteração MAJOR que pode quebrar compatibilidades. Alterações muito grandes.
O '2' - MINOR ela é uma alteração menor que implementam
novas funcionalidades mas mantém compatibilidades.
O '7' - PATCH alterações que corrigem bug e alterações menores
do dia a dia.


Conventional Commits
Define um conjunto de regras para criar um historico de
commit explícito para faciliar a criação de ferramentas automatizadas baseadas na especificação. Esta convenção se
encaixa com o SemVer, descrevendo os recursos, correções e
modificações que quebram compatibilidade nas mensagens de
commit.
https://www.conventionalcommits.org/

Os prefixos demonstrados no convetional commits são tão
importantes pois podem automatizar, por exemplo as versões
de patchs das aplicações por exemplo o fix:, se a versão de
patch era 3.2.7 commitando usando fix iria para 3.2.8 se o
patch foi aceito.

A leitura é extremamente recomentada.
