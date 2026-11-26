# The Sims Quatro Estações

**Primeira beta pública · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · **Português (Brasil)** · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

As quatro estações chegam ao The Sims Legacy Collection. Uma tempestade pode fazer seus Sims correrem para dentro de casa, e a neve fresca se acumula no jardim. Ao carregar uma partida, o lote retoma o clima e o calendário que tinha quando você salvou. Este é um mod não oficial feito por fãs.

![Neblina em um lote residencial no The Sims Legacy Collection](../media/weather.png)

[Folhagem de outono](../media/autumn.png) · [Um jardim coberto de neve](../media/winter.png) · [Galeria completa (ZIP, 8 imagens)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## O clima no seu lote

- Chuva, tempestades, granizo, neve, nevascas e neblina acompanham as estações. Com a estação meteorológica opcional, você também pode escolher o clima, inclusive chuva e neblina mágicas.
- No outono, as folhas mudam de cor. No inverno, a neve cobre as ruas, as plantas e os objetos ao ar livre, até as lápides. As crianças podem brincar nas poças, e os Sims podem fazer um boneco de neve quando houver neve suficiente.
- Sims, cães e gatos podem ficar encharcados e procurar abrigo. A chuva pode apagar incêndios ao ar livre. Você pode ajustar separadamente os efeitos do clima na jogabilidade. Durante o carregamento, toca uma música original, *Pocztówka z doliny*.

## Download e instalação

Você precisa ter o The Sims Legacy Collection completo, versão **1.10.0** ou **1.10.7**, instalado no Windows de 64 bits, além do [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Reserve alguns GB de espaço livre e espaço extra para uma cópia das suas partidas salvas.

1. Na página do projeto no GitHub, abra [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1), escolha a versão **1.0.0-beta.1** e baixe `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` na seção **Assets**.
2. Salve a partida e feche o jogo e o aplicativo de clima. Extraia todo o ZIP para uma nova pasta. Deixe a pasta `data` ao lado de `Setup.exe`.
3. Execute `Setup.exe` e selecione a pasta do jogo que contém `sims.exe`. Clique em **Verificar compatibilidade** e depois em **Instalar**. O instalador verifica os arquivos, cria cópias de segurança e aplica as alterações aos arquivos do seu jogo. Um conflito em um arquivo obrigatório interrompe a instalação.
4. Aguarde a confirmação. Para jogar, use o atalho **The Sims Cztery Pory Roku** na área de trabalho ou `Launch-weather.cmd` na pasta do aplicativo instalado. Assim, o jogo é iniciado junto com o clima e o componente que recupera o clima das partidas salvas.

Deixe o instalador aplicar as alterações nos arquivos do jogo. Ele verifica as somas de verificação antes e depois de cada alteração e mantém `sims.exe` intacto. Os objetos opcionais só recebem as alterações se você já tiver instalado uma versão compatível deles.

## Durante o jogo

Carregue um lote para ver o clima automático. Pressione `Ctrl+Alt+R` para ajustar a precipitação, o som, o calendário e os efeitos na jogabilidade. Os menus dos objetos usam o idioma do jogo. Por padrão, o painel de clima também usa esse idioma. Se você escolher outro idioma para o painel, a mudança entrará em vigor na próxima vez que iniciar o jogo.

## Backup, atualização e desinstalação

O instalador faz cópias de segurança dos arquivos afetados, das partidas salvas e dos dados de clima. Mantenha `backups` e `install-state.json` na pasta do aplicativo em `%LOCALAPPDATA%\TS1CzteryPoryRoku`. Há também dados de clima dos lotes em `%LOCALAPPDATA%\TS1RainOverlay`. Você pode restaurar as partidas manualmente a partir das cópias com o jogo fechado. Mantenha as pastas do jogo e do aplicativo nos locais de instalação.

O backup inclui `Electronic Arts\The Sims 25` na pasta de jogos salvos do Windows e as pastas `UserData`, `UserData2` que existirem na pasta do jogo. Cada backup fica em uma pasta separada. O arquivo `save-backup.json` registra os caminhos originais e as somas de verificação para você identificar os arquivos que deseja restaurar.

Para atualizar o mod, feche o jogo e o aplicativo de clima, extraia o novo ZIP para uma pasta separada e selecione a mesma pasta do jogo no novo instalador. Para remover o mod, feche os dois programas e escolha **Opções → Desinstalar** na cópia de `Setup.exe` que você guardou. Os arquivos originais serão restaurados e as partidas e os backups serão preservados. Se pretende voltar a usar os objetos do mod, guarde uma cópia do lote antes de jogar sem ele.

Se a instalação for interrompida, escolha **Opções → Reverter alterações**. Se a restauração indicar que um arquivo foi modificado, guarde a mensagem e os backups. Se o Windows negar acesso de gravação, execute `Setup.exe` como administrador usando a mesma conta do Windows.

## Testes da beta e relatos de erros

Os testes de instalação abrangem as duas versões compatíveis do jogo. Relatos de partidas longas nos 17 idiomas e de testes em outros PCs, inclusive em máquinas mais modestas, são bem-vindos. Se os efeitos de clima estiverem lentos com a sobreposição da NVIDIA ativada, teste o jogo com ela desativada.

Use a seção [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) no GitHub para relatar um problema. Informe as versões do jogo e do mod, o idioma e os passos para reproduzir o erro. Em caso de falha visual, inclua uma captura de tela e indique o clima, o zoom, o ângulo da câmera, o andar e a visualização das paredes. Para falhas de instalação, inclua a mensagem completa. Confira se os logs contêm caminhos de arquivos pessoais antes de compartilhá-los.
