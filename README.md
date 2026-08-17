# projeto-pratico

Trabalho de aula para testar os conhecimentos em git e github.

Passo 1: Criar uma nova branch de feature/desc-trabalho, será implementada uma nova rota para nossa API.

## Versionamento Semântico

O Versionamento Semântico é um padrão de numeração de versões de software
no formato `MAJOR.MINOR.PATCH` (ex: `1.4.2`), criado para comunicar de forma
clara e previsível o impacto de cada mudança em um projeto.

### Significado de cada parte

- **MAJOR**: incrementado quando são feitas alterações incompatíveis com
  versões anteriores (*breaking changes*), ou seja, o código que usa a
  versão antiga pode parar de funcionar.

### Quando incrementar cada parte

| Parte  | Quando incrementar                                        | Exemplo         |
|--------|-----------------------------------------------------------|-----------------|
| MAJOR  | Mudança que quebra compatibilidade com versões anteriores | `1.0.0 → 2.0.0` |

O primeiro número (`MAJOR`) começa em `0` durante o desenvolvimento inicial
(instável) e passa a `1` quando o projeto atinge sua primeira versão estável
e pública, como foi feito com a tag `v1.0.0` deste projeto.