# Rebuilding the BFF Layer for Product Detail Page at Yanolja

## Overview
One of the projects I’m most proud of is rebuilding the Product Detail Page (PDP) backend at **Yanolja**, Korea’s leading accommodation booking platform.  
I replaced a legacy mashup service with a new **Backend-for-Frontend (BFF)** layer, which directly contributed to a **+5% product-to-order conversion rate** by the end of 2022.


## Background
- The legacy mashup service could not handle **frequent product updates** or new features effectively.
- Business demanded faster iteration, **strict latency targets**, and improved **fault tolerance**.
- Cross-functional collaboration was required across **Backend, Frontend, and Product** teams.


## My Role
- **Main Backend Engineer** in a cross-functional team
- Participated in **weekly Scrum** meetings with FE, QA, and PO
- Led the **design and implementation** of the new BFF layer (Jan – Jul 2022)
- Drove **post-launch improvements** (Aug – Sep 2022)
- Collaborated in **UX research & A/B testing** (Oct – Dec 2022)


## Approach & Solution
1. **Architecture Redesign**
    - Introduced a **layered BFF architecture** with clear separation of presentation, business logic, and external integrations.
    - Supported flexible feature delivery and faster product experiments.

2. **Technology Choices**
    - **Feign clients** to simplify API calls
    - **Circuit Breaker** and **Retry/Fallback strategies** for graceful fault isolation
    - Built monitoring with **Grafana, Sentry, Pinpoint**

3. **Performance & Reliability**
    - Defined latency targets based on benchmarks and cognitive research
    - Reduced PDP API latency with connection pooling and performance tuning
    - Conducted stress testing across environments (Dev/QA/Stage/Prod)

4. **Product & UX Collaboration**
    - Worked with product managers and designers to **redefine FE vs BE responsibilities**
    - Introduced **partially server-driven UI** to enable faster A/B tests
    - Collaborated in focus group interviews to identify what information users needed most
    - Helped analyze order flows by product type and removed unnecessary steps


## Improvements & A/B Testing
- **Aug–Sep 2022:** Post-launch improvements focused on latency and fault tolerance.
- **Oct–Dec 2022:** Ran **A/B tests** with key metric defined as *Order Page Conversion* (not dwell time).
- Focus groups guided us to prioritize clarity of product details and reduce ordering steps.
- Directly contributed as a backend engineer **beyond coding**, influencing how metrics and experiments were run.


## Results & Impact
- **Conversion Rate**: +5% increase in PDP → Order Page conversion
- **Latency**: Reduced P90 latency from **300ms → 50ms**
- **Fault Tolerance**: 80%+ fault isolation during service disruptions
- **Recognition**: CTO (ex-Google) praised the project as *“one of the most outstanding backend initiatives of the year”*


## Key Learnings
- The importance of **BFF in microservices**: balancing responsibilities between FE and BE improves scalability and developer velocity.
- **Cross-functional collaboration** drives stronger results when backend engineers contribute to **metric definition, UX research, and A/B testing**.
- Investing in **fault tolerance and observability early** paid off in long-term stability and confidence in product experiments.  