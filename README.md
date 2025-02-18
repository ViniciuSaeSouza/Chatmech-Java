Aqui está o **README atualizado**, agora corretamente mencionando **Oracle** como o banco de dados utilizado e removendo referências ao Spring:  

---

# 🛠️ ChatMech - Assistência Automotiva Inteligente  

**ChatMech** é um sistema de assistência automotiva desenvolvido em **Java** com **Jersey (JAX-RS)** para a criação de uma API REST. A aplicação permite suporte e diagnósticos automotivos, ajudando na identificação de problemas mecânicos e sugerindo soluções.  

## 📌 Tecnologias Utilizadas  
- **Java 17**  
- **Jersey (JAX-RS)** para criação da API REST  
- **Maven** para gerenciamento de dependências  
- **Banco de Dados Oracle** para armazenamento de informações  
- **Hibernate** para persistência de dados  
- **Postman** para testes de requisições  

## 🔧 Funcionalidades  
✅ API REST para consultas sobre manutenção e falhas mecânicas  
✅ Suporte a diagnósticos e categorização de problemas automotivos  
✅ Integração com **Oracle** para armazenamento de dados  
✅ Filtros e ordenação de informações conforme a necessidade do usuário  

## 📖 Aprendizados  
🔹 Implementação de **APIs REST com Jersey (JAX-RS)**  
🔹 Configuração e utilização do **Hibernate** para persistência de dados  
🔹 Modelagem e manipulação de dados com **Oracle Database**  
🔹 Gerenciamento de dependências e build com **Maven**  

## 🚀 Como Executar  
1. **Clone o repositório:**  
   ```bash
   git clone https://github.com/ViniciuSaeSouza/Chatmech-Java.git
   ```
2. **Acesse o diretório do projeto:**  
   ```bash
   cd Chatmech-Java
   ```
3. **Configure a conexão com o Banco de Dados Oracle** no arquivo `persistence.xml`.  
4. **Execute a aplicação:**  
   ```bash
   mvn jetty:run
   ```

## 📂 Estrutura do Projeto  
```
📦 Chatmech-Java  
 ┣ 📂 src/main/java/com/chatmech  
 ┃ ┣ 📂 resources  
 ┃ ┃ ┣ 📜 ApplicationConfig.java  
 ┃ ┃ ┣ 📜 ChatResource.java  
 ┃ ┃ ┣ 📜 Service.java  
 ┃ ┃ ┣ 📜 Repository.java  
 ┃ ┃ ┗ 📜 Model.java  
 ┣ 📂 src/main/resources  
 ┃ ┗ 📜 persistence.xml  
 ┣ 📜 pom.xml  
 ┗ 📜 README.md  
```  

## 🤝 Contribuição  
Feedbacks e melhorias são bem-vindos! Caso queira contribuir:  
1. Faça um **fork** do projeto  
2. Crie uma **branch** para suas alterações  
3. Envie um **pull request**  

## 📌 Autor  
Desenvolvido por **Vinícius S. Souza** 🚀  
