# keylogger-simulado

> **Aviso importante (ética & segurança):**  
> Este repositório contém uma **simulação educativa** relacionada a keyloggers. **NÃO** use nenhum código para monitorar pessoas sem consentimento explícito — isso é ilegal e antiético. Testes que capturem teclas reais devem ser feitos **apenas** em máquinas virtuais isoladas e com autorização clara.

## Resumo
Projeto didático que demonstra, de forma segura, o conceito por trás de um keylogger. A versão neste repositório é **segura** e funciona em **modo demo**: ela *não captura* teclas do sistema, mas sim reproduz entradas a partir de um arquivo `test_input.txt`, gerando um `log.txt` para análise.

Objetivos:
- Entender como eventos de teclado podem ser gravados (conceito).
- Aprender a identificar riscos, sinais e medidas de defesa.
- Manter práticas éticas durante o aprendizado.

## O que há neste repositório
- `keylogger_demo.py` — simulação segura: lê `test_input.txt` e grava `log.txt`.
- `test_input.txt` — exemplo de entrada para gerar o `log.txt`.
- `README.md` — documentação (este arquivo).
- `.gitignore` — evita versão de arquivos sensíveis/gerados.

## Estrutura esperada
keylogger-simulado/
├── keylogger_demo.py
├── test_input.txt
├── README.md
└── .gitignore

## Pré-requisitos
- Python 3.8+  
- (Opcional) criar e ativar virtualenv:
  ```bash
  python -m venv .venv
  # Windows
  .venv\Scripts\activate
  # Linux/macOS
  source .venv/bin/activate
