---
title: "Lição 12 - Publique o site com o GitHub Pages"
description: "Use o aplicativo GitHub Copilot para configurar um fluxo de trabalho do Pages, revisar a pull request e verificar se o Space Quiz está no ar."
authors:
  - jamesmontemagno
lastUpdated: 2026-10-12
---

Publique o Space Quiz no GitHub Pages para que qualquer pessoa possa acessá-lo. O Copilot pode preparar o fluxo de trabalho e orientar a publicação, mas você é responsável por revisar as alterações e confirmar que o site está no ar.

Nesta lição, você vai:

- Pedir ao Copilot para configurar a publicação no GitHub Pages.
- Revisar o fluxo de trabalho e a pull request antes de fazer o merge.
- Acompanhar a publicação e verificar o site publicado.

## Cenário

O Space Quiz já está em um repositório do GitHub, mas as pessoas ainda precisam de uma forma simples de experimentá-lo. Publicar o site de arquivo único com o GitHub Pages o disponibiliza em uma URL pública sem adicionar um servidor ou dependência de runtime.

## Peça ao Copilot para publicar o site

Na sessão do aplicativo Copilot para `space-quiz`, envie este prompt:

```plaintext
Habilite o GitHub Pages para este repositório. Crie um fluxo de trabalho do GitHub Actions que compile o site, se necessário, e o publique no GitHub Pages. Se ainda não houver um README, adicione um descrevendo o aplicativo e como executá-lo localmente. Crie uma pull request com essas alterações e faça o merge depois que as verificações obrigatórias forem aprovadas. Acompanhe a publicação até que ela seja concluída e, em seguida, informe a URL final do site no ar. Se você não tiver permissão para habilitar o Pages ou fazer o merge, diga exatamente o que preciso aprovar ou fazer; não informe que deu certo até que o site esteja no ar.
```

![Diagrama em três etapas: uma pull request do space-quiz mesclada; uma execução bem-sucedida do GitHub Actions Deploy website com as etapas Build website, Upload artifact e Deploy to Pages; e o Space Quiz publicado em yourname.github.io/space-quiz/.](../../../_images/first-steps-app-pages-deploy.svg)

> [!WARNING]
> Este prompt pede que o agente crie e faça o merge de uma pull request e altere as configurações do Pages no repositório. Antes de continuar, revise o diff, as permissões de publicação e todas as solicitações de aprovação do GitHub.

## Revise o fluxo de trabalho e verifique a publicação

1. Confirme que o README só foi adicionado se o repositório ainda não tinha um.
2. Revise as alterações da pull request, incluindo as etapas de build e publicação do fluxo de trabalho.
3. Faça o merge somente depois que as verificações obrigatórias da pull request forem aprovadas.
4. Acompanhe a execução de publicação do GitHub Actions até ela ser concluída com sucesso.
5. Abra a URL informada e confirme que o Space Quiz carrega.

Se o agente não puder habilitar o Pages ou fazer o merge da pull request, siga as instruções específicas fornecidas. Não considere a tarefa concluída até que a publicação seja bem-sucedida e o site esteja no ar.

## Resumo e próximos passos

O Space Quiz agora está disponível em um site publicado, e você verificou a publicação em vez de confiar apenas no relato do agente. Continue para a [Lição 13: Revisão e próximos passos][next-lesson].

[next-lesson]: ../13-review/
