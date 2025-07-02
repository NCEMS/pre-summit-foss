# Introduction to Open Science

!!! Success "Learning Objectives"

    After this lesson, you should be able to:
        
    - Explain what Open Science is
    - Explain the components of Open Science
    - Describe the behaviors of Open Science
    - Explain why Open Science matters in education, research, and society
    - Understand the advantages and the challenges to Open Science

<br>

## What is Open Science?

<br>

Open Science is a broad movement dedicated to making scientific processes and knowledge more transparent, inclusive, and accessible to everyone. The core idea is to open up the entire research lifecycle, from the initial idea to the final publication and beyond, fostering collaboration and accelerating discovery.

While the term has been around for a while, its meaning has been formalized and globally recognized through the **[UNESCO Recommendation on Open Science](https://unesdoc.unesco.org/ark:/48223/pf0000379949)**, adopted in 2021. This key document defines Open Science as:

> "...an inclusive construct that combines various movements and practices aiming to make multilingual scientific knowledge openly available, accessible and reusable for everyone, to increase scientific collaborations and sharing of information for the benefits of science and society, and to open the processes of scientific knowledge creation, evaluation and communication to societal actors beyond the traditional scientific community."

### Guiding Principles: FAIR, CARE, and TRUST

Three sets of principles have been developed to guide researchers in practicing open science, particularly concerning data management and stewardship.

To ensure that "open" is also effective and ethical, the community has developed important guiding principles:

The **[FAIR](https://doi.org/10.1038/sdata.2016.18){target=_blank}** principles are a set of guiding principles to make data **F** indable, **A** ccessible, **I** nteroperable, and **R** eusable.

These principles provide a framework for organizing and documenting data, so that it can be more easily discovered, understood, and reused by others.

*   **FAIR Principles:** Research outputs should be **F** indable, **A** ccessible, **I** nteroperable, and **R** eusable. This is a set of technical guidelines to ensure that data and software can be discovered and used by both humans and machines.

The **[CARE](https://doi.org/10.5334/dsj-2020-043){target=_blank}** principles for Indigenous Data Governance are people and purpose-oriented, reflecting the crucial role of data in advancing Indigenous innovation and self-determination.

They are: **C** ollective benefit, **A** uthority to control, **R** esponsibility, and **E** thics.

These principles complement the FAIR principles, and together they guide the move towards more open and equitable data practices.

The **[TRUST](https://doi.org/10.1038/s41597-020-0486-7){target=_blank}** principles provide a framework for digital repositories to demonstrate their reliability and commitment to data stewardship.

They stand for **T** ransparency, **R** esponsibility, **U** ser focus, **S** ustainability, and **T** echnology.

While FAIR and CARE focus on the data itself, TRUST focuses on the repositories that host the data, ensuring they are reliable and can be trusted to preserve data for the long term.


As you can see, Open Science is a rich and evolving ecosystem. In this lesson, we will focus on three foundational components that are a great starting point for any researcher: **Open Access**, **Open Data**, and **Open Source Software**.

## Foundational Open Science Skills

??? Question "What does FOSS mean?"

    :material-open-source-initiative: Free and Open Source Software (FOSS) is the prime acronym. 

    We chose FOSS for the name of our workshop series as a homage to the open source ecosystem that modern scientific research rests upon. 

This lesson is adapted from the curriculum of the **[CyVerse Foundational Open Science Skills (FOSS)](https://foss.cyverse.org){target=_blank}** workshop. FOSS is a comprehensive, hands-on training program designed to equip researchers with the practical skills needed to work effectively in a modern, collaborative, and data-intensive environment.

The main FOSS curriculum goes beyond theory to provide practical experience with core tools and best practices, including:

*   **The Command Line:** For automating tasks and managing computational resources.
*   **Data Management & Tidy Data:** Structuring data for analysis and preservation.
*   **Version Control with Git/GitHub:** Tracking changes and collaborating on code and documents.
*   **Containerization with Docker:** Ensuring computational reproducibility across different systems.
*   **Prompt Engineering:** Leveraging the ever expanding ecosystem of generative AI tools for scientific research.

In this abbreviated short-course for NCEMS we will focus on: 

<span style="font-size:1.2em;">_1. Building a culture of team scientists eager to share research materials - such as data, code, methods, documentation, and early results - with colleagues and society at large, in addition to more traditional peer-reviewed publications_</span> 

<br>
<br>

<span style="font-size:1.2em;">_2. Introduction to CyVerse and ACCESS-CI cyberinfrastructure tools to conducting reproducible science that others can build upon_</span>

<br>
<br>

<span style="font-size:1.2em;">_3. Understanding the push towards increased transparency and accountability for those practicing science (ie., compliance)_</span>

<br>
<br>
<br>
<br>
<br>

<figure markdown="span">
  <a href="" target="blank" rel="open science">![open science](./assets/open_science_word_cloud.png){ width="500" } </a>
    <figcaption> Open Science Word Cloud by [Pownall et al. 2023](http://dx.doi.org/10.31234/osf.io/vypkb)</figcaption>
</figure>

<br>
<br>
<br>
<br>
<br>

<figure markdown="span">
    <iframe width="526" height="340" src="https://www.youtube.com/embed/8fGRN5fa-Ks" title="What is &#39;open science&#39;? | The Royal Society" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    <vidcaption> <br> _What is Open Science | The Royal Society_ </figcaption> 
</figure>

<br>
<br>
<br>
<br>
<br>
<br>

??? Tip "2023: The Year of Open Science"

    Building on the policy momentum of the reproducibility crisis, 2023 was declared the "Year of Open Science" by the White House Office of Science and Technology Policy (OSTP). The initiative focused on sparking culture change and building awareness through a series of events, resources, and community activities designed to support the adoption of open, equitable, and secure science practices across the federal government and the nation.

    The White House OSTP joined by 10 federal agencies and a coalition of more than 85 universities, declared 2023 the Year of Open Science as a way to bring awareness to the benefits of Open Science and to steer the scientitic community towards its adoption. 

    NASA leds a prominent program called [Transform to Open Science](https://github.com/nasa/Transform-to-Open-Science) which included an [online class on Open Science](https://nasa.github.io/Transform-to-Open-Science/take-os101/). 

    <figure markdown>
    <a href="https://github.com/nasa/Transform-to-Open-Science" target="blank" rel="open science">![open science](https://zenodo.org/record/7262104/files/Tops_Badge_Nasa.png){ width="200" } </a>
        <figcaption> NASA Transform to Open Science (TOPS) </figcaption>
    </figure>

<br>
<br>
<br>

??? Tip "2025: Gold Standard Science"

    After the re-election of Donald Trump in late 2024, the White House deprecated or ended nearly all of the scientific policies of the previous administration. This includes the 2023 "Open Science" mandates. 

    [Memorandums](https://www.whitehouse.gov/wp-content/uploads/2025/03/OSTP-Guidance-for-GSS-June-2025.pdf){target=_blank} by OSTP director Michael Krastios and executive orders on ["Gold Standard Science"](https://www.whitehouse.gov/presidential-actions/2025/05/restoring-gold-standard-science/){target=_blank} retain language on the principles of Open Science, though [critics argue](https://www.science.org/content/article/what-does-trump-s-call-gold-standard-science-really-mean){target=_blank} political interference and scientific gate keeping may hinder what types of science is allowed to be funded under the current administration.  

    !!! Quote "2025 Executive Orders"

        * [REMOVING BARRIERS TO AMERICAN LEADERSHIP IN ARTIFICIAL INTELLIGENCE, January 23, 2025](https://www.whitehouse.gov/presidential-actions/2025/01/removing-barriers-to-american-leadership-in-artificial-intelligence/){target=_blank}

        * [OMB Accelerating Federal Use of AI through Innovation, Governance, and Public Trust, April 3, 2025](https://www.whitehouse.gov/wp-content/uploads/2025/02/M-25-21-Accelerating-Federal-Use-of-AI-through-Innovation-Governance-and-Public-Trust.pdf){target=_blank}

            * [Fact Sheet: Eliminating Barriers for Federal Artificial Intelligence Use and Procurement, April 7, 2025](https://www.whitehouse.gov/fact-sheets/2025/04/fact-sheet-eliminating-barriers-for-federal-artificial-intelligence-use-and-procurement/){target=_blank}

        * [ADVANCING ARTIFICIAL INTELLIGENCE EDUCATION FOR AMERICAN YOUTH, April 23, 2025](https://www.whitehouse.gov/presidential-actions/2025/04/advancing-artificial-intelligence-education-for-american-youth/){target=_blank}

        * [Restoring Gold Standard Science, May 23, 2025](https://www.whitehouse.gov/presidential-actions/2025/05/restoring-gold-standard-science/){target=_blank}

            * [Fact Sheet: President Donald J. Trump is Restoring Gold Standard Science in America](https://www.whitehouse.gov/fact-sheets/2025/05/fact-sheet-president-donald-j-trump-deploys-advanced-nuclear-reactor-technologies-for-national-security/){target=_blank}


---

<br>
<br>
<br>


## The Pillars of Open Science

The UNESCO framework organizes Open Science around four key pillars:

1.  **Open Scientific Knowledge:** This includes not just final publications (Open Access), but also the underlying data (Open Data), software source code and models (Open Source Software and Models), and even educational materials (Open Educational Resources).
2.  **Open Science Infrastructures:** The physical and digital tools that make Open Science possible, such as open hardware, open-source software platforms, and shared repositories for data and publications.
3.  **Open Engagement of Societal Actors:** Actively involving the public in research through practices like citizen science and crowdfunding, ensuring science addresses societal needs.
4.  **Open Dialogue with Other Knowledge Systems:** Recognizing and respecting the contributions of diverse knowledge systems, such as Indigenous knowledge, to create a more holistic understanding of the world.


### **:material-pillar: The [6] Pillars of Open Science**

[**:material-pillar: Open Access Publications**](#open-access-publications)

[**:material-pillar: Open Data**](#open-data)

[**:material-pillar: Open Educational Resources**](#open-educational-resources)

[**:material-pillar: Open Methodology**](#open-methodology)
      
[**:material-pillar: Open Peer Review**](#open-peer-review)

[**:material-pillar: Open Source Software**](#open-source-software)

??? Question "Wait, how many pillars :material-pillar: of Open Science Are There Really?"

    !!! Answer "It Depends"
    
        The number of pillars range from [4 :material-pillar:](https://narratives.insidehighered.com/four-pillars-of-open-science/){target=_blank} to 6, up to [8 :material-pillar:](https://www.ucl.ac.uk/library/research-support/open-science/8-pillars-open-science){target=_blank} depending on where you're reading.

<br>
<br>
<br>
<br>
<br>

## **:material-pillar: Open Access Publications**

[![open access](https://upload.wikimedia.org/wikipedia/commons/f/f3/Open_Access_PLoS.svg){width=210}](https://en.wikipedia.org/wiki/Open_access){target=_blank}

!!! Quote "Definition"

    "Open access is a publishing model for scholarly communication that makes research information available to readers at no cost, as opposed to the traditional subscription model in which readers have access to scholarly information by paying a subscription (usually via libraries)." -- [OpenAccess.nl](https://www.openaccess.nl/en/what-is-open-access){target=_blank}

<br>
<br>
<br>

!!! Example "Open Access Journal Examples"

    Major publishers have provided access points for publishing your work 

    - [AAAS Science](https://www.science.org/content/page/open-access-aaas){target=_blank}
    - [Nature](https://www.nature.com/nature-portfolio/open-access){target=_blank}
    - [American Geophysical Union](https://www.agu.org/Publish-with-AGU/Publish/Open-Access){target=_blank}
    - [Commonwealth Scientific and Industrial Research Organisation (CSIRO)](https://acsopenscience.org/australia-csiro/){target=_blank}
    - [Open Research Europe](https://open-research-europe.ec.europa.eu/){target=_blank}
    - [PLOS](https://plos.org/){target=_blank}
    - [MDPI](https://www.mdpi.com/){target=_blank}
    - [Ecosphere](https://esajournals.onlinelibrary.wiley.com/journal/21508925){target=_blank}

    [Directory of Open Access Journals](https://doaj.org/){target=_blank}

<br>
<br>

### Types of Publishing Business Models:

1. Subscription model - the author pays a smaller fee (or no fee) for the article to be published. The publisher then sells subscription access to the article (usually to institutes of higher education).

2. Open Access model - The author pays a larger fee to make the article freely available to anyone through a Creative Commons license. 

    - Open Access publishing in Nature costs $12,290!
    - Open Access publising in PlosOne costs $2,290

<br>
<br>
<br>

### Research Article Versions 

1. Preprint - In academic publishing, a preprint is a version of scholary paper that precedes formal peer-review and publication in a scientific journal. The preprint may be available, often as a non-typeset version available for free online. 

    ??? Example "Pre-print Services"

        - [ASAPbio Pre-Print Server List](https://asapbio.org/preprint-servers){target=_blank} - ASAPbio is a scientist-driven non-profit promoting transparency and innovation comprehensive list of pre-print servers inthe field of life science communication.
        - [ESSOar](https://www.essoar.org/){target=_blank} - Earth and Space Science Open Archive hosted by the American Geophysical Union.
        - [Peer Community In (PCI)](https://peercommunityin.org/) a free recommendation process of scientific preprints based on peer reviews
        - [OSF.io Preprints](https://osf.io/preprints/){target=_blank} are partnered with numerous projects under the "-rXivs"

        ??? Tip "The rXivs"

            - [AfricArXiv](https://osf.io/preprints/africarxiv/){target=_blank}

            - [AgrirXiv](https://cabidigitallibrary.org/journal/agrirxiv){target=_blank}

            - [Arabixiv](https://arabixiv.org/discover){target=_blank}

            - [arXiv](https://arxiv.org/){target=_blank} - is a free distribution service and an open-access archive for 2,086,431 scholarly articles in the fields of physics, mathematics, computer science, quantitative biology, quantitative finance, statistics, electrical engineering and systems science, and economics.

            - [BioHackrXiv](https://biohackrxiv.org/){target=_blank}
            - [BioRxiv](https://www.biorxiv.org/){target=_blank} -  is an open access preprint repository for the biological sciences.
            - [BodorXiv](https://bodoarxiv.wordpress.com/){target=_blank}
            - [EarthArXiv](https://eartharxiv.org/){target=_blank} - is an open access preprint repository for the Earth sciences.
            - [EcsArXiv](https://ecsarxiv.org/){target=_blank} - a free preprint service for electrochemistry and solid state science and technology
            - [EdArXiv](https://edarxiv.org/){target=_blank} - for the education research community
            - [EngrXiv](https://engrxiv.org/){target=_blank} for the engineering community
            - [EvoEcoRxiv](https://www.ecoevorxiv.com/){target=_blank} - is an open acccess preprint repository for Evolutionary and Ecological sciences.
            - [MediArXiv](https://mediarxiv.com/){target=_blank} for Media, Film, & Communication Studies
            - [MedRxiv](https://www.medrxiv.org/){target=_blank} - is an open access preprint repository for Medical sciences.
            - [PaleorXiv](https://paleorxiv.org/){target=_blank} - is an open access preprint repository for Paleo Sciences
            - [PsyrXiv](https://psyarxiv.com/){target=_blank} - is an open access preprint repository for Psychological sciences.
            - [SocArXiv](https://socopen.org/){target=_blank} - is an open access preprint repository for Social sciences.
            - [SportrXiv](https://sportrxiv.org/){target=_blank} - is an open access preprint for Sports sciences.
            - [ThesisCommons](https://thesiscommons.org/) - open Theses


2. Author's accepted manuscript (AAM) - includes changes that came about during peer-review process. It is a non-typeset or formatted article. This often had an embargo period of 12-24 months

3. Published version of record (VOR) - includes stylistic edits, online & print formatting. This is the version that publishers claim ownership of with copyrights or exclusive licensing. 

<br>
<br>

??? Tip "Copyrights and Science Publishing"

    Upon completion of a peer-reviewed science paper, the author typically 1. signs over the copyright of the paper to the publisher or 2. signs an exclusive license agreement with the publisher

    For example authors that publish in [_Science_](https://www.science.org/content/page/science-journals-editorial-policies#copyright-license-to-publish) retain their copyright but sign a 'license to pubish' agreement with AAAS

    Elsevier requires authors to sign over copyright of the article but authors retains some rights of distribution

    - [Elsevier summary of copyright policies](https://www.elsevier.com/about/policies-and-standards/copyright#1-author-rights)
    - [Elsevier article sharing policy](https://www.elsevier.com/about/policies-and-standards/sharing)
    - [Wiley policy on self-archiving](https://authorservices.wiley.com/author-resources/Journal-Authors/licensing/self-archiving.html)
    - [Springer Nature copyright policies](https://www.springer.com/gp/open-access/publication-policies/copyright-transfer#:~:text=Springer%20Nature%20authors%20retain%20copyright,found%20in%20our%20publishing%20policies.)

<br>
<br>

### New Open Access Mandates in US

The White House Office of Science and Technology (OSTP) has recently released a policy document known as the [Nelson Memo](https://www.whitehouse.gov/ostp/news-updates/2022/08/25/ostp-issues-guidance-to-make-federally-funded-research-freely-available-without-delay/) stating that tax-payer funded research must by open access by 2026 with no embargo period. 

Authors can comply with the memo by either:

1. Publishing Open Access (this usually requires higher fees)
2. Distributing the Author's Accepted Manuscript (AAM) 

Read [USDA's open access plan](https://www.nal.usda.gov/sites/default/files/page-files/USDA_Public_Access_Implementation_Plan_8_10_2023_0.pdf) in reponse to the Nelson Memo

<br>
<br>
<br>
<br>

### Additional Info

University of Arizona Libraries information on [Open Access publishing](https://lib.arizona.edu/research/open-access) including agreements with several journals to reduce or waive publishing fees. 

https://www.coalition-s.org/


<br>  
<br>
<br>
<br>

---

<br>
<br>


## **:material-pillar: Open Data**

<br>

!!! Quote "Definitions"

    “Open data and content can be freely used, modified, and shared by anyone for any purpose” - [The Open Definition](https://opendefinition.org/){target=_blank}

    "Open data is data that can be freely used, re-used and redistributed by anyone - subject only, at most, to the requirement to attribute and sharealike." - [Open Data Handbook](https://opendatahandbook.org/guide/en/what-is-open-data/){target=_blank}

    [:material-wikipedia: Wikipedia definition](https://en.wikipedia.org/wiki/Open_data){target=_blank}

<br>
<br>
<br>
   
<span style="font-size:1.1em;">Data are the foundation for any scientific endeavor. A lot of thought needs to go into how to best collect, store, analyze, curate, share, and archive data.</span>

<figure markdown>
  <a href="https://en.wikipedia.org/wiki/DIKW_pyramid" target="blank" rel="open science">![open science](https://upload.wikimedia.org/wikipedia/commons/0/06/DIKW_Pyramid.svg){ width="400" } </a>
    <figcaption> DIKW Pyramid</figcaption>
</figure>

<br>
<br>


### FAIR Principles

In 2016, the [FAIR Guiding Principles](https://www.nature.com/articles/sdata201618) for scientific data management and stewardship were published in _Scientific Data_. 

_**Findable:**_
Making data discoverable by the wider academic community and the public

_**Accessible:**_
Using unique identifiers, metadata and a clear use of language and access protocols

_**Interoperable:**_
Applying standards to encode and exchange data and metadata

_**Reusable:**_
Enabling the repurposing of researach outputs to maximize their research potential

<br>
<br>
<br>
<br>

!!! Tip "Reasons to Make your Data Open"

    - Unnecessary duplication. Duplication of research is costly for society, and places unnecessary burden on heavily researched people and populations.  
    - The data underlying publications are maintained and accessible, allowing for validation of results.
    - Data openness leads to more collaboration and advances research and innovation.
    - Your research is more visible and has greater impact. Publications which allow access to the underlying data get more citations. Greater visibility also allows for better validation and scrutiny of findings.
    - Other researchers can cite your data, which will drive up your citation number and increase your influence in your field of research.
    - Storing your data in a public repository also provides you with secure and ongoing storage that may otherwise not be available to you.
    -[Foster Open Science](https://www.fosteropenscience.eu/)


<br>
<br>
<br>
<br>

### As Open as Possible, as Closed as Necessary

There are many circumstances where open data could be harmful:

- Data on human health

- Location of endangered species or archaeological sites

- Data that individuals or groups do not want to be public

    ??? Tip "CARE Principles"

        The [CARE Principles](https://www.gida-global.org/care) for Indigenous Data Governance were drafted at the International Data Week and Research Data Alliance Plenary co-hosted event "Indigenous Data Sovereignty Principles for the Governance of Indigenous Data Workshop," 8 November 2018, Gaborone, Botswana.

         *Collective Benefit*

         -   C1. For inclusive development and innovation
         -   C2. For improved governance and citizen engagement
         -   C3. For equitable outcomes

         *Authority to Control*

         -   A1. Recognizing rights and interests
         -   A2. Data for governance
         -   A3. Governance of data

         *Responsibility*

         -   R1. For positive relationships
         -   R2. For expanding capability and capacity
         -   R3. For Indigenous languages and worldviews

         *Ethics*

         -   E1. For minimizing harm and maximizing benefit
         -   E2. For justice
         -   E3. For future use

* Data for making [lethal weapons](https://www.theverge.com/2022/3/17/22983197/ai-new-possible-chemical-weapons-generative-models-vx)

    ??? tip "TRUST Principles"

        [Lin et al. 2020](https://www.nature.com/articles/s41597-020-0486-7){target=_blank} The TRUST Principles for digital repositories
    
        *Transparency*
    
        - Terms of use, both for the repository and for the data holdings.
    
        - Minimum digital preservation timeframe for the data holdings.
    
        - Any pertinent additional features or services, for example the capacity to responsibly steward sensitive data.
    
        *Responsibility*
    
        - Adhering to the designated community’s metadata and curation standards, along with providing stewardship of the data holdings e.g. technical validation, documentation, quality control, authenticity protection, and long-term persistence.
    
        - Providing data services e.g. portal and machine interfaces, data download or server-side processing.
    
        - Managing the intellectual property rights of data producers, the protection of sensitive information resources, and the security of the system and its content.
    
        *User focus*
    
        - Implementing relevant data metrics and making these available to users.
    
        - Providing (or contributing to) community catalogues to facilitate data discovery.
    
        - Monitoring and identifying evolving community expectations and responding as required to meet these changing needs.
    
        *Sustainability*
    
        - Planning sufficiently for risk mitigation, business continuity, disaster recovery, and succession.
    
        - Securing funding to enable ongoing usage and to maintain the desirable properties of the data resources that the repository has been entrusted with preserving and disseminating.
    
        - Providing governance for necessary long-term preservation of data so that data resources remain discoverable, accessible, and usable in the future.
    
        *Technology*
    
        - Implementing relevant and appropriate standards, tools, and technologies for data management and curation.
    
        - Having plans and mechanisms in place to prevent, detect, and respond to cyber or physical security threats.

    

<br>
<br>

!!! Tip "Open vs. FAIR"

    FAIR does not demand that data be open: See one definition of open: http://opendefinition.org/
    
    Open data does not necessarily mean it is FAIR

<br>
<br>

#### Additional Info

- The Ethics of Geolocated Data from [UK Statistics Authority](https://uksa.statisticsauthority.gov.uk/publication/ethical-considerations-in-the-use-of-geospatial-data-for-research-and-statistics/pages/1/){target=_blank} 

- Health information [US HIPAA](https://www.hhs.gov/hipaa/index.html){target=_blank}

- Indigenous data sovereignty: [CARE Principles for Indigenous Data Governance](http://doi.org/10.5334/dsj-2020-043){target=_blank} , [Global Indigenous Data Alliance (GIDA)](https://www.gida-global.org/care){target=_blank}, [First Nations OCAP® (Ownership Control Access and Possession)](https://fnigc.ca/ocap-training/){target=_blank}, [Circumpolar Inuit Protocols for Equitable and Ethical Engagement](https://www.arcus.org/arctic-info/archive/33236){target=_blank} 

<br>
<br>
<br>
<br>

---

<br>    
<br>
<br>

## **:material-pillar: Open Educational Resources**

<figure markdown = "span">
    [![open educational resources](https://upload.wikimedia.org/wikipedia/commons/2/20/Global_Open_Educational_Resources_Logo.svg){width=240}](https://www.unesco.org/en/communication-information/open-solutions/open-educational-resources)
</figure>

!!! Quote "Definitions"

    "Open Educational Resources (OER) are learning, teaching and research materials in any format and medium that reside in the public domain or are under copyright that have been released under an open license, that permit no-cost access, re-use, re-purpose, adaptation and redistribution by others." - [UNESCO](https://www.unesco.org/en/communication-information/open-solutions/open-educational-resources){target=_blank}

    [:material-wikipedia: Wikipedia definition](https://en.wikipedia.org/wiki/Open_educational_resources){target=_blank}

??? Example "Digital Literacy Organizations"

    - [The Carpentries](https://carpentries.org/){target=_blank} - teaches foundational coding and data science skills to researchers worldwide  
    - [EdX](https://www.edx.org/){target=_blank} - Massively Open Online Courses (not all open) hosted through University of California Berkeley
    - [EveryoneOn](https://www.everyoneon.org/ ){target=_blank} - mission is to unlock opportunity by connecting families in underserved communities to affordable internet service and computers, and delivering digital skills trainings 
    - [ConnectHomeUSA](https://connecthomeusa.org/){target=_blank} - is a movement to bridge the digital divide for HUD-assisted housing residents in the United States under the leadership of national nonprofit EveryoneOn
    - [Global Digital Literacy Council](https://www.gdlcouncil.org/){target=_blank} -  has dedicated more than 15 years of hard work to the creation and maintenance of worldwide standards in digital literacy
    - [IndigiData](https://indigidata.nativebio.org/){target=_blank} - training and engaging tribal undergraduate and graduate students in informatics
    - [National Digital Equity Center](https://digitalequitycenter.org/about-us/){target=_blank} a 501c3 non-profit, is a nationally recognized organization with a mission to close the digital divide across the United States
    - [National Digital Inclusion Allaince](https://www.digitalinclusion.org/){target=_blank} - advances digital equity by supporting community programs and equipping policymakers to act
    - [Net Literacy](https://www.netliteracy.org/){target=_blank}
    - [Open Educational Resources Commons](https://www.oercommons.org/){target=_blank}
    - [Project Pythia](https://projectpythia.org/){target=_blank} is the education working group for Pangeo and is an educational resource for the entire geoscience community
    - [Research Bazaar](https://resbaz.github.io/resbaz2021/){target=_blank} - is a worldwide festival promoting the digital literacy emerging at the centre of modern research
    - [TechBoomers](https://techboomers.com/){target=_blank} - is an education and discovery website that provides free tutorials of popular websites and Internet-based services in a manner that is accessible to older adults and other digital technology newcomers

??? Example "Educational Materials"

    - [Teach Together](https://teachtogether.tech/en/index.html#){target=_blank} by Greg Wilson
    - [DigitalLearn](https://www.digitallearn.org/){target=_blank}

<br>
<br>
<br>
<br>

---

<br>    
<br>
<br>

## **:material-pillar: Open Methodology**

<br>

!!! Quote "Definitions"

    "An open methodology is simply one which has been described in sufficient detail to allow other researchers to repeat the work and apply it elsewhere." - [Watson (2015)](https://doi.org/10.1186/s13059-015-0669-2){target=_blank}

    "Open Methodology refers to opening up methods that are used by researchers to achieve scientific results and making them publicly available." - [Open Science Network Austria](https://www.oana.at/en/about-open-science){target=_blank}

<br>
<br>

### Sharing Research Computer Code

Scientists around the globe are creating computer code for scientific analysis. These are valuable contributions that need to be shared!

Platforms like [GitHub](https://github.com/search?q=open+science){target=_blank} and [GitLab](https://gitlab.com/explore/projects/topics/Open%20Science){target=_blank} are ideal for collaboratively developing code and sharing with the open internet. 

<figure style="display: flex; justify-content: center;">
    <a href="https://github.com/"><img src="https://cdn.iconscout.com/icon/free/png-256/free-github-169-1174970.png" alt="github" style="width: 200px; margin-right: 30px;"></a>
    <a href="https://gitlab.com/"><img src="https://raw.githubusercontent.com/CyVerse-learning-materials/foss/mkdocs/docs/assets/gitlab_logo.png" alt="gitlab" style="width: 200px;"></a>
</figure>

<br>
<br>
<br>
<br>

### Publishing Your Methods or Protocols 

??? Example "Platforms for Publishing Protocols & Bench Techniques"

    - [BioProtocol](https://bio-protocol.org/Default.aspx){target=_blank}
    - [Current Protocols](https://currentprotocols.onlinelibrary.wiley.com/){target=_blank}
    - [Gold Biotechnology Protocol list](https://www.goldbio.com/search?q=&type=documentation&documentation_type=protocol){target=_blank}
    - [JoVE](https://www.jove.com/){target=_blank} - Journal of Visualized Experiments
    - [Nature Protocols](https://www.nature.com/nprot/){target=_blank}
    - [OpenWetWare](https://openwetware.org/wiki/Main_Page){target=_blank}
    - [Protocol Exchange](https://protocolexchange.researchsquare.com/){target=_blank}
    - [Protocols Online](http://www.protocol-online.org/prot/){target=_blank}
    - [:material-microscope: Protocols](https://www.protocols.io/){target=_blank}
    - [SciGene](http://scigine.com/blog/){target=_blank}
    - [Springer Nature Experiments](https://experiments.springernature.com/){target=_blank}
      

<br>
<br>
<br>
<br>

### PreRegistration

Preregistration is detailing your research and analysis plan and submitting it to an online registry **before** you engage in the research. 

<figure markdown>
  <a target="blank" rel="open science">![open science](./assets/cycle_prereg.png){ width="500" } </a>
    <figcaption> PreRegistration in the Research Life Cycle</figcaption>
</figure>

#### Why Do This?

Preregistration makes your process more open and records the difference between your initial research plan what you end up actually doing.

Preregistration separates _hypothesis-generating_  (exploratory) from _hypothesis-testing_ (confirmatory) research. Both are important. But the same data cannot be used to generate and test a hypothesis, which can happen unintentionally and reduce the credibility of your results. 

It also helps us avoid practices like [p-hacking](https://en.wikipedia.org/wiki/Data_dredging){target=_blank} or [Hypothesizing After the Results are Known(HARKing)](https://en.wikipedia.org/wiki/HARKing){target=_blank}. 

<br>

#### Additional Info

Read this publication by [Nosek et al. 2018](https://www.pnas.org/doi/10.1073/pnas.1708274114){target=_blank}

Open Science Framework Preregistration https://www.cos.io/initiatives/prereg

<br>
<br>
<br>
<br>

---

<br>    
<br> 
<br> 

## **:material-pillar: Open Peer Review**

<br> 
<br> 


!!! Quote "Definitions"

    Open peer review is an umbrella term for a number of overlapping ways that peer review models can be adapted in line with the aims of Open Science, including making reviewer and author identities open, publishing review reports and enabling greater participation in the peer review process.  
    
    [-Ross-Hellauer et al. (2017)](https://doi.org/10.12688%2Ff1000research.11369.2)

    <br>

    [:material-wikipedia: Wikipedia's definition](https://en.wikipedia.org/wiki/Open_peer_review)

<br>
<br>
<br>


### Traditional Closed Peer-Review System

<figure markdown>
  <a target="blank" rel="open science">![close peer-review](./assets/peer_review.png){ width="400" } </a>
    <figcaption> </figcaption>
</figure>

- Throughout and after the process, the author remains unaware of the reviewers' identities, while the reviewers know the identity of the authors. 
- All communications between authors, reviewers and editors remains private 

<br>
<br>
<br>

### Complaints with the Traditional Closed Peer-Review System

- Unreliable and Inconsistent
- Delays and Expense
- Lack of Accountability and Risks of Subversion
- Social and Publication Biases
- Lack of Incentives

[_Ross-Hallauer 2017_](https://f1000research.com/articles/6-588/v2)

<br>
<br>
<br>
<br>


### Open Peer-Review Ideas

<figure markdown>
  <a target="blank" rel="open science">![open science](./assets/plos_peer_review.png){ width="500" } </a>
    <figcaption> Open Peer Review Options at [PLOS](https://plos.org/resource/open-peer-review/)</figcaption>
</figure>

<br>
<br>
<br>


[Defenders of the Traditional Peer-Review System](https://doi.org/10.1038/6295)

<br>
<br>
<br>

!!! Tips "Example Open Peer-Review Systems"

    [F1000Research](https://f1000research.com/about){target=_blank} An open research publishing platform that offers open peer review and rapid publication.
    The article from [Ross-Hellauer et al. (2017)](https://doi.org/10.12688%2Ff1000research.11369.2) has open peer-reviews.

<br>

!!! Tips "Platforms for Reviewing Preprints"
    

    - [PREreview](https://prereview.org/){target=_blank} 
    - [Sciety](https://sciety.org/){target=_blank} 
    - [PubPeer](https://pubpeer.com/){target=_blank} 
    - [ASAPbio](https://asapbio.org/){target=_blank} 

<br>
<br>
<br>
<br>

---

<br>    
<br>
<br>

## **:material-pillar: Open Source Software**

[![](https://upload.wikimedia.org/wikipedia/commons/4/42/Opensource.svg){width=240}](https://opensource.org/){target=_blank}

!!! Quote "Definitions"

    "Open source software is code that is designed to be publicly accessible—anyone can see, modify, and distribute the code as they see fit. Open source software is developed in a decentralized and collaborative way, relying on peer review and community production." - [:material-redhat: Red Hat](https://www.redhat.com/en/topics/open-source/what-is-open-source){target=_blank}


    [:material-wikipedia: Wikipedia definition](https://en.wikipedia.org/wiki/Open-source_software){target=_blank}

<br>
<br>

Research science (and also many companies) rely on open source software to operate

<br>
<br>

!!! tip "Open Source Software"

    - Linux operating system and shell
    - Python 
    - R
    - git
    - Conda
    - Docker
    - Cyverse
    - Pytorch
    - [Tyson's Awesome List](https://tyson-swetnam.github.io/awesome-open-science/software/){target=_blank}


<br>
<br>

When you create a new software, library, or package, you become its parent and guardian.

<figure markdown>
  <a href="https://m.xkcd.com/2347/" target="blank" rel="xkcd">![xkcd](https://imgs.xkcd.com/comics/dependency.png){ width="400" } </a>
    <figcaption> Image Credit: [XKCD Dependency](https://m.xkcd.com/2347/){target=_blank} </figcaption>
</figure>

<br>
<br>
<br>
<br>

---

<br>    
<br>
<br>

## *WHY* do Open Science?


A paper from [Bartling & Friesike (2014)](https://doi.org/10.1007/978-3-319-00026-8){target=_blank} posits that there are 5 main schools of thought in Open Science, which represent 5 underlying motivations:

1.  **Democratic school**: primarily concerned with making scholarly work freely available to everyone
2.  **Pragmatic school**: primarily concerned with improving the quality of scholarly work by fostering collaboration and improving critiques
3.  **Infrastructure school**: primarily focused on the platforms, tools, and services necessary to conduct efficient research, collaboration, and communication
4.  **Public school**: primarily concerned with societal impact of scholarly work, focusing on engagement with broader public via citizen science, understandable scientific communication, and less formal communication
5.  **Measurement school**: primarily concerned with the existing focus on journal publications as a means of measuring scholarly output, and focused on developing alternative measurements of scientific impact
   
Government, universities, and granting agencies have embraced Open Science and [are mandating some elements (e.g., the Nelson Memo)](https://www.whitehouse.gov/wp-content/uploads/2022/08/08-2022-OSTP-Public-access-Memo.pdf){target=_blank}

<figure markdown>
  <a href="https://library.oapen.org/bitstream/handle/20.500.12657/28008/1001989.pdf" target="blank" rel="fecher_friesike">![fecher_friesike](assets/five_schools.png){ width="700" } </a>
    <figcaption> In [Bartling & Friesike (2014)](https://doi.org/10.1007/978-3-319-00026-8){target=_blank} Open Science: One Term, Five Schools of Thought </figcaption>
</figure>

<br>
<br>
<br>
<br>

---

<br>    
<br>
<br>

## Discussion Questions

??? Question "Which of the :material-pillar: pillars of Open Science is nearest to your own heart?"

    **:material-pillar: Open Access Publications**

    **:material-pillar: Open Data**

    **:material-pillar: Open Educational Resources**

    **:material-pillar: Open Methodology**
      
    **:material-pillar: Open Peer Review**

    **:material-pillar: Open Source Software**

??? Question "Are any of the :material-pillar: pillars more important than the others?"

??? Question "Are there any :material-pillar: pillars not identified that you think should be considered?"

??? Question "What characteristics might a paper, project, lab group require to qualify as doing *Open Science*"

??? Question "What are some barriers to you, your lab group, or your domain doing Open Science?"

??? Question "What motivates you to do Open Science?"

??? Question "Do you feel that you fall into a particular "school"? If so, which one, and why?"

??? Question "Are there any motivating factors for doing Open Science that don't fit into this framework?"


<br>
<br>
<br>

---

<br>    
<br>



## Recommended Open Science Communities

<figure style="display: flex; justify-content: center;">
    <a href="https://the-turing-way.netlify.app/welcome.html"><img src="https://the-turing-way-personas.netlify.app/_static/logo.jpg" alt="turingway" style="width: 120px; margin-right: 15px;"></a>
    <a href="https://github.com/nasa/Transform-to-Open-Science"><img src="https://zenodo.org/record/7262104/files/Tops_Badge_Nasa.png" alt="nasatops" style="width: 120px; margin-right: 15px;"></a>
    <a href="https://openscience.eu/foster-open-science"><img src="https://pbs.twimg.com/profile_images/464812585712234496/tI9cRV8S_400x400.png" alt="foster" style="width: 120px; margin-right: 15px;"></a>
    <a href="https://carpentries.org/"><img src="https://datascience.wisc.edu/wp-content/uploads/sites/1430/2021/06/TheCarpentries-260x300.jpg" alt="carpentries" style="width: 120px; margin-right: 15px;"></a>
    <a href="https://www.cos.io/"><img src="https://imagecdn.mightycause.com/2e70620b-783f-4389-93f2-79b2e9b81a22/" alt="cos" style="width: 120px;"></a>
</figure>

[:material-school: Open Scholarship Grassroots Community Networks](https://docs.google.com/spreadsheets/d/1LNF5_bOkRV-RLIF4HYmu-gOemIa4IdfXEer89fM-Vy8/edit#gid=847887324){target=_blank}

??? Info ":fontawesome-solid-earth-europe: International Open Science Networks"

    - [Center for Scientific Collaboration and Community Engagement (CSCCE)](https://www.cscce.org/){target=_blank}
    - [Center for Open Science (COS)](https://www.cos.io/){target=_blank}
    - [Eclipse Science Working Group](https://science.eclipse.org/){target=_blank}
    - [eLife](https://elifesciences.org/){target=_blank}
    - [NumFocus](https://numfocus.org/){target=_blank}
    - [Open Access Working Group](https://sparcopen.org/people/open-access-working-group/){target=_blank}
    - [Open Research Funders Group](https://www.orfg.org/)
    - [Open Science Foundation](https://osf.io/){target=_blank}
    - [Open Science Network](https://www.opensciencenetwork.org/){target=_blank}
    - [pyOpenSci](https://www.pyopensci.org/){target=_blank}
    - [R OpenSci](https://ropensci.org/){target=_blank}
    - [Research Data Alliance (RDA)](https://www.rd-alliance.org/){target=_blank}
    - [The Turing Way](https://the-turing-way.netlify.app/welcome){target=_blank}
    - [UNESCO Global Open Science Partnership](https://en.unesco.org/science-sustainable-future/open-science/partnership){target=_blank}
    - [World Wide Web Consortium (W3C)](https://www.w3.org/){target=_blank}

??? Info ":fontawesome-solid-earth-americas: US-based Open Science Networks"

    - [CI Compass](https://ci-compass.org/){target=_blank} - provides expertise and active support to cyberinfrastructure practitioners at USA NSF Major Facilities in order to accelerate the data lifecycle and ensure the integrity and effectiveness of the cyberinfrastructure upon which research and discovery depend.
    - [Earth Science Information Partners (ESIP) Federation](https://www.esipfed.org/){target=_blank} -  is a 501(c)(3) nonprofit supported by NASA, NOAA, USGS and 130+ member organizations.
    - [Internet2](https://internet2.edu/){target=_blank} - is a community providing cloud solutions, research support, and services tailored for Research and Education. 
    - [Minority Serving Cyberinfrastructure Consortium (MS-CC)](https://www.ms-cc.org/){target=_blank} envisions a transformational partnership to promote advanced cyberinfrastructure (CI) capabilities on the campuses of Historically Black Colleges and Universities (HBCUs), Hispanic-Serving Institutions (HSIs), Tribal Colleges and Universities (TCUs), and other Minority Serving Institutions (MSIs). 
    - [NASA Transform to Open Science (TOPS)](https://github.com/nasa/Transform-to-Open-Science){target=_blank} - coordinates efforts designed to rapidly transform agencies, organizations, and communities for Earth Science
    - [OpenScapes](https://www.openscapes.org/){target=_blank} - is an approach for doing better science for future us
    - [The Quilt](https://www.thequilt.net/){target=_blank} - non-profit regional research and education networks collaborate to develop, deploy and operate advanced cyberinfrastructure that enables innovation in research and education.

??? Info ":fontawesome-solid-earth-oceania: Oceania Open Science Networks"

    - [New Zealand Open Research Network](https://nzorn.netlify.app/) - New Zealand Open Research Network (NZORN) is a collection of researchers and research-associated workers in New Zealand.
    - [Australia & New Zealand Open Research Network](https://www.anzopenresearch.org/) - ANZORN is a network of local networks distributed without Australia and New Zealand.

<br>
<br>
<br>

---

<br>
<br>
<br>

## Self Assessment

Test your knowledge with the following questions.

??? Question "Which of the following best describes the core principles of Open Science?"

    *   a) Secrecy, Competition, and Profit
    *   b) Transparency, Collaboration, and Accessibility
    *   c) Exclusivity, Individualism, and Paywalls
    *   d) Obscurity, Isolation, and Copyright

    ??? Success "Answer"

        The correct answer is **b) Transparency, Collaboration, and Accessibility**. Open Science is a movement to make scientific research, data, and dissemination accessible to all levels of society.

??? Question "True or False: Open Access publishing means that research outputs are available online to anyone at no cost and are free of most copyright and licensing restrictions."

    ??? Success "Answer"

        **True**. Open Access (OA) literature is digital, online, free of charge, and free of most copyright and licensing restrictions. It allows for the reuse and redistribution of research findings, accelerating discovery.

??? Question "The FAIR principles are a set of guiding principles to make data more reusable. What does FAIR stand for?"

    *   a) Fast, Accessible, Intelligent, and Reproducible
    *   b) Findable, Accessible, Interoperable, and Reusable
    *   c) Frequent, Available, Indexed, and Robust
    *   d) Formal, Actionable, Interconnected, and Relevant

    ??? Success "Answer"

        The correct answer is **b) Findable, Accessible, Interoperable, and Reusable**. These principles provide a framework for improving the quality and reusability of research data.

??? Question "True or False: Sharing research data is not considered a part of Open Science practices."

    ??? Success "Answer"

        **False**. Open Data is a cornerstone of Open Science. Sharing research data allows for verification of results, encourages new research questions, and avoids duplication of effort.

??? Question "Which of the following is a key benefit of practicing Open Science?"

    *   a) It slows down the pace of scientific discovery.
    *   b) It increases the risk of research being stolen before publication.
    *   c) It enhances the transparency and reproducibility of research.
    *   d) It makes it harder for the public to engage with science.

    ??? Success "Answer"

        The correct answer is **c) It enhances the transparency and reproducibility of research**. By making methods, data, and code openly available, other researchers can more easily verify and build upon previous work, which is fundamental to the scientific process.

??? Question "True or False: A Data Management Plan (DMP) is only important after a research project is completed."

    ??? Success "Answer"

        **False**. A Data Management Plan (DMP) is a formal document that should be created *before or at the start* of a research project. It outlines how data will be handled both during research and after the project is completed, ensuring data quality and preservation.


??? Question "True or False: All research papers published in the top journals, like Science and Nature, are always Open Access?"

    ??? Success "Answer"

        False

        Major Research journals like [Science](https://www.science.org/content/page/open-access-aaas){target=_blank} and [Nature](https://www.nature.com/nature-portfolio/open-access){target=_blank} have an "Open Access" option when a manuscript is accepted, but they charge an extra fee to the authors to make those papers Open Access.

        These [high page costs](https://www.science.org/content/article/9500-nature-journals-will-now-make-your-paper-free-read){target=_blank} are exclusionary to the majority of global scientists who cannot afford to front these costs out of pocket.

        This will soon change, at least in the United States. The [Executive Branch of the federal government recently mandated](https://www.nature.com/articles/d41586-022-02351-1){target=_blank} that future federally funded research be made Open Access after 2026.


??? Question "True or False: an article states all of the research data used in the experiments "are available upon request from the corresponding author(s)," meaning the data are "Open""

    ??? Failure "Answer"

        False

        In order for research to be open, the data need to be freely available from a digital repository, like [Data Dryad](https://datadryad.org){target=_blank}, [Zenodo.org](https://zenodo.org){target=_blank}, or [CyVerse](https://cyverse.org/data-commons){target=_blank}.

        Data that are 'available upon request' do not meet the FAIR data principles. 



??? Question "Using a version control system to host the analysis code and computational notebooks, and including these in your Methods section or Supplementary Materials, is an example of an Open Methodology?"

    ??? Success "Answer"

        Yes!

        Using a VCS like GitHub or GitLab is a great step towards making your research more reproducible. 

        Ways to improve your open methology can include documentation of your physical bench work, and even video recordings and step-by-step guides for every part of your project.

??? Question "You are asked to review a paper for an important journal in your field. The editor asks if you're willing to release your identity to the authors, thereby "signing" your review. Is this an example of "Open Peer Review"?"

    ??? Success "Answer"

        Maybe

        There are many opinions on what 'open-review' should consist of. A reviewer signing their review and releasing their identity to the authors is a step toward a more open process. However, it is far less open than publishing the peer-review reports online next to the final published paper. 


??? Question "You read a paper where the author(s) wrote their own code and licensed as "Open Source" software for a specific set of scientific tasks which you want to replicate. When you visit their personal website, you find the GitHub repository does not exist (because its now private). You contact the authors asking for access, but they refuse to share it 'due to competing researchers who are seeking to steal their intellectual property". Is the software open source?"

    ??? Success "Answer"

        No

        Just because an author states they have given their software a permissive software license, does not make the software open source. 

        Always make certain there is a [LICENSE](https://choosealicense.com/licenses/){target=_blank} associated with any software you find on the internet. 

        In order for the software to be open, it must follow the [Open Source Initiative definition](https://opensource.org/osd){target=_blank}


