# e-NatJus Scraper

Este projeto é um web scraper em Python para extrair notas técnicas do e-NatJus (`https://www.pje.jus.br/e-natjus`) sobre "dieta enteral". Usa Selenium para navegação e Requests para baixar PDFs, salvando os dados em CSV.

## Funcionalidades
- Extrai notas técnicas das páginas da pesquisa "dieta enteral".
- Gera um CSV com 36 colunas, incluindo `URL`, `CID`, `Diagnóstico`, `Conclusão`, etc.
- Processa HTML e PDFs dinamicamente.

## Pré-requisitos
- Python 3.8+
- Google Chrome
- Dependências: `requirements.txt`

## Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/e-natjus-scraper.git
   cd e-natjus-scraper
