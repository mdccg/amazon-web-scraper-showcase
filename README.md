# amazon-web-scraper-showcase

## Sumário

- [amazon-web-scraper-showcase](#amazon-web-scraper-showcase)
  - [Sumário](#sumário)
  - [_To-do list_](#to-do-list)
  - [Motivação](#motivação)
    - [API](#api)
    - [Cliente front-end](#cliente-front-end)
    - [_Features_](#features)
  - [Pilha de tecnologia](#pilha-de-tecnologia)
  - [Galeria](#galeria)
  - [Como rodar](#como-rodar)
    - [Pré-requisitos](#pré-requisitos)
    - [Passo a passo](#passo-a-passo)

<details>
  <summary>
  
  ## _To-do list_
  </summary>

  - [X] Adicionar `dotenv` à API
  - [X] Criar uma variável de ambiente que funcione como uma _flag_ booleana para impedir requisições malsucedidas retornando dados falsos
  - [X] Criar um objeto de transferência de dados adequado para o método `getProducts` e colocar o total de produtos encontrados neste serviço em vez de computá-lo no diretório `routes`
  - [X] Jogar todas as mensagens de texto para o enumerador
  - [ ] ~~Criar um interruptor na página web e um parâmetro _query_ adicional para forçar a API a retornar dados falsos~~
  - [X] Criar um arquivo contendo todos os _assets_ utilizados e adicionar a fonte tipográfica Oxygen
  - [X] Procurar uma imagem que represente ficheiros vazios e substitui-la a imagem do caso de resultados não encontrados
  - [X] Adicionar uma tela para que o usuário possa refazer a requisição em caso de erro
  - [X] Adicionar um _listener_ para bloquear o botão de refazer a requisição caso o campo de texto esteja inválido ~~e estilizá-lo com transição de opacidade~~
  - [X] Adicionar um ~~_toast_~~ aviso para notificar que dados falsos estão sendo utilizados
  - [ ] ~~Criar um elemento HTML para encapsular a imagem do componente de produto e evitar que o espaçamento interno~~
  - [X] Definir uma altura máxima para as imagens dos componentes de produto que evite produtos cortados
  - [X] Adicionar reticências aos títulos longos
  - [X] Alterar os metadados do arquivo `index.html` adicionando OpenGL
  - [ ] Explicar a variável de ambiente `BYPASS_SERVER_ERROR_STATUS_CODE` neste arquivo
  - [ ] Adicionar uma subseção "_Features_" à subseção "Motivação" para explicar detalhes técnicos como o comportamento dos botões e telas adicionais em casos de erro
  - [ ] Criar três repositórios[<sup>1</sup>](#nota-de-rodape-1) e hospedar a API e o site no Vercel e Firebase, respectivamente

  <sup id="nota-de-rodape-1">1</sup> Como o Vercel exige que uma API Express esteja em um único repositório de código configurado via `vercel.json` para o _deploy_, o terceiro repositório será composto apenas de um arquivo `README.md` e dois submódulos que redirecionarão o visitante para os respectivos repositórios.

  <!--
  - [ ] Adicionar bateria de testes com Postman e expressão regular na API
  - [ ] Procurar uma estrutura mais complexa com métodos como `initializeMiddlewares` para a API
  - [ ] Verificar se é possível capturar o ID do produto via _web scraping_ e fazer com que o componente na página `index.html` seja clicável e redirecione o usuário para o site da Amazon
  - [ ] Capturar a largura computa`da do componente de produto e, ao redimensionar a tela (que deve ter a largura mínima de 1.368px), usá-la para redefinir a largura máxima dos componentes para que a última fileira não fique com componentes maiores caso o total de produtos não seja múltiplo de quatro
  - [ ] Adicionar _skeleton_ aos cards de produtos
  -->
</details>

## Motivação

<!-- TODO escrever -->

### API

<!-- TODO escrever -->

### Cliente front-end

<!-- TODO escrever -->

### _Features_

<!-- TODO escrever -->

## Pilha de tecnologia

| Tecnologia | Função |
|-|-|

<!-- TODO escrever -->

Os créditos pelas mídias utilizadas estão disponíveis [aqui](https://github.com/mdccg/amazon-web-scraper-client/tree/main/assets).

## Galeria

![Tela inicial](./docs/homepage.png)
![Tela de resultados no topo da rolagem](./docs/results-1.png)
![Tela de resultados no final da rolagem](./docs/results-2.png)
![Tela de nenhum resultado encontrado](./docs/no-results.png)
![Tela de erro interno do servidor](./docs/server-error.png)

## Como rodar

### Pré-requisitos

<!-- TODO escrever -->

### Passo a passo

<!-- TODO escrever -->