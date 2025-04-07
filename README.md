# Análise de Qualidade de Código nas Submissões de Estudantes

Este repositório contém uma análise detalhada das **submissões de código realizadas por estudantes** em linguagens **C** e **Python**, considerando tanto entregas **parciais** quanto **finais**. A análise foi feita com ferramentas de análise estática de código e tem como objetivo mapear padrões de erros, más práticas e violações de estilo comuns.

## 📁 Estrutura dos Arquivos

- `warnings_py_parcial.md`: Avisos encontrados nas submissões **parciais** em **Python**
- `warnings_py_final.md`: Avisos encontrados nas submissões **finais** em **Python**
- `warnings_c_parcial.md`: Avisos encontrados nas submissões **parciais** em **C**
- `warnings_c_final.md`: Avisos encontrados nas submissões **finais** em **C**

Cada arquivo apresenta uma tabela com:
- **Mensagem de Aviso**: descrição do problema identificado pela ferramenta
- **Quantidade de Ocorrências**: quantas vezes o problema apareceu nas submissões
- **Categoria**:
  - `Formatação`: problemas de indentação, espaçamentos, linhas em branco, etc.
  - `Nomeação de Funções`: funções que não seguem o padrão de nomenclatura
  - `Nomeação de Variáveis`: variáveis, argumentos ou constantes com nomes fora do padrão
  - `Outro`: outros problemas, como uso de `eval`, má prática em castings, ausência de comentários, etc.

## 🎯 Objetivo da Análise

A análise visa:
- **Identificar padrões de erro recorrentes** entre estudantes
- **Avaliar a evolução** da qualidade do código entre as versões parciais e finais
- **Promover boas práticas** de codificação desde os primeiros estágios da formação acadêmica

## 📈 Exemplos de Resultados

### Python (Parcial)
- `Bad indentation. Found 1 spaces, expected 4` – 692.148 ocorrências
- `Missing function or method docstring` – 154.573 ocorrências
- `Use of eval` – 76.192 ocorrências

### C (Parcial)
- `Tab found; better to use spaces` – 5.613.231 ocorrências
- `Missing space before {` – 1.366.562 ocorrências
- `Functions names should be lower cased` – 215.569 ocorrências

### Comparação com as Submissões Finais
Nos arquivos finais é possível observar:
- **Redução geral no número de avisos**
- **Melhoria na formatação**
- **Melhor aderência a convenções de nomenclatura**
- **Correção de práticas arriscadas e advertências críticas**

## 🧠 Conclusão

Estes dados servem como insumo para feedbacks pedagógicos, ajustes curriculares e possíveis automatizações de revisão de código. Espera-se que com base nesses resultados, os estudantes possam refinar suas habilidades de escrita de código limpo e profissional.

---

> Este repositório pode ser utilizado como material de apoio em disciplinas de Programação, Engenharia de Software ou em iniciativas de análise automática de código.
