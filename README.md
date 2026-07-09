# Awesome Analysis [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome tools, frameworks, standards, and resources for business, systems, and product analysis.

📖 **For comfortable reading:** [Web version](https://sbarkalov.github.io/awesome-analysis/)

✨ **Spotted a gap?** [Suggest an addition](https://github.com/sbarkalov/awesome-analysis/issues/new) or [start a discussion](https://github.com/sbarkalov/awesome-analysis/discussions)

Business, systems, and product analysis turn stakeholder needs into clear, verifiable
requirements, designs, and product decisions. This list collects the best of the discipline —
from AI-assisted and code-driven workflows to classic bodies of knowledge, modeling notations,
product analytics, and templates.

## Contents

- [AI & Agentic Analysis](#ai--agentic-analysis)
- [Requirements as Code](#requirements-as-code)
- [Modeling & Diagrams as Code](#modeling--diagrams-as-code)
- [Integration Analysis](#integration-analysis)
- [Product Analysis](#product-analysis)
- [Elicitation & Collaboration](#elicitation--collaboration)
- [Agile & Delivery](#agile--delivery)
- [Requirements Management Tools](#requirements-management-tools)
- [Frameworks & Bodies of Knowledge](#frameworks--bodies-of-knowledge)
- [Domains](#domains)
- [Templates](#templates)
- [Certifications](#certifications)
- [Learning Resources](#learning-resources)
- [Books](#books)
- [Community](#community)

## AI & Agentic Analysis

Using LLMs and autonomous agents to elicit, draft, refine, and trace requirements.

- [Model Context Protocol](https://modelcontextprotocol.io) - Open standard for connecting AI agents to tools and data sources.
- [Claude](https://claude.ai) - Assistant strong at drafting requirements, user stories, and acceptance criteria.
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer that also drafts specs, diagrams, and ADRs in-repo.
- [Cursor](https://cursor.com) - AI-first editor useful for editing specs and diagrams-as-code with context.
- [ChatPRD](https://www.chatprd.ai) - AI copilot for product requirement documents and user stories.
- [LangChain](https://www.langchain.com) - Framework for building custom analysis and elicitation agents.
- [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps) - Patterns and examples for building agentic workflows.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Requirements as Code

Treating requirements and specifications as plain-text, version-controlled artifacts.

- [Gherkin](https://cucumber.io/docs/gherkin/) - Business-readable language for executable, behavior-driven specifications.
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

Notations and tools for process, data, and architecture models — text-first where possible.

- [Mermaid](https://mermaid.js.org) - Diagrams from text, rendered natively in Markdown and many tools.
- [PlantUML](https://plantuml.com) - Text-based UML and more (sequence, class, activity, C4).
- [C4 model](https://c4model.com) - Lean approach to visualizing software architecture at four levels.
- [Structurizr](https://structurizr.com) - Tooling for the C4 model with diagrams defined as code.
- [BPMN](https://www.bpmn.org) - OMG standard notation for modeling business processes.
- [bpmn.io](https://bpmn.io) - Open-source web toolkit for viewing and editing BPMN, DMN, and forms.
- [Camunda Modeler](https://camunda.com/platform/modeler/) - Desktop modeler for BPMN and DMN.
- [draw.io](https://www.drawio.com) - Free, general-purpose diagramming tool.
- [Excalidraw](https://excalidraw.com) - Virtual whiteboard for quick, hand-drawn-style diagrams.
- [dbdiagram.io](https://dbdiagram.io) - Entity-relationship diagrams generated from a simple DSL.
- [Lucidchart](https://www.lucidchart.com) - Web-based diagramming for flowcharts, ERDs, and UML.
- [Sparx Enterprise Architect](https://sparxsystems.com/products/ea/) - Modeling platform for UML, BPMN, SysML, and ArchiMate.
- [UML](https://www.uml.org) - OMG's Unified Modeling Language for software systems.
- [Archi](https://www.archimatetool.com) - Open-source modeling tool for the ArchiMate enterprise architecture language.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Integration Analysis

Designing and analyzing interfaces, contracts, and data exchange between systems.

- [OpenAPI Specification](https://www.openapis.org) - Standard, language-agnostic description for REST APIs.
- [Swagger](https://swagger.io) - Toolset for designing, documenting, and trying out OpenAPI definitions.
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
- [Jobs to be Done](https://jtbd.info) - Framework for the progress customers are trying to make.

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

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Agile & Delivery

Frameworks and comparisons for iterative delivery of analysis and product work.

- [The Scrum Guide](https://scrumguides.org/) - The definitive rules of the Scrum framework by its creators.
- [Kanban vs Scrum](https://www.atlassian.com/agile/kanban/kanban-vs-scrum) - Atlassian's practical comparison of the two agile approaches.

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

## Frameworks & Bodies of Knowledge

The canonical standards and *BOK references that define the profession.

- [BABOK Guide](https://www.iiba.org/career-resources/a-business-analysis-professionals-foundation-for-success/babok/) - IIBA's Business Analysis Body of Knowledge, the core reference for BAs.
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

- [IIBA Certifications](https://www.iiba.org/business-analysis-certifications/) - ECBA, CCBA, CBAP, plus specialized credentials (agile, data, product).
- [PMI-PBA](https://www.pmi.org/certifications/business-analysis-pba) - PMI Professional in Business Analysis.
- [IREB CPRE](https://www.ireb.org/en/cpre/) - Certified Professional for Requirements Engineering.
- [BCS Business Analysis](https://www.bcs.org/qualifications-and-certifications/certifications-for-professionals/business-analysis-certifications/) - BCS (ISEB) diploma and certificates in business analysis.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Learning Resources

- [Modern Analyst](https://www.modernanalyst.com) - Articles, templates, and a large BA community library.
- [Bridging the Gap](https://www.bridging-the-gap.com) - Practical guidance for new and transitioning business analysts.
- [BA Times](https://www.batimes.com) - News, articles, and webinars on business analysis.
- [IIBA](https://www.iiba.org) - The International Institute of Business Analysis and its resources.
- [Analyst Roadmap](https://github.com/analystRoadmap/analyst_book) - Open roadmap of skills for business and systems analysts.
- [The API Book](https://twirl.github.io/The-API-Book/) - Free online book on designing APIs, by Sergey Konstantinov.
- [Learn API Documentation](https://idratherbewriting.com/learnapidoc/) - Comprehensive course on documenting REST APIs.

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
- [IIBA Chapters](https://www.iiba.org/iiba-chapters/) - Local chapters for networking and events worldwide.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Related Lists

Adjacent domains and specialties this list points to rather than duplicates — including data
analysis, the quantitative subdomain it deliberately hands off.

- [Awesome Data Analysis](https://github.com/PavelGrigoryevDS/awesome-data-analysis) - Data analysis resources: Python, SQL, statistics, and visualization.
- [Awesome Data Science](https://github.com/academic/awesome-datascience) - Broad data science list spanning analysis, modeling, and learning paths.
- [Awesome Integration](https://github.com/stn1slv/awesome-integration) - Curated list of system integration software and patterns.
- [Awesome GraphQL](https://github.com/chentsulin/awesome-graphql) - Curated list of GraphQL resources and tools.

<p align="right">(<a href="#contents">↑ back to top ↑</a>)</p>

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

---

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/) To the extent
possible under law, the contributors have waived all copyright and related or neighboring rights to
this work. See [LICENSE](LICENSE) for details.
