# 🍃 MongoDB - Introdução

## 🤔 Banco Relacional x Banco Não Relacional

- Os bancos relacionais demandam uma forte configuração de:
	- tabelas;
	- colunas;
	- e relações entre tabelas para seu funcionamento.
- Os bancos não relacionais não são rigorosos quanto a isso;
- Podemos criar colunas quando o dado é inserido.
	- O que gera flexibilidade para o banco não relacional.
	- Também pode ser sinônimo de desorganização.
- Apesar do nome, o banco não relacional pode ter relações entre **collections**.


## 🍃 E o MongoDB?

- É o banco não relacional mais utilizado.
- Os dados são inseridos em formato de objetos (**JSON**).
- Os comandos em vez de queries são métodos.
- Podemos criar relações entre entidades.
- Facilmente adaptado para diversas linguagens através de drivers.
- Possui uma proximidade com a linguagem de programação **JavaScript**.


## 🛠 Instalação do MongoDB

- Para a instalação é necessário instalar duas ferramentas:
	- **MongoDB**, que é o sistema de banco de dados;
	- **MongoDB tools**, ferramenta para importação e exportação de bancos.
	
	
## 🧐 Principais Entidades do MongoDB

- **Database:** é onde fica as nossas collections e dados;
- **Collections:** são como as tabelas nos bancos relacionais, pois vamos inserir dados nelas;
- **Documents:** são os dados, no MongoDB tem essa nomenclatura;
- Collections podem ser criadas livremente a qualquer momento, e não possuem colunas fixas para dados.


## Mongo e JSON

- O tipo de dado inserido na tabela é o **BSON**, uma variação de JSON;
- O **BSON** é semelhante ao JSON, porém com recursos a mais;
- A forma de criar um **BSON** é igual ao **JSON**, veja:
````sh
{
	nome: "Marcos",
	idade: 28
}
````


## MongoDB e os Drivers

- Quando utilizamos MongoDB e alguma linguagem de programação, precisamos utilizar o driver da mesma;
- todos estão disponíveis na documentação oficial.
- Os comandos do **shell** são os mesmos que o driver do **JavaScript (NodeJS)**, o que facilita muito para as aplicações **MERN/MEAN/MEVN**.