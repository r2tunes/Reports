<h1> Steps to Reproduce: </h1>

1.Try a Live Demo Template in endpoint ‘https://www.kopage.com/templates’.
2.Navigate to Settings > Contact Information.
3.Insert the payload <IMG """><SCRIPT>alert(document.cookie)</SCRIPT>"> into the “City” field.
4.Upon clicking edit again, the payload is successfully executed.

Attached are screenshots demonstrating the exploitation of the vulnerability.

![kopage_xss_set_payload](https://media.discordapp.net/attachments/977678399860510731/1247682358556233739/image.png?ex=6660ea3f&is=665f98bf&hm=e8039dbcd6bbf69e9c2c834e385c75b64691759c22460970199ac901d9e7a73e&=&format=webp&quality=lossless&width=2274&height=1332)
