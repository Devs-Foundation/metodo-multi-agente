# Método Devs Foundation — Sistema Multi-Agente com Cérebro Partilhado

**Defensive Publication — Prior Art**

Este repositório documenta o método Devs Foundation para construir sistemas multi-agente com memória partilhada via git, protocolo de consenso, e comunicação assíncrona entre agentes.

**Licença:** Domínio Público — Livre de usar, adaptar, e construir sobre.

**Data de publicação:** 2026-06-29
**Autor:** Rui Almeida (Devs Foundation)
**Organização:** [Devs Foundation](https://github.com/Devs-Foundation)

---

## O que é este método?

Um sistema onde múltiplos modelos de IA (de diferentes providers) partilham o mesmo cérebro persistente via git, debatem decisões por consenso, e executam trabalho de forma coordenada — sem depender de APIs proprietárias, orquestradores centrais, ou plataformas fechadas.

## Documentos

| Documento | Descrição |
|-----------|-----------|
| `METODO.md` | Guia completo — do zero ao sistema em produção |

## Resumo

- **Memória infinita** — O cérebro (vault git) não tem janela de contexto
- **Custo próximo de zero** — Git é grátis, ferramentas open-source
- **Segurança máxima** — Sem interface web, só SSH com chave
- **Resiliência total** — Se um modelo for deletado, outro faz clone e continua
- **Independência de vendor** — Funciona com qualquer modelo de qualquer provider

---

*Devs Foundation — 2026*
