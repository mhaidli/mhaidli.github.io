---
title: "Shockvertising, Malware, and a Lack of Accountability: Exploring Consumer Risks of Virtual Reality Advertisements and Marketing Experiences"
authors: Abraham Mhaidli, Shwetha Rajaram, Selin Fidan, Gina Herakovic, Florian Schaub
venue: IEEE Security & Privacy, vol. 22, no. 1, pp. 43-52
weblink: https://doi.org/10.1109/MSEC.2023.3332105
localpdf: "/papers/VRME_study.pdf"
writtenyear: 2024
tags: [publication]
category: publication
lastupdated: March 6 2024.
---

<!-- ## Takeaway & Summary

We analyzed VR ads to understand what are the harms they pose. 
The main issue is that VR ads are more immersive and difficult to escape than non-VR ads. As such, any graphic or explicit ads (e.g., ads for horror movies; ads that require strenous exercise; etc.) are much more difficult to avoid, and can cause real harms to people. Imagine someone relaxing with a VR application to watch movies, and they get served with a hyperrealistic ad where they are chased by a serial killer and need to rapidly run and escape or else be bludgeoned to death.  -->

<!-- ## Paper Summary -->
*This is a high level summary of the paper. It is deliberately informal, casual, and only talks about the high level points from the paper. For full details about the study, please refer to the full paper, which can be found [here](/papers/VRME_study.pdf).*

### Motivation of Study
The goal of this study was to get a better understanding of how VR ads could be harmful. There has already been work studying and thinking about VR advertising and how they can hurt users (incluing some of [my own work](/publications/2021-01-01-identifyingmanipulativeadvertisinginxr/)). Possible harms include privacy risks, manipulation, physical harms, and more. But VR ads are relatively rare, meaning that a lot of this prior work has been speculating about what *could* happen rather than observing what *is* happening.
Slowly but surely, however, VR advertising is expanding. And to the extent it is expanding, we do not have a good sense of what the state of VR advertising is like, and how they care or could be harmful towards people.

That is what this study sought to investigate. In short, we asked (1) what do VR ads look like? and (2) what are the harms they pose for users? 
We did this by analyzing existing VR ads and noting down the harms and risks they posed for consumers. We then extrapolate based on these findings to understand how these harms might evolve as the VR advertising ecosystem matures and evolves. 

### Step 1: Find VR Ads
To analyze VR ads, we first had to find them. This proved to be a lot tougher than expected. Unfortunately, there is no neat search term one can use, or a simple directory where one can find them. We had to examine every VR application on both the Steam store and Oculus store to see. And by every application, I do mean every application -- collectively, we reviewed over 8,000 VR apps to see if they were ads. We then isolated 87 VR ads from these VR apps.
We note that these are standalone VR ads (which we termed "VR Marketing Experiences") -- for example, apps like this [Ikea VR experience](https://store.steampowered.com/app/447270/IKEA_VR_Experience/). We also searched for in-app advertisements, but an initial examination found that in-app VR advertisements were surprisingly rare. Thus, our study focused on standalone VR advertisements.

### Step 2: Analyzing the ads
To analyze these apps, we used a walkthrough approach: basically play through the VR ad from start to finish and noted down features about the ad (for example, what was the ad advertising? What interaction techniques were present?), potential harms, and any interesting features we observed about the ad. We had an analysis sheet (serving almost like a checklist) with things to watch out for and to take notes.

### Step 3: The Findings
We identified multiple risks and harms that VR ads can pose for users. These include:

* A lack of clarity over data practices. Many VR ads did npt have privacy policies, nor did they describe their data collection pratcies. As such, we were unsure of what data was being collected, and what it was used for. 
* Weblinks opening without user content depending on their position. Thus, when a user was walking around a VR ad, a webpage would randomly open if the user stepped on a specific spot, without the user knowing or being aware of it. In these cases the weblinks were fairly benign (webpages to book tourist trips), but one can imagine more evolved ads opening links towards harmful webpages, such as those that serve malware.
* A lack of appropiate exit options that allow users to safely and quickly exit VR ads. This is particularly problematic in VR, where looking away from an ad is complicated by the bulky nature of VR headsets and the 360 nature of virtual worlds and virtual advertisements.
* Shocking and graphic ads that can cause emotional distress in users, (e.g., ads for horror movies that involve the user being chased or dying, ads that show disgusting content, etc.) While this type of 'shockvertising' is not unique to VR, the immersiveness of VR, coupled with the difficulty to escape VR situations, make these types of ads more disturbing.
* Physical exertion from ads. Unlike non-VR ads (where most of the content is consumed passively), VR ads can involve several degrees of physical movement. There may be instances where a user is unable to perform these physical movements, or those movements cause physical injuries (e.g., because the movements are too strenous)

I summarize these harms below:

![Alt text](/images/vrme-harms-summarized.png)

Top-left: Shockvertising—VR ads may display distressing content to users. In this case, to make users fearful of competitors’ products, a VR ad may have users experience dying in a car
crash to highlight the safety features of their own product. 

Top-right: Interactive VR ads may require intense physical movements
to complete and finish the advertising—physical movements that could injure a user or which the user is unable to carry out.

Bottom-left: VR advertisements may use proxemic interactions to open weblinks. Malicious VR ads may distract users with
content (e.g., chasing butterflies or some animated object) to make them unaware of their interactions with their environment.

Bottom-right: VR ads can collect biometric data from users and use it to target advertising. Without clear requirements for
disclosure, what information is being collected by VR advertisers and how that information is being used will be hidden from
the user, who may object to their data being leveraged for advertising purposes.

### Step 4: Implications -- Why do our findings matter?
Perhaps the main takeaway from our paper is that we draw attention to the issue of shockvertising in VR. When talking about the harms of VR advertising, it seems most people focus on two key harms: privacy risks and manipulation. However, we find that a third harm needs to be considered: that of emotional and physical harms /  distress. 

Our results points to the need for guidelines (and enforcement) regarding what can and cannot be advertised through VR. Without these guidelines, people will make all types of VR advertisements. Ads for horror movies where the user experiences death; ads that force the user to carry out controversial tasks; and more. Not all of these ads will start with malicious intent; but the end results of shocking and graphic content distressing the users will still be the same. 
Yes, we know there are already guidelines that exist for acceptable and unacceptable advertising in non-VR. However, it is not enough to copy paste these guidelines into a VR world. Instead, guidelines should take into account the uniqueness of VR (including the high levels of immersion; difficulty escaping the ad; and the fact that one lives through the ad rather than watch it passively) and be updated.


<!-- ## Reflections on the paper
What are some reflections from carrying out this study?

First, one difficulty was finding the ads. This was incredibly annoying. 

Another part was identifying harms is a nightmare.
Reviewers are mean.  -->
