## **README.md**

### **Imersão gratuita realizada pela Alura e Google Gemini**

**Projeto de site sobre atletas olímpicos brasileitos realizado durante a imersão** 

**Descrição:**
Esta aplicação web simples permite a busca de atletas e esportes utilizando um banco de dados simulado (arquivo `dados.js`). A interface do usuário é bem simples e intuitiva, com um campo de pesquisa e uma seção para exibir os resultados.

**Funcionalidades:**

* **Busca por palavras-chave:** Permite pesquisar por nome de atleta, esporte, termos presentes na descrição ou palavras-chave.
* **Exibição de resultados:** Apresenta os resultados da busca de forma clara e concisa, com título, descrição e link para mais informações.

**Tecnologias Utilizadas:**

* **HTML:** Estrutura da página.
* **CSS:** Estilização da interface.
* **JavaScript:** Lógica da aplicação, incluindo a função de pesquisa e a manipulação do DOM.

**Estrutura de Arquivos:**

* **index.html:** Arquivo principal da aplicação.
* **style.css:** Arquivo de estilos CSS.
* **dados.js:** Arquivo contendo os dados dos atletas (banco de dados simulado).
* **app.js:** Arquivo contendo a lógica da aplicação, incluindo a função de pesquisa.

**Lógica da função de pesquisa:**
A função `pesquisar()` itera sobre os dados dos atletas, comparando as palavras-chave da pesquisa com o título, descrição e tags de cada atleta. Se houver correspondência, o atleta é adicionado à lista de resultados.

**Como Utilizar:**

1. **Clonar o repositório:** Clone este repositório para sua máquina local.
2. **Abrir o arquivo index.html:** Abra o arquivo `index.html` em um navegador web.
3. **Realizar a busca:** Digite o nome do atleta, esporte ou palavra-chave desejada no campo de pesquisa e clique no botão "Pesquisar".
4. **Visualizar resultados:** Os resultados da busca serão exibidos abaixo do campo de pesquisa.

**Observações:**

* **Banco de dados:** O arquivo JavaScript `dados.js` simula um banco de dados, contendo informações básicas sobre os atletas. Para uma aplicação real, seria necessário utilizar um sistema de banco de dados.
* **Responsividade:** A aplicação não foi projetada para garantir uma boa experiência de usuário adequada a diferentes dispositivos. Pode ser necessário realizar vários ajustes para dispositivos com telas menores, como dispositivos mobile.
