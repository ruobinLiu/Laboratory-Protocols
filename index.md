---
layout: lesson
root: .
# Overall title for the Lesson.
# This should be in the form of a question if possible.
title: "Lab Protocols"

# Single Sentence purpose for this lesson.
short-purpose: "This lesson will show our new researchers some of the protocols we use in our research laboratory."

# Single-Sentence describing the researchers
# who will be helped by this tutorial.
who: "Pulse Crop Researchers"

# A comma-separated list of maintainers for this lesson.
maintainers: "Robert Stonehouse, Ruobin Liu"

# A comma-separated list of the original authors (i.e. the person who determined the protocol or wrote most of the content.)
authors: "Robert Stonehouse"

# A short paragraph describing why we created this lesson.
# What question is it trying to solve and why is that question important.
why: "This lesson is providing some essential laboratory protocols to guide new researchers to conduct their experiments."

# A short list of items researchers will learn in this lesson.
learn:
- "How to crude DNA Isolation from seeds"
- "How to extract DNA from fresh pulse tissues"
- "How to use PCR program for KASP assays, then plot the results data"

data-description: "DNA Extraction from Pulse Crop"

# A statement providing attribution for the material and giving context to the citation
attribution: "These protocols were developed by Rob Stonehouse in Dr. Kirstin Bett's Pulse Crop Research lab at the University of Saskatchewan. Ruobin Liu worked with Rob Stonehouse to format these protocols for this tutorial."

# A casual citation for the protocol
# Format: Author(s). Editor, or professor. Year. Title of lab manual [lab manual]. Place of Publication: Publisher.
# Example: Dorken M. and Nol E. 2014 Fall. Laboratory Manual for Biology 1020H [lab manual]. Peterborough (ON): Trent University.
citation: "Stonehouse, R. Bett, KE. 2022. Molecular marker assay from DNA extraction protocol for the USASK Pulse Molecular Biology Laboratory [lab protocol]. Saskatoon (SK): University of Saskatchewan."
---

The KnowPulse KnowledgeBase focuses on short question-based lessons to help researchers get their work done.

- **Purpose:** {{ page.short-purpose }}
- **Who:** {{ page.who }}
- **Maintainer(s):** {{ page.maintainers }}
- **Original Author(s):** {{ page.authors }}

{{ page.why }}

<strong>Some of the things you will learn include:</strong>
<ul>
	{% for item in page.learn %}
	<li style="font-weight:bold">{{ item|markdownify }}</li>
	{% endfor %}
</ul>

> ## Attribution
>
> {{ page.attribution }}
>
> <div class="citation">{{ page.citation }}</div>

> ## Getting Started
>
> The KnowPulse KnowledgeBase lessons are hands-on, so participants are
> encouraged to use their own computers to ensure the proper setup of tools
> for an efficient workflow. To most effectively use these materials,
> please make sure to download the data and install everything before
> working through this lesson.
>
> This workshop assumes no prior experience with the tools covered in the
> workshop.
>
> To get started, follow the directions in the [Setup](setup.html) tab to
> get access to the required software and data for this workshop.
{: .prereq}


> ## Data
>
> {{ page.data-description }}
{: .prereq}
