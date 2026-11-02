# Urso Dourado: gerar o APK pelo GitHub

1. Crie uma conta em github.com (grátis) e clique em **New repository**. Dê o nome `urso-dourado` e crie.
2. No repositório novo, clique em **uploading an existing file** e envie TODOS os arquivos desta pasta,
   incluindo a pasta `.github`. Clique em **Commit changes**.
   - Se a pasta `.github` não subir (pastas ocultas às vezes são ignoradas), clique em
     **Add file > Create new file**, digite o nome `.github/workflows/build-apk.yml`, cole o conteúdo
     do arquivo `build-apk.yml` e salve.
3. Abra a aba **Actions**. O "Gerar APK" começa sozinho (ou clique em **Run workflow**). Leva uns 5 a 10 minutos.
4. Quando ficar verde, abra a execução e baixe o arquivo **urso-dourado-apk** em **Artifacts**.
5. Descompacte, envie o `app-debug.apk` para o celular e instale (permita "instalar apps desconhecidos").

Observações
- As fontes e o ícone do urso são colocados automaticamente durante a geração.
- O app funciona sem internet e guarda os dados no próprio aparelho.
- Versão sem chat de IA, começa vazia.
