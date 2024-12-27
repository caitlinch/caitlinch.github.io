---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
  * Doctor of Philosophy, Biology 2025 (expected)
      * __The Australian National University, Canberra__
      * Thesis: _“Systematic bias in phylogenetic methods: investigating the 
      adequacy of the treelikeness assumption”_
      * Supervised by Dr. Robert Lanfear, with Dr. Minh Bui, Dr. Maja Adamska, 
      and Dr. Barbara Holland
      * Research areas: phylogenetics, evolutionary biology, bioinformatics
  * Bachelor of Science (Honours, First Class) 2018
      * __The Australian National University, Canberra__
      * Honours thesis: _“Detecting introgression in multiple sequence 
      alignments: a new test for quantifying treelikeness”_
      * Supervised by Dr. Robert Lanfear and Dr. Minh Bui
      * Coursework: evolutionary biology, chemistry, systems engineering, 
      biomedical engineering

Work experience
======
* __Research Officer__ (R package development): 26/08/2024 - present
  * _National Centre for Epidemiology and Population Health, ANU_
  * Developer of R package [PoolTestR](https://github.com/AngusMcLure/PoolTestR)
  and Shiny app [PoolTools](https://github.com/AngusMcLure/PoolTools)
  * Duties included: 
      * Created documentation and tutorials for development team and end users
      * Transformed R package functions into a user-friendly Shiny app with 
      accessible GUI
      * Developed a test suite for an existing R package
      * Added new classes and generics to an existing R package
      * Developed and implemented new features to facilitate checking the
      formatting of user datasets (and test for common errors present within
      user datasets).

* __Bioinformatician__ (Genome assembly and analysis): 27/05/2024 - present
  * _National Collections and Marine Infrastructure, CSIRO_
  * Duties included: 
      * Developed Snakemake pipeline from existing BASH and SLURM scripts
      * Structured Snakemake pipeline to meet diverse end user analyses
      * Documented methods and approach for end users
      * Adjusted existing R and Bash scripts for use on high performance 
      computing servers

* __Research Assistant__ (Climate modelling): 12/2017 - 11/2017 
  * _Australian National Wildlife Collection, CSIRO_
  * Duties included: 
      * Used daily climate data and niche modelling software to model 
      incubation temperature for wild specimens of bearded dragon, while 
      accounting for uncertainty in age and location
      * Developed a model for predicting the hatching date and nest location 
      for wild bearded dragon specimens, based on capture location and life 
      stage.
      * Collated over 10 years of research data (lab notebooks, spreadsheets,
      other documents) into machine-readable database to facilitate data 
      analysis

Skills
======
* Phylogenetics
    *	Managed DNA and AA multiple sequence alignments including reformatting, extracting individuals genes or sequences, filtering sites or taxa, and mapping SNPs to reference genomes
    *	Developed phylogenetic pipelines using current best practices including:
        *	Data selection and data filtering
        * Identification of appropriate phylogenetic methods and parameters
        * Model assessment and tests of model adequacy
        * Tree estimation
        * Tests of tree topology and comparison of tree topologies
    * Estimated phylogenetic trees including:
        * Maximum parsimony
        * Maximum likelihood tree estimation with current best practices (in IQ-Tree, RAxML, FastTree)
        * Gene tree estimation with current best practices (in IQ-Tree, RAxML)
        * Summary tree estimation with current best practices (in ASTRAL)

* Data science
    *	Developed workflows for data aggregation and formatting, including sanity checks and data conversion
    *	Performed exploratory data analysis, statistics, and data visualisation on hundreds of datasets in multiple disciplines including genetics, phylogenetics, ecology, climate science, geography, 
    *	Wrote executable programs to automatically perform repetitive tasks for myself and others such as: applying statistical tests; aggregating and summarising data; and automating repetitive tasks including file management, text processing, or calling software via command line

* Statistics and experimental design
    *	Designed experiments considering: controls and randomisation; available time and manpower; specific research questions; statistical analyses; and the scientific literature
    *	Selected and implemented appropriate statistical tests 
    *	Developed custom implementations of statistical tests depending on experimental design and requirements, such as custom bootstraps and parametric bootstraps


* Software programming
    *	Fluent in R and Python. 
    * Experienced with Julia and BASH
    *	Applied R and python software packages for applications such as statistics, data conversion and cleaning, data analysis, data visualisation, bioinformatics, population biology, spatial analysis, climate modelling, niche modelling, evolutionary biology, genetics, and phylogenetics
    *	6 research projects in R and 2 in Python each with hundreds of lines of code and dozens of functions, covering a range of biological disciplines from phylogenetics to climate modelling to population genetics

* Bioinformatic pipelines
    * Created and documented custom bioinformatics or data science pipelines incorporating custom programming scripts
    * Incorporated existing software into custom pipelines, including Microsoft Excel and programs for phylogenetics, genetics, recombination detection, data formatting and data conversion, and statistics

* High performance compute (HPC) systems
    * Ran custom scripts and pipelines on HPC systems, with Slurm or PBS scheduling
    * Extracted data from online databases or servers via GUI and API call

* Documentation and record-keeping
    * Collaborated on research projects via GitHub with best practices
    * Summarised data from years of lab notebooks and providing thorough documentation for future researchers, including data visualisations to enable planning for field work and lab experiments
    * Thoroughly documented all code to allow replication or adaptation

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Professional development
======
* __Graduate of Homeward Bound 7__, 2022-2023
    * One of 109 women selected globally to participate in a year-long leadership program for women in STEMM with focuses on Leadership, Strategy, Visibility and Science
    * Fortnightly workshops with topics including strategic planning, developing a personal leadership philosophy, intersectional leadership, science communication, and personal and professional visibility
* __Organising committee member of graduate student conference__, 2020
    * _Research School of Biology (RSB) Higher Degree by Research (HDR) Student Conference_
    * Logistics and organisation including planning program, and providing support on the day for registration and conference sessions
* __Mentee, paired with a postdoctoral researcher__, 2019 - 2022
    * _ANU Research School of Biology (RSB) Higher Degree by Research (HDR) mentoring program_
    * Met fortnightly with my postdoctoral researcher mentor to plan and progress my scientific career
* __Science outreach and volunteering__, 2014 - 2016
    * _Committee member of student-led STEM outreach organisations including Engage: University Outreach, Fifty50 ANU, and Robogals ANU_
    * Independently recruited, trained and managed volunteers
    * Created and maintained relationships with local and rural schools
    * Designed and ran programs such as a mentoring program for first-year women in engineering
    * Planned and attended multi-day trips to teach engineering workshops to students in rural areas
    * Managed budget and financial reporting
    * Recorded and reported program outcomes to stakeholders

Awards and funding
======
* __Secured funding for Homeward Bound program__ ($7000), 2022
    * Secured funding for the 2022-2023 women in STEMM leadership program
    * Awarded by Research School of Biology, Australian National University
* __Visualise Your Thesis runner-up__ ($500), 2019
    * Awarded by The Australian National University
* __RSB Director's Prize in Honours__ ($500), 2018
    * Awarded by the Director of the Research School of Biology at the Australian National University
* __Undergraduate travel award recipient__ ($405), 2018
    * Awarded by the Genetics Society of AustralAsia
* __Angus Nicholson Honours Scholarship in Science__ ($7500), 2018
    * Awarded by the College of Science, The Australian National University
* __CSIRO Summer Research Scholarship__ ($7500), 2018
    * Awarded by the National Research Collections of Australia
* __Lisa Brodribb Scholarship for Women in Engineering__ ($5000), 2016
    * Awarded by the College of Engineering and Computer Science, The Australian National University
* __New Columbo Plan Mobility Grant recipient__ ($3000), 2015
    * Awarded by Department of Foreign Affairs and Trade, Australian Government 
* __Lisa Brodribb Scholarship for Women in Engineering__ ($5000), 2014
    * Awarded by the College of Engineering and Computer Science, The Australian National University
