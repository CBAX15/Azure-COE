# Problem 
X15 being a highly agile, fast growing organization demands fast turn around time for support from its partner organizations like Microsoft for resolving roadblocks to ensure smooth delivery and short time to market for its ventures. 

These support requests can often be complex due to the heterogeneity of the nature of requests ranging from technical issues, resourcing requests, troubleshooting requests, technology/service support, agreement renewals requests, requests for best practices and patterns, etc. The partner organization having multiple field personals associated with the account (X15) adds to the complexity as the business unit they belong to may have specific processes which is unique to it.

These complexities makes it challenging for the venture leads and X15 platform leads to raise an issue with the right point of contact, to track them, and to optimize the resolution time.

The following list articulates an abstraction of the problem:
1. The requests raised by X15 (towards Microsoft) are very heterogeneous in nature.
1. There are multiple Microsoft resources who are associated with X15 account and their responsibilities and roles can be confusing. There may also be overlaps in terms of ownership.
1. The ambiguity in this perspective can result in request hops, in turn causing higher turnaround time.
1. The information about the complex structures of Microsoft roles is not of relevance to the venture leads. 
1. Multiple point of contacts belonging to different business units introduce different processes, which adds to the complexity.
1. Diverse processes forces the use of different tools and systems. This forces the venture and X15 leads to interact with multiple tools making it difficult to raise and track requests. 
1. Lack of a centralized control plane for issue tracking prevents transparency of the resolution process.

# Proposed Solution
The proposed solution (CITBot - Centralized Issue Triaging Bot) is to enable a centralized triaging process for raising and tracking requests targeting Microsoft, using ChatOps. The process will be driven by an automated workflow power by a Chat Bot which will enable the following:
1. Single channel of interaction (Chat Bot). Ability to raise, track, query and modify the request using the chat channel. 
1. Automated ingestion of metadata relevant to classify and categorize a request 
1. Machine learning enabled assignment of requests to appropriate resources
1. Automatic escalation of issues as per the severity and resolution delays
1. Smart duplicate resolution using cognitive services
1. Advanced reporting of requests

## What is ChatOps

ChatOps can be defined as a collaboration model that connects people, tools, process, and automation into a transparent workflow. The Workflow is usually surfaces using a channel which can be a chat client, an IVR (interactive voice response) system, emails conversations, etc. ChatOps offers a good depth of transparency which tightens the feedback loop, improves information sharing, and enhances team collaboration. 

## Solution Scope
The CITBot solution will be delivered in the following Three phases:
1. Phase 0 - Pilot
   1. Teams Channel integration
   1. Simple authentication and authorization
   1. Power virtual agents and Power Automate setup
   1. Azure Boards setup
   1. Simple workflow for Azure related issues
   1. Simple email notifications 
   1. Adaptive cards driven 
   1. Machine learning integration
   1. Basic operations
      1. Raise request
      1. Query request
      1. Delete request
      1. Provide feedback
1. Phase 1
   1. Enable user claims
   1. Enhance Workflow for Non-technical and Non-Azure cloud technologies
   1. Notifications
   1. Editing requests
   1. Templatized notifications
   1. Setting up alerts 
   1. Automatic escalation
1. Phase 2
   1. Machine learning feedback loops (self learning)
   1. Automatic duplicate resolutions
   1. Non cloud workflows
   1. Integration with live feeds (like Azure health reports)
   1. Reporting 

### Most Viable Product
Phase 0 will be considered as the MVP for this engagement. 

## Solution Blueprint
![Image](/Images/CITBot.png)

