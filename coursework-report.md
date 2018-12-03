# CM4107 CW Part2: Submission Template

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

definitions

AI
...

harm
...

ethics
L’éthique (du grec ethos « caractère, coutume, mœurs »1) est une discipline philosophique portant sur les jugements de valeur. L'éthique se définit telle une réflexion fondamentale2 sur laquelle la morale établira ses normes, ses limites et ses devoirs3. Sa formulation se caractérise par des énoncés normatifs, prescriptifs ou encore évaluatifs parmi lesquels on trouve des impératifs catégoriques. La démarche éthique se distingue donc de la démarche scientifique qui elle se base sur des jugements de fait formulés dans des énoncés descriptifs, parmi lesquels on trouve des impératifs hypothétiques4. En absence d'impératif catégorique une formulation éthique relève d'une faute de logique intitulée paralogisme naturaliste. Pour des philosophes tel que Aristote et Kant, l'éthique a pour but de définir ce qui doit être5.

Conséquentialisme

Dans les actions, l'humain prend souvent en compte les conséquences de ses actes. Ces conséquences peuvent donc être considérées comme des critères possibles de notre comportement, ce qui fait de ce type de morale, un type normatif. Pour une morale de ce genre, une conduite est morale si les conséquences d’un acte sont plutôt bénéfiques que défavorables. L’évaluation de la moralité d’une conduite se fait donc sur la base de ce qui est observable, plutôt que sur l’intention qui a un caractère privé et difficile à appréhender.

Plusieurs types de conséquentialisme peuvent être distingués, selon le critère choisi pour déterminer ce qui est bénéfique et ce qui est nuisible :
* l’altruisme, qui cherche à maximiser le bénéfice d'autrui, sans considération des avantages ou désavantages pour l'auteur,
* l’égoïsme, qui cherche à maximiser le bénéfice de l'auteur,
* l’utilitarisme, qui vise le bien de la majorité des parties prenantes.

L'éthique de l'informatique est une branche de l'éthique appliquée qui traite de la façon dont les usagers et les professionnels de l'informatique font un usage de l'information et prennent des décisions au regard de critères éthiques.

L'éthique de l'informatique s'intéresse tant à la gouvernance (décision du management) qu'au comportement individuel des utilisateurs et des professionnels de l'informatique.

La morale (du latin moralis « relatif aux mœurs »1) est une notion qui désigne l'ensemble des règles ou préceptes, obligations ou interdictions relatifs à la conformation de l'action humaine aux mœurs et aux usages d'une société donnée. Aujourd'hui la notion d'éthique s'impose dans la communauté scientifique. Bien qu'étymologiquement proche, la morale se distingue de l'éthique qui se définit telle une réflexion fondamentale2 sur laquelle la morale établira ses normes, ses limites et ses devoirs3. De la morale est née la philosophie morale qui se distingue de la métaphysique de par son aspect pratique. Une action immorale est parfois une action nuisible comme le vol. La morale ne doit pas être confondue ni avec la casuistique ni avec l'idéologie4.

En s'intéressant à la question du bien et du mal, la morale se distingue de la logique5 (dont les valeurs sont le vrai et le faux), du droit (le juste et l'injuste), de l'Art (le beau et le laid) et de l'économique (l'utile et l'inutile). C'est d'après ces valeurs que la morale fixe des principes d'action, qu'on appelle les devoirs de l'être humain, vis-à-vis de lui-même, ou des autres individus, ou de l'ensemble de la société, ou d'idéaux plus élevés (la tradition, l'harmonie, la paix, les dieux, etc.), principes qui définissent ce qu'il faut faire et comment agir. 

Kant, Nietzsche
https://medium.com/moral-robots/kants-ethics-summary-a96ea67bc504
considerations similar to other important technological innovations applies, because of the impact it can have, on an individual and social level.

---

enumerate problems

**fails**
https://en.wikipedia.org/wiki/Tay_(bot)
https://www.technologyreview.com/s/601897/tougher-turing-test-exposes-chatbots-stupidity/
http://time.com/3944181/robot-kills-man-volkswagen-plant/
https://www.huffingtonpost.co.uk/entry/google-black-people-goril_n_7717008?guccounter=1&guce_referrer_us=aHR0cHM6Ly9kem9uZS5jb20v&guce_referrer_cs=OTDqV7nGEP2T73s0rnIKiQ
http://www.kotaku.co.uk/2016/06/03/elites-ai-created-super-weapons-and-started-hunting-players-skynet-is-here
https://www.theguardian.com/technology/2016/jul/01/tesla-driver-killed-autopilot-self-driving-car-harry-potter
https://www.entrepreneur.com/video/287281

Boston Dynamics => US army (DARPA funding)

existential threat
​	* by design
​		- The terminator
​		- Alien
​		- WarGames
​		- Black Mirror (Metalhead)
​	* by evolution
​		- 2001 a space odyssey
​		- The Matrix
​		- Portal 1 & 2
​		- Tron

in between
- Blade Runner

non existential threat
- Ghost in the shell
- Metropolis
- WALL-E
- Black Mirror (Be Right Back)

https://medium.com/moral-robots/racist-ai-d067f79b044

---

enumerate reasons(precision, context, training)

AI drives a car, have to choose between kill a child or an elder

---

present solutions

https://en.wikipedia.org/wiki/Laws_of_robotics
https://en.wikipedia.org/wiki/Machine_ethics
https://en.wikipedia.org/wiki/Robot_ethics
https://en.wikipedia.org/wiki/Ethics_of_artificial_intelligence

---

state role of IA

---

## References

Provide references in the format: 

[1] G. Eason, B. Noble, and I.N. Sneddon, “On certain integrals of Lipschitz-Hankel type involving products of Bessel functions,” Phil. Trans. Roy. Soc. London, vol. A247, pp. 529-551, April 1955. (*references*)