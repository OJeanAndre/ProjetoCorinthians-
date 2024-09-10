 **Aplicação: Busca de Atletas do Corinthians**  IMERSÃO DEV + GOOGLE GEMINI

**Descrição:**

Esta aplicação web permite a busca por atletas do Corinthians. Ao digitar o nome de um atleta no campo de pesquisa, a aplicação filtra os dados e exibe os resultados relevantes.

**Funcionalidades:**

* **Pesquisa por nome:** Permite buscar atletas por parte do nome, independente de letras maiúsculas ou minúsculas.
* **Resultados dinâmicos:** A lista de resultados é atualizada em tempo real conforme o usuário digita no campo de pesquisa.
* **Informações detalhadas:** Para cada atleta encontrado, são exibidos nome, descrição e um link para mais informações.

**Tecnologias Utilizadas:**

* **HTML:** Estrutura da página web, definindo os elementos como cabeçalho, corpo, seções, formulários, etc.
* **CSS:** Estiliza a página, definindo cores, fontes, layout e responsividade.
* **JavaScript:** Linguagem de programação utilizada para criar a lógica da aplicação, como a função de pesquisa e a manipulação do DOM (Document Object Model) para atualizar a página dinamicamente.

**Como funciona:**

1. **Interface do usuário:** O usuário interage com a aplicação através de um campo de texto para digitar o nome do atleta e um botão para iniciar a pesquisa.
2. **Evento de pesquisa:** Ao clicar no botão "Pesquisar", a função `pesquisar()` é chamada.
3. **Processamento da pesquisa:**
   * A função obtém o valor digitado no campo de pesquisa.
   * Itera sobre um conjunto de dados de atletas (armazenado em um arquivo JavaScript separado), comparando o nome digitado com os nomes dos atletas, descrições e tags.
   * Se houver correspondência, cria um elemento HTML para exibir as informações do atleta.
   * Se não houver resultados, exibe uma mensagem informando que nada foi encontrado.
4. **Atualização da página:** Os resultados da pesquisa são inseridos em uma seção específica da página, substituindo o conteúdo anterior.

**Estrutura de arquivos:**

* **index.html:** Arquivo principal da aplicação, contendo a estrutura HTML da página.
* **style.css:** Arquivo com as regras de estilo CSS para a página.
* **dados.js:** Arquivo JavaScript contendo um array com os dados dos atletas (nome, descrição, link, tags).
* **app.js:** Arquivo JavaScript com a lógica da aplicação, incluindo a função `pesquisar()`.

**Observações:**

* A pesquisa é case-insensitive, ou seja, não diferencia entre letras maiúsculas e minúsculas.
* A pesquisa é realizada tanto no nome do atleta quanto na descrição e em tags associadas a cada atleta.
* O design visual da aplicação pode ser personalizado através do arquivo CSS.
* A lista de atletas pode ser expandida editando o arquivo `dados.js`.

**Próximos passos:**

* **Melhorias na pesquisa:** Implementar pesquisa por outras propriedades dos atletas (e.g., posição, nacionalidade).
* **Funcionalidades adicionais:** Adicionar filtros, ordenação dos resultados, detalhes mais completos sobre os atletas.
* **Integração com API:** Buscar dados dos atletas em uma API externa.

**Este README.md serve como um guia rápido para entender a estrutura e o funcionamento da aplicação. Para mais detalhes, consulte o código fonte.**
