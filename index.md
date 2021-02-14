# Ellie Lockhart, Software & Data Developer
## Personal Website & Portfolio

Welcome to the personal website & portfolio of Ellie Lockhart, software & data developer. Ever since I got my first personal computer (a Mac SE older than I was!) at the age of nine, I've wanted to work with software & data. Data runs in my family - my mother was the author of a textbook on the nearly-forgotten scientific programming language FORTH, & I was always encouraged in my interests. As an adult, I went into research professionally and spent seven years working on data research as an employee of the states of, first, Texas, and then, New Jersey. Today I work as a freelance/independent data & software developer, and am seeking to expand my professional horizons.

### Contact Information
You can reach me at elliedev at protonmail.com. 

### Professional Interests
I wrote my first line of BASIC at the age of nine, on the aforementioned Mac SE, and my first line of Python at 10 when involved in a hobby project involving a long-forgotten adventure game development engine. Picking up new development skills, whether that means new programming languages, new database architectures, or entirely new modes of software development like Agile and microservices, is one of my passions. I use technology to accomplish goals, whether those goals are working with a team, completing academic research & publication, or developing my own passion project. The things I am particularly enthusiastic about working on include:

- data pipelines that serve deep analysis of data, including machine learning;
- machine learning itself, *especially* natural language processing & developing predictive models of online behavior;
- making data accessible, whether that is through traditional dashboards, "report" websites resembling white papers, slideshows, or full-on web applications that allow stakeholders to query and conduct their own data exploration;
- finding novel but effective ways to bridge the front-end & back-end of applications - I like to find ways to be creative with APIs while still meeting the goals of the project;
- finding effective ways to deploy applications in a cost-effective manner - in other words, cost-aware but also security- and quality-aware DevOps;
- accessibility! It is extremely important to me that projects I personally design meet a11y standards to the greatest extent possible so that everyone can make use of the work that I do.

While these are my dominant professional interests, I also code and work with data in my spare time; many of my hobby projects directly support my professional efforts. For instance:

- I work with single-board computers, and am currently utilizing an nVidia Jetson developer's kit to conduct in-depth natural language processing for my professional projects, while also exploring the other capabilities of the board;
- I have an interest in exploring new angles on independent game development, whether that means harnessing industry-standard game engines to get around the fact that, frankly, and to my deep frustration, I can't make my own game art, or trying to use new languages like Golang and Rust to develop open source frameworks to democratize game development.

### Professional Tools 
As I mention above, it's important to me that my tools serve the project I'm working on, and I pick up new tools quickly. A brief, non-exhaustive list of the coding languages, environments, and frameworks that I've used to solve the various challenges I mention above:

- Python, including all major data science libraries, the Jupyter ecosystem, & some experience with Django;
- C++;
- Java (and Groovy & Scala, especially Scala!);
- Swift (great for Apple ecosystem app development, but I actually love it for data processing & look forward to the day when it can better integrate with systems such as Apache Spark);
- TypeScript (my default) & JavaScript (& associated frameworks like Express.js and Vue.js);
- .NET (C# and F#, which I think is going to be a big thing soon) and ASP.NET, especially API-focused systems;
- GoLang (great for simple APIs, and a lot of other things that I'm looking forward to exploring);
- Rust (still very much a novice here, but I'm hoping to be able to contribute to hobby game development FOSS projects and make Rust even more viable for games, which is an area where it should excel);
- Natural language processing with Gensim, spaCy, PySpark, and of course basic work with NLTK;
- All three major cloud providers (AWS, Azure, and GCP), and also IBM Cloud;
- Databases - SQL, NoSQL & graph (Neo4j, also Amazon Neptune)
- Virtualization, virtual machines, and systems administration (I administered a hobby website running on virtual machines for six years, with a long record of uptime);
- Docker, Docker Compose, and Kubernetes;
- a11y accessibility standards;
- systems administration on *nix and Windows

My projects use the technologies that are most helpful, but I make sure to familiarize myself with the dominant industry ecosystems. For instance, while I am unable to subscribe to DataBricks, I've used its community edition for data processing, and have done similar work with Azure Data Factory, in order to keep myself up to date with where the field is currently at. Above all, though, I select technologies that are needed for the task at hand. Right now, that means that my predominant programming languages are Python, Scala, .NET, and TypeScript, and PostgreSQL or whichever document database fits the environment I'm working in. I also like to work with JSON files through Apache Spark as a method of data exploration.

### Current Projects
While I'm seeking to advance my career in the tech industry, I do not think that I do anyone any favors by simply rebuilding a to-do list app recruiters have seen a thousand times. Instead, I work on freelance and independent projects that I or those I am working with belief have a chance to be truly useful. This means that some of my projects are complete, but many are in-progress or at very early alpha stages; several I have done, then changed methodology on and started over. I believe that this allows me to ultimately contribute more and better show my experience and what I can do for a company.

Current projects include:
**Datasets**
- CDC Mask Data & Amazon masks advertising themselves in association with the US FDA. [(GitHub)](https://github.com/EllieLockhart/US-FDA-EUA-Masks---Marketing) [(Kaggle)](https://www.kaggle.com/ellielockhart/us-fda-eua-masks-amazon-marketing)
  
    - This project came from discovering that some medical-grade masks I had purchased for the safety of my family were not in fact in any way inspected by the US FDA, and that they were being misleadingly advertised for sale. This dataset includes a list of all *actual* companies authorized to sell masks with medical purpose in the US, and a detailed Amazon search with product information for all "FDA" keyword masks, allowing statistics to be collected about the extent to which masks that are being implied to be medical-grade have in fact been approved. 
    - This project has effectively been **completed**.
    
- Media Viewpoints: Controversial Media Reviews of the 2010s [(GitHub)](https://github.com/EllieLockhart/Metacritic---Rotten-Tomatoes-Controversial-Reviews-Dataset) [(Kaggle)](https://www.kaggle.com/ellielockhart/metacritic-rotten-tomatoes-controversial-reviews)
    
    - This project stems from my personal interest in popular culture and my academic history of researching harassment and fraud related to popular culture. The goal is to examine particularly controversial sets of product reviews for films and video games released during the previous decade, to compare them using NLP techniques with less controversial but equally well-known media products, and to hopefully derive an algorithm which would use fraud detection techniques to predict the likelihood that a given product review is a result of a coordinated/concerted campaign that may involve multiple reviewers, reviews by those who are not actually customers, and so on. This project could be directly applicable to companies whose products' success depends on reviews in adjusting apparent review scores to account for online campaigns, and could have broader applications to the study of online conversation. 
    - The dataset, linked above, **is complete**, including basic NLP used to filter reviews based on language to create a consistent set of reviews for further analysis.
    - The NLP work is ongoing in Python and Scala (with some help from Redis caching) in some of the GitHub branches; I'm also doing some basic work in Azure Data Factory & with DataBricks.

- Untitled .NET Social Content Sharing Project (currently in private repositories only)
    
    - Many social sites, such as Medium and Twitter, utilize various kinds of graph APIs to link users to content they may be interested in. I'm interested in democractizing this content by creating a web application that can be repurposed for various kinds of content sharing - blogs, similar, as mentioned above, to Medium, but also original fiction or even various types of non-text content - and linking users (who register voluntarily) to a recommendation algorithm. I'm currently implementing this project using .NET based web frameworks and industry standard database technologies - although I initially considered using Neo4j, I find that it would be unlikely to scale should this project find potential success.

### My Open Source Contributions
I am currently scaling up my open source contributions; most of my recorded commits on GitHub to projects I do not administer are documentation-related. I hope to change this, possibly through work on niche areas such as database drivers (perhaps implementing better support for Neo4j in .NET) and nVidia Jetson related embedded software. The open source community is important to me.

## A Brief Career Outline
(this is not a resume, you can find that [here](Lockhart-resume.docx))

- Graduate Research & Teaching Assistant, Texas A&M University, 2010-2015

    - Worked on data projects, including streaming data, and learned R, additional data techniques with Python, and how to work with MySQL/MariaDB. I also administered a hobby website with approximately 40 users *per* day.

- Assistant Professor, Rowan University, 2015-2018

    - Continued my research, published two peer reviewed research papers, and advocated for greater digital involvement in the classroom. Mastered data analysis skills, but decided to leave to pursue a career in corporate software development in order to have a greater impact on the world.

- Now

    - Continuing to research and study data; I've mastered industry standard frameworks that weren't common in academia and been able to freelance and pursue projects of deep importance (see above). I continue to pursue publishing, in addition to development work.

### My Publications
- [Interviewed by Noah Berlatsky for The Observer](https://observer.com/2020/09/lgbt-film-representation-data-ellie-lockhart/) about some low-level data collection work I did regarding diversity in film. *September 2020*
- [Peer reviewed study on science's interface with the communication field](https://www.tandfonline.com/doi/abs/10.1080/00028533.2014.11821824?journalCode=rafa20) published in *Argumentation & Advocacy* (paywall). *February 2016*
- [Peer reviewed ethical study on discourse and content warnings](https://nca.tandfonline.com/doi/abs/10.1080/21689725.2016.1232623) published in *First Amendment Studies*, a publication of the National Communication Association. *July 2016*
- [Data-driven doctoral dissertation on nerd culture](http://oaktrust.library.tamu.edu/handle/1969.1/155516?show=full), distributed by Texas A&M University libraries/OakTrust, constructed in part with data gathered from Twitter streams, and deeply entwined with online culture and technology.

### Coding Metrics
You can check out my [GitHub graph](https://github.com/EllieLockhart?tab=overview) on my GitHub profile, and can view some (sadly, not all) of my coding activity tracked on my [WakaTime freelancing time tracking profile](https://wakatime.com/@EllieNotTifa).
