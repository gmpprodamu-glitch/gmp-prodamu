# GMP PRODAMU — Porta de entrada

Página pública de acesso ao Code App **Prontuário Guardiã Maria da Penha**.

- Endereço: https://gmpprodamu-glitch.github.io/gmp-prodamu/
- Conteúdo: HTML/CSS/JS estáticos + brasão PRODAMU autorizado.
- Segurança: este repositório **não contém** dados de assistidas, GCMs,
  SharePoint, tokens, senhas ou arquivos do Code App.
- O botão "ENTRAR NO GMP" aponta somente para o player oficial do Power Apps.
- PWA: é possível instalar "GMP PRODAMU" (Android/Windows); o ícone instalado
  encaminha direto para o runtime do Code App. No iPhone, use
  Compartilhar → Adicionar à Tela de Início.
- O service worker cacheia somente os assets públicos da landing — nunca dados
  do GMP, respostas de APIs, tokens ou conteúdo SharePoint.
