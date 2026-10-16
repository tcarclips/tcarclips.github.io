---
title: Política de Privacidade — Motor Shorts
---

# Política de Privacidade — Motor Shorts

Última atualização: 16 de outubro de 2026

O Motor Shorts é uma ferramenta interna do canal Tcar Clips ([youtube.com/@Tcar_clips](https://www.youtube.com/@Tcar_clips)). Ela é usada apenas pelo próprio dono do canal para gerar vídeos curtos e publicá-los no canal @Tcar_clips. O aplicativo não é oferecido ao público e não tem outros usuários.

## Uso dos Serviços de API do YouTube

O Motor Shorts usa os **Serviços de API do YouTube** (API de Dados do YouTube v3). Ao usar esta ferramenta, você concorda com os [Termos de Serviço do YouTube](https://www.youtube.com/t/terms). O tratamento de dados pelo Google é regido pela [Política de Privacidade do Google](https://policies.google.com/privacy).

## Dados acessados

A ferramenta solicita uma única permissão: enviar vídeos para o canal autorizado (escopo `youtube.upload`, método `videos.insert`). Ela não lê, coleta, exibe ou armazena dados de espectadores, comentários, inscritos, estatísticas, contatos ou qualquer outra informação de usuários ou canais do YouTube.

## Armazenamento e compartilhamento

O único dado guardado é o token de autorização OAuth do próprio dono do canal, mantido como segredo criptografado no GitHub (GitHub Actions Secrets) e usado apenas para publicar os vídeos. Nenhum dado é vendido, compartilhado ou transferido a terceiros. A ferramenta não usa cookies nem armazena dados em dispositivos de usuários.

## Exclusão de dados e revogação de acesso

O acesso pode ser revogado a qualquer momento na página de permissões de segurança do Google: [myaccount.google.com/permissions](https://myaccount.google.com/permissions). Ao revogar, o token deixa de funcionar imediatamente. Para excluir o token armazenado, basta apagar o segredo `YT_REFRESH_TOKEN` do repositório; também é possível solicitar a exclusão pelo e-mail abaixo, e ela é feita em até 7 dias.

## Contato

Dúvidas sobre esta política: tcarclips@gmail.com
