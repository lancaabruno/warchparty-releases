# warchparty para Mac

O mesmo play. Mesmo de longe.

Este repositório distribui os instaladores públicos do warchparty. O código-fonte do produto é mantido separadamente.

## Download

[Baixar warchparty 0.38.0 para Mac com Apple Silicon](https://github.com/lancaabruno/warchparty-releases/releases/download/v0.38.0/warchparty-0.38.0-arm64.dmg)

Requer um Mac com chip M1 ou mais novo. Ainda não há versão para Mac Intel, Windows, Linux ou celulares.

## Instalação

1. Abra o `.dmg` e arraste o warchparty para Aplicativos.
2. Abra o app e conecte-se ao mesmo servidor de salas que seus amigos.
3. Crie uma sala ou entre com o código do convite.

No ambiente atual do grupo, todos precisam estar conectados ao Tailscale. Assinaturas e contas dos serviços de vídeo, quando necessárias, são de cada pessoa.

Esta versão usa assinatura ad-hoc e ainda não é notarizada pela Apple. Os avisos de primeira abertura dependem da versão do macOS; consulte a [orientação da Apple](https://support.apple.com/pt-br/guide/mac-help/mh40616/mac).

## Integridade e versões

Cada release acompanha o `.dmg`, o arquivo `SHA256SUMS` e `release-manifest.json`. No Terminal, com os dois primeiros arquivos na mesma pasta, confira o download com:

```bash
shasum -a 256 -c SHA256SUMS
```

Veja os detalhes e limitações de cada versão nas notas da release.
