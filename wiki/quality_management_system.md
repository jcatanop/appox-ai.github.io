# Quality

---

The quality of products or services has been a highly debated topic in recent decades and has captured the attention of multiple actors in order to achieve a consensus on the matter.

Consider the following cases:

- For a common buyer, *price* can be an indicator of quality.
- For a public control entity, *product safety* is a quality factor.
- For a manufacturing technician, *low variability* of the units produced is an indicator of quality.
- For a service company, *low complaints* by customers is a quality factor.
- ...

This list of different quality criteria can become as long as different evaluators are involved and it seems endless.

Some authors have debated this topic depth and we could say that although for certain sorts of products/services the definition is quite mature (ie: pharmaceuticals, foods, medicals), for another stage the discussion continues and this is the current status for software quality criterias.

# Historical and Reference Frame

---

In the middle of the 20th century, the concept of *quality* became important in the pharmaceutical and food sectors, due to its direct impact on people's health. All this led to the creation of entities specialized in debating and establishing criteria to ensure the quality of these products. For example the [World Health Organization][who] or the [International Council for Harmonisation][ich].

By the 1990s, the use of computerized systems in food and drug manufacturing goods was gaining leadership. Because of this, computerized systems began to be another point on the agenda for discussions about quality, since the records generated and data stored in these systems were used to make quality decisions about the products to be marketed.

In 1997 the United States government issued federal regulation [21 CFR part 11][cfr] that declares the requirements that computerized systems that store records, manage digital signatures and are a source for making high-impact decisions must meet.

In 2002 the FDA created the [Guide for software validation][guide] to establish standards that must meet medical devices or software intended to support the manufacturing process of medical supplies. 

These two documents have been a reference framework in the evaluation and validation of software, from which the following terms have been adopted:

- User requirements
- Software verification
- Software validation

The United States issued these documents and established a regulatory framework for software quality requirements, but this is not totally applicable to worldwide.

The International Organization for Standardization ([ISO][iso]) is an independent non-governmental entity, which began operations in the mid-1940s and has a worldwide scope. They have worked to define quality standards that can be applied to all types of organizations.

In 2015 was issued the [ISO 9001 Quality management systems][iso9001] which declares the minimum requirements to met by a company in order to implement and sustain an auditable quality system. This standard is not limited to specific type or size company.

Besides the [ISO 9001][iso9001], other standards of interest around *Systems and software Quality Requirements and Evaluation (SQuaRE)* have been issued by [ISO][iso] and below area listed some of them:

- [ISO/IEC 25059:2023 SQuaRE — Quality model for AI systems](https://www.iso.org/standard/80655.html)
- [ISO/IEC 25051:2014 SQuaRE — Requirements for quality of Ready to Use Software Product (RUSP) and instructions for testing](https://www.iso.org/standard/61579.html)
- [ISO/IEC TS 25011:2017 SQuaRE — Service quality models](https://www.iso.org/standard/35735.html)

# Quality Management System (QMS)

---

Current [ISO 9001:2015][iso9001] is focused on establishing a philosophy where every person belonging to a company realizes their impact over quality products and services.

For technicians that are directly involved in the manufacturing process, it is so easy to know how its management affects the quality product, but for other collaborators, it is complex to figure it out. Even worse when the company sells intangible products such as software or services.

The Quality Management System (QMS) is a systematic process where all procedures needed for delivering a value product to customers are clearly defined and assessed. 

Based on the PDCA Cycle, [ISO 9001:2015][iso9001] brings an approach to implement the QMS in a strategic way where continuous improvements are immersed across all processes.

![Deming Wheel][cycle]

As we mentioned before, QMS is immersed across the organization and every collaborator affects this system. 

That’s why the QMS needs some elements to achieve its goals and ensure sustainability over time.

- Documentation
- Training
- Chance Control 
- Deviations and Complaints
- Risk Assessment
- Standardization and Validation
- Quality Control

Quality Assurance (QA) is the area responsible for leading these components and making all efforts needed to touch every person in the company in order to create a culture around quality.

# References

---

1. H.T.  Garston., Software Quality Assurance - A guide for developers and auditors., CRC Press, 1997
2. K. Naik and P. Tripathy., Software Testing and Quality Assurance - Therory and practice., John Wiley & Sons., 2008
3. J. Tian., Software Quality Engineering - Testing, quality assurance and quantifiable improvement.,  John Wiley & Sons., 2005

 
[who]: https://www.who.int/
[ich]: https://www.ich.org/
[iso]: https://www.iso.org
[iso9001]: https://www.iso.org/standard/62085.html
[cfr]: https://www.ecfr.gov/current/title-21/chapter-I/subchapter-A/part-11
[guide]: https://www.fda.gov/media/73141/download
[bnq]: https://www.bnq.qc.ca/en/standardization/business-management/iso-9001.html

[cycle]: https://raw.githubusercontent.com/appox-ai/appox-ai.github.io/master/assets/img/plan_do_check_act.png "DPCA Cycle - Deming Wheel"
