---
layout: default
title: Контакты
permalink: /contact/
---
<p>Свяжитесь с нами</p>

<div id="NhhZEh4E" data-formid="e41575620527i9a" class="_Forms_generate"></div>

_Write_ **something** about [yourself](https://www.google.com/search?q=who+am+i) here.

Also, you might not want to display this many modes of contact.

[посмотреть наш PGP-ключ](/pgp)



<form class="contact_form" action="/" method="post" name="contact_form" id="e41575620527i9a">
    <input name="forms" type="hidden" class="formid" value="e41575620527i9a">
    <ul>
        <li>
             <h2>Contact Us</h2>
             <span class="required_notification">* Denotes Required Field</span>
        </li>
        <li>
            <label for="name">Name:</label>
            <input type="text"  placeholder="John Doe" required />
        </li>
        <li>
            <label for="email">Email:</label>
            <input type="email" name="email" placeholder="john_doe@example.com" required />
            <span class="form_hint">Proper format "name@something.com"</span>
        </li>
        <li>
            <label for="website">Website:</label>
            <input type="url" name="website" placeholder="http://johndoe.com" required pattern="(http|https)://.+"/>
            <span class="form_hint">Proper format "http://someaddress.com"</span>
        </li>
        <li>
            <label for="message">Message:</label>
            <textarea class="" name="message" cols="40" rows="6" required ></textarea>
        </li>
        <li>
        	<button class="submit" type="submit">Submit Form</button>
        </li>
    </ul>
</form>
