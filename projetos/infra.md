# Publicação

O build da aplicação roda no GitHub Actions. A imagem sobe pronta e a VPS só puxa. O servidor não compila o projeto na hora do deploy.

No mesmo ambiente entram o aplicativo, o site, os robôs e o WhatsApp da operação (Evolution). A linha oficial do comercial fala com a API Cloud da Meta a partir da aplicação, sem cliente de WhatsApp no navegador da equipe.

Linux no servidor. Variável de ambiente e segredo ficam no runtime, fora do repositório e fora do navegador.
