# Análise do Comportamento de Usuários de Aplicativos Móveis

Este repositório contém o projeto de análise do comportamento de usuários de aplicativos móveis, com foco inicial na exploração e tratamento de dados em Python.
Os dados foram gerados em um estudo de 2014, por Lim, Soo Ling, "Worldwide Mobile App User Behavior Dataset", https://doi.org/10.7910/DVN/27459, Harvard Dataverse, V1, University College London

## 📌 Visão Geral do Projeto

O objetivo inicial deste projeto é explorar e entender os padrões de comportamento de usuários de aplicativos móveis a partir de um conjunto de dados abrangente, utilizando Python para as etapas de limpeza e análise exploratória. Buscamos extrair insights valiosos sobre as preferências e interações dos usuários com aplicativos.

## 🚀 Status Atual do Projeto

No momento, o projeto está focado na fase de **Análise e Tratamento de Dados com Python**, utilizando o ambiente Jupyter Notebook.

## 📂 Estrutura do Repositório

A estrutura de pastas do projeto está organizada da seguinte forma:

* `APP_USAGE/` (Pasta raiz do projeto)
    * `data/`
        * `raw/`: Contém os conjuntos de dados brutos originais.
            * `mobile_app_user_dataset_1.xlsx`: O conjunto de dados principal utilizado na análise.
            * `mobile_app_user_survey_coded.doc`: Documentação de suporte relacionada à pesquisa.
    * `.gitignore`: Arquivo de configuração do Git para ignorar arquivos e pastas específicos.
    * `script_uso_de_apps.ipynb`: O Jupyter Notebook principal contendo todo o código Python para tratamento, análise exploratória e cálculo de porcentagens.
    * `.ipynb_checkpoints/`: Pasta gerada automaticamente pelo Jupyter Notebook para checkpoints, ignorada pelo Git.
* `README.md`: Este arquivo, descrevendo o projeto.

## ⚙️ Configuração e Execução

Para replicar a análise em Python, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SeuUsuario/NomeDoSeuRepositorio.git](https://github.com/SeuUsuario/NomeDoSeuRepositorio.git)
    cd NomeDoSeuRepositorio
    ```
    *(Lembre-se de substituir `SeuUsuario/NomeDoSeuRepositorio.git` pelo caminho real do seu repositório no GitHub.)*

2.  **Configurar o ambiente Anaconda:**
    É recomendável criar um ambiente virtual para este projeto.
    ```bash
    conda create -n analise_app python=3.9 # Ou a versão que você usou, ex: 3.8
    conda activate analise_app
    ```

3.  **Instalar as dependências:**
    ```bash
    pip install pandas matplotlib numpy
    # Se você usar mais bibliotecas, adicione-as aqui ou crie um requirements.txt
    ```

4.  **Baixar os dados:**
    O conjunto de dados original foi obtido do Kaggle. Faça o download de:
    [Worldwide Mobile App User Behavior Dataset](https://www.kaggle.com/datasets/patriciacarvalhom/worldwide-mobile-app-user-behavior-dataset)
    Após o download, coloque o arquivo `mobile_app_user_dataset_1.xlsx` (e qualquer outro dado bruto relevante) na pasta `data/raw/` dentro do seu projeto.

5.  **Abrir o Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Navegue até `script_uso_de_apps.ipynb` na raiz do projeto e execute as células.

## 📈 Futuras Implementações

As seguintes etapas estão planejadas para o futuro do projeto, visando expandir a análise e a visualização dos dados:

* **📊 Excel:** Organização e estrutura final dos dados tratados em Python para facilitar a importação em ferramentas de Business Intelligence.
* **📈 Power BI:** Criação de um dashboard interativo com filtros e gráficos comparativos para uma visualização mais aprofundada dos insights.

## 🤝 Contribuições

Contribuições são bem-vindas! Se tiver sugestões ou melhorias, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.
