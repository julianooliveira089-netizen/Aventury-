AVENTURY — PROJETO ANDROID

Este pacote contém um projeto Android nativo simples que abre o jogo AVENTURY
em uma WebView de tela cheia. Ele é uma base de compilação, NÃO um APK pronto.

COMO GERAR O APK PELO GITHUB (sem instalar Android Studio no celular):
1. No computador ou navegador, crie um repositório no GitHub.
2. Envie todos os arquivos e pastas deste ZIP para o repositório.
3. Abra a aba Actions e execute "Build AVENTURY APK" (ou aguarde o build após push).
4. Quando terminar, abra a execução e baixe o artefato "AVENTURY-debug-apk".
5. Dentro dele estará app-debug.apk. Instale no Android permitindo a instalação
   de apps dessa origem, se o aparelho solicitar.

REQUISITOS E LIMITAÇÕES:
- O build na nuvem baixa Gradle e Android Gradle Plugin; precisa de internet.
- O jogo carrega Three.js de uma CDN, portanto precisa de internet para carregar
  a biblioteca na primeira abertura.
- Este é um APK de depuração, não assinado para publicação na Play Store.
- Ainda não foi possível compilar/testar aqui porque este ambiente não tem
  Android SDK/Gradle/ADB e não consegue acessar o registro npm.
- A tela do jogo foi configurada em modo paisagem.
