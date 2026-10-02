M.E BEBIDAS — pacote preparado para hospedagem segura

1. Envie index.html e .htaccess para uma hospedagem Apache.
2. No painel da hospedagem, associe seu domínio.
3. Ative um certificado SSL/TLS (muitas hospedagens oferecem Let's Encrypt).
4. Confirme que o endereço abre com https://.
5. Não coloque senhas, tokens, chaves de API ou dados de cartão no HTML.
6. Se a hospedagem usar Nginx em vez de Apache, o .htaccess não é usado; as mesmas políticas devem ser configuradas no Nginx.

Observação: HTTPS/TLS depende do servidor/hospedagem e do domínio; um arquivo HTML sozinho não consegue emitir ou instalar um certificado TLS.
