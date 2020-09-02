# Teste Aplicativo Mobile
Nesse teste você deve desenvolver um app **nativo** para visualização de extrato de parcelas de um usuário.

No decorrer desse **readme** você encontrará as informações necessarias para a realização do teste.

Você também vai encontrar alguns desafios e tecnologias que usamos no nosso dia-a-dia.

# Instruções
//Criar repositorio privado

//Marcar colaboradores

//Seguir o escopo 

# Escopo
 1 - Tela inicial com um form de dois campos e um botão "Login" 
 
   1.2 - Na ação do botão "Login" validar se se os dois campos tem o mesmo valor 
   
   1.2 - Se tiver o mesmo valor abrir a tela de parcelas (2) 
   
   1.3 - Se não tiver o mesmo valor apresentar um alerta de erro 
   
 2 - Tela de extrato onde deve ser apresentadas as informações do cliente e a lista de parcelas do mesmo, da seguinte forma: 
 
   2.1 - Cabeçalho na tela com os dados do cliente (nome e total de parcelas e alguns limites) 
   
   2.2 - Lista de parcelas e os dados da mesma 
   
   2.3 - O acesso a esses dados deve ser feito via REST para a url http://www.icoded.com.br/api/extract.php passando de parâmetro pwd com o valor 123456. 
   
   2.4 - Levar em conta um botão para que seja possível sair da tela e voltar ao form inicial 
   
   2.5 - Ao tocar em uma das linhas de parcelas mostrar um alerta com a data da parcela e marcar a linha selecionada.
   
 3 - Tela de detalhes onde deverá ser apresentadas as informações dos itens da listagem
 
   3.1 - Apresentar todos os dados do nodo retornados da API 

# Projeto
//Explicar o projeto

# Features
1 - Login
2 - Lista de extrato
3 - Detalhes

# Telas

<p align="left">
  <p>
    <h3>Tela de login</h3>
    <img src="http://icoded.com.br/faca-um-app/img/login.png" alt="" data-canonical-src="http://icoded.com.br/faca-um-app/img/login.png" height="400" />
  </p>
  <p>
    <h3>Tela de listar extrato</h3>
    <img src="http://icoded.com.br/faca-um-app/img/extrato.png" alt="" data-canonical-src="http://icoded.com.br/faca-um-app/img/extrato.png" height="400" />
  </p>
</p>

# Tecnologias
Algumas tecnologias que usamos no nosso dia-a-dia:

|  Android | x | IOS  |
|---|---|---|
| Kotlin  | . |  Swift |
| Retrofit  | . |  Alamofire |
| MVC / MVVM | . | MVC / MVVM  |
| ConstraintLayout  | . | AutoLayout  |
| RecyclerView  | . | TableView  |
| SharedPreferences | . | UserDefault  |
| GSON | . | Object Mapper / Codable  |

### Diferenciais
- Testes unitários (JUnit/XCTest)
- Database (Realm / ObjectBox / Room / Core Data)
- Cuidado com UX
- Animação

# O que será avaliado:
- Estrutura, organização, arquitetura.
- Clareza no código(Clean Code / SOLID)
- Performação
- Seguir guidelines das plataformas
- UX/UI


