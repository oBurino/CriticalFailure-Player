# Handout · app do jogador

O **Handout** é um app para Windows que ajuda uma mesa de **D&D 5ª edição (regras de 2014)** a jogar com o Mestre pela internet. Este é o **app do jogador**: você se conecta ao app do Mestre, monta a sua ficha e acompanha a sessão ao vivo. Ele **só funciona com a mesa de um Mestre que use o Handout**.

## O que o app faz

- **Ficha de personagem** de D&D 5e (2014), com assistente em etapas, cálculos automáticos (CA, modificadores, espaços de magia, subida e descida de nível, Forma Selvagem, equipamento e carga) e aviso das regras do livro. Importa e exporta a ficha oficial em PDF.
- **Mesa ao vivo:** o que o Mestre envia a você (pistas, calendário, diário de sessões, itens e bilhetes), o combate e as fichas do grupo.
- **Mapa de combate:** só o que o seu personagem enxerga, com movimento, alcance, ataques, magias, áreas de efeito, luz e visão; o app calcula as regras e o Mestre confere.
- **Inventário** com itens, carga, equipar armas e armaduras, sintonização e cargas de itens mágicos, e passar itens para outro jogador.
- **Anotações e diário** só seus (com busca, carimbo de data, PDF para imprimir) e anotações suas no mapa.
- **Dados 3D**, música e câmeras (o rosto de cada jogador) pela mesa.

## Baixar

Baixe o `HandoutJogador-X.Y.Z-autocontido.zip` da [última release](../../releases/latest) (aba *Releases*). Não precisa instalar nada além disso.

1. Descompacte a pasta onde quiser e abra `HandoutJogador.exe`. Se o Windows mostrar "O Windows protegeu o computador", clique em *Mais informações* > *Executar assim mesmo* (o app não é assinado).
2. Digite o **endereço** e o **código** que o Mestre passou e o seu nome. Escolha o seu personagem ou crie um novo.
3. Para atualizar, feche o app, descompacte o zip novo e substitua a pasta antiga. A sua configuração fica em `%LocalAppData%\HandoutJogador`, fora da pasta do app.

Em casas diferentes, use a rede privada (VPN) que o Mestre combinar, como o Radmin VPN ou o Tailscale.

## O que há de novo

As novidades de cada versão estão no `PatchNotes.txt` dentro do zip e nas notas de cada release.

## Créditos e licenças

O app mostra material do **System Reference Document 5.1** da Wizards of the Coast (enviado pela mesa do Mestre), licenciado em [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). O app usa a biblioteca FlashCap (Apache 2.0) para as câmeras. O texto completo dos créditos está em `Creditos.txt`, dentro do zip.

*Dungeons & Dragons* é marca da Wizards of the Coast. Este é um projeto de fã, sem afiliação nem endosso.
