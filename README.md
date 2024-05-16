# poc-montador-tela

## Escopo
Uma poc que tem o intuito de criar um montador de tela, apartir de uma estrutura de dados usando c#. Essa estrutura não precisa ser percisitida em uma banco de dados, ira tem separação de front vs beackend, o front-end sera feito em nuxt

### Requisitos Funcionais

#### 1. **Interface de Usuário (UI)**
1. **Criação de Tela Dinâmica**
   - O sistema deve permitir a criação de telas dinâmicas com base na estrutura de dados fornecida.
   - O usuário deve ser capaz de visualizar uma prévia das telas enquanto as monta.

2. **Elementos de UI**
   - A interface deve suportar a adição de diversos elementos como:
     - Botões
     - Campos de texto
     - Dropdowns
     - Checkboxes
     - Grids de dados
     - Grids layout

3. **Configuração de Propriedades dos Elementos**
   - Os elementos de UI devem ter propriedades configuráveis, como:
     - Texto de exibição
     - Valores padrão
     - Valores

#### 2. **Back-End (C#)**
1. **Processamento da Estrutura de Dados**
   - O back-end deve receber uma estrutura de dados JSON que descreve a configuração da tela.
   - O back-end deve ser capaz de interpretar essa estrutura e enviar a configuração apropriada para o front-end.
   - 
2. **Validação e Tratamento de Erros**
   - O sistema deve validar a estrutura de dados recebida e retornar mensagens de erro claras em caso de estrutura inválida.
   - Deve haver tratamento adequado de exceções e erros no back-end.

3. **Estado tela**
   - Gerenciar Estado apartir de signalR


#### 3. **Front-End (Nuxt.js)**
1. **Renderização Dinâmica**
   - O front-end deve ser capaz de renderizar dinamicamente a tela com base na estrutura de dados recebida do back-end.
   - Deve ser utilizado Nuxt.js para a construção e renderização das páginas.

2. **Interação com o Usuário**
   - O sistema deve suportar interações do usuário como cliques, inserção de dados e navegação entre diferentes telas.
   - As interações do usuário devem ser enviadas para o back-end para processamento adicional, se necessário.

#### 4. **Geral**

1. **Testes**
   - Implementação de testes unitários.
