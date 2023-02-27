# Architecture Constraints

<!-- Any requirement that constraints software architects in their freedom of
design and implementation decisions or decisions about the development
process. These constraints sometimes go beyond individual systems and
are valid for whole organizations and companies.

Architects should know exactly where they are free in their design
decisions and where they must adhere to constraints. Constraints must
always be dealt with; they may be negotiable, though.

Simple tables of constraints with explanations. If needed you can
subdivide them into technical constraints, organizational and political
constraints and conventions (e.g. programming or versioning guidelines,
documentation or naming conventions) -->

Various constraints limit the design and implementation decisions. These constraints are divided into categories below.

## Political Constraints 

| Constraint | Description |
|------|------------|
| Data Space Interoperability | Interactions with Gaia-X compliant Data Spaces should be explored and, if possible, implemeted. |
| | |

## Technical Constraints 

| Constraint | Description |
|------|------------|
| Kafka communication | The streaming of real-time data over the Internet must implemented with Apache Kafka. |
| P1 port | Real-time data from the smart meter must be collected over the P1 Port.  |
| | |

