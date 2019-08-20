---
templateKey: blog-post
title: Como redirecionar de http para https via htaccess
date: 2019-08-20T21:54:14.497Z
description: >-
  Seus problemas acabaram, agora você vai poder migrar seus site de HTTP para
  HTTPS via htaccess usando o cPanel. Aprenda neste artigo!
featuredpost: true
featuredimage: /img/products-full-width.jpg
tags:
  - SEO
---
O Chrome e o Firefox já exibem um aviso para os usuários alertando sobre o site estar sem certificado SSL. Sem o SSL, o navegador exibirá uma mensagem alertando seus visitantes dizendo de alguma maneira que os mesmos estão inseguros (a forma como essa mensagem é exibida por variar desde a data deste artigo).

Portanto, o uso de uma conexão criptografada por SSL para segurança, acessibilidade ou motivos de conformidade com a PCI se torna necessário. Torna-se muito importante redirecionar de HTTP para HTTPS.

Para forçar o seu servidor a usar HTTPS, você precisa editar um arquivo chamado .htaccess. Antes de começarmos a redirecionar de HTTP para HTTPS, veja como você pode editar o arquivo .htaccess. Se você já sabe, pule para as etapas de redirecionamento.

## Editando o arquivo .htaccess

Existem instruções ou comandos que você pode executar no arquivo .htaccess que informam ao servidor como agir em determinados cenários e afeta diretamente o funcionamento do site. Instruções comuns no arquivo .htaccess:

* Redirects
* Rewrite Rules

## Maneiras de editar o arquivo .htaccess:

1. Edite o arquivo no seu computador e faça o upload para o servidor usando o FTP.
2. Use a opção “Editar” no programa de FTP que permite editar um arquivo remotamente.
3. Use um editor de texto e SSH para editar o arquivo.
4. Use o Gerenciador de Arquivos no cPanel para editar o arquivo.

## Editando o .htaccess usando o gerenciador de arquivos do cPanel

_**Nota**_: Faça o backup do seu arquivo .htaccess caso aconteça algo errado.

1. Faça o login no cPanel;
2. Arquivos > Gerenciador de Arquivos > Raiz do Documento (root):
3. Agora selecione o domínio que você deseja acessar;
4. Marque a opção “Mostrar arquivos ocultos (dotfiles)”;
5. Clique em “Go”;
6. Depois que uma nova guia ou janela for aberta, procure o arquivo .htaccess.
7. Clique com o botão direito no arquivo .htaccess e clique em “Code Edit” no menu.
8. Uma caixa de diálogo pode aparecer perguntando sobre algumas opções do editor de código. Clique no botão “Editar” para continuar.
9. Edite o arquivo;
10. “Salvar alterações” quando terminar.
11. Teste seu site para garantir que seja feito corretamente. Caso haja um erro, restaure a versão anterior e tente novamente.
12. Quando terminar, clique em “Fechar” para fechar a janela.

Segue alguns prints com algumas os passos acima:
