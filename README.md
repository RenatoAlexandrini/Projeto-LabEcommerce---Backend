<h1 align="center" >
<img src="https://user-images.githubusercontent.com/102265620/230518254-e6748768-f953-47b2-a6ed-2696bb89c9fb.png" width="50" height="50"/>
Projeto Lab E-Commerce
<img src="https://user-images.githubusercontent.com/102265620/230518325-d89f7ebe-9ea7-4719-b1a6-ca8ab8d366f4.png" width="60" height="60"/>
</h1>

![Badge Finalizado](http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge)

<hr>
<h4>
<img src="https://user-images.githubusercontent.com/102265620/230518763-c8d4b16b-7b1e-40d1-aae6-b91de72310a2.png" width="25" height="25"/>
 Projeto realizado com a finalidade de introduzir o conceito de criação de uma API, com um banco de daods fornecido pela Labenu e como podemos proteger os dados importantes utilizando o Dotenv.
</h4>
<h4>
<img src="https://user-images.githubusercontent.com/102265620/230518847-78df5e8e-c259-4edb-b333-6fdf9c767d4a.png" width="25" height="25"/>
O projeto simula um um sistema de E-Commerce, contendo as entidades usuários, produtos e compras, possuindo algumas funções que simulam funções reais, como cadastrar um produto, cadastrar um usuário e realizar uma compra.
</h4>
<hr>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/230518924-f1070954-5e4f-43fa-ba61-e069f2bd2701.png" width="35" height="35"/>
Como Testar
</h3>
<h4>
<img src="https://user-images.githubusercontent.com/102265620/230519105-cde9cf7d-02fe-4561-8073-38e6ad1909dd.png" width="20" height="20"/> Link do Render:
 
https://projeto-labecommerce-backend-turma.onrender.com

<br></br>
</h4>

```
- git clone https://github.com/RenatoAlexandrini/Projeto-LabEcommerce-Backend
- npm install
- npm run migrations
- npm run start
```
<hr>



<h2>
<img src="https://user-images.githubusercontent.com/102265620/230520548-8ad92534-3dc5-404e-a71d-e2e13313e0ee.png" width="35" height="35"/> Endpoints:
<br></br>
</h2>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/230521871-67ca7956-aa6e-4152-a991-ad3dfa981e42.png" width="30" height="30"/> Adicionar um usuário:
</h3>
<h5>
Endpoint que adiciona um novo usuário ao banco de dados, utilizando os dados passados através do "body". Não sendo permitida a falta de nenhuma das propriedades e também a criação de um usuário com o email igual a outro usuário adicionado anteriormente.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/230522729-493be4de-0665-4465-9d01-59962d7a5195.png" width="30" height="30"/> Buscar todos os usuários e compras:
</h3>
<h5>
Endpoint que não recebe nenhum tipo de parâmetro, apenas retorna um array com todos os usuários e todas as compras realizadas por ele, retornando um array de compras vazio caso o usuário não tenha realizado nenhuma compra anterior.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/230523061-210fba1e-dc0c-4e63-ada9-5f8aec3b9c68.png" width="30" height="30"/> Adicionar um produto:
</h3>
<h5>
Endpoint que adiciona um novo produto ao banco de dados, utilizando os dados passados através do "body". Não sendo permitida a falta de nenhuma das propriedades e também a criação de um produto com o nome igual a outro produto adicionado anteriormente.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/230523369-0b310ba2-78d5-40cb-b188-db824b8728dd.png" width="30" height="30"/> Buscar todos os produtos:
</h3>
<h5>
Endpoint que retorna uma lista com todos os produtos do banco de dados, podendo ser passado através de uma query um termo para busca de produtos ou uma ordenação(crescente: "ASC" ou decrescente "DESC").
Todos os parâmetros("order" e "search") são opcionais, gerando diferentes resultados, de acordo com o solicitado.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/230523740-afcc9045-9373-4e69-947b-12e88ac040b4.png" width="30" height="30"/> Adicionar uma compra:
</h3>
<h5>
Endpoint que adiciona uma nova compra ao banco de dados, utilizando os dados passados através do "body". Não sendo permitida a falta de nenhuma das propriedades e também havendo a verificação da existência do usuário e do produto pelo id informado.
</h5>

<h3>
<img src="https://user-images.githubusercontent.com/102265620/230526640-fdbb8b79-2261-404c-8939-46a2fbfa2869.png" width="30" height="30"/> Buscar compras de um usuário:
</h3>
<h5>
Endpoint que recebe o id de um usuário através do "path.params", retornando as informações deste usuário junto com as compras realizadas por ele, havendo a verificação da existência do usuário através do id informado.
</h5>

<hr>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/230520839-647a68bd-8a3d-4c4f-890f-e3edbbadcb19.png" width="30" height="30"/> Técnicas e tecnologias utilizadas
<br></br>

- ``Typescript`` <img src="https://user-images.githubusercontent.com/102265620/230519766-2b4903ad-94f7-48e7-b949-4fc981ee519d.png" width="19" height="19"/>
- ``SQL`` <img src="https://user-images.githubusercontent.com/102265620/230519864-6ee2f9d0-1377-4528-a6a1-2b19b5b75d5e.jpg" width="22" height="22"/>

</h3>
<hr>
<h3>
<img src="https://user-images.githubusercontent.com/102265620/230521150-79ed8394-6e7e-4188-80e9-d726e1500137.png" width="30" height="30"/>Autor:
</h3>

| [<img src="https://avatars.githubusercontent.com/u/102265620?v=4" width=115><br><sub>Renato Alexandrini</sub>](https://github.com/RenatoAlexandrini) | 
| :---: |


