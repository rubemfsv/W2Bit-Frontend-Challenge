## W2Bit - Frontend Challenge

Se você chegou até aqui, parabéns! Agora vamos avaliar suas habilidades técnicas com um desafio prático.

Você será avaliado por sua capacidade de escrever códigos legiveis, simples e de fácil manutenção.

### Instruções
* Nome do Projeto: W2Bit Airport
* Objetivo: Criar um app capaz de pesquisar aeroportos e preços de vôos. 
* Tecnologia: React Native e firebase.
* Entrega: Crie um repositório pessoal para esse projeto, siga as instruções abaixo, sinalize o término e envie o link do repositório. 

### Recomendações
* Documente seu projeto em arquivos markdown explicando a estrutura, processo de setup e requisitos.
* Tenha sempre um mindset de usabilidade, escalabilidade e colaboração.
* A organização das branches e os commits no repositório falam muito sobre como você organiza seu trabalho.
* O design/estrutura do código da aplicação deve ser production ready.
* Use boas práticas de programação.
* Lembre-se de formatar bem as datas.
* Você pode usar bibliotecas, mas queremos que as soluções sejam suas, portanto não use dependencias para tudo.
* Inclua no seu readme os desafios/problemas com os quais você se deparou durante a execução do projeto.

## Challenge!
Você foi contratado para fazer um app para buscas de vôos. Você deverá fazer a criação de conta e autenticação utilizando firebase.

A API utilizada é a seguinte: https://rapidapi.com/skyscanner/api/skyscanner-flight-search

O que terá que ser feito:
* Ao cadastrar, você selecionará seu país de moradia. 
  * O cadastro conterá os seguintes campos:
    * Nome
    * Email
    * País de residência (utilizar a API para listar os nomes dos países e os códigos)
    * Senha
* Após fazer login, concluir o cadastro ou toda vez que entrar no app, você será redirecionado para uma dashboard contendo todos os aeroportos de seu país de residência (utilize apenas os que a API listar). 
* Ter uma tela para buscar aeroportos por país, onde você selecionará o país desejado e listará todos os aeroportos localizados no local (utilize apenas os que a API listar).
* Após clicar em um aeroporto em específico, listar a abreviação do aeroporto (PlaceId) e o nome do aeroporto (PlaceName) - essas informações serão utilizadas para a busca por vôos.
* Ter uma tela de busca por empresas que fazem uma rota em específico. Você vai informar uma data, o aeroporto de origem e o aeroporto de destino de destino, o resultado dessa busca será o nome das empresas que estarão disponibilizando vôos para a data informada. (Dica: como não pediremos o valor do vôo e nem outra informação específica além do nome da empresa, você pode utilizar locale = "pt-BR", currency = "BRL" e country você pode utilizar o código do país que se cadastrou).
  * Ex: 
    * Data: 25-12-2020
    * Local de origem: SDU-sky
    * Local de destino: POA-sky
    * Resultado: LATAM Airlines e Azul Airlines
* O Usuário vai poder deslogar de sua conta.  

### O que avaliaremos
* Você será avaliado pela qualidade do código, legibilidade e pelo modo que implementou as funcionalidades.
* Você é livre para tomar as decisões técnicas e de layout com as quais você se sente mais confortável.

### Happy coding!
