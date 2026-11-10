---
# Change these five lines as soon as you copy this starter.
title: The James & Gail Ellis School of Business Leadership 
author: Ricardo Juarez
category: Academic Building              # change to a category from the student guide
header-image: ellis-building.jpg
header-caption: Replace with where your header image came from. Plain text only, no links.

# Fill these in later, once your research is under way.
card-description: Replace this with two sentences that summarize the story your essay tells and why it matters.
start:                                   # the year your story begins, shown on the map

# Leave this line as it is.
layout: essay
---

The James & Gail Ellis School of Business Leadership at the University of New Mexico is part of a larger story about how a university prepares students to lead in business, serve their communities, and shape New Mexico’s economy. Located in the McKinnon Center, the school connects business education with the physical spaces where students learn, collaborate, and prepare for their careers. Looking at the school’s history raises important questions: How has business education at UNM changed over time, and what do the school’s building, leadership, and institutional history reveal about the university’s priorities?


## Main Story

The history of the James & Gail Ellis School of Business Leadership is connected to the development of business education at the University of New Mexico. UNM has served students throughout New Mexico and the Southwest since its founding in 1889. As the university expanded, professional education became an important part of its mission, preparing students for careers in fields that included management, finance, accounting, and entrepreneurship.
The university’s Anderson School of Management provides the broader academic context for understanding business education at UNM. Within this environment, leadership education emphasizes more than learning how businesses operate. It also involves decision-making, communication, teamwork, and understanding the responsibilities that business leaders have toward employees and communities.
The James & Gail Ellis School of Business Leadership, located in the McKinnon Center, represents a more specific focus on leadership development. Its name recognizes individuals associated with the school, while its location provides a physical setting for students to engage with business education. To establish the school's founding date, the circumstances behind its naming, and the contributions of James and Gail Ellis, archival records and official university documents are important sources of evidence.
One of the most important moments in this history occurred on May 8, 2026, when UNM announced a $30 million commitment from James “Jim” Ellis and Gail Ellis. The gift led to the renaming of the Anderson School of Management as the James & Gail Ellis School of Business Leadership. According to the university, it was the first time a UNM college or school had been named in recognition of a philanthropic investment. The announcement marked a major change in the school's identity and signaled a commitment to expanding opportunities for future business students. Jim Ellis's connection to UNM gives the gift a personal dimension. He earned his Bachelor of Business Administration from the university in 1968 and later received an MBA from Harvard University. His professional career included twelve years as dean of the University of Southern California's Marshall School of Business. His experience in business education connects UNM's local mission with a broader conversation about how universities prepare future business leaders.

<!-- Full-width figure. This is the default for any landscape photo wider than about 700px.
     image-path is just the filename: upload your images into this essay's folder,
     next to index.md. -->

{% include images/figure.html
  class="img-center"
  width="100%"
  caption="Replace this caption. Say why the image matters, not just what it shows, then cite where you found it: [Center for Southwest Research](https://econtent.unm.edu/), collection and box number."
  image-path="sample-archive-photo.jpg"
%}

Every image needs a caption, including this one. A caption should explain what the reader should notice and where the image came from. Captions accept Markdown, so use `[source](https://example.com/)` to link to a digital collection whenever the image has an online home.

## What Changed

Use this section to explain change over time. What did your topic used to be? How did people use it, describe it, fund it, argue about it, rename it, neglect it, preserve it, or forget it?

This is a good place to connect your specific topic to a larger campus pattern: enrollment growth, architecture, student life, race, gender, labor, protest, public memory, administration, technology, or access.

<!-- Carousel: use when you have three or more images that belong together but do not
     each need their own paragraph. Images are split on commas, captions on the | character.
     Carousel captions are plain text: Markdown links will NOT work here, so write out
     the collection name and box number instead of linking. -->

{% assign images =
"sample-archive-photo.jpg,
sample-second-photo.jpg,
sample-primary-source.jpg" | split: ','
%}

{% assign headers =
"Replace with a short slide title,
Replace with a short slide title,
Replace with a short slide title" | split: ','
%}

{% assign captions =
"Replace this caption. Explain what this slide shows and why it matters. Center for Southwest Research, collection name, box number.|
Replace this caption. Every slide needs one. Center for Southwest Research, collection name, box number.|
Replace this caption. Plain text only in carousels, so spell out the source instead of linking. Center for Southwest Research, collection name, box number." | split: '|'
%}

{% include images/carousel.html
  images=images
  headers=headers
  captions=captions
%}

Delete the carousel if you do not have a set of images that works this way. Three related photographs, a series of floor plans, or a run of newspaper clippings are all good candidates. Two images that need to be compared directly are usually better as a pair than as a carousel.

## Evidence

Use this section to show readers a document, not just a photograph. Scanned letters, meeting minutes, ledgers, clippings, and blueprints all reward close looking, and they prove you spent time in the boxes.

<!-- Portrait documents are the exception to the full-width rule. A tall scan at 100%
     is over 1200px tall and swallows the screen, so center it and leave it near 55%.
     Keep it centered, not floated. -->

{% include images/figure.html
  class="img-center"
  width="55%"
  caption="Replace this caption. Tell readers what to notice in the document and why it changes how they should understand your topic. Cite the collection, box, and folder."
  image-path="sample-primary-source.jpg"
%}

Explain what the document says, what it does not say, and how it fits the story. A source you actually read and explain is worth more than three you only mention.

## Why This History Matters

End by returning to the present. How should readers see this campus place, person, organization, object, or event differently after reading your essay? Point to continued use, memory, loss, gaps in the archive, or campus change rather than announcing a conclusion.

{% capture bibliography %}
- Replace this with your first source. Include enough detail that someone else could find it: collection name, box, and folder for archival material.
- Replace this with your second source.
- Replace this with your third source.
{% endcapture %}

{% include typography/bibliography.html
  title="Bibliography"
  content=bibliography
%}
