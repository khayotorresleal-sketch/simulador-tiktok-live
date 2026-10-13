# SIMULADOR INTERATIVOS PARA LIVE TIK TOK

Projeto inicial Android (WebView) com um simulador web local.

## O que já funciona
- Interface em português adaptada para celular
- Presentes simulados (rosa, coração, presente e especial)
- Efeitos animados, pontuação, combo e histórico de eventos
- Exportação do histórico em JSON
- App Android que abre a interface local sem precisar de internet

## Limitação importante
Este protótipo NÃO recebe presentes reais do TikTok. Para isso, será necessária uma integração compatível e autorizada com eventos da LIVE. Não coloque senha ou cookies da conta TikTok no aplicativo. Verifique os termos e permissões aplicáveis antes de implementar qualquer conector de terceiros.

## Como gerar o APK
1. Instale o Android Studio em um computador.
2. Extraia este ZIP.
3. No Android Studio, escolha **Open** e selecione a pasta `SimuladorTikTokLive`.
4. Aguarde a sincronização do Gradle e instale os componentes do SDK solicitados.
5. Para testar, clique em **Run** com um dispositivo Android ou emulador conectado.
6. Para criar um APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
7. O Android Studio exibirá um aviso/link para localizar o APK gerado.

## Requisitos
- Android Studio recente
- Android SDK 35 (o Android Studio pode instalar automaticamente)
- JDK gerenciado pelo Android Studio

O APK ainda não foi compilado neste ambiente; este arquivo contém o código-fonte do projeto.
