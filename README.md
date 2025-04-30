# 📊 Análise de Comércio Municipal (Importação/Exportação)

Projeto Python para análise de dados de comércio exterior por município, com foco nas operações de importação e exportação.

## 🚀 Funcionalidades

- Análise por município específico
- Dados organizados por:
  - Seções SH2 (Top 5 por ano)
  - Valores em USD e porcentagens
  - Fluxo (Importação/Exportação)
- Período: 2008-2024 (dados quadrienais)
- Exportação automática para:
  - CSV formatado
  - Excel (com formatação condicional)

## 📋 Estrutura dos Dados

Arquivo de entrada (`./dataset/trabalho.csv`):

Estrutura do CSV:

Fluxo | Ano | Município | Código SH2 | Descrição SH2 | Valor US$ FOB

Saída gerada:

Município | Fluxo | Ano | Seção | Valor (US$) | % do Total | Tipo (Top 5/Total)


## 🛠️ Como Usar

### Pré-requisitos
- Python 3.8+
- Pandas (`pip install pandas`)
- Chardet (`pip install chardet`)  # Para detecção automática de encoding

### Execução
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/analise-comercio.git


## 🔶 Personalização

### Edite no código:

municipio = "Assis - SP"  # Altere para seu município
anos = range(2008, 2025, 4)  # Período de análise

## 📂 Exemplo de Saída

comercio_exterior_[MUNICÍPIO].xlsx contendo:

1. Aba Exportação (Top 5 seções + totais)
2. Aba Importação (Top 5 seções + totais)

## 📊 Estrutura da Saída (Excel)

### Aba de Exportação:

| Município   | Fluxo      | Ano  | Seção   | Valor (US$) | % do Total | Tipo    |
|-------------|------------|------|---------|-------------|------------|---------|
| Assis - SP  | Exportação | 2008 | 15      | 435002      | 48.92%     | Top 5   |
| Assis - SP  | Exportação | 2008 | 1       | 156199      | 17.57%     | Top 5   |
| Assis - SP  | Exportação | 2008 | 21      | 149100      | 16.77%     | Top 5   |
| Assis - SP  | Exportação | 2008 | 73      | 68136       | 7.66%      | Top 5   |
| Assis - SP  | Exportação | 2008 | 7       | 29758       | 3.35%      | Top 5   |
| Assis - SP  | Exportação | 2008 | Subtotal| 838195      | 94.26%     | Total   |
| Assis - SP  | Exportação | 2008 | Outros  | 51004       | 5.74%      | Total   |
| Assis - SP  | Exportação | 2008 | TOTAL   | 889199      | 100.00%    | Total   |

|-------------|------------|------|---------|-------------|------------|---------|

### Aba de Importação:

| Município   | Fluxo      | Ano  | Seção   | Valor (US$) | % do Total  | Tipo    |
|-------------|------------|------|---------|-------------|-------------|---------|
| Assis - SP  | Importação | 2008 | 31      | 13347388    | 90.84%      | Top 5   |
| Assis - SP  | Importação | 2008 | 84      | 595730      | 4.05%       | Top 5   |
| Assis - SP  | Importação | 2008 | 72      | 557910      | 3.80%       | Top 5   |
| Assis - SP  | Importação | 2008 | 25      | 142157      | 0.97%       | Top 5   |
| Assis - SP  | Importação | 2008 | 38      | 19319       | 0.13%       | Top 5   |
| Assis - SP  | Importação | 2008 | Subtotal| 14662504    | 99.79%      | Total   |
| Assis - SP  | Importação | 2008 | Outros  | 31083       | 0.21%       | Total   |
| Assis - SP  | Importação | 2008 | TOTAL   | 14693587    | 100.00%     | Total   |


## 🏁 Conclusão e Próximos Passos

### ✅ Análise Concluída
- Processamento automatizado de dados comerciais
- Visualização dinâmica em Excel com:
  - Tabelas pivotantes organizadas por fluxo
  - Formatação condicional (valores em milhares, 1 casa decimal)
- Documentação completa do processo

📅 Última Atualização: 04/2025
📧 Contato: adri.mayco@protonmail.com
📜 Licença: MIT - Livre para uso e modificação

