# Script de Instalação Automatizada com Winget

Este repositório contém um script de instalação automatizada utilizando o **Winget**, o gerenciador de pacotes da Microsoft para Windows. O objetivo é facilitar a configuração de um ambiente de trabalho completo, instalando diversas ferramentas essenciais divididas em categorias específicas.

## Índice

- [Pré-requisitos](#pré-requisitos)
- [Como Usar](#como-usar)
- [Categorias de Ferramentas](#categorias-de-ferramentas)
  - [Utilitários de Sistema](#utilitários-de-sistema)
  - [Desenvolvimento](#desenvolvimento)
  - [Ferramentas de Desenvolvimento e Design](#ferramentas-de-desenvolvimento-e-design)
  - [Mídia e Multimídia](#mídia-e-multimídia)
  - [Produtividade](#produtividade)
  - [Jogos](#jogos)
  - [Ferramentas Avançadas](#ferramentas-avançadas)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Pré-requisitos

- **Windows 10 ou superior**: Certifique-se de que o seu sistema operacional é compatível.
- **Winget**: O gerenciador de pacotes Winget deve estar instalado. Geralmente, ele já vem pré-instalado nas versões mais recentes do Windows. Caso contrário, você pode instalá-lo através da [Microsoft Store](https://www.microsoft.com/store/productId/9NBLGGH4NNS1).

## Como Usar

1. **Clone este repositório** ou copie a lista de comandos para um arquivo de script, por exemplo, `install.ps1`.

2. **Abra o PowerShell** com privilégios de administrador.

3. **Execute o script**:

   ```powershell
   Set-ExecutionPolicy Bypass -Scope Process -Force; ./install.ps1

    Nota: Certifique-se de revisar o script antes de executá-lo para garantir que você está confortável com as alterações que serão feitas no seu sistema.

Categorias de Ferramentas
Utilitários de Sistema

Ferramentas essenciais para monitoramento e manutenção do sistema.

    7zip.7zip: Gerenciador de arquivos compactados.
    CPUID.HWMonitor: Monitoramento de hardware em tempo real.
    CPUID.CPU-Z: Informação detalhada sobre o processador.
    TechPowerUp.GPU-Z: Informação detalhada sobre a GPU.
    CrystalDewWorld.CrystalDiskMark: Benchmark de desempenho de discos.
    CrystalDewWorld.CrystalDiskInfo: Monitoramento de saúde de discos.
    JAMSoftware.TreeSize.Free: Análise de uso de espaço em disco.
    AntibodySoftware.WizTree: Visualização rápida do uso de disco.
    ShareX.ShareX: Ferramenta de captura de tela e gravação.
    voidtools.Everything: Pesquisa ultrarrápida de arquivos e pastas.

Desenvolvimento

Ferramentas essenciais para desenvolvedores de software.

    OpenJS.NodeJS.LTS: Ambiente de execução para JavaScript.
    Rustlang.Rust.MSVC: Compilador e ferramentas para Rust.
    GoLang.Go: Linguagem de programação Go.
    Python.Python.3.12: Linguagem de programação Python.
    Neovim.Neovim: Editor de texto avançado.
    Microsoft.VisualStudio.2022.Community: IDE completa para desenvolvimento.
    Microsoft.VisualStudioCode: Editor de código-fonte leve e extensível.
    Git.Git: Controle de versão distribuído.
    GitHub.cli: Interface de linha de comando para GitHub.
    GitHub.GitHubDesktop: Interface gráfica para GitHub.
    Postman.Postman: Ferramenta para desenvolvimento e teste de APIs.
    Yarn.Yarn: Gerenciador de pacotes para JavaScript.

Ferramentas de Desenvolvimento e Design

Ferramentas adicionais para aprimorar o fluxo de trabalho de desenvolvimento e design.

    DevToys-app.DevToys: Conjunto de utilitários para desenvolvedores.
    Docker.DockerDesktop: Plataforma para desenvolvimento e implantação de contêineres.
    Parsec.Parsec: Ferramenta de streaming remoto de jogos.
    CalcProgrammer1.OpenRGB: Controle de iluminação RGB de hardware.

Mídia e Multimídia

Aplicativos para consumo e criação de conteúdo multimídia.

    Spotify.Spotify: Serviço de streaming de música.
    VideoLAN.VLC: Reprodutor de mídia versátil.
    Gyan.FFmpeg: Biblioteca para processamento de áudio e vídeo.
    OBSProject.OBSStudio: Software de gravação e streaming.
    MoonlightGameStreamingProject.Moonlight: Streaming de jogos via NVIDIA GameStream.
    Stremio.Stremio: Plataforma de streaming de vídeo.
    yt-dlp.yt-dlp: Ferramenta para download de vídeos do YouTube e outros sites.

Produtividade

Aplicativos para aumentar a eficiência e organização no dia a dia.

    Obsidian.Obsidian: Aplicativo de notas baseado em Markdown.
    Notepad++.Notepad++: Editor de texto e código-fonte.
    RevoUninstaller.RevoUninstaller: Ferramenta para desinstalação completa de programas.
    Google.GoogleDrive: Armazenamento em nuvem.
    Bitwarden.Bitwarden: Gerenciador de senhas seguro.
    Telegram.TelegramDesktop: Aplicativo de mensagens instantâneas.
    Discord.Discord: Plataforma de comunicação para comunidades.
    GitHub.GitHubDesktop: Interface gráfica para GitHub.

Jogos

Plataformas e ferramentas para jogos e realidade virtual.

    Valve.Steam: Plataforma de distribuição de jogos.
    EpicGames.EpicGamesLauncher: Plataforma de jogos da Epic Games.
    HeroicGamesLauncher.HeroicGamesLauncher: Alternativa para Epic Games Launcher.
    SideQuestVR.SideQuest: Plataforma para conteúdo de realidade virtual.

Ferramentas Avançadas

Ferramentas para usuários avançados e desenvolvedores.

    Anaconda.Anaconda3: Distribuição Python para ciência de dados.
    Famatech.AdvancedIPScanner: Ferramenta de varredura de rede.
    Oracle.VirtualBox: Plataforma de virtualização.
    Canonical.Ubuntu: Distribuição Linux para uso via WSL.
    WSL: Subsistema Windows para Linux.