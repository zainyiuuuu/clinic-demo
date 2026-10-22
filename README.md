<!DOCTYPE html>
<html><head><meta charset="utf-8"><title>Clinic Enquiry (Demo)</title></head>
<body>
<h2>Clinic Enquiry (Demo)</h2>
<iframe name="hidden" style="display:none"></iframe>
<form action="PASTE_MAKE_WEBHOOK_URL_HERE" method="POST" target="hidden"
      onsubmit="setTimeout(()=>{alert('Sent!');this.reset()},500)">
  <p><input name="name" placeholder="Name" required></p>
  <p><input name="phone" placeholder="Phone" required></p>
  <p><textarea name="message" placeholder="Message" required></textarea></p>
  <button type="submit">Send</button>
</form>
</body></html>
