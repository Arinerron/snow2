# Snow2

Obfuscate &amp; Encrypt Text as White-Space

Demo: [https://ChaosWebs.net/snow2](https://chaoswebs.net/snow2/)

![snow image](snow.jpg)

# About

Snow2 is a web app inspired by the [original snow program](http://darkside.com.au/snow/) to use whitespace/zero-width characters to obfuscate messages within the whitespace of other content.

# License

MIT license, see LICENSE file.

# Warnings

* No steganography is perfect, your message may be discovered especially by skilled adversaries.
* Some text editors (like vim) show zero width characters
* Some clients/places may strip whitespace characters
* Use encryption if you really need to protect your messages. Use a good password but keep in mind that no encryption is perfect (Snow2 uses cryptojs AES)
* It is best to save the site offline to avoid your messages being intercepted by possible malicious code sent from (my) web server
* The larger your message, the more obvious it is that it is there.

# Roadmap (to do)

* Ability to automatically spread/retrieve message content into paragraphs of "cover" text

* CLI version

* Android app

# Contributing

Feel free to make a pull request if you feel that you have improved the software.
