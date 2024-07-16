#🌟Projeto LiterAlura🌟

## Descrição
Este projeto é uma aplicação de livraria que permite a busca e gerenciamento de livros e autores utilizando diversas funcionalidades avançadas. O projeto foi desenvolvido em Java utilizando o framework Spring Boot e integra várias tecnologias e bibliotecas para oferecer uma experiência robusta e eficiente.

## Tecnologias Utilizadas

- **Java**
- **Spring Boot**
- **PostgreSQL**
- **IntelliJ IDEA**
- **Maven**
- **Git**
- **Gutendex API**
- **Jackson**

## Funcionalidades 📚

### 1. Buscar livro por título
Permite buscar informações de um livro pelo título utilizando a API Gutendex. A busca retorna detalhes completos sobre o livro, incluindo autor, idioma e estatísticas de downloads.

### 2. Listar todos os livros
Mostra todos os livros cadastrados no catálogo da livraria, permitindo navegação e visualização detalhada de cada item.

### 3. Listar livros por idioma
Filtra e exibe livros por um idioma específico, facilitando a busca por literatura em diferentes línguas.

### 4. Listar todos os autores
Exibe todos os autores cadastrados no sistema, incluindo detalhes como nome, nacionalidade e biografia.

### 5. Listar autores vivos em determinado ano
Permite filtrar e listar autores que estavam vivos em um ano específico, útil para pesquisas históricas e literárias.

### 6. Exibir quantidade de livros por idioma
Mostra o número de livros disponíveis em um idioma específico, fornecendo uma visão geral da diversidade linguística do catálogo.

### 7. Exibir estatísticas de downloads dos livros
Apresenta estatísticas detalhadas sobre os downloads dos livros, incluindo total, média, mínimo e máximo de downloads, ajudando a entender a popularidade dos títulos.

### 8. Exibir estatísticas de anos de nascimento dos autores
Mostra estatísticas dos anos de nascimento dos autores cadastrados, permitindo análises demográficas e históricas dos escritores.

### 9. Exibir top 10 livros mais baixados
Lista os 10 livros com maior número de downloads, destacando os títulos mais populares e procurados pelos usuários.

### 10. Buscar autor por nome
Permite buscar autores pelo nome, retornando informações detalhadas sobre cada autor encontrado, incluindo suas obras e contribuições literárias.

## Como Executar

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. **Configurar o banco de dados PostgreSQL:**
   - Crie um banco de dados chamado `livraria`.
   - Configure as credenciais no arquivo `application.properties`.

3. **Instalar dependências e compilar o projeto:**
   ```bash
   mvn clean install
   ```

4. **Executar a aplicação:**
   ```bash
   mvn spring-boot:run
   ```

## Contribuição

1. **Fork o projeto:**
   - Clique no botão `Fork` no canto superior direito do repositório.

2. **Clone o seu fork:**
   ```bash
   git clone https://github.com/seu-usuario/seu-fork.git
   cd seu-fork
   ```

3. **Crie uma branch:**
   ```bash
   git checkout -b minha-feature
   ```

4. **Faça suas alterações e commit:**
   ```bash
   git commit -m "Adiciona minha nova feature"
   ```

5. **Envie suas alterações:**
   ```bash
   git push origin minha-feature
   ```

6. **Abra um Pull Request:**
   - Vá até o repositório original e clique em `New Pull Request`.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
