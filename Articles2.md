####Read up on the Boston Matrix[5]
Boston Matrix helps the company allocate resources and is used as an analytical tool in brand marketing, product management, strategic management, and portfolio analysis. Analysis of market performance by firms using its principles has recently called its usefulness into question.

To use the chart, analysts plot a scatter graph to rank the (or products) on the basis of their relative market shares and growth rates.

Cash cows is where a company has high market share in a slow-growing industry. These units typically generate cash in excess of the amount of cash needed to maintain the business. They are regarded as staid and boring, in a "mature" market, yet corporations value owning them due to their cash generating qualities. 

Dogs, are units with low market share in a mature, slow-growing industry. These units typically "break even", generating barely enough cash to maintain the business's market share. Though owning a break-even unit provides the social benefit of providing jobs and possible synergies that assist other business units, from an accounting point of view such a unit is worthless, not generating cash for the company. They depress a profitable company's return on assets ratio, used by many investors to judge how well a company is being managed.

Question marks are business operating in a high market growth, but having a low market share. They are a starting point for most businesses. Question marks have a potential to gain market share and become stars, and eventually cash cows when market growth slows. If question marks do not succeed in becoming a market leader, then after perhaps years of cash consumption, they will degenerate into dogs when market growth declines. Question marks must be analyzed carefully in order to determine whether they are worth the investment required to grow market share.

Stars are units with a high market share in a fast-growing industry. They are graduated question marks with a market or niche leading trajectory. Stars require high funding to fight competitions and maintain a growth rate. When industry growth slows, if they remain a niche leader or are amongst market leaders they have been able to maintain their category leadership stars become cash cows, else they become dogs due to low relative market share.

As a particular industry matures and its growth slows, all business units become either cash cows or dogs. The natural cycle for most business units is that they start as question marks, then turn into stars. Eventually the market stops growing thus the business unit becomes a cash cow. At the end of the cycle the cash cow turns into a dog.

#####	Weerd & Brinkkemper “Towards a reference framework for software product management” 

This paper presents the reference framework for software product management. In the basic framework structure, the basic structure of the framework is based on the object. At the same time, it is based on the set of stakeholders defined in the scope of work. And then , there are some generic internal and external stakeholders. In next section, it explains the four process areas about the reference framework for software product management. Portfolio includes the decision making of existing products, through analysis the trends of the market, and product development strategy to introduce new products, decide the lifecycle of the product, and conduct partnerships and contracts. Roadmapping is a metaphor for planning and portraying the use of scientific and technological resources, elements and their structural relationships over a period of time. It is used for business oriented long-term planning and technology forecasting. Requirements management includes the activities of collection, define, revising and organizing the incoming requirements from various stakeholders. Requirements management starts from collect the requirements from the company and external stakeholders. Release planning starts from the priorities of the product requirements.  After the prioritisation, the selected requirements will be implemented in the next release.  
#####		–  Regnell & Brinkkemper “Market-Driven Requirements Engineering for Software Products” (Chapter 13 in Engineering and Management of Software Requirements)  
This paper is mainly described the context and concepts of MDRE, and briefly compare it with the customer-specific development. 

Market-driven development is different from the bespoke development that the product is specific to the needs and wishes of one customer. MDRE refers to the situation where the product is offered to an open market with many customers, the development costs are divided among many buyers and the potential profit is rewarded to the producer. MDRE covers the classical RE activities like elicitation, specification and validation. It also covers the release management and market analysis which is specific to MDRE. The following are some differences between MDRE and bespoke development. 

MDRE:

1. The main goal of MDRE is to deliver the right product at the right time. 

2. In the MDRE, whether the product is success or not is decided by sales, market share, and product reviews. 

3. There is often one major release of MDRE and the product is continuous evolution rather than maintenance. 

4. In the NDRE, much effort is devoted to prioritization, cost estimation and release planning. 

5. Case validation in the MDRE is often delayed until a late stage of the development. 

Bespoke:

1. The main goal of the bespoke development is to realisation of a contract and compliance to a requirements specification. 

2. Int the bespoke products, whether the product is success or not is determined by customer satisfaction and user acceptance. 

3. The lifecycle of the bespoke project is often divided into development first and then maintenance. 

4. In the bespoke development, much effort is devoted to negotiation and conflict resolution. 

5. In the bespoke development, validation is continuous doing through the contacts between the customer and the developers. 

There are some challenges in MDRE: find a good balance between technology-driven and need-driven requirements; communication and collaboration between marketing and development; requirements dependencies make release planning difficult; cost-value estimation. The key issue of MDRE is to continuously improve in managing these challenges to make it ahead of the competitors. 

The MDRE process quality is very important in requirements selection. The alfa/beta model of MDRE selection quality is used to capturing decision quality. An alfa requirement has a high inherent quality that it should be selected and a beta requirement has low inherent quality that should be rejected. It is not easy to find and select alfa requirements and rejecting beta requirements and it is difficult to know whether a requirement is an alfa or beta requirements as the cost-benefit trade-off is very difficult.  

There are two typical ingredients in MDRE data management. The requirements state model is used for requirements refinement progress tracking. There are two modes in the requirement state model. 

In the continuous mode, product manager receive and register all kinds of requirements. It includes the following steps:

Candidate: Each received requirements will have the status “Candidate”.

Approved: The requirements with status Candidate will be reviewed at regular time intervals. The requirements that are being accepted get the status “Approved”. This process is very difficult as it is hard to confirm the quality of the requirements. 

Specified: The pervious description of the requirements is almost not very clearly and detail for planning and developing, then a more suitable and detailed specification is linked to the requirements. 

Discarded:  The requirements being rejected get the statusDiscarded. The reason report will be send to the submitter. The discarded requirements are not deleted from the database to enable future analyses. 

In release mode, the release scope is frozen in order to manage the release development project. It includes the following steps:

Planned: The development team will consider about release date and human resources and maximum the number of planned requirements. All the selected requirements get the status Planned and are input for the design and coding process.

Developed: Development includes design, coding, unit tests and production of collateral materials. The requirements will get status Developed when all the activities are successfully completed. 

Verified: Software testing is used to verify the quality of project before it released. 

Released: The requirements will get the status Released when all the activities are completed and the submitter will get a notification. 

The requirements repository is used to store the relevant attributes of candidate requirements. Smaller project will need a simple spreadsheet and large-scale project will need requirements management tool due to the volume of requirements. 

#####		–  D. Leffingwell “Scaled Agile Framework” (Note, there is no good article on this, but his webpage provides some help). 

Scrum become very popular in software development team, but is doesn’t describe how large project can scale or how manager in program level or portfolio level will handle their requirements together with agile teams[1]. Dean Leffingwell created the Scale Agile Framework(SAFe) to apply agile methodologies to the whole companies. SAFe is based on Lean and Agile principles[2]. 

SAFe proposes three levels[1][2][3][4]: 

Portfolio Level[4]: PPM is the core part in Strategy, Investment Funding, Program Management and Governance.  Epics define large development initiatives that encapsulate the new development necessary to realise the benefits of the investment themes which drive the budget allocations[2]. Portfolio philosophy is the centralised strategy with local execution.   

Program Level: SAFe defines an Agile Release Train(ART) to program. The ART is the main instrument for value delivery at the program level which delivers a value stream for the organization[2]. 5 and 10 teams work together and synchronise their release boundaries and iteration boundaries[2][3].  Every 5 iterations, a train delivers a Potentially Shippable Increment(PSI) and held a demo, inspect and adapt seminars and plan for the next PSI[2]. In this level, new roles are defined. In the IT/PMI environments, the program manager may have more than one roles. If they have domain expertise, they can fill the product manager role. The product manager who defines and priorities the program backlog has content authority at this level. SAFe defines an artifact hierarchy of Epics-Features-User Stories. The program backlog is features prioritised list. Features can generate at the Program level or derive from Epics defined at the Portfolio level[2]. The system architect has design authority at this level. He work with teams day by day to ensure the non-functional requirements are met. He also works with the enterprise architect to ensure there are enough architectural runway to support the upcoming user and business needs at the Portfolio level[2].  The UX Designers provide UI design, UX guidelines and design elements for teams. The Release Train Engineering is the Uber-ScrumMaster. The Release Management Team is a cross-functional team that approves frequent releases of quality solution to customers[2].

Team Level: This level works with traditional agile methods but the team meeting are synchronised. Define/Build/Test teams deliver working and the sprint is also fixed as two weeks[2]. Scrum has many events, sprint planing, sprint review and sprint retrospective, SAFe also add an event called “release planning” meeting to synchronise teams after each five iterations[1]. This meeting is essential for SAFe in order to reduce the coordination overhead between teams, conduct a common direction of all members, and reduce the risks[1]. 
Program and Team Level are work together on the same value stream. 

#####Reference

[1] R. Brenner and S. Wunder, “Scaled Agile Framework: Presentation and real world example,” in 2015 IEEE Eighth International Conference on Software Testing, Verification and Validation Workshops (ICSTW), 2015, pp. 1–2.

[2]  “41 Things You Need to Know about the Scaled Agile Framework® (SAFe) | Rally Software Blog.” [Online]. Available: https://www.rallydev.com/blog/agile/41-things-you-need-know-about-scaled-agile-framework-safe.		

[3] “Program Level – Scaled Agile Framework.” [Online]. Available: http://www.scaledagileframework.com/program-level/.

[4] “Portfolio Level – Scaled Agile Framework.” [Online]. Available: http://www.scaledagileframework.com/portfolio-level/.
[5]“Growth–share matrix,” Wikipedia, the free encyclopedia. 18-Dec-2015.

#####–  Wnuk et al. “Are You Biting Off More Than You Can Chew? A Case Study on Causes and Effects of Overscoping in Large-Scale Software Engineering”  

#####		–  Wnuk et al. “Factors Affecting Decision Outcome and Lead-time in Large-Scale Requirements Engineering”  

This paper use case study and survey to investigate the factors affecting decision outcome and lead-time in LSRE. The decision lead-time is the time required to analyse the impact of a decision under this context. The decision outcome is a specific outcome of the decision process called acceptance or rejection under this context. To research on this area, there are three research questions and six hypothesis. After case study and survey among 50 practitioners, they conclude some results. When the decision affect more products, the lead-time to make a decision will increases.  Decision maker should know more complex decisions may take more time. According to the statistical analysis of the decision log, it is more likely to accept the issues of changing requests by important customers. At the same time, the lead-time to accept a decision is shorter than to reject a decision. The number of products affected by a decision increase the decision lead-time. Due to more complex decision take more time, it is wise to decrease their complexity for faster decision. 

#####		–  P. Carlshamre, K. Sandahl, M. Lindvall, B. Regnell, J. Natt och Dag, “An industrial survey of requirements interdependencies in software product release planning”, in Proceedings of the fifth IEEE Interna- tional Symposium on Requirements Engineering, 2001.  

This paper provide an industrial survey in five companies and analysis their requirements’ interdependencies. We found that only about 20% of the requirements are singular. And 20% of the requirements are involved in 75% of all interdependencies. Customer-Specific bespoke product is tend to more functionality-related dependencies, while market-driven product is tend to value-related dependencies. 

In each case, managers are randomly select 20 high priority requirements from the current requirements repository. Based on these cases, there are six commonly used interdependencies of requirements: 

R1 AND R2: means R1 requires R2 to function and R2 requires R1 to function. This is functional-related and is suitable for the bespoke development.

R1 REQUIRES R2: means R1 requires R2 to function but not vice versa. This is functional-related and is tend to be in a bespoke development environment. 

R1 TEMPORAL R2: means either R1 has to be implemented before R2 or vice versa. 

R1 CVALUE R2: means R1 affects the value of R2 for a customer and the value may be either positive or negative. From a product planning view, this relationship is important. It is value-related and is tend to be in a product development situation.  

R1 ICOST R2: means R1 affects the cost of performing R2 and the value could be either positive or negative. In some cases, CVALUE and ICOST are relevant. For instance, R1 increase the value of R2 for the customer, but it increase the cost of implementing R2 at the same time. It is value-related and is tend to be in a product-oriented case. 

R1 OR R2: means only on of R1, R2 needs to be performed. 

In some cases, two requirements may have more then one relationship. In the product development perspective, the value-related interdependencies are more common than functionality-related. However in the bespoke development, functionality-related interdependencies are more common than value-related. To support the release planning, a simple visualization technique is apply to the requirements and their interdependencies. It is a powerful tool and is good for release planning. Requirements having no relationship with others are easily spotted and free clusters can be scheduled for any increment in which requires all involved requirements are scheduled for the same increment. Requirements having interdependencies with others should be implemented at early stage and they should be scheduled for the same release in order to simplify realisation and reduce the risks.  
