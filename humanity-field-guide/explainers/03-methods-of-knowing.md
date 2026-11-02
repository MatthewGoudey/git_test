# Domain 3: Methods of Knowing

Humans make claims constantly: about the weather, the cause of a disease, the guilt of an accused person, the existence of gods. This domain describes the tools humans have built for deciding which claims to trust: mathematics, logic, the scientific method, and statistics. It also describes the ways those tools fail. These methods are why the rest of this guide labels claims as [Established], [Refining], [Contested], or [Belief/Value]. The labels report how much of this machinery stands behind a claim.

---

### 3.1 Mathematics

**In one sentence:** Mathematics is the study of quantity, structure, space, and pattern, carried out by drawing conclusions from starting assumptions with complete logical rigor.

**What an alien needs to know first:** Humans count in **base 10** (ten symbols, 0–9, probably because they have ten fingers). A **number** is an abstract quantity. An **axiom** is a starting assumption accepted without proof. A **proof** is a chain of steps showing that a statement must follow from the axioms. A **theorem** is a statement that has been proved. Unlike scientific results, a correct proof is not revised by new evidence. It stays true for as long as its axioms are accepted.

**How it works:** Mathematicians define objects (numbers, shapes, sets, functions), choose axioms about them, and prove theorems. The main branches are:

| Branch | What it studies | Typical use |
|---|---|---|
| Arithmetic and number theory | Whole numbers and their properties | Accounting; modern encryption |
| Geometry | Shapes, distance, space | Surveying, architecture, navigation |
| Algebra | Rules for manipulating symbols that stand for unknowns | Solving equations in every technical field |
| Calculus | Continuous change (rates and accumulation) | Physics, engineering, economics |
| Probability and statistics | Uncertainty and data | Medicine, insurance, polling (see 3.4) |
| Discrete mathematics and logic | Finite structures, algorithms | Computing |

Mathematics is the language of science because physical laws can be written as equations that predict measurements, often to many decimal places. One physicist called this "the unreasonable effectiveness of mathematics" (Eugene Wigner, 1960). Why it works so well is not fully understood.

**How it developed:**
- **~20,000–40,000 years ago:** notched bones that may be tally marks [Contested whether they record counts].
- **~3000–1800 BCE:** Mesopotamian scribes use a base-60 system (still visible in 60-minute hours and 360-degree circles). Egyptian papyri show practical geometry and fractions.
- **~600–300 BCE:** Greek thinkers introduce deductive proof. Euclid's *Elements* (~300 BCE) organizes geometry from a few axioms and was used as a textbook for over 2,000 years.
- **~200 BCE–200 CE:** China's *Nine Chapters on the Mathematical Art* uses negative numbers and methods for solving systems of equations.
- **~500–630 CE:** Indian mathematicians develop the **place-value decimal system with zero as a number** (Brahmagupta, 628). Maya astronomers in Central America independently used a zero in a base-20 system.
- **~820:** al-Khwarizmi, in Baghdad, writes the book that gives "algebra" its name. Through Arabic texts, Indian numerals reach Europe ("Arabic numerals"), spreading widely after ~1200.
- **1660s–1680s:** Isaac Newton and Gottfried Leibniz independently develop **calculus**.
- **1800s:** geometries that drop Euclid's parallel-line axiom are shown to be consistent. Later, Einstein's theory of gravity used one of them.
- **1931:** Kurt Gödel proves that any consistent formal system rich enough to describe arithmetic contains true statements it cannot prove (see 3.2).
- **1976 onward:** computers help prove theorems (the four-color theorem). In 1994 Andrew Wiles proves Fermat's Last Theorem, open for ~350 years.

**Effects on human life and society:** All engineering, finance, computing, and physical science depend on mathematics. Encryption based on number theory secures online banking and messaging for billions of people. Numeracy (basic skill with numbers) is linked to income and health in many studies. School mathematics is compulsory almost everywhere, and large international tests (such as PISA, given to 15-year-olds in ~80 countries) compare countries on it.

**Major ideas, schools, or ideologies:** What *are* mathematical objects? [Contested]
- **Platonism:** numbers and shapes exist independently of humans, and mathematicians discover them.
- **Formalism:** mathematics is the manipulation of symbols by rules. Its objects need not "exist."
- **Intuitionism/constructivism:** an object exists only if it can be constructed. This rejects some standard proofs.
- **Logicism:** mathematics reduces to logic. This program was weakened by Gödel's results.

Working mathematicians mostly agree on which proofs are valid, whatever their philosophy.

**Key works and figures:**
- Euclid, *Elements* (~300 BCE): the model of axiomatic proof.
- Brahmagupta, *Brāhmasphuṭasiddhānta* (628): rules for zero and negative numbers.
- al-Khwarizmi (~820): algebra; the word "algorithm" comes from his name.
- Newton and Leibniz: calculus, the mathematics of change.
- Carl Friedrich Gauss (1777–1855): foundational work in number theory, statistics, geometry.
- Kurt Gödel (1931): the incompleteness theorems.

**What is established vs. debated:**
- Established: proved theorems, given their axioms. The usefulness of mathematics in science and engineering.
- Debated: whether mathematical objects exist independently; whether computer-assisted proofs fully count as human understanding.
- Matters of belief or value: which problems are worth studying; mathematical beauty.

**Open questions:** Thousands of unsolved problems exist. Famous ones include the **Riemann hypothesis** (about the distribution of prime numbers, open since 1859) and **P vs. NP** (whether every problem whose answer can be checked quickly can also be solved quickly). In 2000 a private institute offered US$1 million each for seven such problems. One (the Poincaré conjecture) was solved by Grigori Perelman in 2002–03. Humans also do not know *why* mathematics describes nature so well.

**See also:** 3.2 Logic and Reasoning; 3.4 Statistics, Probability, and Measurement; 2.1 Physics; 12.6 Computing, the Internet, and Artificial Intelligence; 11.2 Knowledge, Reality, and Mind.

---

### 3.2 Logic and Reasoning

**In one sentence:** Logic is the study of which conclusions actually follow from which starting statements, and reasoning is the everyday human practice of drawing conclusions, done well or badly.

**What an alien needs to know first:** An **argument** is a set of statements (**premises**) offered in support of another statement (the **conclusion**). An argument is **valid** if the conclusion *must* be true whenever the premises are true. It is **sound** if it is valid *and* its premises are actually true. A **fallacy** is a common pattern of reasoning that looks convincing but is not valid.

**How it works:** Humans distinguish three main kinds of inference:

| Kind | Form | Example | Certainty |
|---|---|---|---|
| **Deduction** | From general rules to a specific case | All humans die; Ada is human; so Ada will die | Certain, if premises are true |
| **Induction** | From observed cases to a general rule | Every observed swan was white; so all swans are white | Probable only; one counterexample breaks it (black swans exist in Australia) |
| **Abduction** | To the best available explanation | The grass is wet; rain is the likeliest cause | Plausible; can be wrong |

Science relies heavily on induction and abduction, and uses deduction to work out what a hypothesis predicts. **Formal logic** writes arguments in symbols so that validity can be checked mechanically. That mechanical checking is the basis of computers: electronic circuits ("logic gates") carry out the operations AND, OR, and NOT billions of times per second.

Common fallacies include:
- **Ad hominem:** attacking the person instead of the argument.
- **Straw man:** refuting a weaker version of the opponent's claim.
- **False dilemma:** presenting two options when more exist.
- **Circular reasoning:** assuming the conclusion in the premises.
- **Affirming the consequent:** "If it rained, the grass is wet; the grass is wet; so it rained." (Sprinklers also wet grass.)

Humans are not natural logicians. In a well-known test (the Wason selection task, 1966), most people, often over 75%, fail a simple abstract rule-checking puzzle. They do much better when the same logic is framed as detecting someone breaking a social rule [Refining: the explanation is debated].

**How it developed:**
- **~350 BCE:** Aristotle (Greece) systematizes the **syllogism**, a form of deduction. His logic dominated in Europe and the Islamic world for ~2,000 years.
- **~300–200 BCE:** Stoic philosophers (Greece) develop logic of whole propositions ("if…then," "or"). In China, the Mohist school studies argument and definition.
- **~200 BCE–600 CE:** India's Nyaya school and Buddhist logicians (Dignaga, Dharmakirti) build detailed theories of inference and valid knowledge.
- **~1000s:** Ibn Sina (Avicenna) extends Aristotelian logic in the Islamic world.
- **1748:** David Hume argues that induction cannot be justified without circular reasoning (the "problem of induction").
- **1854:** George Boole writes logic as algebra. In 1937, Claude Shannon shows Boolean algebra can describe electrical switching circuits, the basis of digital computers.
- **1879:** Gottlob Frege invents modern predicate logic.
- **1910–13:** Russell and Whitehead attempt to derive mathematics from logic (*Principia Mathematica*).
- **1931–36:** Gödel proves limits on formal systems; Alan Turing and Alonzo Church prove that no general procedure can decide the truth of every mathematical statement.

**Effects on human life and society:** Every digital device runs on formal logic. Legal systems, scholarly debate, and many education systems teach argument structure. Logic also underlies software verification, used for aircraft control and chip design.

**Major ideas, schools, or ideologies:**
- **Classical logic:** every statement is true or false.
- **Non-classical logics:** modal logic (necessity and possibility), fuzzy logic (degrees of truth, used in control systems), intuitionistic logic, and paraconsistent logic (tolerates some contradictions). Each is useful for particular purposes. Which, if any, is "the correct logic" is [Contested].
- **Dual-process psychology:** human reasoning combines fast intuition and slow deliberation (see 15.3) [Refining].

**Key works and figures:**
- Aristotle, *Prior Analytics* (~350 BCE): the first systematic formal logic.
- Nyaya Sutras (attributed to Gautama, ~2nd c. BCE–2nd c. CE): Indian theory of valid knowledge.
- David Hume, *An Enquiry Concerning Human Understanding* (1748): the problem of induction.
- George Boole, *The Laws of Thought* (1854): logic as algebra.
- Gottlob Frege, *Begriffsschrift* (1879): modern formal logic.
- Kurt Gödel (1931) and Alan Turing (1936): the limits of formal reasoning.

**What is established vs. debated:**
- Established: the validity of standard inference rules within classical logic; Gödel's and Turing's limits; that humans commit predictable reasoning errors.
- Debated: how to justify induction; which logic best describes truth; why humans reason as they do.
- Matters of belief or value: how much weight to give reason versus intuition, tradition, or revelation.

**Open questions:** Whether induction can be justified at all. How human brains actually implement reasoning. Whether machine reasoning systems (see 16.5) reason in a humanlike way or by other means.

**See also:** 3.1 Mathematics; 3.3 The Scientific Method; 11.2 Knowledge, Reality, and Mind; 15.3 Cognitive Biases and Decision-Making; 12.6 Computing, the Internet, and Artificial Intelligence.

---

### 3.3 The Scientific Method

**In one sentence:** Science is a set of practices for testing ideas about the natural world against careful observation, so that wrong ideas can be found and discarded.

**What an alien needs to know first:** A **hypothesis** is a proposed explanation that makes testable predictions. An **experiment** is a deliberate test, ideally changing one factor while holding others constant. A **control group** is a comparison group that does not receive the treatment being tested. In science, a **theory** is *not* a guess. It is a broad, well-tested explanation (e.g., the theory of evolution, the germ theory of disease). **Falsifiability** means a claim could in principle be shown false by some observation. **Peer review** is the checking of a study by other experts before publication. **Replication** is repeating a study to see if the result holds. **Consensus** is broad agreement among experts after the evidence has been weighed.

**How it works:** The idealized cycle is:
1. Observe something puzzling.
2. Propose a hypothesis.
3. Derive a prediction that could fail.
4. Test it by experiment or systematic observation.
5. Publish methods and results so others can check and repeat them.
6. Revise, reject, or provisionally accept the hypothesis.

Real science is messier, and much of it (astronomy, geology, epidemiology) is observational rather than experimental. Its strength is **collective and self-correcting**: individual scientists have biases, but a community that rewards finding others' errors tends to correct them over time.

Consensus changes when evidence accumulates. Examples:
- **Continental drift** was proposed in 1912 and widely rejected. It was accepted in the 1960s once seafloor evidence explained the mechanism (plate tectonics).
- **Stomach ulcers** were thought to be caused by stress. In 1982, Barry Marshall and Robin Warren showed a bacterium causes most of them, and antibiotics became the standard treatment (Nobel Prize, 2005).

Scale today: roughly 9 million full-time-equivalent researchers worldwide, over 3 million scientific papers published per year, and research spending of about 2% of world GDP (on the order of US$2.5–3 trillion a year). The United States and China are the largest funders.

**How it developed:**
- **Antiquity:** systematic observation in Babylonian astronomy, Greek natural philosophy (Aristotle), Chinese astronomy and medicine, and Indian mathematics and medicine.
- **~1011–1021:** Ibn al-Haytham (Cairo) uses controlled experiments in his *Book of Optics* and insists claims be tested.
- **1543–1687:** the **Scientific Revolution** in Europe: Copernicus, Galileo, Kepler, Francis Bacon's program of experiment (1620), and Newton's *Principia* (1687). The first scientific journals appear in 1665.
- **1800s:** science becomes a paid profession with university laboratories.
- **1934:** Karl Popper argues that falsifiability is what separates science from non-science.
- **1962:** Thomas Kuhn argues that science alternates between "normal science" and occasional **paradigm shifts** (revolutions in basic framework).
- **Mid-1900s:** formal peer review becomes standard at major journals.
- **2010s–present:** the replication crisis (see 3.5) prompts reforms such as preregistration and open data.

**Effects on human life and society:** Science is the main source of the knowledge behind modern medicine, agriculture, energy, and computing. Global life expectancy has more than doubled since 1800, from ~30 to ~73 years, largely through science-based sanitation, vaccines, and drugs. Science also produced nuclear weapons and the fossil-fuel technologies driving climate change. Trust in scientists is moderately high in most countries surveyed, but it varies by country and by political group.

**Major ideas, schools, or ideologies:**
- **Inductivism (Bacon):** gather observations, then generalize. Critics say observation is always guided by theory.
- **Falsificationism (Popper):** theories can never be proved, only survive attempts to refute them. Critics note scientists often (sensibly) keep theories despite anomalies.
- **Paradigms (Kuhn):** science is shaped by shared frameworks and community judgment, not by pure logic.
- **Bayesianism:** belief in a hypothesis should be updated in proportion to evidence, using probability (see 3.4).
- **Realism vs. instrumentalism:** do theories describe reality, or just predict well? [Contested]
- **Social critiques:** funding, power, and who does science shape which questions get asked (well documented). How far they shape the results is [Contested].

**Key works and figures:**
- Ibn al-Haytham, *Book of Optics* (~1021): early experimental method.
- Francis Bacon, *Novum Organum* (1620): the program of experiment-based knowledge.
- Isaac Newton, *Principia* (1687): the model of mathematical physical science.
- Karl Popper, *The Logic of Scientific Discovery* (1934): falsifiability.
- Thomas Kuhn, *The Structure of Scientific Revolutions* (1962): paradigms.

**What is established vs. debated:**
- Established: scientific methods have produced reliable, cumulative, technologically useful knowledge; consensus has repeatedly changed in response to evidence.
- Debated: whether one "scientific method" exists at all, or many; the best philosophical account of why science works; how to reward replication rather than novelty.
- Matters of belief or value: which research to fund; whether certain research (e.g., on weapons or human embryos) should be done at all; how science should relate to religious belief.

**Open questions:** How to make science more reliable (see 3.5). How to set research priorities fairly. How scientific practice will change as AI systems begin to generate hypotheses and analyze data.

**See also:** 3.4 Statistics, Probability, and Measurement; 3.5 How Humans Get Things Wrong; 2.1 Physics; 4.4 The Medieval and Early Modern World; 11.2 Knowledge, Reality, and Mind; 10.6 Secularism, Atheism, and Religious Change.

---

### 3.4 Statistics, Probability, and Measurement

**In one sentence:** Measurement turns the world into numbers, probability describes uncertainty, and statistics draws conclusions from imperfect, incomplete data.

**What an alien needs to know first:** A **unit** is an agreed standard quantity (a meter of length, a second of time). **Probability** is a number from 0 (impossible) to 1 (certain) expressing how likely something is. A **sample** is a subset of a larger group (the **population**) studied in order to learn about the whole. A **correlation** is a tendency for two things to vary together. **Causation** means one thing actually produces the other. A **randomized controlled trial (RCT)** assigns subjects to groups by chance so that the groups differ only in the treatment being tested.

**How it works:**

*Measurement.* Most of the world uses the **International System of Units (SI)**, with seven base units: meter, kilogram, second, ampere (electric current), kelvin (temperature), mole (amount of substance), and candela (light intensity). Since 2019, all seven are defined by fixed constants of nature rather than physical objects. The United States still mainly uses older "customary" units (feet, pounds) in daily life. Every measurement has **uncertainty**, and good practice reports it (e.g., 9.81 ± 0.01).

*Probability and sampling.* A well-chosen random sample of about 1,000 people can estimate the opinion of a country of 100 million to within about ±3 percentage points, *if* the sample is truly random. A biased sample fails however large it is. In 1936 a US magazine polled 2.4 million readers (drawn largely from car and telephone owners) and wrongly predicted a landslide defeat for the winning candidate. A pollster using a much smaller but more representative sample got it right.

*Correlation vs. causation.* Ice cream sales and drownings rise together because both rise in hot weather, a **confounder**. To test causation, humans use RCTs, natural experiments, and statistical adjustment.

*Significance and uncertainty.* A **p-value** is the probability of seeing results at least this extreme if there were really no effect. By convention, p < 0.05 is called "statistically significant." This threshold is arbitrary and widely misused (see 3.5). **Confidence intervals** give a range of plausible values instead.

*Base rates.* If a disease affects 1 in 1,000 people and a test is 99% accurate, most people who test positive are still healthy, because false positives from the 999 healthy people outnumber true cases. Humans routinely misjudge this kind of problem.

**How it developed:**
- **Ancient times:** censuses count people for taxes and armies. Han China recorded ~58 million people in 2 CE.
- **1654:** Blaise Pascal and Pierre de Fermat work out the mathematics of probability through gambling problems.
- **1713, 1763:** Jacob Bernoulli's law of large numbers; Thomas Bayes's rule for updating probabilities.
- **1795–1875:** France creates the metric system; the 1875 Metre Convention makes it international. SI is adopted in 1960.
- **~1809:** Carl Friedrich Gauss describes the **normal distribution** (the "bell curve").
- **1880s–1930s:** Francis Galton and Karl Pearson develop correlation and regression. Ronald Fisher develops randomization, significance testing, and experimental design. Note: Galton, Pearson, and Fisher were all prominent supporters of **eugenics**, a movement to "improve" human heredity that led to forced sterilizations (see 3.5).
- **1948:** a British trial of the antibiotic streptomycin for tuberculosis becomes a model for the modern RCT.
- **1950–54:** Richard Doll and Austin Bradford Hill show statistically that smoking causes lung cancer.

**Effects on human life and society:** Governments run on statistics: census counts allocate seats and money, and unemployment, inflation, and GDP figures (see 5.4) steer policy. Insurance, with several trillion dollars a year in premiums, prices risk using probability. Every approved medicine passes clinical trials. Misused statistics also cause harm, from misleading drug marketing to wrongful convictions.

**Major ideas, schools, or ideologies:**
- **Frequentist statistics:** probability is the long-run frequency of an event. This is dominant in 20th-century science.
- **Bayesian statistics:** probability is a degree of belief, updated with evidence. It is now widely used, helped by modern computing.
- Both are mathematically sound. Disputes concern interpretation and practice [Contested]. A 2016 statement by the American Statistical Association warned against over-reliance on p-values.

**Key works and figures:**
- Pascal and Fermat (1654): founding probability theory.
- Thomas Bayes (published 1763): the rule for updating beliefs on evidence.
- Ronald Fisher, *Statistical Methods for Research Workers* (1925) and *The Design of Experiments* (1935): randomization and significance testing.
- Doll and Hill (1950s): statistical proof of smoking's harm.

**What is established vs. debated:**
- Established: the mathematics of probability; that randomization and representative sampling reduce bias; that correlation alone does not prove causation.
- Debated: frequentist vs. Bayesian practice; the proper role of significance thresholds; how far observational data can establish cause.
- Matters of belief or value: which risks are acceptable; what governments should measure (e.g., GDP vs. well-being).

**Open questions:** How to infer causes reliably from huge observational datasets. How to make statistical findings robust and honestly reported. How to measure hard-to-quantify things such as well-being, intelligence, or corruption.

**See also:** 3.1 Mathematics; 3.3 The Scientific Method; 3.5 How Humans Get Things Wrong; 5.4 Growth, Development, and Poverty; 6.3 Democracy and Elections; 1.6 Health, Disease, and Medicine.

---

### 3.5 How Humans Get Things Wrong

**In one sentence:** Humans, including experts and whole institutions, regularly believe false things, and their methods for catching errors are powerful but slow and incomplete.

**What an alien needs to know first:** **Pseudoscience** is a set of claims presented as scientific but not produced or supported by scientific methods. A **conspiracy theory** explains events as the secret work of powerful groups, usually without good evidence. Some conspiracies are real; the term refers to unsupported ones. **Motivated reasoning** is the tendency to judge evidence by whether one wants its conclusion to be true. **Confirmation bias** is seeking or remembering evidence that fits existing beliefs. **Misinformation** is false information. **Disinformation** is false information spread on purpose. A **retraction** is the formal withdrawal of a published scientific paper.

**How it works:** Errors arise at several levels:
1. **Individual minds.** Human cognition takes shortcuts (see 15.3). People see patterns in noise, overweight vivid stories, remember hits and forget misses, and trust their own group. Repeating a false claim makes it feel more true (the "illusory truth effect").
2. **Social identity.** When a belief marks group membership (political, religious, national), rejecting it can cost a person socially. Then more knowledge can *increase* polarization rather than reduce it [Refining].
3. **Incentives.** Scientists are rewarded for new, positive, striking results. Companies and governments may benefit from certain conclusions. Examples: tobacco companies funded campaigns from the 1950s onward to cast doubt on the link between smoking and cancer. Some fossil-fuel interests did the same on climate science.
4. **Institutions.** Whole fields can share a mistaken assumption for decades.

**The replication crisis.** In the 2010s, attempts to repeat published studies often failed. A 2015 project repeated 100 psychology studies, and only about 36–39% produced a clearly similar result. In 2012, a drug company reported confirming only 6 of 53 landmark cancer-biology findings. Causes include small samples, flexible analysis ("p-hacking," trying analyses until one crosses p < 0.05), and journals preferring positive results. The problem is [Established]. How large it is varies greatly by field.

**Documented cases of error and harm:**
- **Witch hunts (Europe, ~1450–1750):** about 40,000–60,000 people, most of them women, were executed on the belief that they caused harm through magic. Similar accusations still lead to killings in parts of Africa, South Asia, and Papua New Guinea.
- **Scientific racism and eugenics (~1850–1945):** claims of biological racial hierarchy, presented as science, justified slavery, colonialism, and genocide. The United States forcibly sterilized roughly 60,000–70,000 people; Nazi Germany about 400,000.
- **Lysenkoism (USSR, ~1930s–1960s):** state-backed rejection of genetics damaged Soviet agriculture, and dissenting scientists were imprisoned or killed.
- **Thalidomide (1957–61):** an inadequately tested sedative caused severe birth defects in roughly 10,000 children. This led to stricter drug-approval laws.
- **The 1998 MMR-autism paper:** a fraudulent study linking a childhood vaccine to autism was retracted in 2010. It nonetheless fed lasting vaccine hesitancy and measles outbreaks.

Unsupported practices remain widespread, such as astrology and homeopathy (remedies diluted until typically no molecule of the original substance remains; large reviews find no effect beyond placebo).

**How it developed:** Greek skeptics, Indian logicians, and Islamic hadith scholars all built methods for weighing reports and sources. Francis Bacon (1620) listed "idols of the mind," the sources of human error. Retractions and research-integrity offices grew in the late 20th century. Since ~2011, the "open science" movement has pushed preregistration (stating a study's plan before collecting data), data sharing, and replication projects.

**Effects on human life and society:** Vaccine refusal contributed to measles resurgence in the 2010s, and misinformation complicated the COVID-19 response [Refining: size of effect debated]. Conspiracy beliefs are associated with lower trust in institutions and sometimes with political violence. In the US, DNA evidence has exonerated several hundred wrongly convicted people since 1989, many convicted on flawed forensics or eyewitness error.

**Major ideas, schools, or ideologies:**
- **Deficit model:** people err mainly from lack of information, so education fixes it. Evidence suggests this is only partly true.
- **Identity-protective cognition** (Dan Kahan and others): people process evidence to protect their group identity [Refining].
- **Bounded rationality** (Herbert Simon): errors come from limited time and information, not stupidity.
- **Relativist critiques:** all knowledge claims reflect power. Critics reply that this undermines correcting real errors [Contested].

**Key works and figures:**
- Francis Bacon, *Novum Organum* (1620): the "idols" of human error.
- John Ioannidis, "Why Most Published Research Findings Are False" (2005): a statistical argument that sparked reform.
- Open Science Collaboration (2015): the large psychology replication project.
- Daniel Kahneman, *Thinking, Fast and Slow* (2011): popular account of cognitive biases (some studies it cites later failed to replicate, as the author acknowledged).
- Naomi Oreskes and Erik Conway, *Merchants of Doubt* (2010): how industries manufactured doubt about science.

**What is established vs. debated:**
- Established: humans show systematic cognitive biases; many published findings fail to replicate; past expert consensus has sometimes been badly wrong; error correction does happen over time.
- Debated: how large and widespread the replication problem is; whether misinformation is rising or merely more visible; which interventions (fact-checking, education, platform rules) work best.
- Matters of belief or value: who should decide what counts as misinformation; how to balance free speech against harm.

**Open questions:** How to design institutions that correct errors faster. Whether social media and AI-generated content are making human knowledge less reliable. Why some false beliefs persist for centuries while others vanish quickly.

**See also:** 3.3 The Scientific Method; 3.4 Statistics, Probability, and Measurement; 15.3 Cognitive Biases and Decision-Making; 13.5 Propaganda, Persuasion, and Misinformation; 8.3 Race, Ethnicity, and Identity; 1.6 Health, Disease, and Medicine.
