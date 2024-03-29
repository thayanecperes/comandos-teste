# COMANDOS BASICOS 
Conhecendo os comandos basicas para utilização e atualização dos repositorios no GIT HUB. 

Para enviar uma atualização para o GitHub, você geralmente segue três passos principais:
1-  adicionar as mudanças ao índice (staging area);
2-  fazer um commit das mudanças e;
3- em seguida, empurrar (push)as alterações para o repositório remoto no GitHub. 

Aqui estão os comandos básicos para fazer isso:

Adicionar as mudanças ao índice (staging area):

``` git add .```

Este comando adiciona todas as mudanças (novos arquivos, modificações e exclusões) ao índice para prepará-las para o commit. Você também pode substituir o ponto (.) por nomes de arquivos específicos se quiser adicionar apenas certos arquivos.

Fazer um commit das mudanças:

``` git commit -m "Mensagem do commit aqui" ```

Este comando cria um novo commit com as mudanças que estão no índice. Certifique-se de incluir uma mensagem descritiva e significativa que explique as mudanças realizadas.

Empurrar (push) as alterações para o repositório remoto no GitHub:

``` git push origin main ```


Este comandgito envia os commits locais para o repositório remoto chamado "origin" (que geralmente é o GitHub) e para o ramo (branch) chamado "main" (ou outro ramo, se você estiver trabalhando em um ramo diferente). Certifique-se de substituir "main" pelo nome do ramo que você deseja enviar, caso esteja trabalhando em outro ramo.

Com esses três passos, você deve ser capaz de enviar suas atualizações para o GitHub. Lembre-se de que você precisa ter permissões de escrita no repositório remoto para poder fazer push das alterações.

