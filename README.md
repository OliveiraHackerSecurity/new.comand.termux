# new.comand.termux

Criando comando/script para o Terminal Android.

Antes de iniciar o processo preste bastante atenção pois onde você vai inserir o arquivo pode danificar seu terminal

Porém se fizer como no tutorial nada de ruim vai acontecer

#Vamos lá:

Para criamos um comando script é necessário o NANO

Instale o nano
>pkg install nano

Crie um arquivo e digite o nome
>nano atualizar

Digitando o camindo acima vai abrir um arquivo para escrever comandos
Exemplo

Para atualizar o terminal você precisa dos comandos
>apt update
>apt upgrade

Digite esses dois comandos dentro do arquivo e para sair e salvar aperte CTRL+x e aperte Y e Enter

Com o arquivo criado vamos copiar para o local que precisa está
>cp atualizar /data/data/com.termux/files/use/bin

Entre na pasta e procure o arquivo para ter certeza que está lá
>cd /data/data/com.termux/files/use/bin

Agora de permissão ao arquivo para uso
>chmod +x  atualizar

Após isso você já pode ultilizar o novo comando criado
>atualizar

Dica:
Se você entendeu como isso funciona, ótimo vai conseguir automatizar seu terminal da forma que deseja criando novos comandos.


