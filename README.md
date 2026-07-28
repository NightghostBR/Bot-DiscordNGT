# 🚀 Bot DiscordNGT - Integração Avançada Unturned & Discord

Um plugin completo para servidores de **Unturned (RocketMod)**.
Traga a administração do seu servidor para a palma da sua mão através do Discord!

---

## ✨ Recursos Principais

* 💬 **Sincronização de Chat Bidirecional:** O chat global do Unturned é espelhado em um canal do Discord em tempo real, permitindo que jogadores no Discord conversem com quem está dentro do jogo e vice-versa.
* 🔨 **Sistema de Moderação Completo (In-Game e Discord):** Gerencie punições de qualquer lugar! Use comandos de chat no jogo ou **Slash Commands** no Discord para gerenciar sua comunidade:
  * `/botwarn`: Adverte o jogador na tela do jogo e na DM.
  * `/bottempban`: Bane temporariamente (por segundos), informando o motivo na DM.
  * `/botban`: Banimento permanente com notificação via DM.
  * `/botunban`: Tira o ban dos jogadores usando o SteamID.
  * *Todos os comandos geram logs detalhados com embeds coloridos nos canais da Staff.*
* 🚨 **Sistema de Reportes Integrado:** Jogadores podem denunciar infratores usando `/botreport` dentro do jogo ou via Slash Command no Discord. A denúncia vai direto para um canal privado da Staff.
* 🔗 **Sistema de Verificação (Vinculação):** Os jogadores usam o comando `/vincular` no jogo para gerar um código e enviá-lo na DM do bot. O bot valida a conta e concede automaticamente o cargo de "Verificado" no Discord.
* 🔓 **Desvinculação Segura (2FA):** Através do comando `/desvincular`, o jogador gera um novo código e o envia na DM. O bot exige uma confirmação ("Sim" ou "Não") antes de limpar os dados, removendo o cargo de Verificado. Cooldown anti-spam de 10 minutos.
* 🛡️ **Anti-Raid & Escudo Pacifista:** Proteção total para jogadores pacifistas! O plugin anula *qualquer* ataque vindo de jogadores (C4, Foguetes, Tiros, Facadas) em bases protegidas, mas permite que zumbis quebrem barricadas normalmente.
* 📡 **Console Interativo:** Leia os logs do servidor e envie comandos diretamente de um canal seguro no Discord.
* 📊 **Painel de Status em Tempo Real:** Embed visual que mostra se o servidor está online/offline, mapa atual, jogadores online e atualiza tudo automaticamente.
* 💀 **Kill Feed Detalhado:** Canal exclusivo narrando as mortes do servidor (PvP, zumbis e atropelamentos).
* 🎨 **100% Customizável:** Todos os textos, mensagens de aviso, canais e IDs são facilmente configuráveis via arquivo XML.

---

## 📖 Documentação e Instalação

Para manter o nosso repositório organizado, todos os tutoriais, guias de instalação, lista de permissões e configurações do XML foram movidos para a nossa **Wiki oficial**.

👉 **[CLIQUE AQUI PARA ACESSAR A WIKI E APRENDER A INSTALAR](https://github.com/NightghostBR/Bot-DiscordNGT/wiki)** 👈

Lá você encontrará o passo a passo completo, incluindo:
1. Como criar o Bot no Developer Portal e obter o Token.
2. Onde instalar as `.dll`s no RocketMod.
3. Como preencher o arquivo `.xml` corretamente.
4. A lista completa de permissões para a sua Staff.

---

## 📜 Termos de Uso e Licença

Este projeto foi criado com o intuito de ajudar a comunidade de Unturned. Ao baixar e utilizar o **Bot DiscordNGT**, você concorda com os seguintes termos:

* ✔️ **Uso Livre:** Você é 100% livre para baixar, instalar e usar este plugin em quantos servidores próprios desejar, sem nenhum custo.

* ❌ **Proibida a Venda (Monetização):** É estritamente proibido vender, revender ou colocar este plugin atrás de *paywalls* (conteúdo pago). Este é um projeto gratuito feito para a comunidade.

* ❌ **Engenharia Reversa e Modificações:** Este é um projeto de código fechado (*Closed-Source*). É estritamente proibido descompilar o arquivo `.dll`, realizar engenharia reversa ou tentar extrair/modificar o código-fonte original. 

* ⚠️ **Direitos Autorais e Distribuição:** Você não pode clamar a autoria do plugin. A distribuição oficial e segura é feita **única e exclusivamente** através das *Releases* deste repositório do GitHub. É proibido fazer o re-upload dos arquivos em outros fóruns, sites de download ou servidores do Discord como se fossem seus.
