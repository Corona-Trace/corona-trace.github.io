---
title: "Get involved"
layout: splash
permalink: /
date: 2020-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/hero.jpeg
  actions:
    - label: "Join Slack Team"
      url: "https://join.slack.com/t/coronatrace/shared_invite/zt-cwbz4cdh-q2l7B~DlYNpxnjrn2zF23g"
excerpt: "CoronaTrace is a platform to facilitate decentralized contact tracing for confirmed Covid-19 patients."
intro: 
  - excerpt: 'Our mission is to limit the spread of Covid-19 and save lives by using decentralized contact-tracing using mobile phones and GPS. Prioritize saving lives over privacy.'
feature_row:
  - image_path: assets/images/hero.jpeg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: assets/images/hero.jpeg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/hero.jpeg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: assets/images/hero.jpeg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: assets/images/hero.jpeg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: assets/images/screenshot-notification.png
    alt: "placeholder image 2"
    title: "Ready to change the world?"
    excerpt: 'Then click this button to join our Slack team and make an impact on the world.'
    url: "https://join.slack.com/t/coronatrace/shared_invite/zt-cwbz4cdh-q2l7B~DlYNpxnjrn2zF23g"
    btn_label: "Join Slack Team"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

## Start here

If you are a developer, designer, copywriter, product manager, agile coach, lawyer, public relations specialist, health practitioner, or in any other way want to contribute to the success of the CoronaTrace mission, please follow these steps: 

1. [Join our Slack team](https://join.slack.com/t/coronatrace/shared_invite/zt-cwbz4cdh-q2l7B~DlYNpxnjrn2zF23g) and introduce yourself in the #general channel
2. [Check out the Git repo](https://github.com/Corona-Trace)
3. [Pickup a task in JIRA](https://coronatrace.atlassian.net/secure/RapidBoard.jspa?rapidView=1&projectKey=DEV&view=planning.nodetail&selectedIssue=DEV-2&issueLimit=100)

We look forward to welcoming you and working together in the fight against Covid-19!

## Overview

Mitigation of Coronavirus must balance the effects on the economy with the safety of citizens. 

Nationwide social isolation and quarantines are helpful in the short-term to limit the possibility that hospitals are overwhelmed. In the long term, quarantines are not sustainable because the economy pays a huge price when people continue to socially isolate. Lifting quarantine-like restrictions is not possible without risking a subsequent flareup of cases unless we adopt contact tracing as a wide-spread measure. Contact Tracing is currently a time-intensive and centralized process that will overwhelm health systems when tracking thousands of cases unless we adopt technology to decentralize and load-balance.

## Philosophy on Privacy 

We take privacy seriously. We believe that private information can be sufficiently protected and voluntarily shared to help save lives during this crisis. 

* **CoronaTrace is an opt-in app.** We will use clear disclaimers as people sign up to explain what information is shared and how it will be used.
* **Location History** - This traditionally private information will be disassociated from an individual before inclusion in the CoronaTrace database; this information will not be made publicly visible; any displays will be of aggregated information
* **COVID-19 Test Confirmation** - The test result documentation will not be permanently stored by CoronaTrace; only infectious status will be stored in the database; any PII included on the test result documentation will not be stored in the database
* **All information and communication will be encrypted**

## FAQ

**What is CoronaTrace?**

CoronaTrace is a platform to facilitate decentralized contact tracing for confirmed Covid-19 patients. 

**What is contact tracing?**

In public health, contact tracing is the process of identification of persons who may have come into contact with an infected person ("contacts") and subsequent collection of further information about these contacts. By tracing the contacts of infected individuals, testing them for infection, treating the infected and tracing their contacts in turn, public health aims to reduce infections in the population. Diseases for which contact tracing is commonly performed for include tuberculosis, vaccine-preventable infections like measles, sexually transmitted infections (including HIV), blood-borne infections, some serious bacterial infections, and novel infections (e.g. SARS-CoV and SARS-CoV-2).

**What are the goals of contact tracing?**

* To interrupt ongoing transmission and reduce the spread of an infection
* To alert contacts to the possibility of infection and offer preventive counseling or prophylactic care
* To offer diagnosis, counseling, and treatment to already infected individuals
* If the infection is treatable, to help prevent reinfection of the originally infected patient
* To learn about the epidemiology of a disease in a particular population

Contact tracing has been a pillar of communicable disease control in public health for decades. The eradication of smallpox, for example, was achieved not by universal immunization, but by exhaustive contact tracing to find all infected persons. This was followed by isolation of infected individuals and immunization of the surrounding community and contacts at-risk of contracting smallpox.

Read more here:
* [https://www.who.int/features/qa/contact-tracing/en/](https://www.who.int/features/qa/contact-tracing/en/)
* [https://en.wikipedia.org/wiki/Contact_tracing](https://en.wikipedia.org/wiki/Contact_tracing)

**Who is involved in this?**

This group was initiated by the team at [Mutual Mobile](https://mutualmobile.com/) who believe that decentralized smartphone-GPS based contact tracing is a critical component of our response to Covid-19. After the creation of an initial prototype, the group was opened to a broader audience to help with various efforts ranging from scalability, privacy, security, etc.

It is now an effort with a broader coalition of volunteers and companies that are working together, sharing resources in order to make this a reality. 

Now, that includes you!!

**How far along are you?**

An initial MVP of the application has completed the first phase of development - which means full-end-to-end notifications on iOS and Android-based on people that were in a Spatio-temporal radius. 

<video width="640" height="360" style="margin-bottom: 1.3em;" preload="auto" controls>
  <source src="/assets/videos/demo.mp4" type="video/mp4">
  <p><a target="_blank" href="/assets/videos/demo.mp4">Here’s a video of the app in action.</a></p>
</video>

**Is there a Github repo?**

Yes: [https://github.com/Corona-Trace](https://github.com/Corona-Trace)

**What is the Roadmap?**

* **Priority 1:** Make sure the core Spatio-temporal notification capability is robust, scalable, secure and private-enough. 
* **Priority 2:** Workflow to verify that self-reporting is authentic - upload photo to the reviewer. 
* **Priority 3:** Upload Google Location History & iCloud Location History via Web for confirmed users to submit their location history. 
* **Priority 4:** Map and increased radius alerts so users can proactively avoid hotspots. 
* **Priority 5:** SDKs so other apps can promote this to their user base. 
* **Priority 6:** Automated Place Matching to notify venues that have been contaminated. 

**What are the various channels / sub-groups for discussion?**

The Slack team has many channels covering a wide variety of topics. Here are a few key channels to join: 

* #onboarding: onboard new members
* #development: for engineering discussions
* #mobile: for mobile-app specific discussions
* #pr: PR and media marketing
* #security: how do we make sure this is secure
* #design: how does it work?
* #news: relevant Covid news

**How can I help? What are the important problems to tackle?**

**Working Group Needed:** 
We need a workflow to verify that self-reporting is authentic - perhaps uploading a photo on a confirmed diagnosis to the reviewer. We need people to research how to go about confirming that a person that reports that they are positive is indeed positive. We need this workflow designed and coded. 

**Working Group Needed:**
Upload Google Location History & iCloud Location History via Web for confirmed users to submit their location history if they did not previously have the app installed on their phone. 
This is very important!

**Working Group Needed:**
Automated Place Matching to location history of an infected individual to notify venues that have been contaminated so that the venue can notify their patrons. 

Feel free to research any of these topics and post in the #general channel or start your own channel within our Slack to discuss your progress. 

**Next:**
* **Priority 4:** Map and increased radius alerts so users can proactively avoid hotspots. 
* **Priority 5:** SDKs so other apps can promote this to their user base. 
* **Priority 6:** Automated Place Matching to notify venues that have been contaminated. 

{% include feature_row id="feature_row4" type="center" %}

<!-- 
{% include feature_row %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="right" %}
 -->