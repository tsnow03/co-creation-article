---
# File metadata may be provided as frontmatter YAML
title: A path to better science through co-creation and open infrastructure
description: 
date: 2025-04-08
tags:
  - open science
  - open source
  - geoscience
thumbnail: images/Model_CollaborationFigure1.png
abstract: |
  Proprietary development solutions are often perceived as being delivered more quickly and easily than open methods, fueling the misconception that they inherently produce better overall outcomes. However, we argue that open development practices can lead to both efficient and maximally impactful outcomes and that one successful strategy for accelerating open approaches in the geosciences is co-creation. This collaborative flywheel dynamic -- pioneered in the geosciences by the Pangeo project -- encourages teamwork, standardizes access to shared infrastructure, and facilitates iterations of stakeholder feedback and development to accelerate solution finding.
summary: |
  Proprietary development solutions are often perceived as being delivered more quickly and easily than open methods, fueling the misconception that they inherently produce better overall outcomes. However, we argue that open development practices can lead to both efficient and maximally impactful outcomes and that one successful strategy for accelerating open approaches in the geosciences is co-creation. This collaborative flywheel dynamic -- pioneered in the geosciences by the Pangeo project -- encourages teamwork, standardizes access to shared infrastructure, and facilitates iterations of stakeholder feedback and development to accelerate solution finding.
# AGU requires a Data Availability Statement for the underlying data needed to understand, evaluate, and build upon the reported research at the time of peer review and publication.
data_availability: |
  The code for this article [is available on GitHub](https://github.com/tsnow03/co-creation-article). No other data was used.
acknowledgments: |
  We thank NASA Transform to Open Science program (grant 80NSSC23K0002), and the NASA Cryosphere Program and ICESat-2 Project Science Office (grant 80NSSC22K1877) for funding this work. We thank the development teams, collaborators, and users within each of our development or research communities: Openscapes, NASA OpenScienceLab, 2i2c, CryoCloud, NASA Veda, icepyx, NOAA Fisheries, NASA SlideRule, National Snow and Ice Data Center, Development Seed. The scientific results and conclusions, as well as any views or opinions expressed herein, are those of the authors and do not necessarily reflect those of NASA, NOAA, or the Department of Commerce.
bibliography:
  - references.bib
keypoints:
  - A co-creation community model can produce geoscience solutions that are more impactful and more efficient than proprietary methods
---

>If you want to go fast, go alone; if you want to go far, go together
>
>— African proverb

During the Palisades Fire, researchers were unable to access critical real-time fire mapping for over 12 hours preventing them from tracking the fire's spread to better warn communities in the potential path [@pagan2025]. This was not due to a lack of technology or data, but rather because access was locked behind proprietary walls. In contrast, open infrastructure ensures that science and technology reach and serve the broadest possible audience. 

Adoption of open science and open-source development principles is growing in science and technology as 35 years of mounting evidence from software communities has shown they lead to better outcomes [@gnu; @royalsociety2012openscience; @unesco2021openscience; @besancon2021]. Open-source development is a collaborative approach to creating software with publicly available code, and open science is the principle and practice of making research processes and products accessible, reproducible, and usable by the public. Disciplines across science are transitioning to more openness to improve research efficiency [@donoho2024datascience], enhance impact [@woelfle2011openscience; @antelman2004openaccess], and ensure that science created with public funding is available to the public.

At the same time, there is tension between the collaborative nature of open approaches against the ambition to build faster and more efficiently, often accomplished via proprietary technology. Proprietary development models reduce the number of voices that must be considered and narrow development approaches [@aksulu2010opensource]. As a result, these solutions are often perceived as delivered more quickly and easily than open methods, fueling the misconception that they inherently produce better overall outcomes [e.g., @rocklin2024pangeo].

We are a group of scientists, software developers, and engineers that have separately taken open approaches in our research or development. We all sit near or at the intersection of technology and science, with computing projects designed to facilitate research. Some focus on developing tools or analytical methods, others on enhancing research capabilities, and others on training and education. Our communities range from dozens needing a specific tool, to hundreds using data from a single NASA mission, to thousands of students requiring compute power for coursework. Across our respective research and technology collaborations, we have seen the benefits of open practices not only for improving the quality of our solutions, but also our speed of development.

**We believe that open development practices can lead to both efficient and maximally impactful outcomes**. We argue that a model called *co-creation* is a powerful strategy for accelerating progress through open approaches. This collaborative flywheel dynamic [@collins2009flywheel] — pioneered in the geosciences by the Pangeo project — encourages teamwork, standardizes access to shared infrastructure, and facilitates iterative stakeholder feedback and development to drive solutions forward more efficiently. When combined with thoughtful technological vision, co-creation helps open-development and open-science initiatives build better solutions for wider audiences while also keeping pace with proprietary alternatives.

# From cost savings to community impact: the case for open development
The key strength of open development methods is integrating the micro-expertise and perspective of many, ensuring that development goals serve a broader base of users rather than just those who can pay. As a result, open-development methods often create technology that has many benefits over closed and proprietary methods. For example:

- **Lower cost to use.** Open development usually results in open source technology that can be used for any purpose at no cost [@hoffmann2024value].
- **Easier to reach.** Tools are designed to serve the needs of broader audiences, regardless of funding, location, or infrastructure availability.
- **More innovative solutions for a wider variety of problems.** By involving more perspectives in the *direction* of a project, tools solve challenges on broader and different kinds of fronts.
- **More reproducible.** By focusing on accessibility across the development pipeline, collaboratively developed products are often easier to reproduce [@barba2022defining].
- **More customizable.** Openly developed tools empower users, providing more choice and flexibility than most proprietary tools. This encourages re-mixing and re-use, allowing users to customize existing tools themselves without starting from scratch [@medappa2019opensource].
- **Community empowerment.** By opening pathways for modification and development, users are converted into *collaborators*. They can provide their unique skills and perspectives to a problem in the way that best fits their interests and the project's needs [@lerner2005economics]. This often leads to network effects where a project team becomes greater than the sum of its parts [@medappa2019opensource].


# Co-creation: *How* you build influences what you build
Building on the strengths of open development across many communities we participate in, the most value comes from what we call *co-creation*: the collaborative dynamics enabled by shared infrastructure across communities and the feedback loops we can rapidly cycle through with open infrastructure, end-to-end transparency, and agency over a shared platform. Co-creation requires both having shared access to data, computational environments, and computational infrastructure, and also community investment in their social and collaboration practices, including development of a unique community identity.

In this way, the infrastructure that communities use influences *how and what they create*. By using tools and services that follow the same open development values, shared infrastructure creates its own virtuous cycle with community workflows, enabling communities built on these values to do their work more openly, and thus, *create* scientific and technological outcomes that were more impactful. The history of innovation highlights the critical importance of these connected spaces where a wide range of people naturally encounter and exchange ideas [@johnson2011goodideas].

As an example of co-creation, the eScience Institute (the center for data science collaboration at the University of Washington) regularly hosts five-day hackweeks, workshops centered around training participants in the most up-to-date methods for accessing, developing tools, and analyzing scientific data while working in a cooperative environment. Attendees at one such workshop (Earth Science Hackweek) included new and experienced science users and team members from a variety of privately and publicly funded projects that included dataset producers, open-source data science tool developers, and cloud-computing infrastructure engineers. These participants used shared infrastructure and collaborative practices to complete many instances of a core *co-creation feedback loop* for delivering effective and efficient development. This allowed technology developers to:

- Work with scientific users to learn about their workflows;
- Collaboratively identify ways the open-source ecosystem could solve end-user problems more effectively;
- Immediately make progress on one or more open-source projects, with rapid feedback from domain scientists; and
- Deploy prototypes into production for communities to test.

As a result, these co-creation cycles made improvements throughout the open source ecosystem, quickly deployed new technologies into scientists' hands, and accelerated scientific impact  [@huppenkothen2018hackweeks].


# A feedback loop rooted in co-creation
The feedback loop described above is a common pattern seen across our communities and projects. We generalize the process as a *three-phase co-creation cycle* that repeats itself:

1. **Availability.** A shared platform ensures all participants can immediately use the community-tailored tools needed for collaborating together. 
2. **Learn.** A strong definition of community practices and values with investment in community skills in facilitating collaboration and learning lays a foundation for growing the co-creation skills of community members. A clear definition of community workflows, enabled by their shared platform, lets new members quickly learn and begin contributing to the science or development collective intelligence.
3. **Create.** By giving community members the *skills* and *tools* they need for co-creation, they can answer modular questions, gain insight, and build tools on their own or in groups. With shared infrastructure, these ideas and improvements quickly permeate the broader community and, in many cases, the larger open-science ecosystem.

A co-creation dynamic can be implemented beyond in-person workshops to persistent workspaces, as demonstrated by the Openscapes [@openscapes] and CryoCloud [@cryocloudbook] communities. These long-term collaborative community workspaces foster the three-phase co-creation cycle through shared persistent computational hubs (e.g., a JupyterHub [@jupyterhub]), shared communication platforms with saved histories (e.g., Slack), open training resources for new users (e.g., JupyterBook), and inviting all users and developers from the product pipeline into the community.

Active co-creation occurs when a troubleshooting question generates dozens of responses that result in deploying a bug fix [@panda2024bug] and sharing the solutions widely [@panda2024limits] within a few hours. A new scientific community tool can be staged openly on a shared computing environment, instantly accessed and tested by the user base in the same shared computing space; users can readily ask for and receive assistance from the developer when they run into roadblocks, and developers receive immediate, specific feedback on user experience. Development cycles are completed in as little as hours or days *because* of the one streamlined and interconnected set of workspaces.

In co-creation, using shared open technologies and leveraging a broad community of experts for science, development, and user support reduces the burden on project leads to provide all of the specialized expertise and time themselves. This enables the community to not only move faster but also achieve greater impact.


# Co-creation in Action: Lessons from the Pangeo Project
The open-source science Pangeo project [@pangeo] pioneered a powerful co-creation approach for the geosciences by uniting a strong technological and scientific vision with shared community infrastructure, collaborative workflows, and deep ties to open-source communities. Their goal was to build accessible, high-impact geoscience workflows through fully open tools and services. By forming cross-functional international teams, Pangeo created a tight co-creation feedback loop: new challenges receive immediate attention and solutions were quickly shared with the broader community.

Notably, Pangeo leveraged platforms like GitHub and standardized cloud computing environments to enable rapid iteration, ensuring that solutions developed for specific needs also benefit the public. This strategy helped produce or improve widely adopted cross-domain software (e.g., Xarray, Dask, Jupyter, Zarr, hvplot, Kerchunk) and cloud-computing infrastructure (e.g., JupyterHub distribution for Kubernetes), now used worldwide in both industry [@holoviz] and academia.

Pangeo’s successes demonstrate how co-creation and shared infrastructure foster network effects that elevate the collective scientific enterprise. Communities benefit by using open standards, tools, and services that adapt to specific needs through co-creation, making any improvement immediately usable by all. That is the power of open technology, open science, and services that facilitate the co-creation of value within each.

# Replicating co-creation in more communities
How do we replicate this co-creation model in practice? Below is a short list of items we believe can serve as a catalyst for co-creation in tool development teams, research teams, and/or funding agencies:

First, **lay a strong foundation for collaboration.** This creates the conditions for communities to connect and learn:

- Begin by designing a strong technological vision around a need that others can coalesce around [@schweik2013digitalcommons], then refine it collaboratively with the growing community [@shah2006motivation].
- Disseminate and uphold a welcoming Code of Conduct that promotes a positive work environment [@nielsen2011reinventing].
- Create, fund, and maintain a shared, democratic, open communication space that efficiently directs users to relevant conversations (e.g., Slack, Zulip, GitHub)
- Provide a shared computing space with a shared environment (e.g., JupyterHub)

Next, **invest in your community and its growth** to define *modular* community workflows and build upon this foundation with a broad pool of members:

- Invite new and experienced users and developers from all pieces of the toolchain (e.g., infrastructure engineers, tool developers, data producers and users, domain practitioners/scientists)
- Provide structured training and encourage teaching spaces that resonate with *beginner* users
- Build documentation (e.g., JupyterBook, Quarto [@jupyterbook; @quarto]) that can guide beginners in contributing to the community and technology development  [@nielsen2011reinventing]

Finally, **encourage co-creation cycles and sharing:**

- Encourage community members to share intermediate research ideas and products early and often to stimulate collaboration and feedback [@nielsen2011reinventing]
- Make upstream contributions to open source communities that are needed to complete your workflows
- Practice and encourage intellectual generosity, sharing, and iterating on ideas across all users
- Uphold your community's commitment to using open infrastructure and open collaboration [@invest2025].

While not exhaustive, these practices have been irreplaceable in our projects. However, we note that co-creation can be hindered by a lack of community safety (if the Code of Conduct is not upheld), a clear beginner entry point, ineffective communication forums, or a community without a shared value system, like the scientific method [@nielsen2011reinventing].


# Towards a global network of co-creation for open science
Pangeo's most innovative contribution to the scientific community has been an open development model guided by a powerful technological and scientific vision. This workflow reminds us that moving intentionally for the sake of allowing others to participate accelerates the creation of resilient, useful solutions by leveraging the micro-expertises and labor of many. In this way, open approaches can outperform proprietary ones.

In our research and development cloud communities, we aim to scale Pangeo's collaborative co-creation model, which is fundamentally rooted in **how we do our work, not just what we build**. Prioritizing open technology, standard workflows, and community-centric infrastructure fosters more meaningful improvements along the way, such as more discoverable and analysis-ready data, more useful and user-friendly tools, and more impactful and reproducible science. Expanding this co-creation model will foster a broader, more resilient network of communities that share knowledge and develop enabling technologies. Ultimately, the greatest impact comes from this interconnected collaboration.


<!-- ```{figure} images/la-palma-map.png
:name: map
:align: center
:width: 100%

Map of La Palma in the Canary Islands. Image credit [NordNordWest](https://commons.wikimedia.org/w/index.php?curid=76638603)
``` -->
