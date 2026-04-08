# Modelo UTP em LaTeX

Projeto reorganizado para facilitar manutenção, reutilização e expansão do trabalho acadêmico.

## Estrutura

- `trabalho.tex`: arquivo principal do projeto.
- `packages/abnt-UTP.sty`: estilo institucional e comandos auxiliares.
- `referencias/referencias.bib`: base BibTeX.
- `assets/img/`: imagens e arquivos gráficos.
- `conteudo/pre-textuais/`: resumo, listas, siglas, símbolos e sumário.
- `conteudo/textuais/`: capítulos separados em arquivos independentes.
- `conteudo/pos-textuais/`: referências, apêndices e anexos.

## Fluxo recomendado

1. Edite os metadados no arquivo `trabalho.tex`.
2. Escreva cada capítulo no respectivo arquivo em `conteudo/textuais/`.
3. Mantenha referências em `referencias/referencias.bib`.
4. Salve imagens em `assets/img/`.

## Compilação

Use `make` para compilar o PDF e `make clean` para remover arquivos temporários.
