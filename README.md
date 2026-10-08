# Awesome Analysis [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://github.com/sbarkalov/awesome-analysis"><img width="1003" height="365" alt="header-dark" src="https://github.com/user-attachments/assets/3240155f-20e2-4d85-ab8e-4d37c6eae22b" /></a>

> Analysis is the work of deciding what a system should do, and why. It spans the business, systems, and product sides of that question, from eliciting needs to validating the solution.

## Contents

- [AI & Agentic Analysis](#ai--agentic-analysis)
- [Requirements as Code](#requirements-as-code)
- [Modeling & Diagrams as Code](#modeling--diagrams-as-code)
- [Integration Analysis](#integration-analysis)
- [Data & Domain Modeling](#data--domain-modeling)
- [Business Analysis](#business-analysis)
- [Product Analysis](#product-analysis)
- [Systems Thinking](#systems-thinking)
- [Elicitation & Collaboration](#elicitation--collaboration)
- [Agile Requirements](#agile-requirements)
- [Requirements Management Tools](#requirements-management-tools)
- [Regulatory Requirements](#regulatory-requirements)
- [Frameworks & Bodies of Knowledge](#frameworks--bodies-of-knowledge)
- [Domains](#domains)
- [Templates](#templates)
- [Certifications](#certifications)
- [Learning Resources](#learning-resources)
- [Books](#books)
- [Community](#community)

## AI & Agentic Analysis

Using LLMs and autonomous agents to elicit, draft, refine, and trace requirements. Any general-purpose assistant (Claude, ChatGPT, Gemini, DeepSeek, Qwen) drafts requirements and user stories well enough, so use whichever you already have; the entries below are tools built specifically for analysis work.

- [Model Context Protocol](https://modelcontextprotocol.io) - Open standard for connecting AI agents to tools and data sources.
- [MCP Registry](https://registry.modelcontextprotocol.io) - Official directory of MCP servers for trackers, wikis, and databases.
- [Atlassian MCP Server](https://github.com/atlassian/atlassian-mcp-server) - Official server exposing Jira and Confluence to agents over OAuth.
- [Agent Skills](https://agentskills.io) - Open standard for packaging procedures and templates as agent skills.
- [Anthropic Skills](https://github.com/anthropics/skills) - Reference skills, including Word, Excel, and PowerPoint deliverables.
- [ChatPRD](https://www.chatprd.ai) - AI copilot for product requirement documents and user stories.
- [LangChain](https://www.langchain.com) - Framework for building custom analysis and elicitation agents.
- [Spec Kit](https://github.com/github/spec-kit) - GitHub's toolkit for spec-driven development with AI coding agents.
- [OpenSpec](https://github.com/Fission-AI/OpenSpec) - Spec-driven workflow that aligns humans and AI agents before any code.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Requirements as Code

Treating requirements and specifications as plain-text, version-controlled artifacts.

- [Gherkin](https://cucumber.io/docs/gherkin/) - Business-readable language for executable specifications.
- [Cucumber](https://cucumber.io) - BDD tool that runs Gherkin scenarios as living documentation.
- [Markdown](https://www.markdownguide.org) - Lightweight plain-text format, the backbone of docs-as-code.
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) - Popular static-site generator for project documentation.
- [Docusaurus](https://docusaurus.io) - Static-site generator for versioned documentation sites.
- [AsciiDoc](https://asciidoc.org) - Rich plain-text authoring format for technical documentation.
- [StrictDoc](https://github.com/strictdoc-project/strictdoc) - Text-based requirements management with tracing and export.
- [Doorstop](https://github.com/doorstop-dev/doorstop) - Requirements management using version-controlled text files.
- [OpenFastTrace](https://github.com/itsallcode/openfasttrace) - Requirements tracing suite for plain-text artifacts.
- [ReqIF](https://www.omg.org/reqif/) - OMG standard for exchanging requirements between tools.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Modeling & Diagrams as Code

Notations and tools for process, decision, data, and architecture models — text-first where possible.

- [Mermaid](https://mermaid.js.org) - Diagrams from text, rendered natively in Markdown and many tools.
- [Mermaid Live Editor](https://mermaid.live) - Browser playground for authoring and sharing Mermaid diagrams.
- [PlantUML](https://plantuml.com) - Text-based UML and more (sequence, class, activity, C4).
- [C4 model](https://c4model.com) - Lean approach to visualizing software architecture at four levels.
- [Structurizr](https://structurizr.com) - Tooling for the C4 model with diagrams defined as code.
- [BPMN](https://www.bpmn.org) - OMG standard notation for modeling business processes.
- [DMN](https://www.omg.org/dmn/) - OMG standard for decision models and decision tables.
- [SBVR](https://www.omg.org/spec/SBVR/) - OMG standard for business vocabularies and rules in structured natural language.
- [bpmn.io](https://bpmn.io) - Open-source web toolkit for viewing and editing BPMN, DMN, and forms.
- [Camunda Modeler](https://camunda.com/platform/modeler/) - Desktop modeler for BPMN and DMN.
- [GoRules](https://github.com/gorules/zen) - Open-source rules engine with a visual decision table and graph editor.
- [draw.io](https://www.drawio.com) - Free, general-purpose diagramming tool.
- [Excalidraw](https://excalidraw.com) - Virtual whiteboard for quick, hand-drawn-style diagrams.
- [Lucidchart](https://www.lucidchart.com) - Web-based diagramming for flowcharts, ERDs, and UML.
- [Sparx Enterprise Architect](https://sparxsystems.com/products/ea/) - Modeling platform for UML, BPMN, SysML, and ArchiMate.
- [UML](https://www.uml.org) - OMG's Unified Modeling Language for software systems.
- [Archi](https://www.archimatetool.com) - Open-source modeling tool for the ArchiMate language.
- [Markmap](https://github.com/markmap/markmap) - Renders Markdown outlines as interactive mind maps.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Integration Analysis

Designing and analyzing interfaces, contracts, and data exchange between systems.

- [OpenAPI Specification](https://www.openapis.org) - Standard, language-agnostic description for REST APIs.
- [Swagger](https://swagger.io) - Toolset for designing and documenting OpenAPI definitions.
- [Redoc](https://redocly.com/docs/redoc) - Renders OpenAPI definitions into readable reference docs.
- [Postman](https://www.postman.com) - Platform for exploring, testing, and documenting APIs.
- [AsyncAPI](https://www.asyncapi.com) - Specification for event-driven and message-based APIs.
- [JSON Schema](https://json-schema.org) - Vocabulary for validating and documenting JSON data structures.
- [XML Schema (XSD)](https://www.w3.org/TR/xmlschema11-1/) - W3C standard for defining and validating XML document structure.
- [JSON:API](https://jsonapi.org) - Specification for building conventional JSON APIs.
- [GraphQL](https://graphql.org) - Query language and runtime for typed API contracts.
- [gRPC](https://grpc.io) - High-performance RPC framework using Protocol Buffers contracts.
- [SOAP](https://www.w3.org/TR/soap12-part1/) - W3C messaging protocol still common in enterprise integrations.
- [WSDL](https://www.w3.org/TR/wsdl20/) - W3C standard for describing SOAP and XML web service interfaces.
- [Google Cloud API Design Guide](https://cloud.google.com/apis/design) - General design guidance for networked APIs.
- [Microsoft REST API Guidelines](https://github.com/microsoft/api-guidelines) - Widely-referenced guidelines for designing REST APIs.
- [API Security Checklist](https://github.com/shieldfy/API-Security-Checklist) - Key security countermeasures for designing and releasing APIs.
- [OAuth 2.0](https://datatracker.ietf.org/doc/html/rfc6749) - IETF authorization framework for delegated API access.
- [JWT](https://jwt.io/introduction) - Compact token format for securely transmitting claims between parties.
- [Apigee](https://cloud.google.com/apigee) - API management platform for designing and governing APIs.
- [Pact](https://pact.io) - Consumer-driven contract testing for integrations.
- [Enterprise Integration Patterns](https://www.enterpriseintegrationpatterns.com) - Catalog of messaging patterns by Hohpe and Woolf.
- [NIST RBAC](https://csrc.nist.gov/projects/role-based-access-control) - NIST model and INCITS 359 standard for role-based access control.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Data & Domain Modeling

Agreeing on what the data means before agreeing on where it is stored. For data analysis itself, see the [Related Lists](#related-lists) section.

- [dbdiagram.io](https://dbdiagram.io) - Entity-relationship diagrams generated from a simple DSL.
- [DBML](https://dbml.dbdiagram.io) - Database Markup Language for defining and versioning schemas as text.
- [SchemaSpy](https://schemaspy.org) - Generates diagrams and documentation from an existing database schema.
- [Data Contract Specification](https://datacontract.com) - Open specification for agreeing on data structure and semantics.
- [Open Data Contract Standard](https://bitol.io) - Linux Foundation standard for data contracts between teams.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Business Analysis

Framing the business problem and the case for change before any solution exists.

- [Business Architecture Guild](https://www.businessarchitectureguild.org) - Holds BIZBOK, the body of knowledge for business architecture.
- [APQC Process Frameworks](https://www.apqc.org/process-frameworks) - Cross-industry reference models for classifying business processes.
- [Porter's Frameworks](https://www.isc.hbs.edu/resources/Pages/frameworks.aspx) - Five forces, value chain, and clusters from Porter's institute.
- [The Green Book](https://www.gov.uk/government/publications/the-green-book-appraisal-and-evaluation-in-central-government) - How to build and appraise a business case, from the UK Treasury.
- [Theory of Constraints](https://www.tocinstitute.org/theory-of-constraints.html) - Goldratt's method for finding and managing the limiting constraint.
- [5 Whys](https://www.lean.org/lexicon-terms/5-whys/) - Root cause technique from the Lean Enterprise Institute lexicon.
- [ASQ Quality Topics](https://asq.org/quality-resources/learn-about-quality) - A to Z of quality and analysis techniques: Ishikawa, SIPOC, DMAIC.
- [PM4Py](https://processintelligence.solutions/pm4py) - Open-source process mining library for Python.
- [Process Mining](https://processmining.org) - Community reference site with techniques, public event logs, and courses.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Product Analysis

Understanding product usage, opportunities, and outcomes to inform what to build.

- [Amplitude](https://amplitude.com) - Product analytics for user behavior, funnels, and retention.
- [Mixpanel](https://mixpanel.com) - Event-based product analytics and engagement metrics.
- [PostHog](https://posthog.com) - Open-source product analytics, session replay, and experiments.
- [Productboard](https://www.productboard.com) - Centralizes feedback and insights to prioritize the roadmap.
- [Dovetail](https://dovetail.com) - Customer research repository for synthesizing user insights.
- [GrowthBook](https://www.growthbook.io) - Open-source feature flagging and A/B testing.
- [Opportunity Solution Tree](https://www.producttalk.org/opportunity-solution-tree/) - Teresa Torres's model for continuous product discovery.
- [Jobs to be Done](https://jobs-to-be-done.com/) - Framework for the progress customers are trying to make.
- [Outcome-Driven Innovation](https://strategyn.com/jobs-to-be-done/) - Strategyn's JTBD-based innovation method by Tony Ulwick.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Systems Thinking

Reasoning about feedback loops, delays, and leverage points before specifying a solution.

- [Leverage Points](https://donellameadows.org/archives/leverage-points-places-to-intervene-in-a-system/) - Donella Meadows on where to intervene in a system.
- [The Systems Thinker](https://thesystemsthinker.com) - Practitioner articles on archetypes, feedback, and leverage points.
- [Insight Maker](https://insightmaker.com) - Free browser tool for system dynamics and agent-based models.
- [NetLogo](https://www.netlogo.org) - Open-source environment for agent-based modelling and simulation.
- [Mental Modeler](https://www.mentalmodeler.com) - Fuzzy cognitive mapping for modelling a system with stakeholders.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Elicitation & Collaboration

Gathering requirements through workshops, surveys, interviews, and shared visual spaces.

- [Miro](https://miro.com) - Online whiteboard for workshops, mapping, and facilitation.
- [FigJam](https://www.figma.com/figjam/) - Collaborative whiteboard from Figma for diagrams and workshops.
- [SurveyMonkey](https://www.surveymonkey.com) - Survey platform for stakeholder feedback and analytics.
- [Typeform](https://www.typeform.com) - Conversational forms and surveys with high response rates.
- [Mentimeter](https://www.mentimeter.com) - Live polls, quizzes, and Q&A for interactive sessions.
- [Otter.ai](https://otter.ai) - AI meeting transcription for capturing interviews and notes.
- [XMind](https://xmind.net) - Cross-platform mind mapping and brainstorming.
- [Freeplane](https://freeplane.org) - Open-source desktop mind mapping and knowledge structuring.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Agile Requirements

Slicing, prioritising, and agreeing on scope when requirements arrive continuously.

- [The Scrum Guide](https://scrumguides.org/) - The definitive rules of the Scrum framework by its creators.
- [Kanban Guides](https://kanbanguides.org) - The definition of the Kanban method for flow-based delivery.
- [Splitting User Stories](https://www.humanizingwork.com/the-humanizing-work-guide-to-splitting-user-stories/) - Patterns for slicing a story small without losing value.
- [MoSCoW Prioritisation](https://www.agilebusiness.org/resource/what-is-moscow-prioritization/) - DSDM's Must, Should, Could, Won't method for scope decisions.
- [Definition of Done](https://www.scrum.org/resources/what-definition-done) - Shared agreement on what makes an increment complete.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Requirements Management Tools

- [Jira](https://www.atlassian.com/software/jira) - Widely-used issue and backlog tracker for agile teams.
- [Confluence](https://www.atlassian.com/software/confluence) - Collaborative workspace for specifications and documentation.
- [Azure DevOps](https://azure.microsoft.com/products/devops) - Boards, backlogs, and traceability for work items.
- [Notion](https://www.notion.so) - Flexible docs-and-database workspace for lightweight requirements.
- [Aha!](https://www.aha.io) - Product roadmapping and requirements management.
- [Jama Connect](https://www.jamasoftware.com) - Requirements, risk, and test management for complex products.
- [IBM DOORS Next](https://www.ibm.com/products/requirements-management-doors-next) - Enterprise requirements management for regulated industries.
- [ReqView](https://www.reqview.com) - Lightweight requirements management with full traceability.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Regulatory Requirements

Turning statutory obligations into requirements a solution has to satisfy.

- [GDPR](https://commission.europa.eu/law/law-topic/data-protection_en) - European Commission guidance on the EU data protection rules.
- [EU AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) - The EU AI regulation by risk tier, from the Commission.
- [DORA](https://eur-lex.europa.eu/eli/reg/2022/2554/oj) - EU rules on operational resilience for the financial sector.
- [CCPA](https://oag.ca.gov/privacy/ccpa) - California's consumer privacy law, with FAQs from the state AG.
- [WCAG 2.2](https://www.w3.org/TR/WCAG22/) - The accessibility standard most accessibility laws point to.
- [Web Accessibility Laws and Policies](https://www.w3.org/WAI/policies/) - Which accessibility law applies, country by country.
- [PCI DSS](https://www.pcisecuritystandards.org/standards/pci-dss/) - Security requirements for handling payment card data.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Frameworks & Bodies of Knowledge

The canonical standards and *BOK references that define the profession.

- [BABOK Guide](https://www.iiba.org/career-resources/a-business-analysis-professionals-foundation-for-success/babok/) - IIBA's Business Analysis Body of Knowledge, the core BA reference.
- [IREB](https://www.ireb.org) - Requirements Engineering Board: bodies of knowledge and syllabi.
- [BPM CBOK](https://www.abpmp.org) - ABPMP's Business Process Management Common Body of Knowledge.
- [PMBOK Guide](https://www.pmi.org) - PMI's project management body of knowledge, adjacent to analysis work.
- [SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering) - IEEE's Software Engineering Body of Knowledge.
- [DAMA-DMBOK](https://www.dama.org) - Data Management Body of Knowledge for data-focused analysis.
- [TOGAF](https://www.opengroup.org/togaf) - The Open Group's enterprise architecture framework.
- [ISO/IEC/IEEE 29148](https://ieeexplore.ieee.org/document/8559686) - International standard for requirements engineering.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Domains

Industry-specific standards, reference models, and bodies of knowledge for domain analysts.

### Telecommunications

- [TM Forum](https://www.tmforum.org) - Open Digital Framework: eTOM, SID, TAM, and Open APIs.
- [3GPP](https://www.3gpp.org) - Standards for mobile networks (4G, 5G, and beyond).
- [MEF](https://www.mef.net) - Standards and APIs for carrier-grade network services (LSO, MEF 3.0).

### Insurance

- [ACORD](https://www.acord.org) - Global data and messaging standards for the insurance industry.
- [IFRS 17](https://www.ifrs.org/issued-standards/list-of-standards/ifrs-17-insurance-contracts/) - Accounting standard for insurance contracts.
- [NAIC](https://www.naic.org) - US insurance regulatory standards and data reporting.

### Banking

- [BIAN](https://bian.org) - Banking Industry Architecture Network: a reference service landscape.
- [ISO 20022](https://www.iso20022.org/) - Universal standard for financial messaging.
- [Open Banking](https://www.openbanking.org.uk) - Standards and APIs for account access and payments.
- [SWIFT](https://www.swift.com/standards) - Messaging standards for cross-border financial transactions.

### Travel

- [IATA NDC](https://www.iata.org/en/programs/airline-distribution/retailing/ndc/) - XML standard for modern airline retailing and distribution.
- [OpenTravel Alliance](https://opentravel.org) - Open specifications for exchanging travel data.
- [HTNG](https://www.ahla.com/htng) - Hospitality technology standards (now part of AHLA).

### Other Industries

- [HL7 FHIR](https://www.hl7.org/fhir/) - Interoperability standard for healthcare data.
- [GS1](https://www.gs1.org) - Supply-chain standards for product identification and data exchange.
- [FpML](https://www.fpml.org) - XML standard for complex financial derivatives.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Templates

- [arc42](https://arc42.org) - Pragmatic template for documenting software architectures.
- [Architecture Decision Records](https://adr.github.io) - Lightweight format for capturing significant decisions.
- [MADR](https://github.com/adr/madr) - Markdown Any Decision Records template and toolkit.
- [Volere Requirements Template](https://www.volere.org/templates/volere-requirements-specification-template/) - Comprehensive requirements specification template.
- [User Story Mapping](https://www.jpattonassociates.com/story-mapping/) - Technique and template for framing backlogs around user journeys.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Certifications

### Business Analysis

- [IIBA Certifications](https://www.iiba.org/business-analysis-certifications/) - ECBA, CCBA, CBAP, plus specialized credentials (agile, data, product).
- [PMI-PBA](https://www.pmi.org/certifications/business-analysis-pba) - PMI Professional in Business Analysis.
- [IREB CPRE](https://www.ireb.org/en/cpre/) - Certified Professional for Requirements Engineering.
- [BCS Business Analysis](https://www.bcs.org/qualifications-and-certifications/certifications-for-professionals/business-analysis/) - BCS (ISEB) diploma and certificates in business analysis.

### Cloud

- [AWS Certified Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) - Foundational AWS cloud literacy for analysts.
- [Microsoft Azure Fundamentals](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/) - Entry-level Azure cloud fundamentals (AZ-900).
- [Google Cloud Digital Leader](https://cloud.google.com/learn/certification/cloud-digital-leader) - Foundational Google Cloud knowledge for non-engineers.

### Product & Service Management

- [ITIL 4 Foundation](https://www.axelos.com/certifications/itil-service-management/itil-4-foundation) - Foundation in IT service management, common for IT-facing analysts.
- [Pragmatic Institute](https://www.pragmaticinstitute.com/product/product-management-certification/) - Product management certification built on the Pragmatic Framework.
- [Product School](https://productschool.com/certifications/product-manager-certification) - Product management certifications from beginner to executive.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Learning Resources

- [Modern Analyst](https://www.modernanalyst.com) - Articles, templates, and a large BA community library.
- [Bridging the Gap](https://www.bridging-the-gap.com) - Practical guidance for new and transitioning business analysts.
- [BA Times](https://www.batimes.com) - News, articles, and webinars on business analysis.
- [IIBA](https://www.iiba.org) - The International Institute of Business Analysis and its resources.
- [Analyst Roadmap](https://github.com/analystRoadmap/analyst_book) - Open roadmap of skills for business and systems analysts.
- [The API Book](https://twirl.github.io/The-API-Book/) - Free online book on designing APIs, by Sergey Konstantinov.
- [Learn API Documentation](https://idratherbewriting.com/learnapidoc/) - Comprehensive course on documenting REST APIs.
- [Google Technical Writing Courses](https://developers.google.com/tech-writing/overview) - Free courses on writing clear technical documentation.
- [Coursera](https://www.coursera.org) - MOOC platform with analysis, product, and data courses.
- [TutorialsPoint](https://www.tutorialspoint.com) - Free tutorials on SQL, UML, and technical topics.
- [Atlassian University](https://university.atlassian.com) - Official training for Jira, Confluence, and agile ways of working.
- [System Design Primer](https://github.com/donnemartin/system-design-primer) - Open guide to system design concepts and trade-offs.
- [Prompt Engineering Guide](https://www.promptingguide.ai) - Techniques like few-shot and chain-of-thought for reliable LLM use.
- [SQLBolt](https://sqlbolt.com) - Interactive lessons for learning SQL from scratch.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Books

- [Software Requirements](https://www.microsoftpressstore.com/store/software-requirements-9780735679665) - By Karl Wiegers and Joy Beatty; a foundational requirements text.
- [Mastering the Requirements Process](https://www.volere.org/books/) - By Suzanne and James Robertson; the Volere approach.
- [User Stories Applied](https://www.mountaingoatsoftware.com/books/user-stories-applied) - By Mike Cohn; writing and managing user stories.
- [User Story Mapping](https://www.oreilly.com/library/view/user-story-mapping/9781491904893/) - By Jeff Patton; framing backlogs around user journeys.
- [Writing Effective Use Cases](https://www.pearson.com/en-us/subject-catalog/p/writing-effective-use-cases/P200000009127) - By Alistair Cockburn; the classic on use cases.
- [Domain-Driven Design](https://www.domainlanguage.com/ddd/) - By Eric Evans; modeling complex business domains.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Community

- [r/businessanalysis](https://www.reddit.com/r/businessanalysis/) - Subreddit for business analysis discussion.
- [Modern Analyst Forums](https://www.modernanalyst.com/Community.aspx) - Long-running community Q&A for analysts.
- [IIBA Chapters](https://www.iiba.org/business-analysis-membership/chapters/) - Local chapters for networking and events worldwide.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Related Lists

Adjacent domains and specialties this list points to rather than duplicates — including data analysis, the quantitative subdomain it deliberately hands off.

- [Awesome Data Analysis](https://github.com/PavelGrigoryevDS/awesome-data-analysis) - Data analysis resources: Python, SQL, statistics, and visualization.
- [Awesome Data Science](https://github.com/academic/awesome-datascience) - Broad list spanning analysis, modeling, and learning paths.
- [Awesome Integration](https://github.com/stn1slv/awesome-integration) - Curated list of system integration software and patterns.
- [Awesome GraphQL](https://github.com/chentsulin/awesome-graphql) - Curated list of GraphQL resources and tools.
- [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps) - Patterns and examples for building agentic workflows.
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - Community catalog of MCP servers across categories.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. Spotted a gap? [Suggest an addition](https://github.com/sbarkalov/awesome-analysis/issues/new) or [start a discussion](https://github.com/sbarkalov/awesome-analysis/discussions).

## Footnotes

- [Web version](https://sbarkalov.github.io/awesome-analysis/) - This readme rendered as a browsable site.

