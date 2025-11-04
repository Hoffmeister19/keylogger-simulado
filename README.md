# keylogger-simulado

> **Aviso importante (ética & segurança):**  
> Este repositório contém uma **simulação educativa** sobre keyloggers. **NÃO** utilize código para monitorar pessoas sem consentimento explícito — isso é ilegal e antiético. Testes que envolvam captura real de teclas devem ser feitos **apenas** em máquinas virtuais isoladas, com snapshots, sem rede e com autorização.

## Resumo
Projeto didático que demonstra o conceito por trás de um keylogger de forma **segura**. A versão aqui disponível é um **modo demo**: não captura teclas do sistema, apenas reproduz entradas a partir de um arquivo `test_input.txt` e grava em `log.txt` para análise.

Objetivos:
- Entender como eventos de teclado podem ser registrados (conceito).
- Aprender a identificar sinais, riscos e contramedidas.
- Preservar práticas éticas ao estudar segurança.

## O que contém este repositório
- `keylogger_demo.py` — simulação segura: lê `test_input.txt` e grava `log.txt`.
- `test_input.txt` — exemplo de entrada para gerar o `log.txt`.
- `README.md` — documentação (este arquivo).
- `.gitignore` — regras para não versionar arquivos sensíveis/gerados.

## Estrutura esperada
keylogger-simulado/
├── keylogger_demo.py
├── test_input.txt
├── README.md
└── .gitignore

bash
Copiar código

## Pré-requisitos
- Python 3.8+  
- (Opcional) criar/ativar virtualenv:
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# Linux/macOS
source .venv/bin/activate
