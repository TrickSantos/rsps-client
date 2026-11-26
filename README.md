# RSPS

Cliente do servidor **rsps.starforge.io**. Já vem com o Java embutido e com o endereço do servidor
configurado: é baixar, descompactar e abrir.

## Download

- [Windows](https://github.com/TrickSantos/rsps-client/releases/latest/download/RSPS-Windows.zip)
- [macOS](https://github.com/TrickSantos/rsps-client/releases/latest/download/RSPS-macOS.zip) (Mac com chip Apple: M1 ou mais novo)

## Windows

1. Descompacte o zip e abra `RSPS\RSPS.exe`.
2. Se o Windows mostrar "O Windows protegeu o computador", clique em **Mais informações** e depois
   em **Executar assim mesmo**. O aviso aparece porque o app não é assinado.

## macOS

1. Descompacte o zip e arraste `RSPS.app` para a pasta Aplicativos.
2. Abra o app. Na primeira vez o macOS bloqueia, porque o app não é assinado pela Apple: vá em
   **Ajustes do Sistema → Privacidade e Segurança**, role até o aviso do RSPS e clique em
   **Abrir Mesmo Assim**.

   Ou, no Terminal: `xattr -dr com.apple.quarantine /Applications/RSPS.app`

No Mac o jogo roda no modo de renderização seguro (software), que é o único que funciona em chip Apple.

## Jogando

Na primeira vez o cliente baixa o cache do jogo, o que leva alguns minutos. Crie sua conta pela
própria tela de login.

## Código e licença

O cliente é o [darkan-bot](https://gitlab.com/darkanrs/darkan-bot), sem modificações, distribuído
sob a GNU AGPL 3.0 (`LICENSE`). Cada release informa o commit exato de onde foi gerado, e
`.github/workflows/release.yml` mostra como.
