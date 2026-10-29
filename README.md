# PromptFlow

Engenharia de prompts passo a passo: da ideia à estrutura, do prompt ao resultado.

**Abrir o app:** https://eneas-ena.github.io/PromptFlow/

## Como funciona

- App feito em página web; pode ser instalado na tela inicial do iPad, iPhone ou Mac.
- Os dados ficam salvos no Supabase, por isso aparecem iguais em todos os aparelhos.
- Os serviços externos, como a inteligência artificial, passam pelo Worker `promptflow-ia` no Cloudflare; as chaves secretas ficam guardadas lá, nunca neste código.

## Observações

- `gerador-lemas.html` é uma ferramenta à parte, dentro do mesmo repositório.

## Como publicar uma nova versão

1. Nesta página do repositório, clique em **Add file → Upload files**.
2. Arraste os arquivos novos, com os mesmos nomes dos antigos.
3. Clique em **Commit changes**.

Em um ou dois minutos a nova versão está no ar no mesmo endereço.

---
Desenvolvido por Bispo Enéas Araújo.
