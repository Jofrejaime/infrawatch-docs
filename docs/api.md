# API - InfraWatch

## Autenticação
`POST /api/login`
- Body: `{ "email": "user@test.com", "senha": "123456" }`
- Resposta: `{ "token": "..." }`

## Sistemas Monitorados
`GET /api/sistemas`
- Retorna a lista de sistemas e status.

## Logs e Métricas
`GET /api/logs/:sistema`
- Retorna histórico de métricas de um sistema.

## Notificações
`POST /api/notificacoes`
- Cria nova regra de alerta.
## API LINK
- Segue o link da API para mais instruções detalhadas.
[API Documentation](https://share.apidog.com/e86cc317-b31d-4f7a-b798-2341787555e4)