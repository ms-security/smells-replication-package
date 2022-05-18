# Raw Replication Package

We here provide a raw version of the replication package. We below report on the **study protocol** and we provide the **raw data** of our analysis in a CSV format.

## Study Protocol

### Research questions			
* **RQ1**:	What are the smells indicating possible security violations in microservice-based applications?		
* **RQ2**:	How to refactor microservice-based applications to mitigate the effects of security smells therein?		
			
### Literature Search			
Please find below the search strings used on each **white literature** indexing database, together with the number of matching results.

* **ACM Digital Library**:	
`microservice* AND secur* AND (smell OR antipattern OR "bad practice" OR pitfall OR refactor OR reeingeer OR restructure)`
(results: 101)
* **DBLP**:
`microservice security (smell | antipattern | bad practice | pitfall | refactor | reeingeer | restructure)`
(results: 1)	
* **IEEE Xplore**:
`microservic* AND secur* AND (smell OR antipattern OR "bad practice" OR pitfall OR refactor OR reeingeer OR restructure)`
(results: 4)
* **ISI Web of Science**
`ALL=(microservice*) AND ALL=(secur*) AND (ALL=smell OR ALL=antipattern OR ALL="bad practice" OR ALL=pitfall OR ALL=refactor OR ALL=reengineer OR ALL=restructure)`
(results: 2)
* **Science Direct**
`microservice AND security AND (smell OR antipattern OR "bad practice" OR pitfall OR refactor OR reeingeer OR restructure)`
(results: 68)	
* **Scopus**:
`microservice AND security AND (smell OR antipattern OR "bad practice" OR pitfall OR refactor OR reeingeer OR restructure)`
(results: 129)	
* **SpringerLink**:
`microservic* AND secur* AND (smell OR antipattern OR "bad OR practice" OR pitfall OR refactor OR reengineer OR restructure)`
(results: 629)
* **Google Scholar**:
`(microservice) AND (security) AND (smell OR antipattern OR "bad practice" OR pitfall OR refactor OR reengineer OR restructure)`
(results: 169 -- restricted to scientific articles)
			
Please find below the search strings used on **Google**, **Bing**, and **DuckDuckGo** to search for **grey literature**. For each string, and each search engine, we considered the firts 250 hits, according to Garousi et al.'s _effort bounded_ stopping criteria.
* `microservice security smell`
* `microservice security antipattern`
* `microservice security bad practice`
* `microservice security pitfall`
* `microservice security refactor`
* `microservice security reenginer`
* `microservice security restructure`

As a result, we had 6353 matching white/grey primary studies to consider.

### Literature Selection
Among the matching primary studies, we selected those satisfying the following **inclusion criteria**:
* A study is selected if published between 01/01/2011 and 31/12/2020			
* A study is to be selected if it is written in English.			
* A study is to be selected if it qualifies as white literature, or as a blog post, whitepaper, industrial magazine publication, or video authored by a practitioner.		
* A study is to be selected if it focuses on microservices.			
* A study is to be selected if it focuses on security.			
* A study is selected if it presents at least one security smell possibly resulting in a violation of a security property defined by the ISO/IEC 25010 standard			
* A study is selected if it presents at least one refactoring for mitigating the effects of a security smell, even if the latter is not explicitly mentioned.			

### Coding Schema			
* type (white/grey)			
* sub-type [white] conference vs journal paper vs book chapter | [grey] blog post vs video vs whitepaper vs documentation			
* authors			
* title			
* publication venue: [white] bibliographic information | [grey] name of the blog/news (e.g., TechBeacon, Medium), video hosting service, …			
* year			
* URL/link			
* Search engine			

# Raw Data
