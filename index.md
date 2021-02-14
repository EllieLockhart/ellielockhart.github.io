# Ellie Lockhart, Software & Data Developer
## Personal Website & Portfolio

Welcome to the personal website & portfolio of Ellie Lockhart, software & data developer. Ever since I got my first personal computer (a Mac SE older than I was!) at the age of nine, I've wanted to work with software & data. Data runs in my family - my mother was the author of a textbook on the nearly-forgotten scientific programming language FORTH, & I was always encouraged in my interests. As an adult, I went into research professionally and spent seven years working on data research as an employee of the states of, first, Texas, and then, New Jersey. Today I work as a freelance/independent data & software developer, and am seeking to expand my professional horizons.

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
- CDC Mask Data & Amazon masks advertising themselves in association with the US FDA. (GitHub) (Kaggle)
  
    - This project came from discovering that some medical-grade masks I had purchased for the safety of my family were not in fact in any way inspected by the US FDA, and that they were being misleadingly advertised for sale. This dataset includes a list of all *actual* companies authorized to sell masks with medical purpose in the US, and a detailed Amazon search with product information for all "FDA" keyword masks, allowing statistics to be collected about the extent to which masks that are being implied to be medical-grade have in fact been approved. 
    - This project has effectively been **completed**.
    
- Media Viewpoints: Controversial Media Reviews of the 2010s (GitHub) (Kaggle)
    
    - This project stems from my personal interest in popular culture and my academic history of researching harassment and fraud related to popular culture. The goal is to examine particularly controversial sets of product reviews for films and video games released during the previous decade, to compare them using NLP techniques with less controversial but equally well-known media products, and to hopefully derive an algorithm which would use fraud detection techniques to predict the likelihood that a given product review is a result of a coordinated/concerted campaign that may involve multiple reviewers, reviews by those who are not actually customers, and so on. This project could be directly applicable to companies whose products' success depends on reviews in adjusting apparent review scores to account for online campaigns, and could have broader applications to the study of online conversation. 
    - The dataset, linked above, **is complete**, including basic NLP used to filter reviews based on language to create a consistent set of reviews for further analysis.
    - The NLP work is ongoing in Python and Scala (with some help from Redis caching) in some of the GitHub branches; I'm also doing some basic work in Azure Data Factory & with DataBricks.
