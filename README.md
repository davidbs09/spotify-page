# Spotify Dev 🎧💻

> **Com muito orgulho que apresento para vocês o meu último projeto feito.** 🎉
<br>
<br>

## Ideia 😃
A ideia é criar um website igual o Spotify com a interação de busca dos artistas que nós gostamos, usei o json.server para injetar alguns artistas para que a API pudesse consumir, são poucos mas a gosto do cliente podemos adicionar mais artistas assim como preferir.
O site está responsivo e para melhor experiência dos usuários de dispositivos móveis eu implementei um Mobile Button, usando media-queries para que quando for visto a página de uma tela menor, não fique mostrando aquele excesso de informações que geram uma má experiência para quem estiver acessando, o Mobile Button ajuda até mesmo na responsividade.
<br>

## Demonstração 👀
![image](https://github.com/user-attachments/assets/eabf8f6d-8cce-44c2-a7bc-398b56e780d0)
<br>
> **O `Mobile Button` esconde a biblioteca para ajudar na responsividade e melhorar a experiência do usuário, evitando excesso de informações que em uma tela pequena não fica legal.** <br>
![image](https://github.com/user-attachments/assets/a73d31fc-19ab-4a4c-8f5f-769390e59da5)
<br>

## Tecnologias utilizadas 👨‍💻

- HTML, CSS e JavaScript 🎨  
- Json.server 📡  
- Git e GitHub 🐙
<br>

# Porque instalar o json.server ? 🤔

O `json.server` é uma ferramenta leve e fácil de configurar para simular uma API REST com um simples arquivo JSON.  
Ele é útil para prototipação rápida, desenvolvimento front-end e testes sem precisar de um backend completo.  
No projeto, ele permite armazenar e fornecer os dados dos artistas de forma dinâmica, como uma API real faria.

## Como instalar o json.server 

Para rodar o json.server no seu ambiente local, siga estes passos:

1. Instale o `json.server` globalmente com o npm:
   ```sh
   npm install -g json-server

2. No diretório do projeto, execute o servidor apontando para o arquivo artists.json:
   ```sh
   json-server --watch artists.json --port 3000
   
3. A API estará disponível em:
   ```sh
   http://localhost:3000/artists
<br>

# Quando posso pesquisar pelos artistas ? 🤔

Quando o json.server estiver rodando na porta 3000, você já pode iniciar a Aplicação.
Dessa forma ele vai esta rodando e funcionando corretamente a pesquisa dos artistas.
<br>

##  Exemplos na prática 😎

> **Inicialmente foram implementados apenas alguns artistas, podemos conferir ele acessando a porta 3000 depois que iniciamos o  json.server.
> Depois que iniciamos, podemos pesquisar as palavras chaves ele vai procurando os artistas com o nome mais próximo do que você está digitando.**
![image](https://github.com/user-attachments/assets/a690a757-fe95-4f8b-a146-d00fd33e5970)
![image](https://github.com/user-attachments/assets/2475c8b7-cfae-4abf-aea3-5ea8174cd60e)

