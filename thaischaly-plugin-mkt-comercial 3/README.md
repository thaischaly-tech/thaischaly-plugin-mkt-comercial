# Plugin Scaldgen — Marketing e Comercial

Plugin de 20 skills de Marketing e Comercial para escritorios de advocacia, no padrao Scaldgen.

## Estrutura

```
.claude-plugin/
  ├── plugin.json
  └── marketplace.json
skills/
  ├── revisar-posicionamento/SKILL.md
  ├── analisar-concorrente/SKILL.md
  └── ... (20 skills no total)
```

## As 20 skills

**MKT Estrategico**
1. revisar-posicionamento
2. analisar-concorrente
3. desenhar-esteira
4. canais-aquisicao-entrega

**Conteudo**
5. calendario-editorial
6. roteiro-video
7. escrever-linkedin
8. artigo-site-jusbrasil
9. reaproveitar-conteudo

**Comercial**
10. atendimento-lead
11. analisar-leads-semana
12. fechar-mes-comercial
13. precificar-servico-juridico
14. estruturar-escopo-comercial
15. elaborar-proposta-comercial
16. relacionamento-posvenda

**Design e Documentos**
17. construir-identidade-marca
18. template-proposta-honorarios
19. template-contrato-honorarios
20. template-documento-operacional

## Instalacao via GitHub

1. Crie um repositorio no GitHub (ex.: `thaischaly-plugin-mkt-comercial`).
2. Suba todo o conteudo desta pasta para a raiz do repositorio (a pasta `.claude-plugin` e a pasta `skills` devem ficar na raiz).
3. No Claude, adicione o marketplace apontando para o repositorio e instale o plugin `scaldgen-mkt-comercial`.

## Atualizacao

Para editar uma skill, altere o respectivo `SKILL.md` e suba a alteracao. Para adicionar uma skill nova, crie uma pasta dentro de `skills/` com um `SKILL.md` contendo o frontmatter `name` e `description`.
