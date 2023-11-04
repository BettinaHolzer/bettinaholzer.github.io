+++
slug = "Kontakt"
title = "Kontakt"
description = "Kontakt"
+++

# Kontaktformular

Gerne können Sie mich anfragen zu den Themen Kodierevision, Beratung und Coaching.

{{< rawhtml >}}
<form action="https://send.pageclip.co/JJJHTtQ45VuXS4hQhYm18AO9XIwnsyTt/contact-form" class="pageclip-form" method="post">
  <!-- Replace these inputs with your own. Make sure they have a "name" attribute! -->

  <!-- It looks like you are creating a contact form. These email and subject fields are special -->
  <!-- See https://pageclip.co/docs#special-fields for more info -->
  <input type="email" name="email" placeholder="Ihre E-mail" required />
  <input type="text" name="subject" placeholder="Thema Ihrer Anfrage" required />

  <textarea name="body" placeholder="Ihre Anfrage" required></textarea>

  <!-- This button will have a loading spinner. Keep the inner span for best results. -->
  <button type="submit" class="pageclip-form__submit">
    <span>Schicken</span>
  </button>
</form>
<script src="https://s.pageclip.co/v1/pageclip.js" charset="utf-8"></script>
<script>
  const form = document.querySelector('.pageclip-form');
  Pageclip.form(form, { successTemplate: '<span>Danke!</span>'});
</script>
{{< /rawhtml >}}

## Adresse
B Holzer Consulting
Chemin de Villardiez 18
1009 Pully
