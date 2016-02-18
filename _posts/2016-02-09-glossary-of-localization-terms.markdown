---
layout: post
title:  "Let's all get on the same page"
date:   2016-02-09 17:06:41 -0800
description: "This is a glossary of localization terms we can share with people so they know what we're talking about when we say it: l10n, i18n, LQA explained."
---


One of the first things you may have noticed if you work as a localization professional (let's shorten this to LPM for localization project manager from here on out) is that you use a lot of acronyms. No one really understands what you're saying outside of the industry. Now, using acronyms is by no means unique to localization, but the field is so small that only at a localization conference will people look at you like you're not speaking complete nonsense.

Anyway, there are a few key terms that if everyone could come to a common understanding about, life would be better for about 30 people. If you are, or have to live or work with, an LPM, these are the terms that you should know.

{: .table .table-bordered .table-striped}
| Term            | Definition/acronym expansion  |
|:----------------|:------------------------------|
| l10n            | Localization                 - Adapting a product's voice, tone and associated assets (videos, images, colors) to another language/country combination |
| i18n            | Internationalization         - making your code base scalably localizable. This is a very relative definition and the degree to which a product is internationalized varies from company to company. It usually includes, at a minimum, display support for foreign characters, string externalization, and time/date formating according to a user's locale setting. It can also include support for right-to-left layouts and various languages' grammar and pluralization rules. |
| t9n             | Translation                  - The actual translation of the words in the software. This work is usually outsourced to an LSP that contracts their translation work out to smaller LSPs or individual translators--these guys don't make enough to care about your product so it pays to make their job easy |
| Externalization | Abstracting user-facing text from code into resource files or a database |
| LQA             | Linguistic Quality Assurance - Testing the quality of the translations in the context of app/site. This is done in a sanbox/staging area by a third-party QA vendor or the same lingusts that did the original translations. They report the issues in some sort of bug tracking system and the LPMs are tasked with verification, root cause analysis and triaging the bugs, all in a language that they likely don't speak |
| Testing         | Often used synonymously with LQA and this varies from company to company but can mean simply mean 'verify that all of the text is translated' |
| LSP             | Language Service Provider    - Localization vendor  |
| TM              | Translation Memory           - A database (usually file-based) of English segments and their corresponding translations. This exists so previously translated content can be reused to save money and increase consistency. Most modern CAT tools perform fuzzy matching as well |
| CAT tool        | Computer Aided Translation tool - This is working environment for a translator. Different ones can come with a lot of bells and whistles but the general purpose of them if to sit on top of the TM suggest matches and lock untranslatable content (placeholders and HTML tags) so the translator doesn't accidentally break the software |