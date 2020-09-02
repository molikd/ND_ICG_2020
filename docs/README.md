## Introduction to Computational Genomics

- **Instructor**:
  - David Molik <dmolik@nd.edu>
- **GTA**:
  - Chissa Rivaldi <crivaldi@nd.edu>
- **Supervisor**:
  - Michael Pfrender <mpfrende@nd.edu>

#### Course Number
- BIOS 60132 
#### Resources
- [ND_ICG_2020](http://david.molik.co/ND_ICG_2020/)
- [Code of Conduct](https://docs.google.com/document/d/19WQbWr_TMDqStCyfhpA4BJZllcCEK4CMt3dxwWGkeUg)
- [Daily Feedback](https://docs.google.com/forms/d/1BACFIOS1Bd1DquipudU1TZk0Y9GreacObac6gPbg5tg)
#### General Description:

Massive amounts of data are being generated that biologists are now expected to analyze. In order to use this data to answer research questions, bioinformatics skills are necessary. The skills we will cover in this course center around manipulating big data, using and creating bioinformatic pipelines, and visualization of data. 

This class is aimed at people who may have some experience with computational biology, but still consider themselves beginners to the field. Computational biologists employ a vast array of methods and skills that often change with evolving technology. Our goal here is to focus on the most commonly used and widely applicable ones that can provide a solid foundation from where to grow. These skills include overall efficiency, building pipelines, and writing and reading code. After this course, students should be able to carry this knowledge to more specialized courses (e.g. algorithms, data structures, data visualization, GIS).

The weekly structure of the class will include both lecture material and hands-on coding experience, and the material will be reinforced with homework covering fundamental and practical topics, including code review, using code to solve problems, and a final project that will incorporate as much of the course material as possible. Feedback on course material and instruction will be incorporated as the semester progresses.

#### Learning Goals
After successful completion of this course students will be able to: Complete intermediate bioinformatics tasks, such as, manipulate big data files, implement common bioinformatic pipelines, and visualize data. Understand beginner computational biology algorithms, as such, course participants will reach a level of comfort that would allow them to take a CSE Data Structures or Algorithms course after successful completion. 

#### Grading Policies and Criteria

- Practicals: %35 - Practicals Are analysis and code problems that students have five days to complete. Practicals are assigned on Thursdays and due the night before class on Tuesdays, students will submit the practicals to a github repository on a branch named after their netid. Practicals can be retaken as many times as the student would like for a regrade. 
- Assignments: %20 - Each class, due before class starts a series of activities that will need to be completed. These include:
  - Readings handed during Tuesday class
  - Weekly status updates on Final Project
  - Other, mostly administrative activities (e.g. installing Julia)
- Course Participation: %5
- Final project: %40

#### Textbooks

- Practical reference material: Lauwens, Ben. 2019. Think Julia: How to Think Like a Computer Scientist. O'Reilly Media, Incorporated. 
*Two physical copies have been placed on reserve at Hesburgh, however, the entire book is free online: [ThinkJulia.jl](https://benlauwens.github.io/ThinkJulia.jl/latest/book.html)*
- Another reference material: https://docs.julialang.org/en/v1/ 
- Yet another: https://github.com/topics/julia 

*Optional reading: “Introduction to Computational Biology An Evolutionary Approach” ISBN: 978-3-7643-6700-8 - We will not be using this book in the class, but it is an excellent algorithmic level resource 

#### Office Hours
- David Molik: by appointment, remote
- Chissa Rivaldi: Thursdays 3-4pm (remain on class zoom) or by appointment, remote

#### Final Project
Over the course of semester you will be expected to design and complete a final project, the final project can be completed in Teams, however, the amount of work expected from the final project will be linear for additional team members (i.e. two people are expected to work on a project requiring two peoples amount of work). During the class we will have weekly homeworks ensuring the completion of the final project, however, it is a good idea to come into the class with an idea of data resources available to you. The final project will consist of an analysis designed to answer a novel question of that data, and a PLoS style write-up.

The Navari Family for Digital Scholarship (cds@nd.edu) the Biology Librarian (Parker Ladwig: ladwig.1@nd.edu) and the head of the Genomics and Bioinformatics Core (Mike Pfrender: mpfrende@nd.edu) are all excellent resources for genomics data resources. Genomics data is often closer than you realize, your advisor and senior labmates might be a great resource as well. 

#### Course Flow

There will be lecture on Tuesdays and Thursdays, this will be augmented with a Lab/Pracitcal and Status Report due Monday night, and a Reading and sometimes admin due Wednesday night. 

#### Schedule (see course website for updates) 
- Week One: Introduction of “Introduction to Computational Genomics” This week will mostly be review of the Unix Command Line, and Git, but will set the groundwork for the Final Project, which is the majority of course grade, how to submit assignments, and introduce the main scripting language of the course, Julia, a just-in-time compiled analytical language similar to that of R or Python. 
  - Day One, Introduction, Syllabus, CRC login, Unix, time allowing: Julia
  - Day Two, Git, Github Homework Submission
    - Reading due: [A Quick Introduction to Version Control with Git and GitHub](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668)
      - Reading question: What is git fork, what does it do? and why would you use it?
    - Admin due:
      - Decide on CRC or local computer for Julia and Bioinformatics. 
      - create a .vimrc for yourself
      - create a .bashrc for yourself
- Week Two: Assembly Part One - Introduction to a Assembly Pipeline, This week will demonstrate how to run assembly on the command line, specifically how to use a work queue manager, like SGE, which is in use at Notre Dame, to assemble reads into a de novo, we will then take our assembled genome and annotate it using an orthologs.
  - Day One: Scripting, Submission of Grid Computing, *de novo* Assembly
    - Practical due: 
      - [Practical Repo One](https://github.com/molikd/ND_ICG_2020_Practical_One)
        - In order to complete the practical and gain access to the repo you will need email Dave your github username (dmolik @ nd.edu)
    - Final project status update due:
      - Email Chissa three datasets that you could use for the final project
  - Day Two: Annotation Job Submission, Genome Graphs
    - Reading due: [Sequence assembly demystified](https://www.nature.com/articles/nrg3367)
      - Reading question: What is N50 in the context of the article, how is it used, and how is it misused? 
    - Admin due:
      - install and use Julia to print fizz buzz from one to twenty
        - [A blog article going over fizz buzz](http://blog.leahhanson.us/post/julia/julia-fizzbuzz.html), also the answer is on the page if you get stuck. 
- Week Three: Assembly Part Two - We now go deeper down the computational chain, looking under the hood of how an assembler works. This will focus again on creating assemblies, but specifically look at how to compute the same work in the Julia language. 
  - Day One - How an Assembler works, Genome Assembly in Julia 
    - Practical due:
      - [Practical Repo Two](https://github.com/molikd/ND_ICG_2020_Practical_Two)
    - Final project status update due:
      - Email Chissa and Dave an abstract of a final project plan.
  - Day Two - Julia Annotation, Genome Graphs
    - Reading due: [A beginner's guide to eukaryotic genome annotation](https://www.nature.com/articles/nrg3174)
      - What is the difference between *Ab initio* gene prediction and Evidence based gene prediction? 
    - Admin due:
      - Put together final project group and email Dave & Chissa
- Week Four: Assembly Part Three  - We will continue our descent down the computational chain, now we go still deeper, looking at the underlying algorithms that make assembly possible. 
  - Day One - String Comparisons, Distances
    - Practical due:
      - [Practical Repo Three](https://github.com/molikd/ND_ICG_2020_Practical_Three)
    - Final project status update due:
      - make Chissa and Dave collaborators on a repo with an extended project abstract with your project team covering:
        - AS a README.md in a project repo add:
          - Team
          - New Code Required 
          - Activities Required 
          - Data Used
          - Question Asked
  - Day Two - Smith-Waterman, Other Assembly Methods
    - Reading Due: [Basic Local Alignment Search Tool](https://www.nature.com/scitable/topicpage/basic-local-alignment-search-tool-blast-29096/) [smithwaterman.jl](https://github.com/mattjones315/LocalAlignment.jl/blob/master/src/algorithms/smithwaterman.jl)
      - Why are alignment algorithms faster than looping through both sequences (what makes them faster?) 
    - Admin due: Setup time to talk to Chissa/Dave about Final project. 
- Week Five: SNPs Part One - Back up for air! We’ve learned about assemblies, time for something different, we’ll be looking at Single Nucleotide Polymorphisms, this week will focus on what a SNP pipeline looks like, and how to submit Grid Computing jobs for a SNP pipeline. 
  - Day One:  Read Quality/Trimming Filtering
    - Pratical Due:
      - [Pratical Repo Four](https://github.com/molikd/ND_ICG_2020_Practical_Four)
    - Final project status update due:
      - Please create a draft of your code for your final project, and send an update to Dave and Chissa (we will gove over what this means in class)
  - Day Two: Variant Calling
- Week Six: SNPs Part Two, We've doen SNP calling on the command line, now we are going to turn around, and write our own pipeline in Julia
  - Day One: Julia version of building a SNP, Read Quality/Trimming Filtering
  - Day Two: Julia version of Variant Calling, 
- Week Seven: SNPs Part Three, What's under the hood of SNP calling?
  - Day One: Frequency Estimation 
  - Day Two: Key - Value stores 
- Week Eight: Differential Expression Part One, Say I want to run a differential expression analysis analysis on some RNAseq data, how do I do that?
  - Day One - Creating the RNAseq expression table
  - Day Two - Visualizing RNAseq expression
- Week Nine: Differential Expression Part Two, Now that we know how to run a differential expression analysis, lets look deeper and do it in Julia. 
  - Day One - Julia RNAseq expression table
  - Day Two - Julia RNAseq Visualization
- Week Ten: Differential Expression Part Three, What is this clustering thing anyway?
  - Day One - Ordination
  - Day Two - Clustering 
- Week Eleven: Population Genomics, I want to look at populations, what are some ways to do that?
  - Day One: Post Assembly - Calculating Genotypes
  - Day Two: Visualization of Genotypes
- Week Twelve: Population Genomics, More populations. 
  - Day One - Julia Fitness Landscapes
  - Day Two - Running Fitness Models in Julia
- Week Thirteen: Population Genomics, Still more Populations. 
  - Day One - Time Zones, Coordinate Transformations 
  - Day Two - Finding local optima 
- Week Fourteen: Final Project Presentations


[Collection of Class notes on HackMD](https://hackmd.io/@NFpEogXySTuWExLvDQQHig/H1JqRVhzv)
