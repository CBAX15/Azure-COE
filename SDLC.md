# Software Development Life Cycle

Microsoft Cloud CoE recommends a Software Development LifeCycle for X15 ventures which is aligned to strong DevOps principles to support agility in development and short time to market. 

The contraction of “Dev” and “Ops” refers to replacing siloed Development and Operations to create multidisciplinary teams that work together with shared and efficient practices and tools. Essential DevOps capabilities include continuous planning​, integration​, delivery​, operations​, quality​, security​, collaboration​, and improvement​.

The following diagram illustrates the cycle:

![image](./images/SDLC.png)

## Capabilities and Practices
<table >
	<tr align="left" valign="top">
		<th >Continuous planning</th>
		<th>Continuous integration</th>
		<th>Continuous delivery</th>
        <th>Continuous operations</th>
 	</tr>
	<tr align="left" valign="top">
		<td>
            Objectives & Key Results (OKR) </br>
            Lean product discovery</br>
            Lean product definition</br>
            Release planning</br>
            Sprint planning</br>
            Agile requirements</br>
            Security requirements</br>
            Architecture design</br>
            Capacity planning</br>
            UX architecture design</br>
            Threat modeling</br>
            Prioritization & estimation</br>
            Demos & Retrospectives</br>
        </td>
		<td>
            Behavior-driven development (BDD)</br>
            Test-driven development (TDD)</br>
            Microservices & container development</br>
            Mono-repo & Multi-repo</br>
            Unit testing & code coverage</br>
            Version control</br>
            Git pull request</br>
            Trunk-based policies</br>
            Security static code scan</br>
            CredScan</br>
            Open Source software (OSS) component compliance</br>
            Build parallel & serial pipeline</br>
        </td>
		<td>
            Release pipeline</br>
            Secure infrastructure deployment</br>
            IaaS deployment</br>
            PaaS deployment</br>
            SaaS deployment</br>
            Shared services</br>
            Infrastructure as code (IaC)</br>
            Change management</br>
            Configuration management</br>
            Release management</br>
            Blue-green deployments</br>
            Canary deployments</br>
            Feature flags</br>
            Trunk production ready</br>
        </td>
        <td>
            Site reliability engineering (SRE) </br>
            Telemetry & monitoring</br>
            Application performance monitoring</br>
            Auto Failover, scaling, & DR</br>
            Modern service management</br>
            Secure access & application data</br>
            High availability, security, cost & performance advisory</br>
            Secure DevOps ChatOps</br>
            Shift-right testing</br>
            Secrets management</br>
            Governance & GDPR support</br>
            Automation & AIOps</br>
            Continuity & resilience</br>
        </td>
 	</tr>
</table>

<table>
	<tr align="left" valign="top">
		<th>Continuous quality</th>
		<th>Continuous security</th>
		<th>Continuous collaboration</th>
        <th>Continuous improvement</th>
 	</tr>
    <tr align="left" valign="top">
		<td>
            Quality requirements</br>
            Shift-left testing</br>
            Governance & standards</br>
            Test automation</br>
            Compliance & audits</br>
            Shift right testing</br>
        </td>
		<td>
            Security architecture</br>
            Access & identity management</br>
            Application & data security</br>
            Security infrastructure</br>
            Secure operations</br>
            Governance, risk, & compliance</br>
        </td>
		<td>
            Collaborative culture</br>
            Alignment & autonomy</br>
            Kanban collaboration</br>
            Wiki & Teams collaboration</br>
            ChatOps collaboration</br>
            Feature Team & SRE</br>
        </td>
        <td>
            Lead time & cycle time</br>
            Deployment frequency</br>
            Mean time to restore (MTTR)</br>
            Change fail percentage</br>
            Continuous feedback</br>
            Value stream mapping</br>
        </th>
 	</tr>
</table>	



## Tools and Processes 
Microsoft Cloud CoE recommends the following tools for the SDLC activities:
* Capturing requirements - Azure Boards
* Work forecasting, effort estimation and scheduling - Azure Boards
* Resource management - Azure Boards
* Source code repository - Git hub Enterprise
* Dev Ops pipeline - Azure DevOps 
* Integrated Development Environment - Visual Studio code / Visual Studio enterprise


## Choosing the Software Development Process

Anytime you create a project, you must choose a Software delivery process on the process model you use. 

This can be one of the following:

* [Basic](https://docs.microsoft.com/en-us/azure/devops/boards/get-started/plan-track-work?view=azure-devops&tabs=agile-process)
* [Agile](https://docs.microsoft.com/en-us/azure/devops/boards/work-items/guidance/agile-process?view=azure-devops)
* [Scrum](https://docs.microsoft.com/en-us/azure/devops/boards/work-items/guidance/scrum-process?view=azure-devops)
* [CMMI](https://docs.microsoft.com/en-us/azure/devops/boards/work-items/guidance/cmmi-process?view=azure-devops)


More about choosing a process can be found [here](https://docs.microsoft.com/en-us/azure/devops/boards/work-items/guidance/choose-process?view=azure-devops&tabs=basic-process)

## Requesting a board for your project
The workflow will go here

## Inviting your team members to the Kanban board
Your Azure Board is federated with the X15 Azure Active Directory. This will enable users under the X15 directory to be invited to your board. 

Note: If you need to enroll your team members to the X15 Active Directory, please refer to the article [here](To_be_filled)

The steps for inviting members to the Azure board is captured [here](https://docs.microsoft.com/en-us/azure/devops/boards/get-started/sign-up-invite-teammates?view=azure-devops)

## 

## Useful links
* [Azure Boards shortcuts](https://docs.microsoft.com/en-us/azure/devops/boards/get-started/keyboard-shortcuts?view=azure-devops)
