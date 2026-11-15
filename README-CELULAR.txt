COMO GERAR O APK USANDO SOMENTE O CELULAR

Este pacote ainda NÃO contém um APK binário. Ele contém o projeto Android e uma automação para o GitHub compilar o APK na nuvem.

Você precisará de uma conta gratuita no GitHub e conexão com a internet.

1. No navegador do celular, acesse https://github.com e crie uma conta/entre.
2. Crie um repositório novo chamado motoca, deixe-o Public (para usar Actions sem configuração adicional) e crie-o.
3. Extraia este ZIP no celular usando o gerenciador de arquivos.
4. No repositório, use Add file > Upload files e envie TODOS os arquivos e pastas que estão dentro da pasta motoca_android (incluindo a pasta oculta .github). Não envie a pasta externa motoca_android como uma única pasta compactada.
5. Faça Commit changes na branch main.
6. Abra a aba Actions do repositório. O fluxo Build Motoca APK deve iniciar. Se não iniciar, abra o fluxo e toque em Run workflow.
7. Aguarde terminar com marca verde. Abra a execução concluída, desça até Artifacts e baixe Motoca-debug-APK.
8. Extraia o arquivo baixado. Dentro dele estará app-debug.apk. Toque nele para instalar e autorize a instalação pelo navegador/gerenciador de arquivos quando o Android perguntar.

IMPORTANTE:
- O APK gerado é de depuração (debug), suficiente para instalar e testar no seu aparelho. Não é uma versão assinada para distribuição ampla.
- O GitHub Actions precisa estar habilitado no repositório.
- O projeto usa dados locais no aparelho. Faça backups para não perder registros.
- Não compartilhe publicamente dados financeiros pessoais nem backups.
