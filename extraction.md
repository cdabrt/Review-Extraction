# Bajaj D, Goel A, Gupta S

Context Of The Study: Academia
Outcomes And Findings: Results:
Close-knit use cases are clustered in order to recover meaningful microservices.

The approach enables system architects to identify microservice candidates at an early analysis and design phase of development.

The proposed solution determines dependencies between use cases even with their informal descriptions.

The approach was investigated and validated on an in-house proprietary web application and three sample benchmark applications.

Limitations:
No stated limitations
Publication Type: Article
Publication Year (1): 2022
Research Methodology Employed: Empirical Study
Reviewer: Carlo Baretta
Submission time: June 8, 2025 11:24 PM
Technical Focus: Clustering techniques
Utilization of Use Cases and Database Entities
Similarity Measurement: Cosine Similarity
Title: GreenMicro: Identifying Microservices From Use Cases in Greenfield Development
Tools And Frameworks: GreenMicro, the proposed approach
Hierarchical Agglomerative Clustering
Cosine Similarity
Teachers Feedback Web Application
JPetStore
AcmeAir
Cargo Tracking System
Venue: IEEE Access

# Birchler De Allende A, Sultan B, Apvrille L

Context Of The Study: Academia
Outcomes And Findings: Results:
The approach generates ADTs comparable in quality to those created by an associate-level security engineer.
ADTGC (with CAPEC mitigations) produced better results than ADTG (without CAPEC mitigations), especially for complex attack nodes.

Manual and ADTGC methods create sets of countermeasure pairings with fewer omissions compared to ADTG.

ADTGC can identify commonly recognized countermeasures for each attack tree.

Limitations:
The evaluation was based on a limited number of input attack trees. Only three of them were used as the basis for the experiments.

The manual ADTs were evaluated by two security experts. The AI-generated ADTs were evaluated by the same security experts who designed the manual ADTs.

The method does not produce ADTs that are as complete and semantically accurate as those created by human security experts.

The current solution can not handle other attack tree structures other than the structure it was tested on.

The current method accounts only for the leaf attack nodes, not all the attack nodes present in the tree.
Publication Type: Conference Proceedings
Publication Year (1): 2024
Research Methodology Employed: Empirical Study and experiment
Reviewer: Carlo Baretta
Submission time: June 8, 2025 10:45 PM
Technical Focus: Cybersecurity, threat modeling, and model-driven engineering in systems design.

GPT-4 Turbo model.

Attack-Defense Tree generation, countermeasure identification, documentation of security threats, and enhancing traditional manual threat analysis.
Title: From Attack Trees to Attack-Defense Trees with Generative AI & Natural Language Processing
Tools And Frameworks: TTool, TTool-AI
MITRE's CAPEC database, CAPEC
NLTK Python library
ATT&CK BERT
GPT-4 Turbo model
Venue: ACM/IEEE 27th International Conference on Model Driven Engineering Languages and Systems

# Chen L, Cheang W, Jiang Z, Xu Y, Cai Z, Sun L, Childs P, Han J, Hansen P, Zuo H

Context Of The Study: Academia and industry (supporting designers in design method application)
Outcomes And Findings: Results:
The authors propose I-Card to provide support for designing method applications.

User studies demonstrated that I-Card effectively improves the confidence, efficiency, and interest of designers in applying design methods.

The iterative design and evaluation process led to a preferred method, that being I-Card, by professional designers.

Limitations:
The generative AI can have so called "hallucinations", which can affect the accuracy of personalised design methods and the reliability of data support provided by I-Card.

Limited sample size and experimental differentiation.

There was an absence of professional designers in early studies.
Publication Type: Article
Publication Year (1): 2025
Research Methodology Employed: Formative study, Iteration study, User study
Reviewer: Carlo Baretta
Submission time: June 8, 2025 11:33 PM
Technical Focus: LLMs.
Method application design and personalised design methods.
Title: I-Card: A Generative AI-Supported Intelligent Design Method Card Deck
Tools And Frameworks: I-Card, the proposed solution
AI-powered tools providing identified support

# Cunha W, Armijo G, de Camargo V

Context Of The Study: Academic
Outcomes And Findings: Results:
Good result are reported in terms of accuracy, precision, recall, F-measure and Kappa's coefficient. However, the specific values for these metrics are not included in the paper.

Limitations:
The paper states that identifying architectural smells is inherently subjective and influenced by domain, developer experience, and context.

The reliance on user feedback for "repopulating the datasets" and the use of techniques like "Under-Sample" to balance the datasets alludes to that either the initial datasets or the feedback collection process might have limitations. These limitations are not stated in the paper.

Although the paper reports "good results", specific quantitative values for the evaluation metrics are not provided.

Publication Type: Conference Proceedings
Publication Year (1): 2020
Research Methodology Employed: Experiment
Reviewer: Carlo Baretta
Submission time: June 8, 2025 11:57 PM
Technical Focus: Machine learning and supervised learning.
Identification of architectural smells.
Title: InSet: A Tool to Identify Architecture Smells Using Machine Learning
Tools And Frameworks: InSet, the tool presented in the paper.
JDepend, CKJM.
ML algorithms.
Random Forest algorithm.
K-fold cross-validation.
Under-Sample technique.
Friedman test.
Nemenyi test.
Venue: Brazilian Symposium on Software Engineering '20

# Daniel Guamán, Soledad Delgado, and Jennifer Pérez

Context Of The Study: The study is set in the domain of software architecture and software quality. It specifically investigates architectural solutions based on the Model-View-Controller (MVC) pattern. The dataset consists of 87 real-world Java MVC applications of varying sizes (XS to M), sourced from public GitHub repositories and university labs.
Outcomes And Findings: The SOM-based clustering method successfully classified the 87 MVC applications into distinct groups based on their quality profiles, providing an objective way to analyze architectural similarity. The study shows it's possible to use the clustering results to improve application quality. For example, within a cluster, an application with better metrics can serve as a reference example for improving another with poorer metrics (Finding F.5).

Contrary to common architectural assumptions (bias), technological information, such as the kind of application (web, desktop), the specific MVC implementation, or the database used, are not the main drivers for classifying applications based on quality (Finding F.2 and F.4).

The primary factors determining the similarity of Java MVC applications are size, maintainability, and code complexity (Finding F.1).
Publication Type: Journal Article
Publication Year (1): 2021
Research Methodology Employed: Empirical Study
Reviewer: Alpay Hasanli
Submission time: June 8, 2025 11:42 PM
Technical Focus: The study uses Self-Organizing Maps (SOM), a type of artificial neural network for unsupervised clustering and data visualization. It does not use Large Language Models (LLMs).

The research addresses architectural analysis and decision-making. It aims to create an objective, data-driven knowledge base to help software architects make better-informed, less-biased decisions by classifying existing MVC pattern implementations based on their quality attributes. The goal is to understand what drives similarity and quality in different implementations of the same architectural pattern.

The AI technique (SOM) is not integrated into a live development process but is used for the offline analysis of a dataset of software artifacts. The goal is to extract architectural knowledge that can later inform decision-making.
Title: Classifying Model-View-Controller Software Applications Using Self-Organizing Maps
Tools And Frameworks: SonarQube, and various Eclipse IDE plugins (Eclipse Metrics, Structural Analysis, JDepend Analysis, Design Pattern Recognition). 24 software quality metrics covering Count/Size, Maintainability, Duplications, Complexity, and Design Quality, plus 2 attributes describing technology choices (database, MVC implementation variant).
Venue: IEEE Access

# Eisenrich, T. Speth, S. Wagner, S.

Context Of The Study: Academia
Outcomes And Findings: Results:
Envisions automatic evaluation and trade-off analysis of generated architectures.

Believes the proposed process can improve the quality of architecture and reduce creation time in most projects.

Exploratory analysis suggests LLMs are capable of understanding application domains and generating valid PlantUML diagrams.

GPT-3.5 showed it handled relations between concepts well in domain model generation.

Limitations:
A fully automated solution for software architecture generation might not perform well with current state-of-the-art LLMs.

There is currently no data available to easily train and improve standard LLMs for software architecture generation.

In initial tests, LLMs sometimes modeled the system itself instead of the domain as intended.

Despite the semi-automated approach, the process still requires manual effort for adjusting LLMs

The output of the LLM should be checked so that it is certain that the LLM isn't reproducing architectures that it previously trained with. It should generate new ideas for the architectures.
Publication Type: Conference proceedings / Vision paper
Publication Year (1): 2024
Research Methodology Employed: Vision paper
Reviewer: Carlo Baretta
Submission time: June 8, 2025 11:07 PM
Technical Focus: Supporting software architects in architectural design decisions and evaluation to reduce time and increase reproducibility.

AI techniques, Natural language processing, LLMs

Semi-automatic generation of software architecture candidates based on requirements.
Title: From Requirements to Architecture: An AI-Based Journey to Semi-Automatically Generate Software Architectures
Tools And Frameworks: PlantUML
MobSTr-dataset
For future evaluation as reference architectures: T2-Project , TeaStore , SockShop
Mentions potential use of :"4+1 Model" by Kruchten, and Palladio Component Model.


Venue: ICSE Proceedings Designing '24

# Gunter Mussbacher, Benoit Combemale, Silvia Abrahão, Nelly Bencomo, Loli Burgueño, Gregor Engels, Jörg Kienzle, Thomas Kühn, Sébastien Mosser, Houari Sahraoui, and Martin Weyssow

Context Of The Study: Academia
Outcomes And Findings: A comprehensive assessment grid for evaluating Intelligent Modeling Assistants based on nine key properties. This grid facilitates structured comparison to guide future research (since current tools achieve low scores).
Publication Type: Conference Proceedings
Publication Year (1): 2020
Research Methodology Employed: Conceptual framework proposal combined with a literature survey
Reviewer: Lorenzo Steno
Submission time: June 8, 2025 9:42 PM
Technical Focus: Providing intelligent assistance for the practice of software modeling with machine learning and other techniques.
Title: Towards an Assessment Grid for Intelligent Modeling Assistance
Tools And Frameworks: The paper introduces the conceptual Reference Framework for Intelligent Modeling Assistance and a corresponding Assessment Grid. It also uses this grid to analyze existing research tools and commercial platforms.
Venue: ACM/IEEE 23rd International Conference on Model Driven Engineering Languages and Systems (MODELS '20 Companion), Virtual Event, Canada

# Houichime TEl Amrani Y

Context Of The Study: Industry
Outcomes And Findings: Findings:
F1-scores are comparable or better than other models. For the patterns that have not been tested in other models, the model that was developed in this research had an F1-score of > 0.85.
Overall accuracy, F1-score, precision and recall values are larger than the DPD_Att, DPD_F and FeatureMap methods.
The dataset used for this method contains the most files out of all other mentioned methods, all GoF design patterns, behavioural analysis, data augmentation, and is language agnostic. The datasets used for the other methods are smaller, tested less GoF design patterns and did not support the behavioural analysis, data augmentation and language agnosticism.

Limitations:
Method arguments are excluded.

Ambiguities in compile-time and runtime polymorphism.

The structural analysis is constrained by the number of keywords that are allowed as input for the sequencing stage.

If elements within the callgraph are not processed in a uniform manner it could hurt the accuracy of the model.

Model not well trained on complex code samples

(Not mentioned in the paper) enormously varied representation of the GoF patterns in the dataset. Interpreter is especially under-represented.


Publication Type: Research article
Research Methodology Employed: Experiment
Reviewer: Carlo Baretta
Submission time: June 8, 2025 8:24 PM
Technical Focus: Machine learning.
Using the attention mechanism for detecting design patterns (Model is trained on samples representing all 23 GoF (Gang of Four) design patterns).
Detection of design patterns is used for reverse engineering of programs.
Data collection -> preprocessing -> embedding -> transforming -> classifying/predicting
Title: Context Is All You Need: A Hybrid Attention-Based Method for Detecting Code Design Patterns
Tools And Frameworks: PyDesignNet dataset, containing Python code files.


Venue: IEEE Access

# Louis Richard Timperley, Lucy Berthoud, Chris Snider & Theo Tryfonas

Context Of The Study: The study is set in the context of aerospace systems engineering, specifically focusing on the generative design of Earth observation spacecraft system architectures. The research uses three design cases to ensure broad applicability:      Academia (Nano-satellite): The University of Bristol's CubeSat payload, PROVE Pathfinder.      Academia (Full-size satellite): A masters' level group design project for an Earth observation spacecraft.      Industry (Full-size satellite): An industrial study for a European Space Agency (ESA) Earth Observation (EO) mission.
Outcomes And Findings: The LLM-based toolchain successfully generated spacecraft system architectures of acceptable quality, with high textual similarity, traceability, and alignment to pre-existing designs. The quality of the generated architecture is highly dependent on the quality of the input prompts and the coverage of the initial requirements. More detailed prompts yield better results, but with diminishing returns. Human-in-the-loop control is essential. Designer intervention to down-select suggested elements at each stage is crucial to prevent the propagation of errors and ensure a high-quality final design. Precision scores for generated elements were high (avg. ~2.3/3), while recall scores were lower (avg. ~1.8/3), showing that generated elements were generally correct but some baseline elements were missed.
Publication Type: Journal Article
Publication Year (1): 2025
Research Methodology Employed: Case study
Reviewer: Alpay Hasanli
Submission time: June 8, 2025 10:48 PM
Technical Focus: OpenAI's text-davinci-003 (a GPT-3.5 series model), The research addresses the early-stage system architecting process within a Model-Based Systems Engineering (MBSE) framework. It specifically focuses on the automated generation of architectural elements—functions, modes, and components—from an initial set of system requirements. An LLM is integrated with an MBSE tool to act as a generative design assistant. This involves a toolchain integration where prompts are sent to the LLM, and its textual responses are parsed and used to automatically create and populate model elements within the MBSE environment.
Title: Assessment of large language models for use in generative design of model based spacecraft system architectures
Tools And Frameworks: MBSE Tool: Eclipse Capella, MBSE Method: ARCADIA, Developed Toolchain: A custom Python package named NalMage (Neural Network-Assisted Language Modelling for Architecture Generation and Engineering) was developed to bridge the LLM and the MBSE tool.
Venue: Journal of Engineering Design

# Ludovic Apvrille and Bastien Sultan

Context Of The Study: Academia
Outcomes And Findings: The main finding is that the TTool-AI framework, with its automated feedback loop, can successfully and rapidly generate SysML diagrams from natural language, slightly outperforming students (For Block diagrams 81 vs 76 average with 16 vs 26 standard deviation and for State Machine Diagram 63 vs 58 with 15 vs 32 standard deviation) in an experimental comparison. The authors report significant time savings compared to students.
Publication Type: Conference Proceedings
Publication Year (1): 2024
Research Methodology Employed: Development and evaluation of a tool. The authors created a framework and then assessed its performance through a case study and a comparative experiment against master-level students.
Reviewer: Lorenzo Steno
Submission time: June 8, 2025 10:19 PM
Technical Focus: Using GPT-3.5 turbo Large Language Model to automatically create SysML block and state machine diagrams.
Title: System Architects Are not Alone Anymore: Automatic System Modeling with AI
Tools And Frameworks: e paper introduces and uses TTool-AI, a novel framework that integrates the ChatGPT language model directly into the TTool MBSE toolkit.
Venue: 12th International Conference on Model-Based Software and Systems Engineering (MODELSWARD 2024)

# Maddeh MAyouni SAlyahya SHajjej F

Context Of The Study: Industry
Outcomes And Findings: Outcomes:
Scores for precision are below 70%, and for most projects the F1-scores are also below 70%.

Limitations:
The set of examples is limited to two open source projects. This is a weird limitation that the authors have stated, as there are three other, totalling five, projects that have been used in the measurements. In some previous sections it was stated that three projects were used to test these algorithms. Even more confusing is the authors then mention the "PMD" and "Nutch" projects, and the measurements of their solution using these projects are never shown in any figures.

Limitations which are never stated within the paper follow below:

Manual input of design defects that are intended to be detected.
"We entered manually the design defects we intend to detect.".
So in the program it is first stated which design defects they intend to detect, before the program tries to detect them. Furthermore, they make a statement about a certain method of detection in a previous section in the paper:
"It is also based on a manual detection that is very difficult to generalize for large projects. In our current study, we overcome this problem and we propose generic detection process that can be applied for any design defect."
It is subsequently never stated what it is that makes their detection process generic.

Their quantification of defects.
"Defects could be quantified as metrics based rules that represent a
combination of software metrics."
I would assume defects would be measured as the amount of "bad smells" or "anti-patterns", which they also mention in the paper.

Scores:
The precision and F1-scores are very low and the number of detections for each project and each defect vary wildly. It is subsequently never discussed why these scores vary so much.


Many grammatical mistakes in the paper. Almost impossible to follow.
Publication Type: Article
Research Methodology Employed: Experiment
Reviewer: Carlo Baretta
Submission time: June 8, 2025 9:20 PM
Technical Focus: Design defect detection at the UML model level.
ID3 algorithm.
Title: Decision tree-based Design Defects Detection
Tools And Frameworks: The ID3 algorithm is used in their detection method.
The proposed solution was tested on the following projects:
Xerces v2.7
ArgoUML 0.19.8
Lucene 1.4
Log4j 1.2.1
GanttProject v1.10.2
Venue: IEEE Access

# Pradas Gómez A, Krus P, Panarotto M, Isaksson O

Context Of The Study: Academia
Outcomes And Findings: Results:
LLMs can significantly enhance the engineering design process, particularly in early design and conceptualisation. The LLMs can support designers in the design phases.

LLMs can interpret system requirements that are written in a natural language, which enables faster validation and refinement.

LLMs can generate design concepts, explore design alternatives, and perform trade-off analyses.

Limitations:
The study is based on only two aerospace cases, one for an SAD and one for a CAD solution. This could limit the generalisability of the findings to other domains.

While opportunities and challenges are discussed, the paper does not provide detailed quantitative metrics on the performance or impact of LLMs in these specific design activities.

The paper emphasises how LLMs support designers, rather than offering a fully automated design solution, implying that significant human oversight and interaction are still required.
Publication Type: Conference Paper
Publication Year (1): 2024
Research Methodology Employed: Case study
Reviewer: Carlo Baretta
Submission time: June 9, 2025 12:04 AM
Technical Focus: LLMs.
Complex system design, design phases, SADs.
CAD models.
KBE.
Requirement engineering.
Title: Large language models in complex system design
Tools And Frameworks: GPT-4.
CAD.
KBE.
Simulink.
Venue: INTERNATIONAL DESIGN CONFERENCE - DESIGN 2024

# Ramos, Felipe & Costa, Alexandre & Perkusich, Mirko & Pereira, Luiz & Valadares, Dalton & Neto, Ademar & Cunha, Felipe & Almeida, Hyggo & Perkusich, Angelo.

Context Of The Study: Academia
Outcomes And Findings: The recommendation system achieved rates of 78.5%, 84.5%, and 79.0% for precision, recall, and F-measure, respectively, using a database of 13 projects. There are generalization limitations because the system was only developed for one project type (Web information systems).
Publication Type: Article
Research Methodology Employed: Empirical Study
Reviewer: Alpay Hasanli
Submission time: June 8, 2025 8:41 PM
Technical Focus: kNN-based algorithm
Title: A Data-Driven Recommendation System for Enhancing Non-Functional Requirements Elicitation in Scrum-Based Projects
Tools And Frameworks: NFR recommendation system for Scrum projects
Venue: IEEE Access

# Rukmono S, Ochoa L, Chaudron M

Context Of The Study: Academia. Software Architecture Documentation (SAD).  Source code in software engineering.
Outcomes And Findings: Results:
Demonstrates a deductive Software Architecture Recovery approach.

70% accuracy was achieved whilst classifying 54 classes and 184 methods in the K-9 Mail application.

LLMs facilitate the definition of a reference architecture using natural language and exploit both syntactic and semantic aspects for recovery.

Weighted average F1 score with GPT-4o: 0.86, compared to TransArC's 0.87 and ArDoCode's 0.62.

Limitations (inferred from future works):

The current approach's accuracy needs further rigorous evaluation using "ground-truth architectures".

Large reliance on the proper definition of the Reference Architecture (RA);.

The approach needs to be refined and evaluated through industrial case studies, instead of only using the K-9 mail application.
Publication Type: Conference Proceedings
Publication Year (1): 2024
Research Methodology Employed: Empirical Study and Experiment
Reviewer: Carlo Baretta
Submission time: June 8, 2025 10:16 PM
Technical Focus: GPT-4o used for Software Architecture Recovery through chain-of-thought prompting.

Title: Enabling Architecture Traceability by LLM-based Architecture Component Name Extraction
Tools And Frameworks: GPT-4 , Android application K-9 Mail
Venue: Karlsruhe Institute of Technology (KIT)

# Verganti R, Vendraminelli L, Iansiti M

Context Of The Study: Academic
Outcomes And Findings: Results:
AI enables organizations to overcome previous limitations of human-intensive design processes by improving scalability, broadening scope, and enhancing learning and adaptation.

AI reinforces core Design Thinking principles, making solutions more people-centered (highly granular personalization), potentially more creative (abductive), and continuously updated (iterative).

It profoundly changes design practice by automating problem-solving tasks into learning loops that operate without limitations of volume and speed.

Limitations:
The conceptual nature of the paper. The paper does not include empirical validation or systematic testing of the proposed framework.

The paper identifies new theoretical questions that are largely unexplored, due to the scope of the paper.

According to the paper, AI will increasingly handle problem-solving matters, whilst people will focus on finding the problems. They however note that current understanding of this area is limited.
Publication Type: Article
Publication Year (1): 2020
Research Methodology Employed: Vision/conceptual paper
Reviewer: Carlo Baretta
Submission time: June 8, 2025 11:47 PM
Technical Focus: Weak AI
Software architecting
Title: Innovation and Design in the Age of Artificial Intelligence
Tools And Frameworks: Proposing a framework for understanding design
"AI Factories"
Proposed framework used in usecases like Netflix, Airbnb, Microsoft, and Tesla
Venue: Journal of Product Innovation Management

# Ali M. Hosseini, Wolfgang Kastner, and Thilo Sauter

Context Of The Study: Industry
Outcomes And Findings: The proposed framework was found to be effective in automating security compliance tasks. In evaluations, the Llama-2 7B model achieved high performance. The usability study showed that the framework's natural language interface was perceived as 83% easier to use and provided 78% more meaningful responses compared to writing formal SPARQL queries. Augmenting LLMs with domain-specific knowledge graphs makes complex security analysis accessible to non-experts. Limitations include managing LLM hallucinations, scalability, and ensuring the reasoning is transparent and reliable.
Publication Type: Journal Article
Publication Year (1): 2025
Research Methodology Employed: The paper proposes a new framework and validates it through a mixed-methods evaluation. This includes an objective evaluation against expert-provided reference answers, a scenario-based evaluation for a specific use case, and a usability comparison against a baseline
Reviewer: Lorenzo Steno
Submission time: June 9, 2025 12:03 AM
Technical Focus: A hybrid AI approach that combines a Knowledge Graph with a Large Language Model. The knowledge graph is built from an ontology based on the IEC 62443 standard and provides structured, factual, and domain-specific context. The LLM uses this context to provide a natural language question and answer interface. This automates the process of interpreting and validating security requirements against a system's architecture.
Title: Leveraging LLMs and Knowledge Graphs to Design Secure Automation Systems
Tools And Frameworks: The authors developed a custom software framework implemented in Python. The framework is built on an ontology created using Protégé. It uses the Llama-2 7B model as its core LLM and employs the FAISS library for cosine similarity search to retrieve relevant context from a vector database. The framework's usability is benchmarked against the SPARQL query language.
Venue:  IEEE Open Journal of the Industrial Electronics Society (OJIES)

# Choongki Cho, Ki-Seong Lee, Minsoo Lee, and Chan-Gun Lee

Context Of The Study: Academia
Outcomes And Findings: The study found that using cluster ensembles can lead to better architecture recovery results than relying on a single clustering algorithm. The Meta-Clustering Algorithm and EA consensus techniques were found to be the most effective. The research also concludes that non-deterministic algorithms are better for generating the necessary diverse base clusterings and recommends using at least 10 base clusterings for the ensemble to be effective. A limitation is that the study was confined to open-source projects.

Publication Type:  Journal Article
Publication Year (1): 2019
Research Methodology Employed: Case study
Reviewer: Lorenzo Steno
Submission time: June 8, 2025 10:48 PM
Technical Focus: Machine learning, specifically cluster ensemble techniques, applied to software architecture recovery
Title: e Software Architecture Module-View Recovery Using Cluster Ensembles
Tools And Frameworks: The study utilizes the 'Understand' static analysis tool for fact extraction from source code. For the recovery process, it implements and uses several clustering algorithms including Bunch, Weighted Combined Algorithm (WCA), K-means, and Blondel's algorithm via Gephi. The core of the work involves five consensus techniques: CSPA, HGPA, MCLA, HBGF, and EA, which were implemented in Python by the authors.
Venue: IEEE Access

# Daniel N. Ege, Henrik H. Øvrebø, Vegar Stubberud, Martin F. Berg, Christer Elverum, Martin Steinert and Håvard Vestad

Context Of The Study: The research is conducted in the context of engineering design and product development. The study took place in a university makerspace during a competitive 48-hour hackathon where the objective was to design and build a functional device to launch a NERF dart as far as possible.
Outcomes And Findings: The LLM-led team was competitive, finishing 2nd out of 6 teams in the final performance evaluation. The LLM was able to guide the team from concept to a functional and physical prototype.

The LLM tended to interpret minor difficulties as project-ending failures, causing it to abandon promising concepts prematurely. The LLM sometimes introduced unnecessary complexity into its designs (e.g., motorizing a component that could have been simpler).

The LLM-led team's final prototype launched a NERF dart 14.8 meters, securing 2nd place. The winning human team achieved a distance of 37.66 meters. The average distance across all teams was 12.0 meters.
Publication Type: Journal Article
Publication Year (1): 2025
Research Methodology Employed: Experiment
Reviewer: Alpay Hasanli
Submission time: June 8, 2025 11:33 PM
Technical Focus: Primarily ChatGPT 4.0, with some use of ChatGPT 3.5.

The study focuses on engineering design practices rather than software architecture. Key practices investigated include:
- Concept generation and ideation.
- Decision-making throughout the design process.
- Physical prototyping and iterative refinement.

The study explores a unique human-AI team structure where the LLM acts as the sole "inventor" and decision-maker. Two human participants acted as the "arms and feet" of the LLM, executing its instructions, providing objective feedback, and not contributing their own ideas or subjective input.
Title: ChatGPT as an inventor: eliciting the strengths and weaknesses of current large language models against humans in engineering design
Tools And Frameworks: Pro2booth, an online platform for capturing and documenting physical and digital prototypes.
Venue: Artificial Intelligence for Engineering Design Analysis and Manufacturing

# Diana Robinson, Christian Cabrera, Andrew D. Gordon, Neil D. Lawrence, and Lars Mennen

Context Of The Study: Academia
Outcomes And Findings: The main outcome is the proposal of a comprehensive research agenda for enabling end-users to develop software purely from natural requirements. The paper identifies key challenges and research directions, such as creating meaningful tests from high-level requirements, applying language-based security to LLM-generated code, and automating maintenance.
Significant risks: including model collapse from training on AI-generated data, algorithmic bias, and the need to manage the untrustworthy nature of LLM outputs.
Publication Type: Journal Article / Position Paper
Publication Year (1): 2025
Research Methodology Employed: The paper presents a conceptual exploration and proposes a forward-looking research agenda
Reviewer: Lorenzo Steno
Submission time: June 8, 2025 11:29 PM
Technical Focus: The technical focus is on leveraging Generative AI, especially Large Language Models (LLMs), to enable end-users without technical training to create, test, and deploy entire software applications using only natural requirements such as language, images, or demonstrations. This concept is termed "requirements-driven EUSE," aiming to automate the full software development lifecycle.
Title: Requirements Are All You Need: The Final Frontier for End-User Software Engineering
Tools And Frameworks: Proposal of a new conceptual framework for a "requirements-driven EUSE lifecycle" composed of three iterative stages: Requirements Elicitation, Testing, and Maintenance & Deployment. It does not introduce a new tool but discusses the role of existing and emerging technologies like GPT-4, GitHub Copilot, Devin, and AutoGPT as enablers for this vision.
Venue: ACM Transactions on Software Engineering and Methodology

# Fredy H. Vera-Rivera, Eduard Puerto, Hernán Astudillo, and Carlos Mauricio Gaona

Context Of The Study: Academia
Outcomes And Findings: The "Microservices Backlog" model, using a genetic algorithm, generates microservice decompositions that are better than decompositions made using traditional methods. Quantitatively, the Microservices Backlog model solutions have lower coupling, higher cohesion, significantly lower cognitive complexity, and fewer dependencies. The approach provides architects with a tool to graphically analyze and evaluate decomposition strategies.
A limitation is the need to manually define dependencies between user stories for large applications and the non-deterministic nature of the genetic algorithm.
Publication Type: Journal Article
Publication Year (1): 2021
Research Methodology Employed: The paper follows a Design Science Research approach
Reviewer: Lorenzo Steno
Submission time: June 8, 2025 11:58 PM
Technical Focus: The paper's technical focus is on applying Genetic Programming to the software architecture problem of decomposing an application into microservices. The AI technique uses user stories as input and optimizes the decomposition based on a combination of software metrics and semantic similarity.

Title:  Microservices Backlog-A Genetic Programming Technique for Identification and Evaluation of Microservices From User Stories
Tools And Frameworks: A web application named "Microservices Backlog (MB)". For calculating semantic similarity between user stories: the Spacy Natural Language Processing (NLP) library.
Venue: IEEE Access

# Idris Oumoussa and Rajaa Saidi

Context Of The Study: Software architecture, specifically the challenge of migrating monolithic systems to microservice architectures. The study uses three real-world and well-known case studies to demonstrate and validate the approach.
Outcomes And Findings: The semantic-driven approach produces microservice decompositions with higher cohesion and lower coupling compared to several existing methods. The resulting architectures are more stable. Scalability can be a concern, as the computational load of NLP and clustering increases with the number of activities and dependencies. Manual validation or input may still be necessary.
Publication Type: Journal Article
Publication Year (1): 2025
Research Methodology Employed: Case Study
Reviewer: Alpay Hasanli
Submission time: June 8, 2025 10:54 PM
Technical Focus: The approach is driven by advanced Natural Language Processing (NLP) techniques, not large generative models. The primary focus is on the automated identification of microservice boundaries during the decomposition of a monolithic application. The method uses a top-down, business process-driven strategy. The system integrates Business Process Models (BPMN) as the primary input source. These models are processed through an NLP pipeline to create a semantic representation, which is then used by clustering algorithms to derive a microservice architecture.
Title: Automated Microservices Identification Through Business Process Analysis: A Semantic-Driven Clustering Approach
Tools And Frameworks: Business Process Model and Notation (BPMN) models, converted to XML using tools like Camunda.
Venue: IEEE Access

# J.D. Zamfirescu-Pereira, Eunice Jun, Michael Terry, Qian Yang, and Bjoern Hartmann

Context Of The Study: The iterative design and prototyping of small, interactive programs by programmers with various levels of experience, aiming to support the creative and exploratory phases of program design rather than just code generation.
Outcomes And Findings: PAIL successfully encouraged participants to consider a broader design space, including end-user needs and alternative solutions, which they might not have considered otherwise. All participants found at least one unconsidered alternative via PAIL that influenced their design.

Participants frequently felt overwhelmed by the sheer volume and speed of information generated by the agents across the code, chat, and design panels. articipants made little use of the AI-generated rationales and trade-offs, preferring to directly test an alternative ("show, don't tell") rather than trust the LLM's assessment.
Publication Type: Conference Proceedings
Publication Year (1): 2025
Research Methodology Employed: Formative Study
Reviewer: Alpay Hasanli
Submission time: June 8, 2025 11:07 PM
Technical Focus: The system uses multiple agents powered by Large Language Models, GPT-4o and Claude
The work addresses the broader program design process, moving beyond code generation to support higher-level activities. These include:
Problem-space exploration, Solution-space exploration, and Decision tracking.

LLM-powered agents are integrated into a custom-built web-based Integrated Development Environment (IDE). This integration features a chat interface, a code editor, a live preview, and a novel "design panel" that surfaces design artifacts like goals, requirements, and alternatives.
Title: Beyond Code Generation: LLM-supported Exploration of the Program Design Space
Tools And Frameworks: A prototype web-based IDE named PAIL (Program-Design Assistance & Iteration with LLMs).
Venue: CHI '25 (ACM CHI Conference on Human Factors in Computing Systems)

# Jp, Sanjanasri & Menon, Vijay & Kp, Soman & Atul, Kr.Ojha.

Context Of The Study: Industry
Outcomes And Findings: The proposed CNN-based classifier achieved overall accuracy >70%, with some classes reaching up to 95%, especially where data was abundant. It was also found that an imbalanced data led to poor performance in certain classes. The study highlights that data imbalance limits generalizability, and deeper architectures are needed for a confidence above 90%.
Publication Type: Article
Research Methodology Employed: Empirical Study
Reviewer: Alpay Hasanli
Submission time: June 8, 2025 9:45 PM
Technical Focus: Convolutional Neural Networks, Natural Language Processing, Requirement classification from unstructured SRS documents, Comparison of custom-trained vs. pre-trained word embeddings (Word2Vec, FastText)
Title: A Non-Exclusive Multi-Class Convolutional Neural Network for the Classification of Functional Requirements in AUTOSAR Software Requirement Specification Text
Tools And Frameworks: Word2Vec and FastText word embeddings, Custom enterprise dataset (AUTomotive Open System ARchitecture or AUTOSAR) for training and validation
Venue: IEEE Acces

# Noor Mohammed Sabr Al-Gburi, András Földvári, Kristóf Marussy, Oszkár Semeráth, and Imre Kocsis

Context Of The Study: Academia
Outcomes And Findings: The study introduces a novel, automated workflow for generating and evaluating DLT network architectures from requirements. The evaluation showed the approach is feasible and scalable, generating valid architectures with up to 70 nodes, with the largest median generation time being under 110 seconds. The resulting candidates architectures are presented as Pareto fronts to aid designers in decision-making.
Publication Type: Conference Proceeding
Publication Year (1): 2024
Research Methodology Employed: Empirical study
Reviewer: Lorenzo Steno
Submission time: June 8, 2025 11:43 PM
Technical Focus: Applying Model-Driven Engineering and Search-Based Software Engineering to architectural synthesis. It uses partial modeling to capture requirements and graph generation to create candidate architectures. A key aspect is the use of Answer Set Programming (ASP), a form of declarative logic programming, to evaluate and rank the generated architectures against extra-functional requirements like cost and resilience.
Title:  Requirement-Driven Generation of Distributed Ledger Architectures
Tools And Frameworks: The proposed workflow is implemented using the Refinery model generation framework to create architectural candidates from partial models. For the analysis and scoring of these candidates, the Clingo solver for Answer Set Programming (ASP) is used.
Venue:  ACM/IEEE 27th International Conference on Model Driven Engineering Languages and Systems (MODELS '24)

# Rudra Dhar, Karthik Vaidhyanathan, Vasudeva Varma

Context Of The Study: Software Architecture and Architectural Knowledge Management. It specifically focuses on the task of generating Architecture Decision Records. The experimental data consists of 95 ADRs collected from five open-source software repositories on GitHub.
Outcomes And Findings: Large models like GPT-4 perform best in a zero-shot setting, providing high-quality outputs without any examples. Models like Flan-T5 show significantly improved performance after fine-tuning. After fine-tuning Flan-T5 achieves results comparable to much larger cloud-based models.

No LLM was able to achieve human-level performance. Human-written decisions were often more comprehensive. This indicated that human oversight and involvement are still essential. The impact of the few-shot approach was inconsistent and did not universally improve performance for all models, especially the largest ones.

The fine-tuned Flan-T5-base model was the top performer in its category, with a BERTScore of 0.841, demonstrating that smaller, specialized models can be highly effective.
Publication Type: Conference Paper
Publication Year (1): 2024
Research Methodology Employed: Empirical Study. The experiments involve testing various LLMs using three distinct prompting/training methodologies: zero-shot prompting, few-shot prompting, and fine-tuning. The generated outputs are evaluated using a suite of standard NLP metrics and supplemented with manual review.
Reviewer: Alpay Hasanli
Submission time: June 8, 2025 11:24 PM
Technical Focus: The study uses a representative set of LLMs from two major families.
Decoder-only Models: GPT-2, GPT-3, GPT-3.5, and GPT-4.
Encoder-Decoder Models: T5, T0, and Flan-T5, in various model sizes (small, base, large, xl, 3b).
The study specifically investigates the feasibility of LLMs generating the decision sections of an ADR based on a given context.
This research explores three distinct methods for using LLMs for this task:
Zero-shot prompting, few-shot prompting, and fine-tuning.
Title: Can LLMs Generate Architectural Design Decisions? – An Exploratory Empirical Study
Tools And Frameworks: A curated dataset of 95 ADRs from public GitHub repositories., Various models from OpenAI (via API) and Google (hosted locally).
Venue: ICSA 2024 (IEEE International Conference on Software Architecture)

# Hari Subramonyam, Divy Thakkar, Andrew Ku, Juergen Dieber, and Anoop K. Sinha

Context Of The Study: Industry
Outcomes And Findings: Generative AI shifts the prototyping process to be content-centric. Design and computation become intertwined. Prompts emerge as a shared design artifact. This blurs the line between designers, engineers, and product managers. Teams used LLMs as collaborative partners to generate requirements and explore design spaces. Key challenges were identified, including the model's limited interpretability, its high sensitivity to prompt phrasing, and the risk of overfitting designs to specific content examples, which introduces new hurdles for collaboration and evaluation.
Publication Type: Conference Proceeding
Publication Year (1): 2025
Research Methodology Employed: Qualitative design study
Reviewer: Lorenzo Steno
Submission time: June 8, 2025 11:49 PM
Technical Focus: Integration of generative AI into collaborative software design workflows. The focus lies on prompt engineering acting as a primary method for prototyping AI application.
Title: Prototyping with Prompts: Emerging Approaches and Challenges in Generative Al Design for Collaborative Software Teams
Tools And Frameworks: AI Studio, a browser-based IDE for rapid prototyping with generative models, as the primary tool for participants. Participants also used shared Google Documents for collaborative brainstorming and note-sharing during the workshops.
Venue:  CHI Conference on Human Factors in Computing Systems (CHI '25)

# Christian Cabrera, Andrei Paleyes, and Neil D. Lawrence

Context Of The Study: Academia
Outcomes And Findings: As a position paper, the primary outcome is the proposal of the S4 concept as a new research agenda for building interpretable and adaptive autonomous systems. It is argued that S4 provides richer knowledge for decision-making than current methodologies.
Challenges: Translating raw system data into knowledge representations for knowledge graphs, ensuring data privacy and security in DOA, and managing the hallucinations in LLMs.
Publication Type: Workshop/Position Paper
Publication Year (1): 2024
Research Methodology Employed: The paper presents a conceptual proposal and discusses a new research agenda
Reviewer: Lorenzo Steno
Submission time: June 8, 2025 11:23 PM
Technical Focus: The technical focus is on a novel architectural concept, S4, that integrates multiple advanced technologies to improve system interpretability and self-adaptation. It proposes a "knowledge loop" that combines three sources: system design artifacts modeled as Knowledge Graphs (KGs), operational data from deployed systems built on Data-Oriented Architectures (DOA), and domain knowledge from the software engineering community encoded in Large Language Models (LLMs). This integration is facilitated by a multi-agent system.
Title: Self-sustaining Software Systems (S4): Towards Improved Interpretability and Adaptation
Tools And Frameworks: A conceptual framework called Self-sustaining Software Systems. The framework includes three conceptual agents: A System2KG, KG2LLM, and an Adaptive agent.
Venue: 2024 IEEE/ACM International Workshop New Trends in Software Architecture (SATrends)