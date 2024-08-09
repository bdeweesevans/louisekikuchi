---
weight: 4
title: Contact
BookToC: false
---

# Contact

## Email

For purchase and other inquiries, please contact below.

{{< rawhtml >}}
<form name="contact" netlify data-netlify-recaptcha="true">
    <input type="text" name="name" placeholder="Your Name" required><br>
    <input type="email" name="email" placeholder="Your Email" required><br>
    <textarea name="message" placeholder="Your Message" required></textarea>
    <div data-netlify-recaptcha="true"></div><br>
    <button type="submit" class="button">Send</button>
    <button type="reset" class="button reset">Clear</button>
</form>
{{< /rawhtml >}}