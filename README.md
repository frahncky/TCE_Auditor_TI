# TCE-MA 2026 — Auditor Estadual de Controle Externo — TI

Material de preparação para o **Cargo 15 — Auditor Estadual de Controle Externo — Tecnologia da Informação**, conforme o Edital nº 1 do TCE-MA, de 6 de julho de 2026.

- Banca: **Cebraspe**
- Prova: **29/11/2026**
- Objetiva: **40 questões de conhecimentos gerais + 60 específicas**
- Discursiva: **1 peça técnica + 2 questões discursivas**
- Atualização-base: **15/08/2026**

## Volumes

### `main_teoria.tex`
Apostila exclusivamente de teoria:
- conceitos aprofundados;
- exemplos;
- tabelas;
- figuras e diagramas;
- mapas mentais funcionais;
- conhecimentos gerais e específicos do edital.

### `main_questoes.tex`
Apostila exclusivamente de questões:
- questões classificadas visualmente de ★ a ★★★★;
- questões em perfil Cebraspe e principais bancas;
- nos itens de julgamento, o enunciado é seguido apenas por `(  ) certo` e `(  ) errado`;
- peças técnicas e questões discursivas;
- simulado completo;
- gabaritos e resoluções após os respectivos blocos de questões.

## Estrutura

```text
TCE_Auditor_TI/
├── main_teoria.tex
├── main_questoes.tex
├── config/
├── capitulos/
├── questoes/
├── solucoes/
├── simulados/
├── atualizacoes/
└── .github/workflows/build-pdf.yml
```

## Compilação

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main_teoria.tex
latexmk -pdf -interaction=nonstopmode -halt-on-error main_questoes.tex
```

O GitHub Actions gera os dois PDFs no artefato `TCE-MA-Auditor-TI-2026`.