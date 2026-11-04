---
layout: home
hero_title: Technical writing for enterprise Data and AI software
hero_text: Six years of documentation, UI content, and animations for IBM Business Automation Workflow and Content Cortex, plus the way I use generative AI to work faster without lowering the bar.
---

I’m an [award-winning](https://www.linkedin.com/posts/aine-doyle-a3b752139_im-excited-to-share-that-ive-received-the-activity-7280758989179518976-IQ11) content developer and technical writer at IBM with 6 years of experience working on Data and AI enterprise software.

## Featured projects

{% assign featured = site.projects | where: "featured", true | sort: "order" %}
{% include project-list.html projects=featured %}

[See all projects]({{ '/projects/' | relative_url }})

## Generative AI in my workflow

I use generative AI to increase productivity and improve IBM’s product documentation, and I review and edit everything it produces for accuracy and compliance with IBM style guidelines. [See how I use it]({{ '/generative-ai/' | relative_url }}).

## About me

Before IBM, I was a technical writer intern at Akamai Technologies and a grant writer intern at UMass Memorial Medical Center. I hold a Master of Science in Technical Communication from North Carolina State University. [More about me]({{ '/about/' | relative_url }}).
