# Software for Open Networking in the Cloud - SONiC
## Governance

## Principles
* **Open and welcoming**: Every participant must abide by the Code of Conduct.
* **Meritocracy**: Contributions are considered on their technical merits.
* **Consensus**: Participants are expected to seek consensus with their peers, project leaders and dependency owners.
* **Conflict resolution**: The Technical Committee is the final conflict resolution body for all instances of the project.

## Code of Conduct
Code of Conduct applies both within project spaces and in public spaces when an individual is representing the project or its community. Examples of representing a project or community include using an official project e-mail address, posting via an official social media account, or acting as an appointed representative at an online or offline event. Please refer [Code of Conduct](https:/github.com/Azure/SONiC/blob/master/CODE_OF_CONDUCT.md) for more information.  

## Definitions   
*	**Participant**: an individual that has an interest in the SONiC project (for example, end users, commercial distributors, or operators) and is subscribed to any of the SONiC mailing lists.
*	**Contributor**: an individual that has contributed a pull request accepted to any SONiC repository. Every contributor is also a SONiC participant.
*	**Working Group**: a self-governed group of individual participants that collaborate on specific areas or initiatives within the SONiC project.
*	**Founder Operators**: a commercial operator that has a founding stake on the SONiC project
*	**Emeritus Members**: an individual that has a founding stake on the SONiC project
*	**Project Lead**: designated individual for driving community, workgroup goals and collaboration among participants.
*	**Technical Committee**: an elected governance body of the SONiC project that provides final conflict resolution services for the SONiC project.

## SONiC Working Groups 
Working Group is created for driving focused discussions or progress in specific area which in turn might include software development, documentation, testing, delivery, or improvisation. Individuals or organizations who are community members, can participate in SONiC Working Group for collaboration around specific effort and join respective meetings of an active Working Group. Contributions that are developed as a part of Working Group, will conform to the SONiC contribution process, as outlined [here](https://github.com/kannankvs/kvskSONiC/blob/master/sonic_contribution.md). 

SONiC has multiple Working Groups. Each SONiC workgroup has project lead assigned to facilitate the discussion among the community members and drive project to completion with minimum governance overhead. Working Groups can be dissolved once the goals are met. Relationship between SONiC Project and Working Group is illustrated below:

![Image](https://github.com/anshuv-mfst/SONiC/blob/master/images/SONiC%20Working%20Group.jpg)

## Create a Working Group
Request for a new Working Group can be made in SONiC Community Meeting forum and will be assessed by Technical Committee, SONiC community members for formation. Alternatively, proposal for creating new Working Group can be emailed to sonicproject@googlegroups.com for focused collaboration and will be subject to assessment. Once consensus is reached in favor of creating a group then, 

*	Working Group should have clear entry and exit criteria defined
*	Working Group should identify key stakeholders for project
*	Working Group should have Project Leader assigned 
*	Working Group should create a new Google Group alias foo-workgroup@googlegroups.com
*	Working Group Project Leader should setup meeting cadence (weekly/bi-weekly) as needed
*	Working Group Project Leader should send out agenda and meeting notes 

Working Group updates should be sent out periodically to the participants and design reviews have to be approved by main community meeting.

## Dissolve a Working Group
Once the objective of the Working Group is met, it can be merged or disbanded. 
*	Send email to sonicproject@googlegroups.com and technical committee notifying status completion.
*	Send cancelation for Working Group meeting invites to the members. 
*	All email discussions are archived in respective Working Group google groups.
 
 For more information on SONiC Working Groups can be found [here](https://azure.github.io/SONiC/workgroups.html). 
 
## Technical Committee 
The Technical Committee is the conflict resolution backstop for the SONiC Project. Its main responsibility is to provide conflict resolution in any instance where contributors cannot achieve consensus within a reasonable timeframe. The Technical Committee has the broadest scope possible in the SONiC project including any subgroup, subproject, workgroup, pull request, architecture decision, specification addenda and design choices. The Technical Committee deliberates openly and transparently and makes decisions on a simple majority. While participants are encouraged to seek consensus, we expect certain decisions that can impact the future of the SONiC Project will need to be brought before the Technical Committee. Even in those cases, the SONiC Project will encourage participants to propose and debate alternatives according to our Code of Conduct. Technical Committee is elected yearly from within SONiC contributors, and is composed of five (5) seats that are allocated as follows:
*	Two (2) seats for Founder Operators
*	Two (2) seats for Contributors
*	One (1) seat for Emeritus Members

The current members of the Technical Committee are:
*	Contributor: [Liat Grozovik](<liatg@mellanox.com>)
*	Contributor: [Ben Gale](<ben.gale@broadcom.com>)
*	Founder Operator: [Lihua Yuan](<Lihua.Yuan@microsoft.com>), [Gouhan Lu](<gulv@microsoft.com>)
*	Founder Operator: [Zhenggen Xu](<zxu@linkedin.com>) 
*	Emeritus Member: [Dave Maltz](<dmaltz@microsoft.com>)

## Roles and responsibilities 
*	*Contributors* are people who have submitted work to the project. Work includes all kinds of tasking, including things like code, tests, code reviews, documentation, infrastructure, and proposals. 
*	*Maintainers* have permission to accept pull requests and merge them into the master branch of a given repository. Each repository contains a MAINTAINERS file listing the maintainers. There must be one or more maintainers per repository. They are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.
*	The *Project Leader* is responsible for the success of the project and resolving conflict between the maintainers and keep the project. Today the project leader is appointed by Microsoft. A new Project Leader is expected to be appointed by the Open Compute Project when it is accepted. 

## Contribution Process 
We welcome everyone to contribute to SONiC project. A [Contribution License Agreement](https://www.1eswiki.com/wiki/Automating_Contribution_License_Agreements) is required for making a contribution to the open source project.  Members can contribute to the community by signing in Github and can access the SONiC contribution. Members can join the various SONiC groups and can start attending actively over the weekly discussion on the ongoing activities. All contributors should follow the contribution process for the community, as outlined [here](https://github.com/kannankvs/kvskSONiC/blob/master/sonic_contribution.md). 

## SONiC Releases 
SONiC release follows the standard development cycle that includes Planning, Design, Coding, Testing and Release process. Until 2018, SONiC Community had three releases per year. Starting 2019, two releases will be published in a year i.e. one middle of the year and other by end of the year. All contributions to the SONiC community should be agreed upon by the SONiC community and align with releases outlined [here](https://github.com/Azure/SONiC/wiki/release_train).  

## Licensing Structure 
Apache License Version 2.0 is required for SONiC. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
