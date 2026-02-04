# MBA em Ciência de Dados - TCC

Trabalho de Conclusão de Curso (TCC) do MBA em Ciência de Dados do ICMC-USP

## 📋 Descrição do Projeto

Este repositório contém análises e modelagens de dados meteorológicos e climáticos de diferentes estações de monitoramento, com foco em análise exploratória, modelagem preditiva e extração de dados de fontes climáticas globais.

## 🗂️ Estrutura do Repositório

```
mba-ciencia-dados/
├── notebooks/                          # Notebooks com análises
│   ├── crhea_analise_completa.ipynb   # Análise completa dos dados da estação CRHEA
│   ├── crhea_analise_completa_com_temperatura.ipynb  # Análise completa dos dados da estação CRHEA com temperatura
│   ├── crhea_analise_var.ipynb        # Modelagem preditiva com VAR (estação CRHEA)
│   ├── crhea_modelagem_pycaret.ipynb  # Modelagem preditiva com PyCaret (estação CRHEA)
│   ├── era5_monte_alegre_analise_completa.ipynb  # Análise ERA5 para Monte Alegre
│   ├── extracao_dados_era5_netcfd4.ipynb         # Extração de dados ERA5 em formato NetCDF
│   ├── iab_analise_completa.ipynb     # Análise completa da estação IAB
│   └── monte_alegre_analise_completa.ipynb       # Análise completa da estação Monte Alegre
├── sgdhm/                              # Documentação do projeto
│   └── SRS_SGDHM.pdf                  # Especificação de Requisitos de Software
└── README.md                           # Este arquivo
```

## 🔬 Tecnologias Utilizadas

- **Python 3.11+** (recomendado para PyCaret)
- **Pandas** - Manipulação e análise de dados
- **NumPy** - Computação numérica
- **Matplotlib** - Visualização de dados
- **Seaborn** - Visualizações estatísticas
- **PyCaret** - Modelagem e automação de machine learning
- **Xarray** - Leitura e processamento de arquivos NetCDF
- **Google Colab** - Ambiente de execução (conforme notebooks)

## 🚀 Como Executar os Notebooks

### Executando no Google Colab

Os notebooks foram desenvolvidos para serem executados no **Google Colab**. Para usar:

1. Acesse [Google Colab](https://colab.research.google.com/)
2. Abra um notebook do seu Google Drive
3. Certifique-se de usar **Python 3.11** nas configurações de ambiente (necessário para PyCaret)
4. Execute as células conforme instruído

> **Nota:** Os notebooks utilizam `drive.mount()` para acessar dados no Google Drive. Ajuste os caminhos conforme necessário.

## 📝 Descrição dos Notebooks

### Análises Exploratórias
- **crhea_analise_completa.ipynb** - Análise exploratória completa dos dados CRHEA
- **crhea_analise_completa_com_temperatura.ipynb** - Análise incluindo variáveis de temperatura
- **crhea_analise_var.ipynb** - Modelagem preditiva com VAR
- **monte_alegre_analise_completa.ipynb** - Análise da estação de Monte Alegre
- **iab_analise_completa.ipynb** - Análise da estação IAB

### Modelagem e Previsão
- **crhea_modelagem_pycaret.ipynb** - Modelagem preditiva automatizada com PyCaret para dados agregados mensalmente

### Dados Globais (ERA5)
- **extracao_dados_era5_netcfd4.ipynb** - Extração de dados de reanálise ERA5 de arquivos NetCDF
- **era5_monte_alegre_analise_completa.ipynb** - Análise de dados ERA5 para a região de Monte Alegre

## 📚 Variáveis Principais Analisadas

- **Precipitação (rain)** - Dados em milímetros
- **Temperatura Média (tmean)** - Dados em graus Celsius
- **Temperatura ERA5 (t2m)** - Temperatura de reanalysis a 2 metros

## 📖 Documentação Adicional

### Documentação do Sistema SGDHM: SRS – Especificação de Requisitos de Software
Veja o arquivo [SRS_SGDHM.pdf](sgdhm/SRS_SGDHM.pdf) para especificações completas do projeto.

## 👨‍🎓 Autor

Trabalho desenvolvido como TCC do MBA em Ciência de Dados do ICMC-USP.

## 📝 Licença

Este projeto é fornecido como material educacional.
