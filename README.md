# claude-plugins

Catálogo dos meus plugins do [Claude Code](https://code.claude.com/docs). Cada plugin vive no
próprio repositório; este aqui só lista onde encontrá-los, para instalar tudo de um lugar só.

## Instalação

```bash
claude plugin marketplace add rsilveirafh/claude-plugins
claude plugin install <nome-do-plugin>@rsilveirafh-plugins
```

## Plugins

| Plugin | O que faz | Repositório |
|---|---|---|
| `banca-simulada` | Revisa projetos de pesquisa como uma banca ou comitê avaliador: TCC, iniciação científica, mestrado, doutorado, pós-doutorado, edital de fomento e concurso docente. Aponta o trecho, a gravidade e a sugestão; não reescreve. | [rsilveirafh/banca-simulada](https://github.com/rsilveirafh/banca-simulada) |
| `memoria` | Transforma um vault Markdown em memória com portão humano: o agente propõe edições a partir do diário (`/memoria:consolidar`) ou de fontes externas (`/memoria:assimilar`), você revisa, e só `/memoria:gravar` aplica. | [rsilveirafh/memoria-skills](https://github.com/rsilveirafh/memoria-skills) |
| `emprego` | Busca de emprego com uma fonte única de verdade: `/emprego:perfil` monta e mantém os fatos da carreira, com a origem de cada número; `/emprego:buscar`, `triar`, `candidatar`, `entrevista` e `retro` só usam o que está lá. O agente propõe, você decide e você envia. | [rsilveirafh/emprego](https://github.com/rsilveirafh/emprego) |

## Licença

MIT. Cada plugin traz a própria licença no repositório dele.
