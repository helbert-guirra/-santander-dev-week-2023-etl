# -santander-dev-week-2023-etl
Pipeline ETL com Python - Santander Dev Week 2023
# 🏦 Santander Dev Week 2023 - Pipeline ETL

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/helbert-guirra/santander-dev-week-2023-etl/blob/main/Santander_Dev_Week_2023.ipynb)
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Status](https://img.shields.io/badge/Status-Concluído-success.svg)

## 📋 Sobre o Projeto

Pipeline ETL desenvolvido para a **Santander Dev Week 2023**, criando mensagens de marketing personalizadas para clientes bancários baseadas em seus perfis financeiros.

### 🎯 Objetivo
Demonstrar o processo completo de ETL (Extract, Transform, Load) aplicado a dados bancários, gerando insights e comunicação personalizada para cada cliente.

## 🔄 Adaptação Realizada

> ⚠️ **Nota Importante:** A API original do desafio está indisponível.

**Solução implementada:**

| Etapa | Original | Adaptação |
|-------|----------|-----------|
| **Extract** | GET API REST | Leitura de CSV |
| **Transform** | ChatGPT API | Lógica condicional |
| **Load** | PUT API REST | Salvamento em CSV |

✅ O conceito ETL e a personalização foram mantidos integralmente.

## 🚀 Funcionalidades

### Extract
- ✅ Leitura de dados de clientes do CSV
- ✅ Validação e estruturação de dados
- ✅ Tratamento de erros

### Transform
- ✅ Análise do perfil financeiro (saldo, limites)
- ✅ Segmentação de clientes
- ✅ Geração de mensagens personalizadas

### Load
- ✅ Exportação dos dados transformados
- ✅ Criação de relatório final
- ✅ Preservação de histórico de processamento

## 💻 Como Executar

### Opção 1: Google Colab (Recomendado)
1. Clique no badge [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/helbert-guirra/santander-dev-week-2023-etl/blob/main/Santander_Dev_Week_2023.ipynb)
2. Execute: `Runtime` → `Run all`
3. Faça upload do arquivo `clientes_santander.csv`
4. Aguarde o processamento

### Opção 2: Localmente
```bash
# Clone o repositório
git clone https://github.com/helbert-guirra/santander-dev-week-2023-etl.git
cd santander-dev-week-2023-etl

# Instale as dependências
pip install pandas jupyter

# Execute o notebook
jupyter notebook Santander_Dev_Week_2023.ipynb
```

## 📊 Estrutura de Dados

### Entrada (CSV)
```csv
UserID,Name,AccountID,AccountNumber,Agency,Balance,AccountLimit,CardID,CardNumber,CardLimit
1,Devweekerson,1,01.097954-4,2030,624.12,1000.0,1,xxxx xxxx xxxx 1111,2000.0
```

### Saída (CSV + Mensagens)
```csv
UserID,Name,Balance,AccountLimit,MarketingMessage
1,Devweekerson,624.12,1000.0,"Devweekerson, investir regularmente é o caminho..."
```

## 🛠️ Tecnologias

- **Python 3.8+**
- **Pandas** - Manipulação de dados
- **Google Colab** - Ambiente de desenvolvimento

## 📈 Resultados

- ✅ 3 clientes processados com sucesso
- ✅ 3 mensagens personalizadas geradas
- ✅ Taxa de sucesso: 100%

## 🎓 Aprendizados

Este projeto demonstra:
- Extração de dados de arquivos CSV
- Transformação de dados com lógica de negócio
- Carregamento de dados estruturados
- Adaptação de soluções quando recursos não estão disponíveis
- Boas práticas de documentação

## 🔮 Melhorias Futuras

- [ ] Integração com API real do ChatGPT/Claude
- [ ] Análise visual com gráficos
- [ ] Dashboard interativo
- [ ] Segmentação avançada de clientes
- [ ] Sistema de envio de notificações

## 👨‍💻 Autor

**Helbert Guirra**
- GitHub: [@helbert-guirra](https://github.com/helbert-guirra)

## 🙏 Agradecimentos

- [DIO (Digital Innovation One)](https://dio.me)
- Santander Dev Week 2023
- Comunidade Python Brasil
- 
## IMPORTANTE
Este projeto foi construído com um viés totalmente educacional para a DIO. Por isso, disponibilizamos uma versão mais robusta dele no repositório oficial da DIO:
