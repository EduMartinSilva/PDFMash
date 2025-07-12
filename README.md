# PDFMash

**PDFMash** é um script Python simples e eficiente pra mesclar PDFs em um único arquivo. Ideal pra juntar vários documentos sem dor de cabeça.

---

## Como preparar e rodar

1. Crie uma pasta chamada `arquivos` **no mesmo diretório onde está o seu script `main.py`** (ou o nome que você usar).
2. Coloque todos os seus arquivos PDF dentro dessa pasta.
3. **Importante:** numere ou nomeie os arquivos de forma que a ordem dos PDFs fique correta ao serem listados e mesclados (exemplo: `01_documento.pdf`, `02_relatorio.pdf`, `03_contrato.pdf`). O script vai ordenar os arquivos em ordem alfabética antes de juntar, então a enumeração garante a ordem certinha.
4. Rode o script normalmente.

---

## Exemplo do fluxo de uso
seu-projeto/
├── main.py
└── arquivos/
├── 01_intro.pdf
├── 02_capitulo1.pdf
├── 03_capitulo2.pdf
