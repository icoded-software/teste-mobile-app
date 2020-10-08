# Teste Aplicativo Mobile
Nesse teste você deve desenvolver um app para visualização de extrato de parcelas de um usuário.

No decorrer desse **readme** você encontrará as informações necessarias para a realização do teste.

Você também vai encontrar alguns desafios e tecnologias que usamos no nosso dia-a-dia.

# Instruções
//Criar repositorio privado

//Marcar colaboradores

//Seguir o escopo do projeto

//A cada nova feature fazer um PR

# Projeto
 1 - Tela inicial com um form de dois campos (usuário e senha) e um botão "Login" 
 
   1.2 - Na ação do botão "Login" chamar o endpoint **POST http://www.icoded.com.br/api/v2/login.php** passando os parâmetros **usr** = parkour! e **pwd** = 123456
   
   1.2 - Se retornar 200 guardar o token e chamar a tela de parcelas (2) 
   
   1.3 - Se não apresentar um alerta de erro 
   
 2 - Tela de extrato onde deve ser apresentadas as informações do cliente e a lista de parcelas do mesmo, da seguinte forma: 
 
   2.1 - Cabeçalho na tela com os dados do cliente (nome e total de parcelas e alguns limites) 
   
   2.2 - Lista de parcelas e os dados da mesma 
   
   2.3 - O acesso a esses dados deve ser feito via REST para a url http://www.icoded.com.br/api/extract.php passando de parâmetro pwd com o valor 123456. 
   
   2.4 - Levar em conta um botão para que seja possível sair da tela e voltar ao form inicial 
   
   2.5 - Ao tocar em uma das linhas de parcelas mostrar um alerta com a data da parcela e marcar a linha selecionada.
   
 3 - Tela de detalhes onde deverá ser apresentadas as informações dos itens da listagem
 
   3.1 - Apresentar todos os dados do nodo retornados da API 

# Features
1 - Login
2 - Lista de extrato
3 - Detalhes

# Telas

<p align="left">
  <p>
    <img src="http://icoded.com.br/faca-um-app/img/test_flow.png" alt="" data-canonical-src="http://icoded.com.br/faca-um-app/img/test_flow.png" height="400" />
  </p>
</p>

# Tecnologias
Algumas tecnologias que usamos no nosso dia-a-dia:

|  Android | x | IOS  | x | React Native  |
|---|---|---|---|---|
| Kotlin  | . |  Swift | . |  Typescript |
| Retrofit  | . |  Alamofire | . |  Axios |
| MVC / MVVM | . | MVC / MVVM  | . | Duck Pattern  |
| ConstraintLayout  | . | AutoLayout  | . | Styled Components  |
| RecyclerView  | . | TableView  | . | React Components  |
| SharedPreferences | . | UserDefault  | . | Async Storage  |
| GSON | . | Object Mapper / Codable  | . | -  |

### Diferenciais
- Testes unitários (JUnit/XCTest/Jest)
- Database (Realm / ObjectBox / Room / Core Data)
- Cuidado com UI / UX
- Animação

# O que será avaliado:
- Estrutura, organização, arquitetura.
- Clareza no código(Clean Code / SOLID)
- Performance
- Seguir guidelines das plataformas
- UX/UI
- Trabalho e comunicação


