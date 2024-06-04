<h1> Steps to Reproduce: </h1>

1. Try a Live Demo Template in endpoint ‘https://www.kopage.com/templates’.

2. Navigate to Files > Professional Photos.

3. Insert the payload <IMG """><SCRIPT>alert(document.cookie)</SCRIPT>"> in the search field.

4. Upon clicking search, the payload is successfully executed.

Attached are screenshots demonstrating the exploitation of the vulnerability.

![kopage_xss_self_set_payload](https://media.discordapp.net/attachments/977678399860510731/1247684394504687646/image.png?ex=6660ec24&is=665f9aa4&hm=f27d59ec70a2475c258964be9e1e1c719ff6e5cb9ba94ed27d5900476f70b7b0&=&format=webp&quality=lossless&width=2278&height=1332)

![kopage_xss_exploiting](https://media.discordapp.net/attachments/977678399860510731/1247684395637280808/image.png?ex=6660ec24&is=665f9aa4&hm=5df40c6c211e9cdba4f6524ee10671cf8be12960f2b5016e9c7186681d456063&=&format=webp&quality=lossless&width=2268&height=1332)
