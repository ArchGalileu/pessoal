---
title: Contact Form

form:
  fields:
    name:
      type: text
      label: Nome
      validate:
        required: true
        message: escreve o teu nome!
    email:
      type: text
      label: Email
      validate:
        type: email	
        required: true
        message: agora... o teu email
    subject:
      type: text
      label: Assunto 
      validate:
        required: true
        message: escreve o assunto!
    message:
      type: textarea
      label: Mensagem
      validate:
        required: true
        min: 10
        message: finalmente, que te trás por cá!

  buttons:
    submit:
      type: submit
      value: Enviar
     
  process:
    message: 'Obrigado pelo teu contato!'
    display: /form/thankyou

---

# Contact Form

  * Required field

