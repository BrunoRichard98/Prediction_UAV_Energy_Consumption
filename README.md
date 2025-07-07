![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) 
## Descrição dos Arquivos

### Arquivos Principais

- **Prediction_UAV_energy_consumption.ipynb**  
  Notebook principal para previsão de consumo de energia de UAVs utilizando os dados disponíveis.

- **testing_rf.ipynb**  
  Notebook para testes e validação de modelos de Random Forest.

- **best_rf.csv**  
  Arquivo CSV contendo os melhores resultados obtidos com o modelo Random Forest.

- **results_rf.csv**  
  Resultados detalhados do modelo Random Forest.

- **df_train.csv**  
  Arquivo CSV contendo os dados de treinamento utilizados para construir os modelos.

---

### Diretório `Data_Mini_Projet_DATA_2025`

Este diretório contém os dados brutos e combinados utilizados nos notebooks:

- **flights.csv**  
  Combinação dos dados disponíveis em `flights.zip` e `parameters.csv`.  
  - **Número de variáveis:** 28  
  - **Número de casos/linhas:** 257,896  
  - **Códigos de dados ausentes:** "NA" (não há dados ausentes neste conjunto).  
  - **Descrição das variáveis:**  
    - `flight`: Código do voo realizado.  
    - `time`: Tempo decorrido no voo em segundos.  
    - `wind_speed`: Velocidade do vento em m/s.  
    - `wind_angle`: Ângulo do vento em graus.  
    - `battery_voltage`: Voltagem do sistema em Volts.  

- **parameters.csv**  
  Arquivo contendo os parâmetros de voo.  
  - **Número de variáveis:** 7  
  - **Número de casos/linhas:** 209  
  - **Códigos de dados ausentes:** "NA" (não há dados ausentes neste conjunto).  
  - **Descrição das variáveis:**  
    - `flight`: Código do voo realizado.  
    - `speed`: Velocidade horizontal programada durante o cruzeiro em m/s.  

- **README.txt**  
  Arquivo de documentação detalhada sobre os dados e convenções de nomenclatura.

---

## Notas Adicionais

- **Relacionamento entre arquivos:**  
  - `flights.csv` combina os dados de `parameters.csv` e os arquivos CSV individuais contidos em `flights.zip`.  
  - `raw_files.zip` contém os dados brutos coletados por cada sensor para cada voo.

- **Citação:**  
  Caso utilize os dados ou modelos deste repositório, por favor, cite o autor principal:  
  - Email: csamaras@cmu.edu  

---

## Contato

Para dúvidas ou suporte, entre em contato com o autor principal:  
- Email: csamaras@cmu.edu  