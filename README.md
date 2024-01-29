
# Spotify-Alura-Imers-o-front-end-2024

PT-BR:

Para que o projeto funcione melhor e exiba artistas com base na sua pesquisa, siga os seguintes passos no terminal do VSCode ou onde estiver codificando:

1: Certifique-se de ter o Node.js baixado. Se ainda não tiver, faça o download em: https://nodejs.org/en

2: Após baixar o Node.js, instale o jserver na versão 0.17.4, que é a mais estável atualmente (atualizado em 29/01/2024). Para fazer isso, digite no terminal: "npm install -g json-server@0.17.4"

3: Agora, execute o jserver com a API que está nos arquivos usando o código "json-server --watch api-artists/artists.json" no terminal.

4: Por último, no terminal, aparecerá uma URL onde o servidor foi aberto. Geralmente é "http://localhost:3000/artists". Verifique se esta URL está escrita corretamente na linha de código 6 do arquivo script.js. Se sua URL for diferente, substitua no diretório da linha de código 6. A linha de código 6 deve estar assim: "const url = http://localhost:3000/artists?name_like=${searchTerm}"

5: Com tudo isso feito, basta executar o index.html e usar o programa. Mesmo que não esteja 100% perfeito, pois foi feito por um estudante de programação (eu mesmo) e ainda não possui todas as funcionalidades, este programa serve para mostrar como estou aprendendo. Este programa foi desenvolvido durante a imersão front-end do curso online da Alura! Obrigado!

ENGLISH:

To make the project work better and display artists based on what you enter in the search, follow these steps in the VSCode terminal or wherever you are coding:

1: Make sure you have Node.js downloaded. If you don't have it yet, download it from: https://nodejs.org/en

2: After downloading Node.js, install the jserver in version 0.17.4, which is currently the most stable version (updated on 01/29/2024). To do this, in your terminal, type: "npm install -g json-server@0.17.4"

3: Now, run the jserver with the API that is in the files using the code "json-server --watch api-artists/artists.json" in your terminal.

4: Finally, in your terminal, a URL where the server was opened will appear. Usually, it is "http://localhost:3000/artists". Check if this URL is correctly written on line 6 of the script.js file. If your URL is different, just replace it in the code on line 6. Line 6 should look like this: "const url = http://localhost:3000/artists?name_like=${searchTerm}"

5: With all of this done, just run the index.html and use the program. Even though it's not 100% perfect, as it was made by a programming student (myself), and it doesn't have all the functionalities yet, this program serves to show how I am learning. This program was created during the front-end immersion of the Alura Online course! Thank you!





