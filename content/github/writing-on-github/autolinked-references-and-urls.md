---
title: Autolinked references and URLs
intro: 'References to URLs, issues, pull requests, and commits are automatically shortened and converted into links.'
redirect_from:
  - /articles/autolinked-references-and-urls
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

### URLs

{% data variables.product.product_name %} automatically creates links from standard URLs.

`Visit https://github.com`

![Rendered autolinked URL](/assets/images/help/writing/url-autolink-rendered.png)

For more information on creating links, see "[Basic writing and formatting syntax](/articles/basic-writing-and-formatting-syntax/#links)."



References to a commit's SHA hash are automatically converted into shortened links to the commit on {% data variables.product.product_name %}.

| Reference type | Raw reference | Short link |
| --- | --- | --- |
| Commit URL | https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e | [a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |
| SHA | a5c3785ed8d6a35868bc169f07e40e889087fd2e | [a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |
| User@SHA | jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e | [jlord@a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e)
| Username/Repository@SHA | User/Repository@SHA: jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e | [jlord/sheetsee.js@a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |

### Custom autolinks to external resources

{% data reusables.repositories.autolink-references %}

### Further reading

- "[Basic writing and formatting syntax](/articles/basic-writing-and-formatting-syntax)"
