# Busca de preços com Selenium

O projeto consiste em realizar o orçamento de produtos pré-determinados (que estão em uma planilha) e salvar em um dataframe todos os itens que estiverem de acordo com alguns requisitos, que são eles:

- Preço mínimo
- Preço máximo
- Termos obrigatórios que devem aparecer no nome do produto
- Termos banidos que não podem aparecer no nome do produto

Esses requisitos foram colocados para garantirmos que somente iremos salvar no dataframe os produtos que estão dentro do padrão exigido pela empresa.

**Exemplo de um pedaço da tabela com os produtos a serem buscados:**
<div align = 'center'>
 <img src='https://user-images.githubusercontent.com/114163919/196525924-c90beba3-ad9d-470e-a322-5d8f799e9d3f.png' width = 65%/>
</div>

Por fim, após as buscas dos orçamentos e criação do dataframe com os itens que estão no padrão proposto, os dados podem ser enviados diretamente por e-mail através de uma tabela em formato html ou os dados podem ser salvos no computador em formato de excel.

No projeto em questão, escolhi enviar diretamente por e-mail através da tabela em html.

**Exemplo da tabela final enviada por e-mail:**

<div align = 'center'>
 <img src='https://user-images.githubusercontent.com/114163919/196526039-e2b6235d-1bb8-4a05-b02f-be3a579e997f.png' width = 80% />
</div>

Os orçamentos foram realizados no site do **Google Shopping** e do **Buscapé**.

