# docker-actions

 # Ação do docker “Hello World”
 Esta ação imprime "Hello World" ou "Hello" + o nome de uma pessoa para saudar no log.

 ## Entradas / Inputs

 ## `quem cumprimentar`

 **Obrigatório** O nome da pessoa a ser cumprimentada. Padrão `"Mundo"`.

 ## Saídas

 ## `hora`

 A hora em que te cumprimentamos.

 ## Exemplo de uso

 uses: camilakbn/docker-actions@v1
 with:
   who-to-greet: Camila Nascimento