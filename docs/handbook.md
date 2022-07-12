# Technical Writing Handbook

# Being a Technical Writer
As a technical writer, you are responsible for providing detailed instructions and conceptual information on a specific product. You will help the user understand what the product is, why you need the product or what problems the product can resolve for you, and how the product works.

As a technical writer, you need to understand the product and the user for whom you are writing. This means that you not only have to keep learning new products but also understand each feature that you are documenting while considering how your user will use the information. Since you need to write about the technical product in simple and straightforward terms, you must be well-versed with the product. 

>*If you can’t explain it to a six year old, you don’t understand it yourself.
Albert Einstein*

## Fundamentals

Some of the fundamentals for being a good technical writer are:

**Audience analysis** 

Know your users. Write based on your user’s context. For example, ask yourself if your user is experienced or novice or somewhere in between. Do not assume a user would know the concepts. Someone who comes to documentation would have either tried everything in the product or might be new to the product and is looking to get started. As a writer, you want to cover content to help them.

**Adapt your writing**

When writing, think of user experience and adapt your writing to match your audience requirements. Think how they will search for information, or navigate through the doc. Will they go based on a workflow? Or will alphabetical order be a better approach? When developing content, take some time to go over the overall flow and think like a user. You want to write a document that is useful as usable by your users/readers and not just comprehensive. Having all the information in the world will not help if the information does not provide what your users need.

**Use proper English**

You must be able to explain not just steps but concepts on features in simple and clear English. Do remember that the content might be translated to other languages. You are not just writing for English speakers but also for non-English speakers. When incorrect English is entered into translation tools, the meaning might change altogether. 

**Write simple**

You are writing to help users understand the product and not showcase your vocabulary. If you can use simple English to convey, use simple words. The only exception would be to use an industry-wide technical term to explain a product.

**Learn the product**

Use the product to understand what it does and how it works. If you do not understand the product, you will most likely just write what the developer is saying. If the developer were able to explain the product, why would we need writers to break it down into simple language? The developers are technical experts and know what they are talking about but our users might not have the same technical skills or be well-versed with the technical language that the developers use. Therefore, learn the product to use, and then write about it.
### [Why do you need a techincal writer](need-for-technical-writer)
### [Skills beyond technical writing](skills-beyond-technical-writing)
# Doc Types
Technical writers are responsible for producing a variety of technical documents. Few of them are listed here:

#### [Release Notes](the-curious-case-of-release-notes)  

#### [API Documentation](art-of-api-documentation)
#### User Guide

#### [Online Help](online-help)
#### Installation Guide

#### Upgrade Guide

#### [System Requirements](system-requirements-two-birds-with-one-stone)
#### [The Science of Troubleshooting](the-science-of-troubleshooting)
#### [Knowledge Base Articles](knowledge-base-articles)
#### Reference Guide
- Coming Soon!
#### Administrator Guide
- Coming Soon!

<!--
# Languages 

#### XML 

#### Markdown

# API documentation

API documentation tools and examples
-->


# Concepts
<!--
#### Good docs vs bad docs (what makes a doc good/what to avoid)
#### Content Planning 
#### Content strategy 
#### Information architecture 
#### Context, Content, User-->
#### [Structured authoring](structured-authoring)
#### [Why topic-based authoring is important for technical writers?](topic-based-authoring)
#### [Skills beyond technical writing](skills-beyond-technical-writing)

<!--
#### Minimalism
#### Every page is page one
#### Simple and Concise
## Tools
#### Madcap flare
#### Topic based authoring with flare
#### Oxygen
-->

# Case Studies

- [The Curious Case of Release Notes](the-curious-case-of-release-notes)
- [What’s New – Promote the new Product Version](what-s-new-promote-the-new-product-version)
- [System Requirements – Two birds with one stone](system-requirements-two-birds-with-one-stone)
- [Troubleshooting your worries away](troubleshooting-your-worries-away)

<!--
#### [The Curious Case of Release Notes](the-curious-case-of-release-notes)

Release Notes are the most popular form of documentation for any release. While the users wait for this document to be made available, writers are as anxious to provide a high-quality content for this highly visible and awaited document. 

**Challenge**

A monolithic Release Notes document tied together release notes for all previous versions since the beginning. Since writers work on multiple parallel branches and trunk based on the releases are in progress at one point in time, there was continuous requirement to duplicate the effort to other parallel branches and the trunk as well to have the ability of deliver this monolithic Release Notes package.

**Approach**

Analyzing the requirement for both product/release notes environments, cloud and on-premiseUnderstanding the requirement to continue to tie all the release notes togetherFocus solution towards the goal of reducing duplicate effort being spent by the writers in various source branches/trunkCreating a Proof of Concept (POC) to gain stakeholder alignment and buy-in. Stakeholders here would be writers as well as product ownersOwning the implementation and delivery of the release notes experience and the technical solution defined.

**Solution**

After discussing several approaches, we were able to finalize the following solution:

- Split the release notes year wise.
- Provide a placeholder to link the consolidated release notes till last year
- For each subsequent year, a new placeholder will be added for the previous year's release note package.

**Result**

With this approach:

- Product users continue to get consolidated release notes 
- Technical writers do not need to duplicate the effort
- The package size reduced to 1/10th, reducing the upload time

**Add on**

- Brevity in left navigation
- Product name added only once
- New sections added in same page area

**Example**

- [Click to view an example](ge.com/digital/documentation/predix-apm/latest/release-notes/previous/2021/release-notes.html).

    ![Example](./images/curious-case-of-release-notes.png)

#### [What’s New – Promote the new Product Version](what-s-new-promote-the-new-product-version)

What’s New section is included in release notes or might take a form of of its own. In either case, this section is used to communicate new features and bug fixes to the customers. Let us look at how What's New was able to support product managers and guide customers. 

**Challenge**

As technical writers, we all know how critical the release notes are! We write Release Notes to inform customer what new features or fixed issues or known issues a new release is bringing for them.  However,  with large products or products with annual releases,  customers will have to look through a large doc set to understand what's happening in a new release. 

Add over 40 modules or components to the product mix, and customers will find navigating through module release notes. But what happened to the overall product change. Whether customer is using 1 module or 10, overall product changes are still relevant and probably more critical to ensure the modules keep working as expected. 

In addition, there was no visible way to help customers get ready for the upcoming changes in advance. 

**Approach**

I used the following approach:

- Think product rather than module
- Analyze all release notes and identify product level changes 
- Define main sections to help user get to the area of interest quickly
- Focus on monthly input rather than end of release input
- Include global documentation changes as well
- Avoid module-specific content
- Include sections with changes only. Do not include a section if there is no corresponding change.

**Solution**

In discussion with product management, we decided to introduce What to Expect and What's New sections. 

- **Start with What to Expect section:** Update this section each month to gather inputs for release related What's New section. This ensures that you get regular input for an upcoming release's major product changes.
- **Wrap up with What's New section:** Move all the content from What to Expect section to What's New section close to release with the following Information Architecture. provided in the next section.Continue to build
- **What to Expect section for the next release:** Ensure that while prioritizing one release, you are continuing to think future and start building for the next release.

**Information Architecture**

- Release Notes
- What's New
    - Visual Changes
    - Documentation Enhancements
    - Features and Enhancements
    - Software Support
    - Performance Improvements
    - End of Life Features
- Upcoming End of Life Features
- What to Expect in `<add the release>`

**Result**

A well-written What's New section was able to accomplish the following for customers:

- Convey upcoming features for the overall product
- Convey call to action based on critical changes
- Help understand the scope of new release in advance

Product Managers were able to use the What to Expect section to convey the upcoming changes on a regular basis.

**Example** 

- [Click here to view an example](ge.com/digital/documentation/predix-apm/latest/release-notes/whats-new.html)
-->