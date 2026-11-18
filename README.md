# Global Solution 2026.2 - Data Science and Analytics

Base de dados usada no notebook `GS_DataScience_Celulares_SP.ipynb` (subtração de celulares na cidade de São Paulo em 2025).

- **Fonte original:** Secretaria da Segurança Pública do Estado de São Paulo (SSP-SP), Portal de Estatísticas, Consultas > Bases de Dados: https://www.ssp.sp.gov.br/estatistica/consultas
- **Arquivo original:** `CelularesSubtraidos_2025.xlsx`, aba `CELULAR_2025`, com 383.635 linhas e 55 colunas (108 MB).
- **Arquivo deste repositório:** `CelularesSubtraidos_2025.csv.gz`, com o mesmo conteúdo da aba convertido para CSV compactado (19 MB).

## Por que esta cópia existe

No último teste, em 18/11/2026, o site da SSP estava instável: o download da planilha pelo navegador parava no meio, e no Google Colab a conexão com o site esgotava o tempo (timeout) sem baixar o arquivo. Para o notebook não depender da disponibilidade do site, o mesmo conteúdo da aba `CELULAR_2025` foi convertido para CSV compactado e guardado aqui.

O notebook baixa esse arquivo em poucos segundos e chega aos mesmos resultados da planilha original: as 383.635 linhas e as 55 colunas foram comparadas uma a uma e são idênticas.

## Integrantes

- João Vitor Anunciação Oliveira - RM567539
- Paulo Ribeiro Marinho - RM567459
