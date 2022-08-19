
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
  
  
  Helpful Links : https://help.apple.com/xcode/mac/current/#/dev3a05256b8
