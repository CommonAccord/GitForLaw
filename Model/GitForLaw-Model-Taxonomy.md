GitForLaw-OTF-Model:


This is an effort to outline a comprehensive naming system (taxonomy) for transacting - modelling an ecosystem of contracts.
It is not yet formatted as wiki markdown, which would allow easy navigation among elements.

It is useful to first put this in context.  The ontology is treated as an approximation; it is intended to be extended, iterated, refactored.  We anticipate that this will happen in a number of ways:

1. By New Data - aka "experience" with the solutions.  Parties are free to tweak Paradigms by overriding.  This informally extends the ontology.  Data methods can identity these variations and propose them back to participants and maintainers.  The solution grows broader and deeper.  Patterns may show the way to better, deeper ontologies, sometimes leading maintainers to refactor the ontologies.

1. By Reference to other Ontologies.  There are many existing ontologies, some of which have substantial traction.  For instance the ISO-LEI for legal entities (a subclass of "Persons").  This is a multilayered semi-structured effort, for instance schema.org covers all categories.

1. By historical Data - Machine learning analytics on existing contracts and activity provides ontologies that emerge from the data. These are important for guiding a future-oriented ontology as well as for understanding existing arrangements. 

1. By Pull-Request - Others are likely to have more knowledge about ontologies.  Please make suggestions.

## See also 
### [https://github.com/CommonAccord/GitForLaw/blob/master/Model/ContractTypes-Taxonomy.md]

We first make a short list of the fundamental elements of a transacting environment - the ones that need to be modelled in most transaction flows.  Then we start a broad list of taxonomies that we are aware of, many of them standards from various organizations, but also less formal taxonomies. A comprehensive system will need to deal with all of them.  A converging system will likely drive standards towards dominance of those that are found to be most useful or most influential.



1.  Fundamental Elements

    1. Person
        1. Human
        1. Entity
        1. Persona

    1. Place
        1. Geographic Latitude, Longitude, Altitude
        1. Political - Country, Region, Locality, Postal Address, Jurisdiction, etc.

    1. Asset - things that are the subject of human transacting  (look for fit with accounting)
        1. Physical - SKUs, real estate, vehicles, animals, books, tissue samples ...
        1. Intangible -
            1. IP - Copyright, Patent, Trademark, 
            1. Benefits - retirement, health, ...
            1. Certifications - diplomas, professional credentials, ...
    1. Time
        1. Universal - GMT and offsets for geography and season
        1. Relative - before, during, after, extended, retroactive, etc.
    
    1. Paradigm - a type of connection among the elements above.  These can be expressed in words (Prose), as algorithms (Code), and perhaps as structure (Objects) (not sure how to classify the significance of classification of objects).
        1. Legal - treaty, law, regulation, court decision, standard, rule, permit, contract, filing
        1. Transacting - description, offer, order, notice (shipping, arrival, delay, change), request, consent
        1. API activity - create, read, update, delete, supporting messaging, ...



1.  Notions of filling in the basic taxonomy:

    1. Person
        1. Human - National identity systems
            1.  eID in the EU - [https://ec.europa.eu/cefdigital/wiki/display/EIDCOMMUNITY/Cooperation+Network+Resources]
        1. Entity - 
            1. ISO Legal Identifiers  (does this include government agencies, courts, etc.)
            1. Identifiers resulting from legal citation standards
    1. Place
        1. US/FR/JP/  SO 3166-1 alpha-2
    1. Asset
    1. Time
    1. Paradigm
        1. Business Taxonomies
            1. Accounting, balance sheets, etc.
                1. XBRL [http://XBRL.org]
                1. UN Sustainability via Standards: for instance TIR system for truck transport [http://www.unece.org/tir/welcome.html]
                1. US FASB [https://asc.fasb.org/home] with modularity, navigation, backlinks (for premium users)
            1. Customs clearances - World Customs Organization [http://www.wcoomd.org/DataModel]
            1. World Intellectual Property Organization [https://www.wipo.int/portal/en/index.html]
        1. Akoma Ntoso
        1. Legal citation systems
        1. Databases
        1. Precedents

1. Tools
    1. APIs
        1. User-Managed-Access
    1. Payments
        1. Credit Card
        1. Tech -  Interledger (W3C), Stripe, Venmo, Zelle, blockchains
        1. Banks and Interbank.  [https://www.ecb.europa.eu]
    1. Management - Workflow
        1. Contract Management software  [http://software.worldcc.com]
        1. 

1. Efforts
    1. EU - 
        1. [https://joinup.ec.europa.eu/collection/better-legislation-smoother-implementation]
        1. [https://cnnumerique.fr/files/uploads/2020/2020.07.06.ra_cnnum_concurrence_web.pdf]
