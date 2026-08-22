## Configuração do Ambiente
1. Instale as dependências: `npm install`
2. Configure as variáveis de ambiente
3. Execute os testes: `npm test`
4. Inicie o servidor: `npm start`
Teste direto na main
Alteração via PR

## Instruções de Deploy v2
1. Executar script `deploy-v2.sh`
2. Verificar logs em `/var/log/deploy.log`
3. Validar endpoints de saúde

## Configurações do Sistema
- Ambiente: produção
- Porta: 8080
- Timeout: 30s
- Max connections: 1000
