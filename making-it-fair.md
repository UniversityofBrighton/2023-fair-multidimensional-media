---
title: 'Making it FAIR'
teaching: 10
exercises: 2
---



## Making it FAIR
Emphasis should be placed in following the FAIR principles
when creating multidimensional data or bringing together
existing data within a project/initiatives. 


FAIR refers to the following 
actions which should be promoted.


### Findability

![&copy; ST.art from AdbobeStock](fig/AdobeStock_605423469.jpeg){alt="findable"}

>"The first step in (re)using data is to find them. Metadata and data should be easy to find for both humans and computers. Machine-readable metadata are essential for automatic discovery of datasets and services...”
[https://www.go-fair.org/fair-principles/](https://www.go-fair.org/fair-principles/)

- Data should be linked to rich and structured metadata.

- Where possible this should be made accessible through a searchable 
resource such as an aggregation platform. 

- Data should be accessible 
through a persistent identifiers (which do not change over time). For example, [DOIs](https://www.doi.org/the-identifier/what-is-a-doi/) can be assigned to data
through platforms such as [Zenodo](https://zenodo.org/) 
or [Github](https://github.com/).

### Accessibility

![&copy; alexdndz from AdobeStock](fig/AdobeStock_408113732.jpeg){alt="access data"}

>The user "need to know how they can be accessed, possibly including authentication and authorisation". [https://www.go-fair.org/fair-principles/](https://www.go-fair.org/fair-principles/)

- Metadata should be accessible via using a *protocol* for web, such as HTTP/HTTPS
which allows to access a webpage over the browser or query a database through
a service known as *Application Programming Interface (API)*. 

- Where necessary, the protocol show allow for authentication and 
authorization to enforce data management rights.

- Consider who will be excluded from access the data, for instance if this is
only available via an institutional platform or in a particular language.

### Interoperability 

![&copy; Molnia from AdobeStock](fig/AdobeStock_301985997.jpeg){alt="interoperable"}

> "The data usually need to be integrated with other data. In addition, the data need to interoperate with applications or workflows for analysis, storage, and processing." [https://www.go-fair.org/fair-principles/](https://www.go-fair.org/fair-principles/)

- Consider how other users will bring together content
from various datasets, for instance to create a new project.
- For visual media, including images, video and 3D, [IIIF](https://github.com/IIIF/awesome-iiif) (generally pronounced "triple-eye-eff") supports its interoperability of across websites and institutions.
- This framework allows to provide access and shared
link to a file, as well as its (meta)data .
- When implemented across many institutions overcomes 
data silos.


For example, through IIIF it is possible to [bring together objects
which physically might be in different locations]([https://projectmirador.org/embed/?iiif-content=https://iiif.io/api/cookbook/recipe/0036-composition-from-multiple-images/manifest.json]).
It does not require a user to download the files but simply to access
the files and metadata over the web.


### Reuse 

![&copy; Olesia Sarycheva from AdbobeStock](fig/AdobeStock_104923735.jpeg){alt="Creative common"}

> "The ultimate goal of FAIR is to optimise the reuse of data."
[https://www.go-fair.org/fair-principles/](https://www.go-fair.org/fair-principles/)

- Multidimensional data should be 
released with a clear and accessible data usage license.

- Provenance data will help for data to not become lost.

## CARE data principles

In addition, a series of principles known as CARE 
have been proposed by the [Global Indigenous Data Alliance](https://www.gida-global.org/care).

These principles include:
Collective Benefit, Authority to Control, Responsibility, and Ethics. 


Their focus on enhancing these
principles by leveling power relationships where data is created within
certain social and historical context. 


::::::::::::: challenge

## Challenge: CARE principles for your data practice

Could you reflect on what implications following the [CARE principles](https://www.gida-global.org/care)
has for your personal practice when creating, collecting and using data.

::::::::::::: 

For more information:

- Carroll, S.R., Garba, I., Figueroa-Rodríguez, O.L., Holbrook, J., Lovett, R., Materechera, S., Parsons, M., Raseroka, K., Rodriguez-Lonebear, D., Rowe, R., Sara, R., Walker, J.D., Anderson, J. and Hudson, M., 2020. The CARE Principles for Indigenous Data Governance. Data Science Journal, 19(1), p.43.DOI: [https://doi.org/10.5334/dsj-2020-043](https://doi.org/10.5334/dsj-2020-043)
- Wilkinson, M., Dumontier, M., Aalbersberg, I. et al.
The FAIR Guiding Principles for scientific data management and stewardship. Sci Data 3, 160018 (2016). [https://doi.org/10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)


::::::::::::: keypoints

|  Principle          | Key Points                        |
|---------------------|-----------------------------------|
| **Findability**         | - Available metadata <br> - Allow for searchability <br> - Persistent IDs |
| **Accesibility**        | - Use web protocols for access <br> - Allow for authorisation <br> - Digital inclusion/exclusion |
| **Interoperability**    | - Data integration <br> - Overcomes data silos <br> - IIIF for visual media |
| **Reuse**              |  - License content <br> - Avoid data becoming lost |

::::::::::::: 
