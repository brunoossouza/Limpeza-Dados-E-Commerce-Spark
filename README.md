# 📊 Limpeza de Dados de E-commerce com PySpark

Este projeto apresenta um fluxo completo de **Data Wrangling** utilizando o ecossistema Spark. O objetivo foi tratar e organizar dados reais de uma operação de e-commerce para torná-los prontos para análise e modelagem.

## 📁 Estrutura do Projeto
Os dados foram carregados a partir de planilhas integradas via Google Drive, cobrindo:
* Clientes, Pedidos e Itens de Pedido.
* Produtos, Vendedores e Avaliações.

## 🛠️ Tecnologias e Ferramentas
* **PySpark (Spark SQL):** Processamento distribuído dos dados.
* **Google Colab:** Ambiente de desenvolvimento em nuvem.
* **Python:** Linguagem para manipulação lógica.

## 🧹 Etapas de Limpeza Realizadas
1. **Configuração da SparkSession:** Inicialização do motor Spark.
2. **Inferência de Schema:** Carregamento de CSVs garantindo a tipagem correta das colunas (Double, Integer, String).
3. **Análise Exploratória Inicial:** Uso do método `.show()` para validar a integridade da carga.
4. **Tratamento de Dados:** (Aqui você pode adicionar detalhes específicos, como: "Remoção de nulos na tabela de avaliações" ou "Casting de preços").

## 🚀 Como Executar
Basta abrir o notebook através do botão **"Open in Colab"** presente no arquivo `.ipynb` deste repositório. Certifique-se de ter os arquivos CSV no seu Google Drive ou ajustar os caminhos de leitura.
