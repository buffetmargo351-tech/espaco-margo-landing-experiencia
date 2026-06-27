CORREÇÃO WHATSAPP MOBILE — LANDING EXPERIÊNCIA

Problema:
No celular, o botão estava abrindo uma tela intermediária perguntando sobre WhatsApp Web.

Correção aplicada:
- Em celular, o clique agora usa o deep link:
  whatsapp://send?phone=...&text=...
- Em desktop, continua usando:
  https://wa.me/...

Preservado:
- v18_api_registrar_atribuicao
- protocolo MRG-XXXXXX
- captura de UTMs
- GTM
- vídeos em alta qualidade
- preload="none"
- botão WhatsApp e texto da mensagem

Observação:
Alguns navegadores/sistemas ainda podem mostrar uma confirmação de segurança do tipo
“Abrir WhatsApp?”, mas a rota agora direciona para o aplicativo, não para WhatsApp Web.
