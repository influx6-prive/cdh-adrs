# CDH Architecture Decisions (AD)
This AD contains all documentation related to the current existing work ongoing in the development of the Client Data Hub. Which is being extracted from the SLYAWS monolith into a series of different services which power existing infrastructure but provide us a means to scale more efficiently.

*The documentation will be a living documentation for all things related to CDH and will be terse where necessary and broad when needed.*

![CDH Workshop Goals](./assets/images/aab_workshop/aab_2.jpg)

# Architecture Decision Records (ADRs)

From existing analysis of existing systems and architectural meetings, the 4 major parts required for CDH led to 4 ADRs listed below, where each describes with necessary details the problem, scope and decisions necessary for these services:


Services    | ADRs
-------  | ---------
Uploader | [Uploader ADR](./adrs/uploaders.md)
ETL Service      | [ETL ADR](./adrs/etl.md)
Pentaho  | [Pentaho ADR](./adrs/pentaho.md)
CDH Service | [CDH ADR](./adrs/cdh.md)


# Links

- https://adr.github.io/
- https://github.com/joelparkerhenderson/architecture_decision_record