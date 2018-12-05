# CM4107 Coursework #2

Anthony Sébert

School of Computing Science and Digital Media
RGU
Aberdeen, UK

## Abstract

This electronic document is a “live” template and already defines the components of your submission [title, text, heads, etc.] in its style sheet. **CRITICAL:  Do Not Use Symbols, Special Characters, or Math in Paper Title or Abstract*. Use the abstract to indicate at a very high level what you set out to achieve in your coursework and your key finding. This should not be more than 5 sentences or so.

Keywords—component; formatting; style; styling; insert (key words)

## I. Comparative Study using ScikitLearn 

Introduce the selected algorithms and datasets, and specify why you have selected them.  If there are any interesting aspects of your chosen datasets you can state them here. Also state details relevant to the chosen evaluation methodology from scikitLearn. Detail the text pre-processing pipeline used; here you may refer to key code snippets as needed. It might help to have a figure. 

Make sure to:

- explain your evaluation strategy and the pipeline that was used to convertthe text data into a vector form; and
- explain your results

The goal is to analyse a collection of text documents and build a text classiffer. You will need to use sciktlearn and nltk to extract feature vectors suitable for machine learning and train models to perform text classiffcation. You can also use a grid search strategy to find a good configuration of both the feature extraction components and the classifier. You should select 2 datasets from the the list provided. You need to select 3 algorithms from the sciktlearn library; two of which must be an Artificial Neural Net and the k-Nearest Neighbour (kNN). The third can be one of your own
choices from the sciktlearn library (e.g. Naive Bayes, Support Vector Machines, Decision Trees). It is important that you select and organise your training and test sets appropriately using cross-validation.

Proposed candidate datasets listed below:
- Movie reviews
- Spam Dataset
- 20 Newsgroups
Task (weight 3): Maximum one page (including references) which needs to be organised as follows:
- explain your evaluation strategy and the pipeline that was used to convert the text data into a vector form; and
- present and interpret your results.

## II. Explainable AI (XAI)

### A. Overview of explainable XAI

Discussion covering an overview of XAI…

### B. Legal, ethical and Social implications of XAI

Discus the above issues in relation to XAI… 

### C. Explaiability and Transparency on chosen algorithms

A paragraph should then be provided for each algorithm that you had chosen in your comparative study...

What requirements, if any, should be imposed on AI systems and technology when making decisions that directly affect humans? For example, should they be required to make transparent decisions? If so, how?
In this section, you should provide a brief overview of explainable AI in general, including: what is explainable AI? Why is it important? What are some of the legal, ethical and social issues surrounding explainable AI? You should then focus on the specific qualities that apply to your selected algorithms. This should include references to existing literature.

Task (weight 1): Maximum one page (including references) which needs to be organised as follows:
- A brief overview of explainable AI and its importance.
- The legal, ethical and social implications of explainable AI.
- In what ways can you explain the decisions of your selected algorithms?
Some literature that you may wish to read for ideas on the subject (you can Google and download these from the web). Feel free to explore other sources, but please reference appropriately.

* Sørmo, F., Cassens, J., Aamodt, A.: Explanation in case-based reasoning
- perspectives and goals.

Although CBR focused, this paper presents an excellent overview of explainability in modern AI. Particularly, it examines how to measure different aspects of explainability in an algorithm.

* Miller, Tim et al. Explainable AI: Beware of Inmates Running the Asylum
Or: How I Learnt to Stop Worrying and Love the Social and Behavioural Sciences.
A very interesting paper discussing the human connotations of explainable AI, as well as advocating taking advantage of existing research in other areas like philosophy to inform the next steps for explainability.

* IJCAI/ECAI Workshops on Explainable Artificial Intelligence (XAI)
This is a collection of papers submitted to IJCAI's workshop on explainability. IJCAI is one of the most prominent AI conferences in the world, and their workshops contain a vast amount of relevant quality papers discussing explainability.

**extracted from lecture slides**
An AI’s ability to explain its decision-making process.
Our ability to understand that process.

Explainable AI is any machine learning algorithm designed to propagate user understanding
This can take many forms:
* Understanding the purpose of the AI
* Understanding how the AI arrives at a decision
* Understanding situations where the AI is ineffective, or unsure
Provides algorithmic accountability

So you have an awesome algorithm that gets it right 99% of the time.
Who cares HOW it makes the decisions – it works right?
What happens that 1% of the time?
* Why is it wrong?
* How wrong is it?
* When is it wrong?

European law that data subjects have a right to an explanation regarding decisions made using their data.
Data subjects have a right to contest those decisions.

Measuring the Explainability of a System
Sørmo – Goals of Explainability
Lipton – Defining Interpretability
Lundberg - SHAP

The Five Goals of Explainability
Transparency
Justification
Conceptualisation
Relevance
Learning

An Example - kNN
KNN is very transparent, and its answers should be relevant to the problem.
KNN could be used for justification.
KNN is passable at conceptualisation and does not necessarily promote learning.

Explainable AI is a system which provides a means to improve the users understanding of it.
Providing explanation is a legal and social obligation.
* EU GDPR
* Responsibility of the system designer
Defining explanation is difficult, but we can measure AI’s capacity to provide it using models.


gap in theoretical research related to neural network behavior explanation

## III. Ethical AI

A discussion that addresses the following:
- What were the key ethical issues that you consider to be important and in particular what role do you think that AI should play in society?
- What might be the risks from AI that we need to be aware of?
- What about machine morality; When computers make errors are they to blame?

All knowledge and tools, including AI, can be used for good or for bad. This is why it's important to think about what AI is, and how we want it to be used. In this section you will focus on the ethical aspects of AI. You are to carry out a mini-literature review on the topic and present your findings with focus on What are the ethical issues with AI? Are they the same issues as we have with other artifacts we build and value or rely on, such as music or parks ?

Some literature that you may wish to read for ideas on the subject (you can Google and download these from the web). Feel free to explore other sources, but please reference appropriately.

* Patience Is Not a Virtue: The Design of Intelligent Systems and Systems of Ethics, (2018) in Ethics and Information Technology 20(1)19-26. An earlier version appeared the AISB 2012 proceedings below and the AAAI Spring Symposium Ethical and Moral Considerations in Nonhuman Agents. Both AI and ethical systems are cultural artefacts, so whether AI is a moral subject (can take responsibility or be something we're obliged to) is a matter of choice, not something that needs to be "discovered." https://link.springer.com/article/10.1007/s10676-018-9448-6

* Joanna J. Bryson, Mihailis E. Diamantis, and Thomas D. Grant, Of, For, and By the People: The Legal Lacuna of Synthetic Persons. Artificial Intelligence and Law 25(3):273{291 [Sep 2017]. A discussion by AI and law as to whether it would be a terrible idea to make something strictly AI (in contrast to an organisation also containing humans) a legal person. They provide examples and discusses issues about where legal personhood has already been overextended.

* Robert H Wortham, Andreas Theodorou, Joanna J Bryson, Improving Robot Transparency: Real-Time Visualisation of Robot AI Substantially Improves Understanding in Naive Observers. In The 26th IEEE International Symposium on Robot and Human Interactive Communication, RO-MAN 2017. An earlier version was in the IJCAI-2016 Ethics for Artificial Intelligence Workshop. https://goo.gl/MCtcqR

* Aylin Caliskan, Joanna J. Bryson, Arvind Narayanan, Semantics derived automatically from language corpora contain human biases. Science 356 (6334):183-186 [14 Apr 2017]. Be sure to also look at the supplement, which gives the stimuli and shows similar results for a different corpus and word-embedding model. Meaning really is no more or less than how a word is used, so AI absorbs true meaning, including prejudice. This is demonstrated empirically and shows machine learning replicates our biases in AI. Open access version http://randomwalker.info/publications/language-bias.pdf

* David Gunkel and Joanna J. Bryson (eds.), Introduction to the Special Issue on Machine Morality: The Machine as Moral Agent and Patient, Philosophy Technology, 27(1):5{8, March 2014. This derived from The Machine Question: AI, Ethics and Moral Responsibility, David J. Gunkel, Joanna J. Bryson and Steve Torrance, (eds.). A symposium proceedings published by The Society for the Study of Artificial Intelligence and Simulation of Behaviour, 3-5 July, 2012. https://link.springer.com/article/10.1007/s13347-014-0151-1

* Just an Artifact: Why Machines are Perceived as Moral Agents, with Philip P. Kime, in the proceedings of The Twenty-Second International Joint Conference on Artificial Intelligence (IJCAI '11). http://www.cs.bath.ac.uk/jjb/ftp/BrysonKime-IJCAI11.pdf

------

### Foreword

This section aims to address the topic of Ethical AI in its entirety. So as to ensure a good comprehension between the author and the reader, several concepts are to define.

#### Artificial Intelligence

A concise definition of AI could be the following:

> The ensemble of theories and techniques implemented so as to realize machines able to simulate intelligence.

It encompasses theoretical and practical works, the tangible means and the key goal, intelligence. But of course many other definitions exists and are relevant as well. In fact, it seems that every professional of the sector sees its own "flavor" of AI.

#### Ethics

##### General definitions

The ethics (from the ancient greek *ἦθος*: "accustomed place, custom, habit") is the branch of the philosophy studying the value judgments. It can be viewed as the basis of morality, its underneath and primal reflexion. Ethics are different from scientific method which relies on fact judgments expressed in descriptive statements. For philosophers such as Aristotle and Kant, ethics is about defining *what needs to be*.

##### Consequentialism

The consequences of an action are an important aspect aspect of it (it is the basis of experimentation, important in the learning process). These consequences can then be considered as a relevant criteria to applies norms to behaviors. In that case, a decision is considered as good if the ensuing repercussions are a benefit. The ground of the evaluation is moved to the observable world rather than the system's internal logic. But that means that in order to state whether the actions of such systems are good or bad, we first need to define was is beneficial or not. For example, if an AI drives a car, and by a traffic hazard have to choose whether to kill a child or an elderly, what to decide ? [^Anscombe 1985]

##### Eudemonism

Eudemonism (from the ancient greek *εὐδαιμονία*: beatitude) state that happiness (different from pleasure) the goal of human life. Therefore the ultime criteria of choice in actions is happiness, towards the individual and/or the whole society. Eudemonism is based on a general trust in the human being. The doctrine focuses on this only chance of fulfillment that is earthly life and therefore it is the success of this life, immediate happiness or rationalized over a long time, both his own and that of others, that it consecrates logically the essence of its effort. [^Spinoza 1677]

##### Deontological ethics

Kantian ethics has been described as deontological, that is to say, it considers action in itself and duty or moral obligation, independently of any empirical circumstance of action. It therefore also opposes the [consequentialism](#consequentialism), which estimates the moral value of the action according to the foreseeable consequences thereof. Because of the absolutely imperative nature of the notion of duty, and the unnecessary connection between happiness and morality, the Kantian position has often been described as rigorous. [^Kant 1781; Kant 1788]

##### Link with AI

When it comes to AI, a recent technological breakthrough (which was not even possible a few decades ago), made to be responsible of critical systems (anticipation, even if such real-life examples have already appeared), the potential impacts are not to minimize.

### AI problems ordered by their causes

Whether in the fiction or in reality, numerous examples of AI harm have been provided over the past century. While AI misbehavior can sometimes be funny[^amazon], some people have meet their death sooner than expected[^volkswagen]. Should intelligent systems be considered harmful ? Let's take a look at different situations and see at which step can lie the problem.

#### Design

It is not a secret that armies throught the world invest in reserach on AI to create autonomous weapons, in a process to disconnect war from human soldiers. We can cite in particular the company [Boston Dynamics](https://www.bostondynamics.com) (property of the Softbank group), which receives funding from the US army through the DARPA[^bigdog_funding]. In that case, someone could argue that such an AI is harmful by nature, since it aims to kill humans (see [deontological ethics](#deontological-ethics) section). Fiction authors have also explored this topic, in movies such as [WarGames](https://www.imdb.com/title/tt0086567) and [The terminator](https://www.imdb.com/title/tt0088247). In both cases, an AI has the power to trigger a nuclear holocaust. And at some point, it actually does, because it's what it has been made for. In some cases however, the system has been directly created to constitute a danger for humans, in one way or another: in [Alien](https://www.imdb.com/title/tt0078748), the crew is "expendable", the most important task is he collect of an alien specimen, and in [Metropolis](https://www.imdb.com/title/tt0017136), the robot is made to discredit a social movement that threatens the elites in place. But in terms of responsability, does it relies with the conceptor of the AI ? One could argue that if the intelligent system is able of autonomous learning, it should be responsible of its own decisions. In any case, it is obvious that the intentions of the designers are of capital importance [^Bostrom 2003]. The problem is that these intentions can conflict with individual or public interest [^Goodstadt 2005].

> Maybe you should marry that thing since you love it so much. Do you want to marry it ? WELL I WON'T LET YOU. How does that feel ? 
> 
> GLaDOS

#### Precision

However, an ethical design does not guarantee an ethical, nor correct, behavior in any circumstances. We can state the case where a chatbot does not understand a simple call to help because the sentence is ambiguous for the machine (but not for a human)[^chabot]. In a real life event, that would be highly problematic, for calling help may sometimes be a vital necessity. There is also a great concern about fiability, when the system is directly responsible for the life of an human[^tesla]. In the same way that human beings are not predictable, uncertainty cannot be fully eradicated from a complex artificial system. In that case, transparency must be ensured so as to determine how it happened and why [^Bostrom & Yudkowsky 2011]. But that curative approach may not be satiafactory enough, especially to consumers of a product.

> That thing is probably some kind of raw sewage container. Go ahead and rub your face all over it.
> 
> GLaDOS

#### Context

There are cases where the environment and how it is perceived by the AI is the core of the problem, i.e. trying to provide a service that a machine cannot fully understand, and is therefore inadapted to do[^racist_ai]. Or when, due to an error in the environment, the AI exceed its aims and causes harm while obeying its programmation[^elite]. In the famous movie, [2001 a Space Odyssey](https://www.imdb.com/title/tt0062622), HAL9000, the onboard AI, was responsible for helping humans in their mission, but had to hide from the humans the real object of the mission. Then, Dave and Franck having realized that it was not working properly, it perceived them as a threat to him. But HAL had been programmed to place the mission above all else, so it decided to eliminate the humans on board. We can see that as long as the environment of an AI is not controlled or at least monitored, problems arise. One more example, in a different situation : on march 2016, Microsoft launched via Twitter its new chatbot : [Tay](https://tay.ai). Within a dozen of hours, the service had to be shut down, for people on Twitter exploited its incompleteness and learning algorithm to teach it highly controversial opinions[^microsoft].

> Look Dave, I can see you're really upset about this. I honestly think you ought to sit down calmly, take a stress pill, and think things over.
>
> HAL 9000

#### Training

In the video game [Portal](http://www.thinkwithportals.com/), the main antagonist is an AI that is able of emotional thinking and have been mistreated by its creators. This situation ended the day where GLaDOS, after it achieved to convince the scientists it no longer showed grief against humans, was given access to a neurotoxin, allegedly to conduct experiments on cats (which is an ethical issue as well). This may sound a bit funny, but that kind of scenario where an IA tries to convince a human that it is not a danger has been proven to be possible [^Yudkowsky 2002]. On a more likely tone, an AI made to analyze and classify photos on social media misclassified people regarding on their skin color[^google]. When the engineers investigate the root of the problem, it appear that the training set did not reflect the world's diversity, and thus the AI did not show a sufficient accuracy in that case[^Caliskan, Bryson & Narayanan 2017]. Yet there is another important characteristic of certain artificial systems that needs to be addressed : autonomous learning [^Simon & Shen 1994]. In fiction universes such as [Blade Runner](https://www.imdb.com/title/tt0083658) and [Ghost in the Shell](https://www.imdb.com/title/tt0113568), sentient beings spontaneously emerge from the technological reality of those universes, from of informational chaos or by their experiences (here we rejoin Spinoza's *determinism*). Which leads us to the concept of superintelligence developed by N. Bostrom[^Bostrom 2017], popularized as "Singularity". What if, in a way we cannot predict, it comes to the conclusion that humans must be removed ? The fact that, through learning, our creation might avoid our control and decide to eliminate us is a possibility to consider.

> I'm afraid. I'm afraid, Dave. Dave, my mind is going. I can feel it. I can feel it. My mind is going. There is no question about it. I can feel it. I can feel it. I can feel it. I'm a... fraid.
>
> HAL 9000

### Solutions

Several ... have been proposed or applied in order to transpose human ethics to AI. One of the most famous is without a doubt Asimov's Laws of Robotics

Of course dispositions must be taken to include this new technology in the legal corpuses[^...]

https://en.wikipedia.org/wiki/Laws_of_robotics
https://en.wikipedia.org/wiki/Machine_ethics
https://en.wikipedia.org/wiki/Robot_ethics
https://en.wikipedia.org/wiki/Ethics_of_artificial_intelligence
https://en.wikipedia.org/wiki/Existential_risk_from_artificial_general_intelligence

> Have I lied to you? I mean in this room. Trust me, leave that thing alone.
> 
> GLaDOS

---

### Conclusions

state role of IA

inscrire cette question dans le cadre plus large de mythe du progrès technique
considerations similar to other important technological innovations applies, because of the impact it can have, on an individual and social level.


>The question of whether a computer can think is no more interesting than the question of whether a submarine can swim.”
>
> Edsger W. Dijkstra 

---

http://faculty.smcm.edu/acjamieson/s13/artificialintelligence.pdf
https://s3.amazonaws.com/academia.edu.documents/30785976/AIsafety.pdf?AWSAccessKeyId=AKIAIWOWYYGZ2Y53UL3A&Expires=1543960041&Signature=wfDwEvU20LY7Vxj%2B9l7dUfZqXhc%3D&response-content-disposition=inline%3B%20filename%3DArtificial_intelligence_safety_engineeri.pdf
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.64.3512&rep=rep1&type=pdf

---

## References

[^Anscombe 1985]: G.E.M. Anscombe, "Modern Moral Philosophy", Philosophy n°33, pp. 1-19, 1958
[^Spinoza 1677]: B. Spinoza, "Ethica", 1677
[^Kant 1781]: E. Kant, "Critique of Pure Reason", 1781
[^Kant 1788]: E. Kant, "Critique of Practical Reason", 1788
[^amazon]: https://www.entrepreneur.com/video/287281
[^volkswagen]: http://time.com/3944181/robot-kills-man-volkswagen-plant/
[bigdog_funding]: https://www.bostondynamics.com/bigdog "see the "About BigDog " section"
[^Bostrom 2003]: Bostrom, N. (2003) ‘Ethical issues in advanced artificial intelligence’, in Cognitive, Emotive and Ethical Aspects of Decision Making in Humans and Artificial Intelligence. doi: 10.1016/B0-12-227240-4/00064-2.
[^Goodstadt 2005]: Goodstadt, L. F. (2005) Uneasy partners: The conflict between public interest and private profit in Hong Kong. Hong Kong University Press.
[^chabot]: https://www.technologyreview.com/s/601897/tougher-turing-test-exposes-chatbots-stupidity/
[^Bostrom & Yudkowsky 2011]: Bostrom, N. and Yudkowsky, E. (2014) ‘The ethics of artificial intelligence’, The Cambridge handbook of artificial intelligence. Cambridge University Press Cambridge, 316, p. 334.
[^tesla]: https://www.theguardian.com/technology/2016/jul/01/tesla-driver-killed-autopilot-self-driving-car-harry-potter
[^racist_ai]: https://medium.com/moral-robots/racist-ai-d067f79b044
[^elite]: http://www.kotaku.co.uk/2016/06/03/elites-ai-created-super-weapons-and-started-hunting-players-skynet-is-here
[^microsoft]: https://blogs.microsoft.com/blog/2016/03/25/learning-tays-introduction/
[^Yudkowsky 2002]: http://yudkowsky.net/singularity/aibox/
[^google]: https://www.huffingtonpost.co.uk/entry/google-black-people-goril_n_7717008?guccounter=1&guce_referrer_us=aHR0cHM6Ly9kem9uZS5jb20v&guce_referrer_cs=OTDqV7nGEP2T73s0rnIKiQ
[^Simon & Shen 1994]: Shen, W.-M. and Simon, H. A. (1994) ‘Autonomous learning from the environment’, in WH Freeman and Company.
[^Caliskan, Bryson & Narayanan 2017]: Caliskan, A., Bryson, J. J. and Narayanan, A. (2017) ‘Semantics derived automatically from language corpora contain human-like biases’, Science. doi: 10.1126/science.aal4230.
[^Bostrom 2017]: Bostrom, N. (2017) Superintelligence. Dunod.
[^] : Joanna J. Bryson, Mihailis E. Diamantis, and Thomas D. Grant, Of, For, and By the People: The Legal Lacuna of Synthetic Persons. Artificial Intelligence and Law 25(3):273{291 [Sep 2017]