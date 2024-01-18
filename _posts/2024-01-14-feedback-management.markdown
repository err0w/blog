---
author: Saurabh
comments: true
date: 2024-01-14
layout: post
slug: feedback-management
title: 'Feedback Management'
desc: 'A first principle take on "managing feedback"'
wordpress_id: 26
categories:
- Blog
tags:
- philosophy
---
The only way to come up and more importantly to generate product ideas is through *feedback from the system*. And hence, receiving, consuming & analyzing feedback is of utmost important to product teams.  The type of feedbacks can be broadly classified into two categories:

1. **Active Feedback** → Here, the feedback is directly visible and is actively given by subject. *Examples could be a customer or sales rep requesting for a certain feature.* The characteristic is that subject expects a specific action from someone.
    
    A key pitfall about such a feedback is the fallacy of ***“noise = priority”,** that is, certain subjects are just very much vocal about feedback than others and product builders tend to confuse noise with severity*
    
2. **Inferred Feedback** → Here, the feedback might not be directly visible and a conscious effort needs to be made for making the feedback visible. *Examples could be user behavior or complaints.* 
    
    Complaints are active dialogues but the feedback is inferred. Active dialogue means that the   subject expects a quick actions but the feedback is not directly visible. 
    
    **Example Being**: In the early days of Flipkart, there were lots of complaints on one SKU (***category: table***) being broken and customer wanted a quick resolution (in the form of return, replacement or refund), however, *the feedback was that supply chain of that specific SKU was broken.* Another example can come from my own experience at 1K, while running 1K mall, we had lots of complaints on a specific brand of smart watches and customers wanted a refund ***(an active action)*** however *the real feedback was that the quality of the watch is bad.*
    

The sources of feedback can be broadly classified into:

1. **External Feedback** → The feedback that you receive *“from the subjects outside the company”*. Examples include Customer Feedback, feedback from partners (*”feedback from implementation partners or franchisee owners”*), feedback from experts (*”feedback on AI from Andrew Cheng”*), or even feedback from media houses (”*feedback on Byju’s from TMS”*), influencers (like *“Dharmesh Ba giving UX feedback to Animall”).* 
    
    Such feedback can be active or inferred in nature. One needs to search for this kind of feedback and is not actively visible to product builders. For example, a product builder needs to make a consciously make a choice to comb through Customer Support tickets, app store reviews, social media posts etc.
    
2. **Internal Feedback →** Feedback from specialists within the company. A product needs to be used (*WMS, Billing Management Systems, Vendor or Procurement Management Systems*), sold (*Sales or BD Teams)* or marketed (*marketing teams*) by internal teams. These internal teams directly *“deal or try to influence”* and may have relevant feedback for making more effective (to large extent) for business or users. 
    
    Depending upon the organizational philosophies, the internal feedback may or may not include feedback from customer research teams, account management teams, or other business teams.
    
    Internal Feedback is active in nature and a product builder is eventually come across such a feedback even if she is not actively searching for it. This is a direct result of internal stakeholders having greater emotional value with the product than external stakeholders.
    
3. **Behavioral Feedback** → Behavior captured by technology. Examples being Amplitude, Mixpanel, Pendo, Microsoft Clarity, Hotjar etc. The key thing about this feedback is that “the intent of the user was not to give feedback”. The feedback is not directly captured but the feedback needs to be inferred from behavior. 
    
    Behavioral feedback is an output of the product, that is, no behavioral feedback would exist without a product.
    

When a feedback is actively given it is usually accompanied with an expectation of an action from product builder but when feedback is inferred from behavior, an action is not expected from the product builder.

**Inference** **→** The active feedback and communication on the action has led to professions like Customer Support or Account Management and industries like Ticket Management or CRMs.  

The key problems related to feedback management can be classified into following →

- ***Capturing Feedback** →* Capturing feedback from subject in any of its variety, source & format. Already existing products catering to this problem are:
    - **For active feedback →**
        - Survey Products like SurveyMonkey, Google or Microsoft Forms or services like GLG or ThirdBridge etc
        - Tools specialized in collecting feedback during sales journey tools like Salesforce, Hubspot etc
        - Or tools specialized in collecting user complaints like freshdesk, zendesk etc
    - **For inferred feedback** →
        - For event based user behavior like Mixpanel, Pendo, Amplitude etc
        - Recording or heat map based heatmap analysis like Hotjar, Microsoft Clarity etc
- **Processing Feedback** → Expect for survey products, other tools intended for capturing feedback also help in processing feedback. However, depending upon the use cases that they cater to their processing capabilities are limited (by design) to the use case that they cater. For example:
    - Hubspot or Salesforce help in processing feedback help during sales journey
    - Event based capturing tools like amplitude also help in generating related charts for making sense of data points
    
    **Draft Inference**: *While there exists a lots of players that specialize in capturing feedback in various formats or sources, those that specializes in processing feedback are limited*.