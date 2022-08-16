
<h4 align="center">A minimal Markdown Editor desktop app built on top of <a href="http://electron.atom.io" target="_blank">Electron</a>.</h4>

<p align="center">
  <a href="https://badge.fury.io/js/electron-markdownify">
    <img src="https://badge.fury.io/js/electron-markdownify.svg"
         alt="Gitter">
  </a>
  <a href="https://gitter.im/amitmerchant1990/electron-markdownify"><img src="https://badges.gitter.im/amitmerchant1990/electron-markdownify.svg"></a>
  <a href="https://saythanks.io/to/bullredeyes@gmail.com">
      <img src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg">
  </a>
  <a href="https://www.paypal.me/AmitMerchant">
    <img src="https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&amp;style=flat">
  </a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#download">Download</a> •
  <a href="#credits">Credits</a> •
  <a href="#related">Related</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://raw.githubusercontent.com/amitmerchant1990/electron-markdownify/master/app/img/markdownify.gif)

## Gerar Certificado P12 de Distribuition e De Desenvolvimento da Apple Passo a Passo :

* Acessar https://developer.apple.com/ Passando Login e Senha do usuario do App na Aba Account
  - Após entrar em account acessar a aba Certificates , identifiers e Profiles.
* Na Aba de Certificados Clica no Mais para Gerar um Novo Certificado
  - Tem Várias Categorias de Certificado mas o necessário para desenvolver na apple são:
    1. Apple Development
    2. Apple Distribuition
    
 

* Após Selecionar o certificado que você quer , aperta em continue e ele vai pedir pra dar upload em um arquivo CSR
  - Pra gerar Esse Arquivo a gente vai acessar o KeyChain do Mac 
  - no KeyChain vai na Aba Certificados e vai Procurar pelo Apple Worldwide Developer Relations Certification Authority e Clicar em Cima dele ver se ele ta expirado ou ativo , se estiver ativo pula pra prox etapa
  - no KeyChain vamo apertar na primeira opcão (Acesso as Chaves) e buscar pelo Assitente de Certificaçoes 
  - no Assitente de Certificaçoes , vai na 5º opção que e Solicitar um Certificado de uma Autoridade de Certificação
  - Vai Abrir uma Aba Com os Campos De Email , nome Comum e Email Ac
  - Vai por Email e Nome Comum exemplo : Rodrigo p12 e Marcar Salvar no Disco
  - Marca Pastinha que ele vai ser Salvo, após Salvo arquivo é só fazer upload na aba de novo certificado da apple. 
  - Ele vai Cadastrar o novo Certificado e agora vamos em Download fazer o download do arquivo no formato Cer.
  - Agora vamos abrir o .cer que o mac vai montar o certificado no KeyChain.
  - Agora So localizar o arquivo do certificado , clica nele para expandir e ele vai abrir a Chave Privada.
  - Vamos Clicar com botão direito na Chave P12 privada e em Exportar Nome_documento_que_vc_criou assim o KeyChain vai exportar um arquivo com o .p12 que
a gente quer . 
  -Vai Selecionar a Pasta aonde o arquivo vai ficar Salvo e apertar em (save)
  - Após isso ele vai pedir para criar e setar uma senha para o documento (Cria a senha e Guarde Ela como sua Vida).
  - E depois e só passar o sua senha de Login na Maquina Mac e Finish!!! , Ta la seu P12. 
  
  PRA CIMA FÉ EM DEUS!!
  
  
* Dark/Light mode
* Toolbar for basic Markdown formatting
* Supports multiple cursors
* Save the Markdown preview as PDF
* Emoji support in preview :tada:
* App will keep alive in tray for quick usage
* Full screen mode
  - Write distraction free.
* Cross platform
  - Windows, macOS and Linux ready.

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/amitmerchant1990/electron-markdownify

# Go into the repository
$ cd electron-markdownify

# Install dependencies
$ npm install

# Run the app
$ npm start
```

> **Note**
> If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.


## Download

You can [download](https://github.com/amitmerchant1990/electron-markdownify/releases/tag/v1.2.0) the latest installable version of Markdownify for Windows, macOS and Linux.

## Emailware

Markdownify is an [emailware](https://en.wiktionary.org/wiki/emailware). Meaning, if you liked using this app or it has helped you in any way, I'd like you send me an email at <bullredeyes@gmail.com> about anything you'd want to say about this software. I'd really appreciate it!

## Credits

This software uses the following open source packages:

- [Electron](http://electron.atom.io/)
- [Node.js](https://nodejs.org/)
- [Marked - a markdown parser](https://github.com/chjj/marked)
- [showdown](http://showdownjs.github.io/showdown/)
- [CodeMirror](http://codemirror.net/)
- Emojis are taken from [here](https://github.com/arvida/emoji-cheat-sheet.com)
- [highlight.js](https://highlightjs.org/)

## Related

[markdownify-web](https://github.com/amitmerchant1990/markdownify-web) - Web version of Markdownify

## Support

<a href="https://www.buymeacoffee.com/5Zn8Xh3l9" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/purple_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

<p>Or</p> 

<a href="https://www.patreon.com/amitmerchant">
	<img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

## You may also like...

- [Pomolectron](https://github.com/amitmerchant1990/pomolectron) - A pomodoro app
- [Correo](https://github.com/amitmerchant1990/correo) - A menubar/taskbar Gmail App for Windows and macOS

## License

MIT

---

> [amitmerchant.com](https://www.amitmerchant.com) &nbsp;&middot;&nbsp;
> GitHub [@amitmerchant1990](https://github.com/amitmerchant1990) &nbsp;&middot;&nbsp;
> Twitter [@amit_merchant](https://twitter.com/amit_merchant)

