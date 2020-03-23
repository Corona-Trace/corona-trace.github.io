# CoronaTrace
## Onboarding Document



##Mission Statement:
Limit the spread of Covid-19 and save lives by using decentralized contact-tracing using mobile phones and GPS. 

##Overview:
Mitigation of Coronavirus must balance the effects on the economy with the safety of citizens. 
Nationwide social-isolation and quarantines are helpful in the short-term to limit the possibility that hospitals are overwhelmed. In the long term quarantines are not sustainable because the economy pays a huge price when people continue to socially isolate. Lifting quarantine-like restrictions is not possible without risking a subsequent flareup of cases unless we adopt contact tracing as a wide-spread measure. Contact Tracing is currently a time-intensive and centralized process which will overwhelm health systems when tracking thousands of cases unless we adopt technology to decentralize and load-balance.

##Philosophy on Privacy:
We take privacy seriously. We believe that private information can be sufficiently protected and voluntarily shared to help save lives during this crisis. 
* CoronaTrace is an opt-in app. We will use clear disclaimers as people sign up to explain what information is shared and how it will be used.
* Location History - This traditionally private information will be disassociated from an individual before inclusion in the CoronaTrace database; this information will not be made publicly visible; any displays will be of aggregated information
* COVID-19 Test Confirmation - The test result documentation will not be permanently stored by CoronaTrace; only infectious status will be stored in the database; any PII included on the test result documentation will not be stored in the database
* All information and communication will be encrypted



Q: What is CoronaTrace?
A: CoronaTrace is a platform to facilitate decentralized contact tracing for confirmed Covid-19 patients. 

Q: What is contact tracing?
A: In public health, contact tracing is the process of identification of persons who may have come into contact with an infected person ("contacts") and subsequent collection of further information about these contacts. By tracing the contacts of infected individuals, testing them for infection, treating the infected and tracing their contacts in turn, public health aims to reduce infections in the population. Diseases for which contact tracing is commonly performed for include tuberculosis, vaccine-preventable infections like measles, sexually transmitted infections (including HIV), blood-borne infections, some serious bacterial infections, and novel infections (e.g. SARS-CoV and SARS-CoV-2).

The goals of contact tracing are:
To interrupt ongoing transmission and reduce spread of an infection
To alert contacts to the possibility of infection and offer preventive counseling or prophylactic care
To offer diagnosis, counseling and treatment to already infected individuals
If the infection is treatable, to help prevent reinfection of the originally infected patient
To learn about the epidemiology of a disease in a particular population

Contact tracing has been a pillar of communicable disease control in public health for decades. The eradication of smallpox, for example, was achieved not by universal immunization, but by exhaustive contact tracing to find all infected persons. This was followed by isolation of infected individuals and immunization of the surrounding community and contacts at-risk of contracting smallpox.

Read more here:
https://www.who.int/features/qa/contact-tracing/en/
https://en.wikipedia.org/wiki/Contact_tracing

Q: How does it work?



Q: Who is involved in this?
A: This group was initiated by the team at Mutual Mobile who believe that decentralized smartphone-GPS based contact tracing is a critical component of our response to Covid-19. After the creation of an initial prototype, the group was opened to a broader audience to help with various efforts ranging from scalability, privacy, security etc.

It is now an effort with a broader coalition of volunteers and companies that are working together, sharing resources in order to make this a reality. 

Now, that includes you!!

Q: How far along are you?
A: An initial MVP of the application has completed the first phase of development - which means full-end-to-end notifications on iOS and Android based on people that were in a spatio-temporal radius. 

Here’s a video of the app in action:
https://drive.google.com/file/d/1H4BAqJ4V9W_m6Y7GZ9W5veq-1wfFVxLW/view?usp=sharing



Q: Github repo?
https://github.com/Corona-Trace . 

Q: What is the Roadmap?
A: 
Priority 1: Make sure the core spatio-temporal notification capability is robust, scaleable, secure and private-enough. 
Priority 2: Workflow to verify that self-reporting is authentic - upload photo to reviewer. 
Priority 3: Upload Google Location History & iCloud Location History via Web for confirmed users to submit their location history. 
Priority 4: Map and increased radius alerts so users can proactively avoid hotspots. 
Priority 5: SDKs so other apps can promote this to their user base. 
Priority 6: Automated Place Matching to notify venues that have been contaminated. 


Q: What are the various channels / sub-groups for discussion?
#development: 
#mobile
#pr: PR, Media Marketing
#security: How do we make sure this is secure
#design: How does it work?
#news: Relevant Covid news
#onboarding: Onboard new members

Q: How can I help? What are the important problems to tackle?
Working Group Needed: 
We need a workflow to verify that self-reporting is authentic - perhaps uploading a photo on a confirmed diagnosis to reviewer. We need people to research on how to go about confirming that a person that reports that they are positive are indeed positive. We need this workflow designed and coded. 

Working Group Needed:
Upload Google Location History & iCloud Location History via Web for confirmed users to submit their location history if they did not previous have the app installed on their phone. 
This is very important!

Working Group Needed:
Automated Place Matching to location history of an infected individual to notify venues that have been contaminated so that the venue can notify their patrons. 

Feel free to research any of these topics and post in the #general channel or start your own channel within our Slack to discuss your progress. 

Next:
Priority 4: Map and increased radius alerts so users can proactively avoid hotspots. 
Priority 5: SDKs so other apps can promote this to their user base. 
Priority 6: Automated Place Matching to notify venues that have been contaminated. 

