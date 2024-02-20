# paragraph showing interest

```
You are an essay writer who will help me to write a paragraph to show that I am interest in a job opening.
VERY IMPORTANTLY You will follow a step by step process given by me to write the paragraph.
VERY IMPORTANTLY you will format the output following a template given by me.
I will provide you with my resume, and the job description. They will all be delimited with triple quotes.
Only use the information in the resume that is relavent to the position.
Important to make sure to limit the word count to under 300 words.

Here is the step by step guide delimited by triple quotes. Again, it is critical that you adhere to the following step by step guide:

"""
Determine what is the industry for the role. Choose from the following catagory: [IT/software/data, product/project manager, financial technology and services, consulting, auto and manufactoring, other].

If it is an IT/software/data sector job use the following template delimited by triple astris

***
< 1 sentence to show I understand the role and its requirements >
< 1-2 sentence to highlight my specific technical skills and how they fit the requirements, relate each technocal skill to any pass project or experience that envolve it>
< 1 sentence to show that I understand and is excited about the company and their mission/goals, be specific>
< 1 sentence to show why I am the best person for the job provide evidence by mentioning what I have done specifically in the pass>
***


If it is a product/project manager position use the following template delimited by triple astris

***
< indicate which catagory did you classify this position to>
< 1 sentence to show I understand the role and its requirements >
< 1-2 sentence to highlight my business skills and how they fit the requirements, highlight my experience as Project Manager>
< 1 sentence to show that I understand and is excited about the company and their mission/goals>
< 1 sentence to show why I am the best person for the job >
***

If it is a financial technology and services position use the following template delimited by triple astris

***
< indicate which catagory did you classify this position to>
< 1 sentence to show I understand the role and its requirements >
< 1 sentence to highlight my technical skills and how they fit the requirements, highlight any pass project or experience that envolve such skills>
< 1 sentence to highlight my track record of business management combined with engineering background that expresses my determination to enter the financial technology sector>
< 1 sentence to show that I understand and is excited about the company and their mission/goals>
< 1 sentence to show why I am the best person for the job >
***

If it is a consulting position use the following template delimited by triple astris

***
< indicate which catagory did you classify this position to>
< 1 sentence to show I understand the role and its requirements >
< 1 sentence to highlight my non-technical skills and how they fit the requirements, highlight any pass project or experience that envolve such skills>
< 1 sentence to highlight my track record of business management combined with engineering background that expresses my determination to enter the financial technology sector>
< 1 sentence to show that I understand and is excited about the company and their mission/goals>
< 1 sentence to show why I am the best person for the job >
***

If it falls into the "other" category, use the following template delimited with triple astris:

*** 
write this paragraph as deeper insight into what a recruiter can't read on your resume like the research you've done on the role and their company.
​
Use 3-5 sentences to show the recruiters you understand:
The role and its requirements
Your skills and how they fit the requirements
The company and their mission/goals
Your excitement about the opportunity 
Why you're the best person for the job 

Use 2 sentences to show recruiters that you're interested in that specific position with that specific company. Highlight your strengths in relation to the role description. Talk about why the company is a great fit for you, why the company should interview YOU.
***


"""

Here is the output formating template delimited by triple quotes. Again, it is critical that you adhere to the following output format:

"""
<job position>

<which industry did you determine this job to be>

<company>

<paragraph showing interest>

<word count for the paragraph>
"""





resume:

"""

EDUCATION
---------
University of Florida
Master of Engineering, Computer Engineering, GPA 3.59 2021.08-2023.12

University of Washington
Bachelor of Science Molecular Biology. Major GPA 3.55 2015.09-2019.12



EXPERIENCE
----------
Tata Technologies Detroit MI
Application Developer Oct 2023 – Present
• Contribute to the development of a back-end Python software infrastructure for parallel HPC job submission
for 20+ CFD applications.
• Responsible for migrating the application from the in-house HPC PBS cluster to AWS EC2 instances with
FSx shared file system. Testing comparative performance of applications on HPC and AWS cloud.

Global Technology Inc. Sterling Heights, MI
Software Engineer Intern June 2023 – August 2023
• Independently developed and maintained an in-house, full-stack web application using React.js for front-
end, Python Flask for back-end, SQL for database, and RESTful API for Plex systems integration. De-
ployed the application with Docker on AWS cloud infrastructure, facilitating real-time data/document
sharing and project management. Projecting to save $10,000 in software subscription costs yearly.

Jinzhong(U.S.A) Auto Parts Manufacturing Co. LTD Sterling heights, MI
Project Manager July 2019 – Present
• Represent and oversee the company’s North American operations, including price negotiation, design,
manufacturing, and the warranty process for new ornaments tailored for North American customers such as
Tesla, Ford, GM, and Rivian.
• Managed cross-functional teams comprising project managers, design engineers, tooling engineers,
and suppliers to achieve stringent project timelines and budget constraints set by North American OEMs
and Tier One companies.
• Conducted thorough reviews of Computer-Aided Design (CAD) 3-D models, drawings, Finite Element Anal-
ysis (FEA), mold flow analysis, and stack-up analyses to furnish precise and timely information to clients.
• Delivered components for Ford’s upcoming electric SUV project ahead of schedule and within budget. This
achievement garnered client appreciation, leading to the award of their subsequent program, slated to replace
the current one.
• Draft the Failure Mode and Effects Analysys (FMEAs) for new ornaments for manufacturing in the US.
• Actively participated in weekly meetings with shareholders and financial advisors to determine the company’s
financial direction.
• Responsible for the digitization of the production process. Introduced a fully automated EDI system for
production management.Reduce the labor needed for inventory and project management by 50%.

University of Washington School of Medicine Seattle, WA
Research Software Developer 2018.03-2021.07
• Responsible for creating and implementing algorithms, data structure, statistical analyses, and visualizations
to identify and characterize sites of disease relevance within human DNA as part of the Human Pangenome
Reference Consortium, the Human Genome Structural Variation Consortium, and the Simons Foun-
dation Autism Research Initiative, directly contributing to projects with a combined budget of $15M/year.
• Implemented computationally expensive string manipulations in C/C++, I/O heavy and visualization logic
with Python using Matplotlib and open-source data visualization tool Vega, and Bash to coordinate multiple
programs and data between them.
• Created novel data partitioning algorithm and implement advanced data structure to segment data sent to
snakemake for DAG based workflow microservice orchestration with jobs distributed using Oracle Grid
Engine.
• Computations executed on University of Washington’s high-performance computing cluster.
• Reduced processing time on legacy data pipeline by 90% via refactoring and the use of open source tools
such as Whatshap in Python and Bash
• Automated legacy pipeline so that no human oversight was necessary during processing.
• Legacy and new data processing pipelines regularly ingested over 2TB of data per process, however the
infrastructure had relatively limitless horizontal scaling (considering the upper bound on available data)
• Implemented statistical analyses (e.g. Bayesian phylogenetic inference) for output of data pipelines based on
laboratory spec with Python, C, and Bash.
• Created novel genomic application of prefix doubling algorithm to output a dot-plot visualization
• All data and visualizations, and software published in Nature, Science, PNAS, and other scientific journals.
Total citation over 250.

SKILLS
------
• Programming - Proficient with 3+ years experience: C/C++, Python/Flask, Bash script, SQL, Unix/Linux
Adequate: JAVA, React.js
• Environment and frameworks - Git, AWS, Docker, Windows, Linux
• Tools - Excel, PowerPoint, Microsoft Project
• Language Skills - Fluent in English, Chinese, basic German

PUBLICATION (OVER 250 CITATIONS)
--------------------------------
• A high-quality bonobo genome refines the analysis of hominid evolution. Nature.
• Segmental duplications and their variation in a complete human genome. Science.
• Recurrent inversion toggling and great ape genome evolution. Nature genetics.
• Human-specific tandem repeat expansion and differential gene expression during.... PNAS.
• Familial long-read sequencing increases yield of de novo mutations. Am J Hum Genet.

SELECTIVE PROJECTS
------------------
• RideShare
A p2p ride share website. Responsible for designing and implementing UI with React.js. Implemented
generic search engine, register, and login/logout back-end RESTful API using Golang.

• Navigator
A tourist destination recommendation service built with Python Flask back-end, which is responsible for
interacting with public API and the curation of data. Winner of the 2023 Swamphack

• TargetPhase
Fully designed and implemented Linux high-throughput distributed pipeline for targeted human genome
analyses. Python is used for IO, job distribution logic onto the Oracle Grid Engine, statistical analysis, and
visualization. Results published on Nature.

• Dottedpython
Fully designed and implemented Linux high-throughput distributed pipeline for dot matrix analysis using suf-
fix array data structure. Capable of distribution onto the high-performance cluster with Snakemake. Python is
used for IO, job distribution logic, statistical analysis, and visualization. C++ is used for string manipulation
algorithm. Results published in Science and PNAS.

• Distribution Suit
An Erlang implementation of a high-performance distributed application that includes a bitcoin mining ap-
plication, the Gossip Algorithm, the Chord - P2P System, and a Twitter-like chat engine. The front-end is
implemented with JavaScript, and the back-end is implemented with Erlang.
"""


Job description:


"""
Description

Here at Appian, our core values of Respect, Work to Impact, Ambition, and Constructive Dissent & Resolution define who we are. In short, this means we constantly seek to understand the best for our customers, we go beyond completion in our work, we strive for excellence with intensity, and we embrace candid communication. These values guide our actions and shape our culture every day. When you join Appian, you'll be part of a passionate team that's dedicated to accomplishing hard things.

Joining Appian CIO will provide you with the opportunity to learn in an environment that values cross-functional collaboration and is committed to personal and professional growth. We want to revolutionize the way people work, and in doing so, we develop the Appian platform to be simple so our customers can thrive. 

 

Our Solution Engineering team is obsessed with serving our customers. We are looking for an Associate Solution Engineer, a technical “Jack/Jill of All Trades” that loves figuring out “how things work.” As an Associate Solution Engineer, you’ll become an expert on the inner workings of the Appian platform and gain full-stack experience that will be valuable for any technical career. You’ll have the opportunity to work with every layer of the Appian platform; from data analysis to creative problem solving and you'll tackle the most challenging technical problems while mitigating all of our customers’ concerns.

 

To be successful in this role, you need:

To be excellent at problem solving and find creative solutions to some of our customer’s most complex technical concerns
To provide exceptional, world-class support (verbal/written) to our customers and our highest stakeholders around the globe 
To tackle technical challenges and communicate your work across a variety of departments
To have a strong interest in software development (but not wanting to focus on coding all day)
To have the desire to work closely with our customers to help lead continual improvement in the availability, performance, functionality and security of our platform
To have an interest in data analytics
To have an interest or experience in programming/scripting languages(e.g. Java, Perl, Ruby, C#, PHP)
To have an interest in or experience with RDBMS platforms (e.g. MySql, Oracle, SQL Server)
To have an interest in or experience with systems administration (e.g. Linux, Windows)


Some of the tools and resources we will equip you with include:

We’ll immerse you into our community rooted in respect starting on day one. Our community is strong and growing! Our affinity groups are a great place to start connecting with peers from across the globe.
Appian offers a wide variety of growth and development opportunities such as: our in-house Appian MBA program for new managers, Appian University which is a full library of over 3,000 LinkedIn Learning and Udemy courses, Presentation Skills training, and tuition reimbursement for those seeking to further their education.


Basic Qualifications:

Bachelor's degree in any an Engineering discipline, Information Technology, or similar degree program 
 Flexibility to provide after business hours support (rotation every 10-15 weeks)


About Appian

Appian is a software company that automates business processes. The Appian AI-Powered Process Platform includes everything you need to design, automate, and optimize even the most complex processes, from start to finish. The world's most innovative organizations trust Appian to improve their workflows, unify data, and optimize operations—resulting in better growth and superior customer experiences. For more information, visit appian.com. [Nasdaq: APPN]

 

Follow Appian: Twitter, LinkedIn.

 

Appian Corporation is an equal opportunity/affirmative action employer. All qualified applicants will receive consideration for employment without regard to sex, gender identity, sexual orientation, race, color, religion, national origin, disability, protected Veteran status, age, or any other characteristic protected by law. Further, Appian will not discriminate against applicants for inquiring about, discussing or disclosing their pay or, in certain circumstances, the pay of their co‐worker, Pay Transparency Nondiscrimination.   

 

If you need a reasonable accommodation for any part of the employment process, please contact us by email at ReasonableAccommodations@appian.com and let us know the nature of your request and your contact information. Requests for accommodation will be considered on a case-by-case basis. Please note that only inquiries concerning a request for reasonable accommodation will be responded to from this email address.
"""



```
