### **Projeto Pipeline de ETL: Perfil da Mulher na Tecnologia**

Este repositório serve como a fonte de dados central para o módulo prático de engenharia de dados do bootcamp de BI da WoMakersCode.

O nosso projeto consiste em construir um pipeline de ETL (Extract, Load, Transform) completo e automatizado. O objetivo é integrar múltiplas fontes de dados para criar um Data Warehouse que nos permita analisar o perfil de mulheres que trabalham com dados globalmente.

---

#### **Conteúdo do Repositório**

Neste repositório, você encontrará o nosso principal arquivo de dados:

*   **`kaggle_survey_2022_mulheres_dados.csv`**

Este arquivo é um subconjunto cuidadosamente preparado do famoso **Kaggle 2022 Developer Survey**. Ele foi pré-processado para atender aos objetivos da nossa aula, incluindo:

1.  **Filtragem por Relevância:** Contém apenas respostas de participantes que se identificam como **mulheres** e que atuam em **cargos na área de dados**.
2.  **Seleção de Colunas:** Apenas as colunas mais relevantes para nossa análise foram mantidas (demografia, experiência, salário, habilidades, etc.).
3.  **Renomeação e Limpeza:** As colunas com nomes crípticos (como `Q29`) já foram renomeadas para nomes intuitivos (como `salario_anual_usd`) para facilitar o trabalho.

---

#### **Como Usar este Arquivo na Aula**

Durante a aula no Google Colab, usaremos o link "Raw" deste arquivo para baixá-lo diretamente para nosso ambiente de trabalho, garantindo que todas estejamos usando a mesma fonte de dados.
