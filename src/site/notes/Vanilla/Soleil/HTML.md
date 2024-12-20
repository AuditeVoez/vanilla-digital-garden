---
{"dg-publish":true,"dg-path":"Soleil/HTML.md","permalink":"/soleil/html/","created":"2024-12-17T18:43:59.680+08:00","updated":"2024-12-20T20:37:45.852+08:00"}
---

2024-12-17
Status: #idea
Tags: [[Vanilla/Soleil/Web Development\|Web Development]]
# HTML
- Stands for HyperText Markup Language
- Defines the structure and pure content of the website
- Relies on [[Vanilla/Soleil/CSS\|CSS]] and [[Javascript\|Javascript]] to stylize content
## Structure
- HTML needs to be declared first with `<!Doctype HTML>`
- A lot of HTML syntax relies on nesting and wrapping. For instance, the syntax to write a paragraph is: 
`<p> Content Here </p>`
```ad-info
Some tags do not adhere to this rule, as for instance the tag `<br>` is considered a *Void Element*, and thus does not ned a closing tag
```
- As a rule of thumb, you should encase the HTML code in `<html> </html>`. 
``` ad-note
You might want to add `<lang = "en">` inside the html tag to signal that your website primarily contains the English language. This is useful for things like auto-translate extensions, and accessibility plugins for their code to determine what the website's language is and adjust accordingly.
```
- HTML has two main parts, those being `<head>` and `<body>`.
	- You would want `<meta charset="UTF-8">` inside the head to signal proper display on browsers
### Head
- For me, it's best to think about the head as the "backend" of the page, where it holds important data, like the [stylesheet](CSS) it references, the [scripts]([[Javascript\|Javascript]]) it will run, and meta tags that help search engines and stuff
```ad-info
VSCode has built in templates and boilerplates for HTML! Type out "!", and experiment with what the suggestions give you!
```
# References
[Elements and Tags \| The Odin Project](https://www.theodinproject.com/lessons/foundations-elements-and-tags)