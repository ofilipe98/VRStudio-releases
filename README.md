# VR Norte Studio — Releases

Instaladores do VR Norte Studio para Windows 10/11 x64. Este repositório
guarda somente os instaladores e os arquivos de atualização; o código-fonte
fica em um repositório privado.

## Instalar

1. Abra [Releases](https://github.com/ofilipe98/VRStudio-releases/releases) e
   baixe `VR-Norte-Studio-<versão>-x64.exe`:
   - **Estável**: a versão marcada como *Latest*.
   - **Beta**: a pré-release mais recente.
2. O instalador não é assinado digitalmente. Na primeira instalação, o Windows
   pode mostrar "O Windows protegeu o computador". Clique em
   **Mais informações → Executar assim mesmo**.
3. Depois de instalado, o Studio verifica as novas versões do canal escolhido
   e oferece a atualização.

Credenciais, CLIs de providers e a base de conhecimento não fazem parte do
instalador.

## Canais

| Canal | Releases | Arquivo de atualização |
| --- | --- | --- |
| Estável | releases normais | `latest.yml` |
| Beta | pré-releases | `beta.yml` |

As releases são publicadas pelo script de release do VR Norte Studio; não
envie arquivos manualmente.
