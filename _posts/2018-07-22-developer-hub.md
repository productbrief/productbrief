---
layout: brief
title:  "Developer Hub - documentation made easy"
author: ryan
categories: [ brief, docs-tools ]
image: https://s3.amazonaws.com/ryanhaber/productbrief/content/images/developerhub-output.png
featured: false
hidden: false
---

*tl;dr*: Developer Hub ([www.developerhub.io](https://www.developerhub.io)) is a new product that makes it easy to create documentation in minutes. It is clean, has core features, and is headed in the right direction.

# the product:

Developer Hub is a new documentation product that clearly aims to get you writing and publishing quickly and easily. It succeeds. Within seconds of sitting down to the website, you'll be creating instantly available documentation. With no need to build, convert, or template your docs, this is SaaS publishing at its easiest.

![simple wysiwyg editor](https://s3.amazonaws.com/ryanhaber/productbrief/content/images/developerhub-wysiwyg.png)

Developer Hub has a simple and intuitive WYSIWYG editor, which means anybody can use it. Adding an image or a code block is as simple as a mouse click. The control panel is simple and reasonably intuitive. As a result, tasks like creating a new version from an existing version are also easy.

You get basic white-labeling options: you can customize the color scheme, logo, and favicon. Obviously this customization will not be enough for some enterprises. For most of us looking to just get up and running, it's plenty.

Google analytics: Increasingly, and especially for technical products, user documentation is a key part of strategy to market to the technical user that informs a purchasing decision. Docs writers also benefit by understanding the behavior of their users. For both of these requirements, easy Google Analytics integration is vital.

# the competition:

Developer Hub is a turnkey SaaS docs portal for small scale documentation projects. As indicated by the code block feature and, well, the name, this product clearly has an eye toward products that include code samples. It could be used easily for other small documentatio projects. Other such products and services include:

* [ProProfs KnowledgeBase](https://www.proprofs.com/knowledgebase/)

* [ClickHelp](https://clickhelp.com/)

* [MindTouch](https://mindtouch.com/)

and my favorite

* [Paligo](https://paligo.net/)

These products are all SaaS docs portals for small scale products.

I distinguish Developer Hub and its competition from products such as [Adobe RoboHelp](https://www.adobe.com/products/robohelp.html), [Madcap Flare](https://www.madcapsoftware.com/products/flare/), and [OxygenXML Editor](https://www.oxygenxml.com/doc/versions/20.1/ug-editor/). The key distinctions are platform, scale, and end product. Developer Hub is SaaS. These products are enterprise installations. Developer Hub helps smaller documentation projects through their life cycle. These products cope with thousands of documents across multiple projects and are overkill and have too much overhead for smaller projects. Developer Hub provides a live website as output. Those products support multiple export and output paths.

Paligo is in some ways the closest. Its UI is perhaps most similar to Developer Hub's. In reality, though, Paligo is an XML content authoring tool and probably more akin to OxygenXML for practical purposes. XYZ - validate

# proposals:

1. Additional customizations: Some clients will want a landing page that they can more fully or totally control. Generally speaking, it will also be useful to allow an HTML view of any particular content page as well, though probably within the existing template. Writers may want this view so they can code tables, set internal anchors, etc. The ability to inject css and javascript may also be helpful to many users.

1. Snippets and variables: Writers, like coders, often want to reuse blocks of code. Very often, they want to be able to edit this blocks in one place and have the edits mirrored in the other instances. We usually call thse blocks 'snippets'. Variables allow users to insert values like current year that are updated at build or display time. Both snippets and variables are a common approach to keeping content fresh and consistent.

1. Internal references: It would be great to have hyperlinks within the documentation automatically updated in the event that a page's URL or name changes.

1. Swagger integration: The dream here is a fancy and configurable UI for OpenAPI/Swagger documentation built into the product. The API reference could be a stand-alone page or it could be inserted into existing docs. The ability to directly edit the HTML of a page would provide a short-term or less dreamy approach to this enhancement.

1. DNS assignment: The ability to assign my org's own domain name to pur docs would be a solid win.

1. Permissions / community involvement: Permissions could work on a few levels. Authorized team members could log in and have permissions granted by the docs admin to write, edit others' writing, and/or publish. An admin or publisher could also have the ability to enable or disable comments and/or likes from readers signed in via SSO. Github, Google, and Facebook seem like likely integrations.

# monetize it:

1. I suggest a basic tier of use for free with the product scaling along with customers' needs and ability to pay.

1. charge for: additional users, additional customizations, additional plugins, easy import/export