
# Spotify-Alura-Imers-o-front-end-2024

PT-BR

Para o projeto funcionar melhor e mostrar artistas dependendo do que você escreve na busca faça os seguintes passos no terminal do vscode ou onde você estiver codando:

1: Tenha o node.js baixado, se nao tiver baixe em: https://nodejs.org/en

2: depois de baixar o node.js baixe o jserver na versão 0.17.4 que é a mais estavel atualmente (atualizado dia 29/01/2024) Para fazer isso no seu terminal digite "npm install -g json-server@0.17.4"

3: Agora coloque o jserver com a api que esta nos arquivos para rodar usando o codigo "json-server --watch api-artists/artists.json" no seu terminal

4: por ultimo no seu terminal vai aparecer uma url onde o server foi aberto. Geralmente é "http://localhost:3000/artists" veja se essa url esta escrita corretamente na linha de codigo 6 do arquivo script.js, Se sua url for diferente é so substituir no diretorio da linha de codigo 6. A linha de codigo 6 deve estar assim: " const url = `http://localhost:3000/artists?name_like=${searchTerm}` "

5: Com tudo isso feito é so rodar o index.html e usar o programa. Mesmo ele não estando 100 por cento perfeito pois foi feito por um estudante de programação (eu mesmo) e ainda nao tem todas as funcionalidades esse programa serve para se notar como estou aprendendo. Esse programa foi feito junto com a imersão front-end do curso Online Alura! Obrigado!

ENGLISH
To make the project work better and display artists based on what you enter in the search, follow these steps in the VSCode terminal or wherever you are coding:

1: Make sure you have Node.js downloaded. If you don't have it yet, download it from: https://nodejs.org/en

2: After downloading Node.js, install the jserver in version 0.17.4, which is currently the most stable version (updated on 01/29/2024). To do this, in your terminal, type: "npm install -g json-server@0.17.4"

3: Now, run the jserver with the API that is in the files using the code "json-server --watch api-artists/artists.json" in your terminal.

4: Finally, in your terminal, a URL where the server was opened will appear. Usually, it is "http://localhost:3000/artists". Check if this URL is correctly written on line 6 of the script.js file. If your URL is different, just replace it in the code on line 6. Line 6 should look like this: "const url = http://localhost:3000/artists?name_like=${searchTerm}"

5: With all of this done, just run the index.html and use the program. Even though it's not 100% perfect, as it was made by a programming student (myself), and it doesn't have all the functionalities yet, this program serves to show how I am learning. This program was created during the front-end immersion of the Alura Online course! Thank you!

