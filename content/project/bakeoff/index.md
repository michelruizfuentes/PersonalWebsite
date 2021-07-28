---
title: "Regression Analysis"
subtitle: "Independent Research Conducted as an Intern with INSPIRE U2"
excerpt: "Data analytics on market structure and the economics of advertising is significant for many reasons. First, businesses are crucial to society's function, so we must make an effort to comprehend the variables that contribute to their expansion. Second, this research can empower and serve as guidance for historically underrepresented entrepreneurs like people of color and immigrants entering the market and aspire to grow their companies."
date: 2021-07-29
author: "Michel Ruiz-Fuentes"
draft: false
tags:
  - hugo-site
categories:
  - Theme Features
  - R
  - package
layout: single
links:
- icon: door-open
  icon_pack: fas
  name: website
  url: https://bakeoff.netlify.com/
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/apreshill/bakeoff

---

### Functional Form

This theme has a **form-to-email** feature built in, thanks to the simple Formspree integration. All you need to activate the form is a valid recipient email address saved in the front matter of the form
(`/content/forms/contact.md`). Of course, the example shown below (`your@email.here`) must not be used. Please use your actual email address.

```toml
# please replace with a valid Formspree form id or email address
formspree_form_id: your@email.here
```

Update that file and you're ready to begin receiving submissions. Just submit
the active form for the first time, and complete the email address verification
step with Formspree, and your contact form is live. The next time someone
fills it out, the submission will land in your inbox.

### Multiple Layouts

The files included with the theme have a contact page ready for copy/paste, or
you can type `hugo new forms/contact.md` and you're off to the races. There are two
layouts for `forms` – `split-right`, and `split-left` – you guessed it, one puts
the form on the right and the other on the left. You just fill out the front
matter, and the rest is automatic.

```toml
# layout options: split-right or split-left
layout: split-right
```

![Contact Form Split Right Layout Screenshot](built-in-contact-form-screenshot.png)

Both layouts display the page title and description opposite the form, and you
can also choose to show your social icon links if you have those configured in
the `config.toml` file.
