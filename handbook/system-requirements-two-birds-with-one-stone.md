# System Requirements – Two birds with one stone!
System requirements is one doc that users look at carefully before they proceed with installation and set up of the product. Providing unclear information in this doc will lead to a highly dissatisfied customer due to blocker at the initial phase of product implementation.

## The Challenge
A brief looking document packing lot of information.

- The single page layout for listing multiple requirements (client, server, database, services, and so on) made the navigation and accessibility of content poor.
- Support matric table became an enormous table making it extremely hard for the writers to update and navigation for users extremely difficult.
## Approach
- Analyzing the requirement for both product/release notes environments, cloud and on-premise
- Understanding how the user consumes the information included in the document.
- Focus solution towards the following goals:
    - Increasing visibility to various chunks of information
    - Improving navigation
    - Reducing effort spent by the writers in updating the support matrix table
- Creating a Proof of Concept (POC) to gain stakeholder alignment and buy-in. Stakeholders here would be writers as well as product owners
- Owning the implementation and delivery of the System Requirements experience and the technical solution defined.
## Solution
After discussing several approaches, we were able to finalize the following solution:

- Split the larger topics into topics with focused content. For example, requirements for client system would have its own topic rather than being part of the monolithic topic. This is inline with DITA guidelines as well.
- Utilize left nav better by adding topic heads for each component, such as client, server, database, services, and so on.
- Split the support matrix table modules or component-wise to make it:
    - Easier to update for writers
    - Provide better navigation and visibility to various components
## Result
This approach resulted in:

- More visibility and accessibility for each component/module.
- Easier to maintain help document.
- Easier to maintain support matrix table
## Example
[Click to view an example](
https://www.ge.com/digital/documentation/apm-classic/v461/help/sys-req-basic-system.html).



