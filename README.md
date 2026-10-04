# Miúdo: gestão simples

Protótipo local de gestão para pequenos negócios que vendem produtos. Inclui painel diário, registro de vendas, recibo imprimível, baixa e reposição de estoque, cadastro de clientes e modelos de mensagens.

## Abrir

Abra `index.html` diretamente no navegador. Não é necessário instalar dependências nem iniciar um servidor. Os dados ficam no armazenamento local desse navegador e dispositivo; use **Exportar dados** na área de produtos para baixar um backup JSON.

## Limites desta versão

- Os dados não são sincronizados entre dispositivos ou usuários.
- As mensagens abrem uma conversa do WhatsApp com texto preenchido; é preciso revisar e enviar manualmente. Envio agendado/automático requer integração com a API oficial do WhatsApp Business e um serviço de backend.
- O lucro exibido é uma estimativa bruta (preço de venda menos custo cadastrado), não considera despesas operacionais, impostos ou taxas de pagamento.
- Os produtos e vendas iniciais são exemplos editáveis, salvos no navegador na primeira utilização.