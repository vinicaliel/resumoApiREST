# README: API REST (Representational State Transfer)

Uma **API REST** (*Representational State Transfer*) é um conjunto de padrões arquiteturais e princípios de design para a criação e o consumo de serviços web. Ela é baseada no conceito de *recursos*, que são entidades ou serviços disponíveis na web e podem ser identificados por URLs. A abordagem REST é frequentemente usada para desenvolver APIs em que a comunicação entre sistemas é realizada de maneira simples, eficiente e escalável.

## Principais Características de uma API REST:

- **Arquitetura Cliente-Servidor:** A arquitetura é dividida entre clientes, que fazem as requisições, e servidores, que respondem a essas requisições. Isso permite uma maior independência entre as partes, facilitando a evolução e manutenção.

- **Statelessness (Sem Estado):** Cada requisição do cliente para o servidor contém todas as informações necessárias para entender e processar a requisição. O servidor não mantém nenhum estado da sessão entre requisições do cliente.

- **Representação de Recursos:** Os recursos, que podem ser dados ou serviços, são identificados por URLs e podem ser representados em diferentes formatos, como JSON ou XML. As representações são usadas para transmitir informações entre o cliente e o servidor.

- **Métodos HTTP (GET, POST, PUT, DELETE):** A API REST utiliza os métodos padrão do protocolo HTTP para realizar operações nos recursos. Por exemplo, o método GET é usado para recuperar informações, POST para criar um novo recurso, PUT para atualizar um recurso existente e DELETE para remover um recurso.

- **HATEOAS (Hypermedia as the Engine of Application State):** Esse princípio sugere que a navegação através da aplicação deve ser guiada por links dinâmicos disponíveis nas representações dos recursos, permitindo uma interação mais dinâmica e autodescritiva.

Ao seguir esses princípios, as APIs REST facilitam a integração de sistemas distribuídos, promovendo a escalabilidade, a simplicidade e a facilidade de manutenção. Elas são amplamente utilizadas na construção de serviços web, especialmente em ambientes onde a comunicação entre sistemas é essencial.

# READ: API RESTFUL

A expressão **RESTful** refere-se a uma implementação específica dos princípios da arquitetura REST (*Representational State Transfer*) em uma API (Interface de Programação de Aplicações). As APIs RESTful seguem rigorosamente os princípios fundamentais do REST para criar serviços web eficientes, escaláveis e de fácil manutenção.

Em resumo, uma API RESTful é uma implementação específica de uma API REST que adere aos princípios fundamentais do REST. Essas APIs são amplamente utilizadas na construção de serviços web, oferecendo uma abordagem padronizada e eficiente para a comunicação entre sistemas distribuídos.

# Diferença entre API REST e RESTful

**API REST:**
- Refere-se a uma Interface de Programação de Aplicações (API) que segue os princípios da arquitetura REST (Representational State Transfer).
- Pode adotar uma abordagem mais flexível em relação aos princípios REST e não necessariamente seguir todas as diretrizes estritas.

**RESTful:**
- Refere-se a uma implementação específica de uma API que adere estritamente aos princípios fundamentais da arquitetura REST.
- Uma API RESTful segue de forma mais rígida os princípios do REST, como arquitetura cliente-servidor, statelessness (sem estado), representação de recursos e uso adequado de métodos HTTP.

Em resumo, uma API REST é uma interface que segue os princípios da arquitetura REST, enquanto o termo RESTful é mais específico e indica que a API segue de maneira rigorosa e completa esses princípios. O uso de "RESTful" geralmente implica em uma adesão mais estrita e fiel aos princípios REST em comparação com uma simples "API REST".


## Códigos de Status HTTP:

### 1xx - Informativo:
- **100 (Continuar):** O servidor recebeu a requisição inicial e encoraja o cliente a prosseguir com a parte restante.

### 2xx - Sucesso:
- **200 (OK):** A requisição foi bem-sucedida, e o servidor está entregando o recurso solicitado.
- **204 (Sem Conteúdo):** O servidor processou a requisição com sucesso, mas não está retornando nenhum conteúdo.

### 3xx - Redirecionamento:
- **301 (Movido Permanentemente):** O recurso solicitado foi movido permanentemente para uma nova localização.
- **302 (Encontrado):** Indica um redirecionamento temporário para outra URI.

### 4xx - Erro do Cliente:
- **400 (Requisição Inválida):** A requisição do cliente é inválida.
- **403 (Proibido):** O cliente não possui permissão para acessar o recurso solicitado.
- **404 (Não Encontrado):** O recurso solicitado não está disponível no servidor.

### 5xx - Erro do Servidor:
- **500 (Erro Interno do Servidor):** Uma condição inesperada impediu o servidor de atender à requisição.
- **503 (Serviço Indisponível):** O servidor está temporariamente incapaz de lidar com a requisição.

## Métodos de Requisição (HTTP Verbs):

1. **GET:**
   - Utilizado para requisitar dados de um recurso específico no servidor.

2. **POST:**
   - Envia dados para o servidor para criar um novo recurso.

3. **PUT:**
   - Atualiza ou cria um recurso no servidor com base nos dados fornecidos.

4. **DELETE:**
   - Remove um recurso específico no servidor.

5. **PATCH:**
   - Aplica modificações parciais a um recurso.

6. **HEAD:**
   - Similar ao GET, mas solicita apenas os cabeçalhos, sem o corpo da resposta.

7. **OPTIONS:**
   - Fornece informações sobre as opções de comunicação disponíveis para o recurso alvo.

8. **TRACE:**
   - Utilizado para testar a conectividade, exibindo o que foi recebido no servidor de volta ao cliente.
  


  Nome: Vinicius Caliel Nunes Passos
  Matrícula: 01554544
