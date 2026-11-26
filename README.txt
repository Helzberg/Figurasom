# FiguraSom PWA — pacote inicial

## Conteúdo
- `index.html`: editor de imagem, texto, gravação de voz, upload, download e compartilhamento.
- `manifest.webmanifest`: identidade PWA.
- `sw.js`: cache básico para abrir novamente sem conexão depois da primeira visita.
- `icons/`: ícones PNG para instalação.

## Publicar gratuitamente
1. Crie uma conta no GitHub.
2. Crie um repositório público chamado `figurasom`.
3. Envie todos os arquivos e pastas deste pacote para a raiz do repositório.
4. Em Settings > Pages, escolha Deploy from a branch, `main` e `/root`.
5. Aguarde a publicação. O GitHub Pages fornece um endereço HTTPS.
6. Abra esse endereço no Chrome Android e use o menu ⋮ > Instalar app ou Adicionar à tela inicial.

Também pode hospedar a pasta em Cloudflare Pages ou outro host HTTPS estático.

## Importante sobre vendas vitalícias
Este pacote é o aplicativo PWA funcional, mas ainda NÃO inclui checkout, autenticação, emissão de licenças ou bloqueio de acesso por comprador. Não anuncie ainda como acesso vitalício protegido por conta. Para vender acesso de forma confiável, precisamos adicionar backend e integração com pagamento, com validação de licença no servidor. Um código de desbloqueio guardado só no JavaScript pode ser copiado e não protege a venda.

## Limitações técnicas
- A gravação de voz exige HTTPS (ou localhost) e permissão do microfone.
- A compatibilidade de formatos de gravação varia por navegador; o app usa o formato aceito pelo dispositivo.
- Compartilhar vários arquivos de uma vez depende do navegador/sistema. O download separado continua disponível.
- O app processa fotos e áudios localmente; não envia os arquivos para um servidor.
- O cache offline funciona após a primeira abertura online. A primeira instalação/publicação precisa de internet.

## Antes de comercializar
- Defina política de privacidade, termos de uso, suporte e reembolso.
- Use apenas imagens e áudios que o cliente tenha direito de utilizar.
- Teste em Android/Chrome e iPhone/Safari.
- Configure domínio próprio e canal de atendimento se desejar uma marca comercial.
