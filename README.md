Como usar o Swagger e testar endpoints protegidos por JWT:

1. Rode a API (dotnet run no projeto Api).
2. Abra http://localhost:5000/ (ou porta informada) para acessar o Swagger UI.
3. Gere um JWT (pode criar um endpoint de login que retorne o token) ou use um token de teste.
4. Clique em "Authorize" no Swagger e cole: Bearer {seu_token}
5. Teste endpoints protegidos.

Endpoints adicionados automaticamente:
- /health  -> retorna status do app