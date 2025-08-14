# dados-python
# Dashboard de Salários na Área de Dados

Este mini projeto foi desenvolvido durante a **Imersão de Dados em Python** da Alura, passando algumas etapas:  
- Limpeza e preparação de dados  
- Criação de DataFrames para testar diferentes formas de correção e análise  
- Geração e análise de gráficos com **Seaborn** e **Plotly**  
- Criação de um **Dashboard Interativo** usando **Streamlit**

O objetivo é permitir a **visualização e filtragem de dados salariais** na área de dados, com métricas e gráficos interativos.

---

## Funcionalidades

- **Filtros interativos** por ano, senioridade, tipo de contrato e tamanho da empresa  
- **Métricas principais**: salário médio, salário máximo, total de registros e cargo mais frequente  
- **Gráficos interativos** com Plotly
- **Tabela de dados filtrados** diretamente no dashboard

---

## Instalação

Clone o repositório e crie um ambiente virtual:

```bash
git clone "linkdorepositorio"
cd repositorio
python -m venv .venv
```

Ative o ambiente virtual:
- Windows
```bash
.venv\Scripts\activate
```
- Mac/Linux
```bash
source .venv/bin/activate
```
Instale as dependências 
```bash
pip install -r requirements.txt
```
## Executando o Dashboard
No terminal, com o ambiente virtual ativo, execute:
```bash
streamlit run project.py
```

## Telas do Dashboard
- Tela inicial
  <img width="1916" height="887" alt="Captura de tela 2025-08-14 131855" src="https://github.com/user-attachments/assets/2304bc94-07c6-43de-81cd-9caf7c290d8f" />
- Gráficos
  <img width="1465" height="818" alt="Captura de tela 2025-08-14 131905" src="https://github.com/user-attachments/assets/b633d2e4-d26c-497d-b2c7-1ce8731c6a80" />
  
  
<img width="1456" height="560" alt="Captura de tela 2025-08-14 131922" src="https://github.com/user-attachments/assets/c99988b4-b7e3-44be-baaf-a158b76e92a9" />



