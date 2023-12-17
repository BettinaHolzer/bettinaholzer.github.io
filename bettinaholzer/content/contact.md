+++
slug = "contact"
title = "Contact"
description = "Contact"
+++

# Formulaire de contact

Vous pouvez volontiers me contacter pour vos besoins de révisions, conseil ou coaching.

{{< rawhtml >}}
<form action="https://send.pageclip.co/B2TuPFO5F5JS4xjns2USxv7RyFXcmHAh" class="pageclip-form" method="post">
<!-- <form action="https://send.pageclip.co/JJJHTtQ45VuXS4hQhYm18AO9XIwnsyTt/contact-form" class="pageclip-form" method="post"> -->
  <!-- Replace these inputs with your own. Make sure they have a "name" attribute! -->

  <!-- It looks like you are creating a contact form. These email and subject fields are special -->
  <!-- See https://pageclip.co/docs#special-fields for more info -->
  <input type="email" name="email" placeholder="Votre e-mail" required />
  <input type="text" name="subject" placeholder="Sujet de votre demande" required />

  <textarea name="body" placeholder="Votre demande" required></textarea>

  <footnote>En soumettant ce formulaire, j'accepte d'être recontacté par B Holzer Consulting.</footnote>  

  <!-- This button will have a loading spinner. Keep the inner span for best results. -->
  <button type="submit" class="pageclip-form__submit">
    <span>Envoyer</span>
  </button>
</form>
<script src="https://s.pageclip.co/v1/pageclip.js" charset="utf-8"></script>
<script>
  const form = document.querySelector('.pageclip-form');
  Pageclip.form(form, { successTemplate: '<span>Merci</span>'});
</script>
{{< /rawhtml >}}

## Adresse
B Holzer Consulting  
Chemin de Villardiez 18  
1009 Pully
