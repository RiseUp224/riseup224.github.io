<link rel="stylesheet" type="text/css" href="form.css">
<script src="./form.js"></script>

<form class="form-style-4" 
      action="https://formspree.io/riseup224@gmail.com" 
      method="POST">
      <input type="hidden" name="_next" value="https://riseup224.github.io/form/thankyou.html" />
      <input type="hidden" name="_subject" value="New submission!" />
      <label for="Nom">
      <span>Votre nom</span><input type="text" name="Nom" required="true" />
      </label>
      <label for="Email">
      <span>Votre email</span><input type="email" name="_replyto" required="true" />
      </label>
      <label for="Objet">
      <span>Objet</span><input type="text" name="Objet" required="true" />
      </label>
      <label for="Message">
      <span>Votre message</span><textarea name="Message" onkeyup="adjust_textarea(this)" required="true"></textarea>
      </label>
      <label>
      <span> </span><input type="submit" value="Send Letter" />
      </label>
</form>
