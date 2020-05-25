---
layout: page
title: README
permalink: /readme/
nav_exclude: true
---

# Font Tutorials  

This repository contains the documentation for Font Tutorials, the home of easy to follow tutorials on various font editing software programs.  

---

## Jekyll Themes  

Font Tutorials uses a modified Jekyll theme for documentation called [just-the-docs].  

Modifications include:  
- adding callouts  
- changing the theme color  
- adjusting the site's column width  
- tweaking some of the padding, margins, alignment, line height, and headings  
- adding a floating right side table-of-contents ([toc]) that lists h2  

Modifications are found within the following files:  
- overrides.scss  
- custom.scss  
- default.html includes a line of code to incoporate the toc  
- toc.html this is an additional file, to accomodate allejo's [toc]  

---

## Known Issues  

The site's search function does't work comprehensively and we are waiting for just-the-docs to fix it.  

---

## Contribute  

Feel free to check the issues or open a new one if you have questions or something is wrong. [Pull requests](https://github.com/g-wallis/font-tutorials/pulls) are always welcome.  

If you'd like to submit a tutorial or article you've written about fonts, to us, please create a pull request and we'll let you know what to do next.  

Something wrong? Let us know by opening an issue or submitting a pull request with the updated information.

---

### Content Guidelines  

- Try to stay consistent with existing content.  
- Introduce acronyms before using them.  
- styles are found within the overrides.scss file, and include the following;

tip callout  
     {: .tip}
{: .tip}

Note callout  
     {: .note}  
{: .note}

Warning callout  
     {: .warning}  
{: .warning}

Indented clear callout  
     {: .blockquote}
{: .blockquote}

Indented square blue callout  
     {: .blockblue}
{: .blockblue}

> Block quote  
     >

Button
     {: .btn}  
{: .btn}

---

## Support or Contact  

Having trouble with Github Pages? Check out Github's [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and they’ll help you sort it out.  

Having trouble with just-the-docs? Check out [just-the-docs] and they’ll help you sort it out.  

Want more information on adding a table-of-contents to your site using allejo's toc? Head to allejo's [toc] page on Github and the community over there will help you out.  

Got a question for us? Get in touch by opening a pull request or issue. We'd love to hear from you.  

---

## License & Copyright  

Font Tutorials are distributed under an open source [MIT] license.  

[toc]: https://github.com/allejo/jekyll-toc  
[just-the-docs]: https://github.com/pmarsceill/just-the-docs  
[MIT]: /license  