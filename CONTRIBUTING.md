# Como manter o contexto entre as três

## Pelo navegador

1. Abra `CONTEXTO-ATUAL.md` para retomar o projeto.
2. Edite o arquivo do assunto em `docs/` pelo botão de edição do GitHub.
3. Se mudou uma decisão vigente, atualize também `CONTEXTO-ATUAL.md`.
4. Acrescente uma entrada em `CHANGELOG.md`.
5. Salve em um commit com mensagem clara. Para revisão entre vocês, use uma branch e abra um pull request.

As outras integrantes precisam de permissão de escrita para editar o repositório. Os nomes de usuário ainda não foram fornecidos; os convites não foram enviados nesta sessão.

## Com um assistente

> Leia o contexto deste repositório. Nós decidimos [mudança]. Atualize o documento do assunto, o contexto atual e o changelog e envie ao GitHub.

Para começar uma sessão de design:

> Leia CONTEXTO-ATUAL.md e docs/03-identidade-visual.md. Abra o Figma indicado e considere as referências do moodboard como principais. Mantenha a apresentação visual e com pouco texto.

## Com Git

```sh
git clone https://github.com/giopimenta0310-jpg/bafafa.git
cd bafafa
git pull --ff-only
# editar os documentos necessários
git add CONTEXTO-ATUAL.md CHANGELOG.md docs/
git commit -m "docs: registrar decisão sobre o pijama"
git push
```

É necessário autenticar com uma conta que tenha acesso. Se houver mudanças de outra pessoa, atualizar antes de enviar e resolver o conflito preservando as duas contribuições. Não usar force-push.

## Onde salvar

| Conteúdo | Local |
|---|---|
| Resumo vigente e próximos passos | `CONTEXTO-ATUAL.md` |
| Direção, personas, fontes e pendências | `docs/` |
| Códigos de cor vigentes | `design/paleta.json` |
| Imagens de referência | `assets/` |
| Origem e categoria das imagens | `referencias/manifesto.json` e `referencias/CATALOGO.md` |
| Transcrições | `fontes/` |
| Documentos antigos | `historico/` |

Imagens de terceiros servem como referências; não são identidade final nem recebem licença de uso por estarem neste repositório. Não atribuir autoria das referências às integrantes.

## Modelo de atualização

```md
### AAAA-MM-DD — assunto
- Mudou: ...
- Decidido por: ... / proposta do assistente, quando não houver confirmação.
- Aplicado em: arquivo ou link.
- Pendente: ...
```

Não há sincronização contínua com chats, Figma ou Pinterest. Uma conversa só estará disponível em outro dispositivo após seu conteúdo relevante ser salvo e enviado ao repositório.
