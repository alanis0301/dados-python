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
## Pré-requisitos
- [Python 3.8+]
- [pip]
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
  <img width="1409" height="648" alt="Captura de tela 2025-08-14 131905" src="https://github.com/user-attachments/assets/b59fca49-244e-4f58-962f-18c853f701af" />
  <img width="1381" height="560" alt="Captura de tela 2025-08-14 131922" src="https://github.com/user-attachments/assets/e2f7c6b1-7744-42cd-acf3-f83fe2783d4c" />
  <img width="1404" height="656" alt="Captura de tela 2025-08-17 130227" src="https://github.com/user-attachments/assets/c7680eaf-d9d6-4dcb-b725-0b7fc30289d6" />




