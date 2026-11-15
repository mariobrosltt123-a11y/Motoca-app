MOTOCA — Projeto Android (APK)

Este projeto encapsula o Motoca em um aplicativo Android nativo com WebView e arquivos locais. A interface funciona offline; os lançamentos ficam no armazenamento local do app (WebView localStorage).

REQUISITOS PARA COMPILAR
- Android Studio atualizado
- Android SDK Platform 35 instalado pelo SDK Manager
- JDK 17 (o Android Studio normalmente oferece o JBR)
- Conexão à internet na primeira sincronização para baixar Gradle/Android Gradle Plugin

COMO GERAR O APK
1. Extraia a pasta motoca_android.
2. Abra essa pasta no Android Studio (Open).
3. Aguarde a sincronização do Gradle e aceite instalar os componentes solicitados.
4. Selecione Build > Build Bundle(s) / APK(s) > Build APK(s).
5. O APK de debug será gerado em app/build/outputs/apk/debug/app-debug.apk.
6. Transfira esse APK ao Android e autorize a instalação desta origem, se solicitado.

NOTAS IMPORTANTES
- Este ambiente de criação não possui Android SDK nem Gradle instalado, então não foi possível compilar nem testar um APK binário aqui. Este ZIP é um projeto Android pronto para abrir/compilar no Android Studio, não um APK instalável.
- O app não pede permissões de localização, contatos ou internet. Os dados são locais. Exporte backups periodicamente; desinstalar o app pode apagar os registros.
- O backup JSON pode ser importado pelo seletor de arquivos Android. A exportação via download pode depender da versão do WebView; se não iniciar, abra o projeto no Android Studio e use o Chrome/WebView atualizado.
