---
layout: page
title: Research Statement
section: CV
top: Chathura Gunasekara
---

Research Statement for Chathura Gunasekara
==================

Introduction
------------

  The rapid increase of genotype and phenotype data have created a need for efficient technologies in moving, storing, analysing and representing them in meaningfull way. Specially with the advent of whole genome approach creates data and we need store and analyse them with computatioanl framworks. My research interest have been revolving around developing computational infrastructure in terms of algorithmic developmetn, web application development and apply and devlop machine learning algorithms. The web applications were developed under the umbrella of plant biology and each web application used different type of data available to the plant biologist. Before starting my PhD, while in Sri Lanka, I worked on a research project to integrate sensor information from coastal transponders around the country to display and visualized on a centalized map. I have used GoogleMap api and other open source GIS applications such as OpenCPN to display realtime sensor information gathered over a wide area network.
  

Description of Research projects
---------------------------

### Web-based Poplar gene expression data analysis pipeline[^1]

We developed and published a web application called Pop’s Pipes to facilitate preprocessing and analysis of substantial poplar gene expression data. The input data can be spatio- temporal microarray and RNA-seq data from comparable tissues, time points, or treatment-vs-control conditions.This web-based application of Pop’s Pipes includes five software pipelines for ana- lyzing both microarray and RNA-seq data: (1) differen- tially expressed gene (DEG) pipeline for the identification of DEGs for each comparison. A comparison, hereafter, is defined as two groups of gene expression data sets from two comparable tissues, two time points, or two experi- mental conditions; (2) gene ontology (GO) pipeline for performing GO enrichment analysis with the DEGs from each comparison as input; (3) domain pipeline for identi- fying enriched protein domains in the DEGs; (4) pathway pipeline for identifying the enriched metabolic pathways using all DEGs; and (5) GO tree construction pipeline for building any three types of hierarchical gene ontology trees—biological processes, molecular function, and cel- lulose component.


### ExactSearch: A Fast Motif Search tool[^2]

In this study, we developed a web portal that enables plant molecular biologists to search for DNA motifs especially degenerate ones in custom sequences or the flanking regions of all genes in the 50 plant species whose genomes have been sequenced. A web tool like this is demanded to meet a variety of needs of plant biologists for identifying the potential gene regulatory relationships. We implemented a suffix tree algorithm to accelerate the searching process of a group of motifs in a multitude of target genes. The motifs to be searched can be in the degenerate bases in addition to adenine (A), cytosine (C), guanine (G), and thymine (T). The target sequences to be searched can be custom sequences or the selected proximal gene sequences from any one of the 50 sequenced plant species. The web portal also contains the functionality to facilitate the search of motifs that are represented by position probability matrix in above-mentioned species. Currently, the algorithm can accomplish an exhaust search of 100 motifs in 35,000 target sequences of 2 kb long in 4.2 min. However, the runtime may change in the future depending on the space availability, number of running jobs, network traffic, data loading, and output packing and delivery through electronic mailing.

### Web application for Targeting Small RNAs for Destruction in Crops by Short Tandem Target Mimic (STTM)[^3]

Develop digital management of resources through advanced web database, application, and service for materials transfer and distribution. 

We will develop a web-based tool termed designSTTM to automate STTM vector design. For each specific STTM, designSTTM will automatically store results into the database, and a sketch of a plasmid construct will be plotted with all boundaries between different fragments and lengths of all fragments being clearly labeled. When a design process is completed, an annotated report detailing the steps of STTM construction will be generated. Users can print the sketch of each plasmid vector with the construction protocol. 

We will also develop a web application, materialSTTM, to support the distribution of STTM constructs and transgenic lines. This web application will display the availability of both STTM constructs and transgenic crops lines in which the targeted miRNAs are knocked down. materialSTTM serves as a venue through which homozygous transgenic seeds of each STTM transgene can be distributed to the research community. The web-application of materialSTTM will provide detailed phenotypic description of all homozygous transgenic lines with the images from various developmental stages. 

Finally, we will develop a genome browser for RNA-seq and Ribo-seq of wild-type and STTM mutants. This browser will provide information on global translation status and miRNA-directed translation inhibition, which is currently lacking in plants. We will make them available to the research community through our web portal. 

Technological approaches for the above objective include the standard Linux server, the open-source database server MySQL and the Apache web server. MySQL will be used as the back-end database and Apache will be integrated to create HTML pages to deliver requested web contents back to the users’ browsers. The web application will use PHP for server-side business logic, HTML for content presentation, cascading style sheets (CSS) for formatting, and JavaScript for dynamic client-side behavior. 

### TF - mining Pipelines for gene expression data
Background:  Although molecular biologists often need to learn which transcription factors (TFs) control a biological pathway, process or complex trait, there are few tools available to aid them to accomplish such a task. 

Result:  We developed two software pipelines for identifying transcription factors controlling a biological pathway, process or complex trait from high-throughput gene expression data previously.  However, both software pipelines need to be properly installed in a Unix environment before they can be used for TF mining. We have implemented a web application of both software pipelines to facilitate their utilization. TF-Cluster is capable of identifying groups of functionally coordinated TFs through coordination network construction and decomposition; each group contains TFs that are coordinated to regulate a biological pathway, process or complex trait. The other pipeline, TF-Finder, uses adaptive sparse canonical correlation analysis to recognize a group of TFs involved in a biological process using a set of bait genes known to participate in this process.

Conclusion:  Two web portals were developed to facilitate utilization of TF-Cluster and TF-Finder software pipelines for TF mining from high throughput gene expression data.  We have also expended the number of methods used for building coordination networks in TF-Cluster pipeline.  The two web-based software pipelines are instrumental to molecular biologists for TF recognition

### TF - Miner partial least squares based Gene selection and Gene regulatory network inference




Future Research
------------------------

Development of bioinformatics web based applications is utmost importance because the complexy and computatioan demand a typical bioinformatics data analsys takes.



Biology/Bioinformatics experience is essential as well as previous experience with web/database development. The applicant should have strong knowledge of Java and JavaScript (jQuery). Experience with Linux/Unix, scripting languages (Python), and relational databases.

https://wiki.galaxyproject.org/Events/GCC2015?action=AttachFile&do=get&target=S6_T4_EmilyGrau_Galaxy2015.pdf
http://gmod.org/wiki/Tripal
(http://www.cyverse.org/).

The successful candidate will work as part of a small interdisciplinary team of bioinformaticians and data curators. Tasks will include development of the existing database, developing connections to collaborating databases, improving the user experience (interface development) and implementation of novel analysis and visualization tools for comparative genomics. The Postdoctoral Scholar will be provided with training opportunities and will attend conferences to present/train users on these new tools. In addition, publications on innovative software solutions will result from this work.

The Plant Computational Genomics laboratory at University of Connecticut (Storrs, CT) has an opening for a database and software developer position as part of a collaborative project involving researchers from around the world. This person will take a lead role in the continued development of the TreeGenes genomics database and the CartograTree application (treegenesdb.org and cartogratree.org). These web-based resources serve vast amounts of genomic, phenotypic, and environmental data to our diverse user community. In specific, the CartograTree application provides a portal for association genetics studies of georeferenced forest trees through the implementation of web services and high performance computing resources available through the iPlant/Cyverse project (http://www.cyverse.org/). In addition, we are committed to developing mechanisms for data sharing among partner databases through Galaxy modules, the Tripal platform (http://www.tripal.info/), the GMOD project, and custom analysis/visualization platforms.


I want to be a researcher to take part of the computational revolution taking part in the biological research. 
  Internet related technology space is developing in very rapid phase and life science computational infrastructure should keep up with those Developments. A limitation I realized in computational research is, lots of outstanding algorithms and methods are locked away in research papers, scripts archived in zip files or github repositories. For some researchers to use those findings, they have to install, configure and setup the methodology by them self. This has been a limiting factors because it takes far too much time and knowledge and resourses might not available for everyone. Amazon web services somewhat address these issues, but still the amount of work to be done to get something up and running is very large. The obvious next step has been taken by cyVerse.org is the step in right direction. Implementation of the algorithms can be accesible as a cyVerse app, where uses can make use of the high performance computing resources without the overhead of managing them. 
  With the deluge of biological data, computational infrastruture to store, share, and analyze data is just as important as physical infrastucture such as laboratories, DNA sequencing machines, greenhouses that make it possible for wet lab biologist to collect data. The development of computing in the cloud will empower the life science researchers in the use of high performance computing and large data resources.
  Content management systems (CMS) used to be light waight web pages that host several gigabytes of content, now have to deals with data the size of hundrads terabytes or petabytes. With powerfull web technologies such as Drupal have make it possible to manage this type of content in the web, giving users the accessibility of managing large amount of content and analyse in a high performance clound infrasturure. The Tripal is specially customized to use as a front end for biological data management. This can be further customized for each researchers data type and analsys requirements. So building custom interfaces and visualizations to show the analsys results is needed to be done.ability to search and edit content, detail pages for different types of content, customizable page layouts, and so on--to provide users with an intuitive, flexible interface to a database. 
  
The  
   
  Computatioanl infrastructure development for scientific analysis. Amazon web servises for life science. With batteries included. develop consoles to interact with the computatiaonl infractructure for each uses specific need.Tasks will include development of the existing database, developing connections to collaborating databases, improving the user experience (interface development) and implementation of novel analysis and visualization tools for comparative genomics. The Postdoctoral Scholar will be provided with training opportunities and will attend conferences to present/train users on these new tools. In addition, publications on innovative software solutions will result from this work. Training biologist on computatioanl infracsture. conduct workshops ect. Using cyberinfrastructure, teams of researchers can attempt to answer questions that previously were unapproachable because the computational requirements were too large, too complex, or simply unknown to some researchers.

CyVerse cyberinfrastructure includes:

A data storage facility
An interactive, web-based, analytical platform
Cloud infrastructure to use remote servers for computation, analysis, and storage
Web authentication and security services
Support for scaling computational algorithms to run on large, high-speed computers
Education and training in how to use cyberinfrastructure
People with expertise in all of the above

 bottleneck in biological research, namely the inability of traditional computing technology to meet computational challenges and support the cross-discipline collaboration needed to solve today’s most pressing questions in plant sciences.
 
Answering the need of an era of data science, CyVerse makes broadly applicable computational resources available across the life sciences.

tackle questions surrounding biological data analysis, data integration, and data sharing.[^1]


References
----------

[^1]: Li, X, C. Gunasekara, Y. Guo, H. Zhang, L. Lei, S. Tunlaya-Anukit , V. Busov, V. Chiang, and H. Wei. 2014. Pop’s Pipes : poplar gene expression data analysis pipelines (http://sys.bio.mtu.edu). Tree Genetics & Genome.

[^2]: Gunasekara, C. A. Subramanian, Avvari, R. K., B. Li, Chen, S. and H. Wei. 2016. ExactSearch: A web-based plant motif search tool. Plant Methods 12:26 10.1186/s13007-016-0126-6 (http://sys.bio.mtu.edu/motif)

[^3]: https://blossom.ffr.mtu.edu





