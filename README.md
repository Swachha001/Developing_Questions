# Software Design – Question Paper (OBE-based)

**Student:** Swapnil Nag Swachha
**ID:** IT24001

**Course:** Software Engineering
**Topic:** Software Design (source: lecture material `SoftEng-Design`)
**Full Marks:** 40 | **Time:** 1 Hour
**Level:** Bachelor (BNQF Level 6)
**Cognitive domain (Bloom's Taxonomy):** C1 – Knowledge, C2 – Understanding

---

## 1. Analysis of the Lecture Material

The whole lecture file was read and grouped by topic. Three things decided the importance of a topic:

1. **Lecture structure.** The section titled "More topics on Software Design" is the instructor's own extension material (LCOM3, RFC, DIT, NOC and extra GoF patterns). The User Interface Design chapter comes last as a separate chapter. The main body is therefore: Design fundamentals → Software architecture → Design patterns (GoF, EAA).
2. **Number of concepts.** How many distinct concepts/patterns a topic covers.
3. **Depth.** Whether the topic has a formal definition, a structure, benefits and liabilities, or a worked example, because such topics give clear C1/C2 questions.

### 1.1 Main body: the topics questions are drawn from

| Topic | Concepts covered | Depth |
|-------|------------------|-------|
| GoF design patterns | Parameterized Factory, Strategy, Template Method, Adapter, Composite, Façade, Command | Each has intent, structure, benefits and liabilities |
| Enterprise Application Architecture (EAA) patterns | Domain Model, Service Layer, ORM, Data Mapper, Identity Field, Foreign Key Mapping, Association Table Mapping, three inheritance mappings, MVC, Page Controller, Front Controller, Template View, Transform View | Many patterns; pros/cons for inheritance mapping and views |
| Design quality and CK metrics | CBO (and COF), LCOM, LCOM2, WMC | Formal definitions, formulas, worked examples on `Controller` and `Rectangle` |
| Design fundamentals | Design process, design outcome, modularity, coupling, cohesion, abstraction, encapsulation, information hiding | Foundation of every later topic |
| Architectural styles | Layered, event-based, MVC, blackboard/repository, pipes and filters | Short definitions with a shell-pipeline example |

### 1.2 Which GoF and EAA patterns are used

Different from the common choice of Composite/Adapter/Façade, this paper tests the behavioral patterns **Strategy** and **Command** (both have a full intent, structure, benefits and liabilities slide set). For EAA, the web presentation patterns **Page Controller** and **Front Controller**, and the mapping patterns **Foreign Key Mapping** and **Association Table Mapping**, are tested.

### 1.3 Not used for questions

| Material | Reason |
|----------|--------|
| "More topics" section: LCOM3, RFC, DIT, NOC, Factory Method, Prototype, Singleton, Decorator, Observer | Marked by the lecture itself as extra material |
| User interface design | Separate chapter; checklist-style content with no formal definitions |
| Composite, Adapter, Façade, Template Method, Parameterized Factory | Left out to keep the paper within 1 hour |

### 1.4 Mark allocation

| Topic | Marks | Share of marks |
|-------|:-----:|:--------------:|
| GoF design patterns | 12 | 30% |
| Enterprise Application Architecture patterns | 12 | 30% |
| Design quality and CK metrics | 6 | 15% |
| Design fundamentals | 5 | 12.5% |
| Architectural styles | 5 | 12.5% |

---

## 2. Course Outcomes (CO)

No official CO list exists for this course, so the following outcomes were defined from the selected topics.

| CO | Course Outcome | Bloom Level |
|----|----------------|-------------|
| CO1 | Recall and explain the fundamental concepts of software design: design process, modularity, coupling, cohesion and information hiding. | C1, C2 |
| CO2 | Explain and apply OO design-quality metrics (CBO, WMC, LCOM2). | C1, C2 |
| CO3 | Describe architectural styles such as layered, event-based and pipes and filters. | C1, C2 |
| CO4 | Explain GoF design patterns (Strategy, Command) in terms of intent, structure, benefits and liabilities. | C1, C2 |
| CO5 | Describe enterprise application patterns for web presentation and for mapping the domain model to a database. | C1, C2 |

---

## 3. Question Paper

**Instructions:** Answer all questions. Marks are shown beside each question.

### Question 1 — Short Questions (C1: Knowledge) `[10 marks]`

| No | Question | Marks | Bloom | CO |
|----|----------|:-----:|:-----:|:--:|
| 1(a) | Define information hiding (encapsulation). | 2 | C1 | CO1 |
| 1(b) | Write the formula of LCOM2. | 2 | C1 | CO2 |
| 1(c) | In a layered architecture, on which layer does each layer depend? | 2 | C1 | CO3 |
| 1(d) | State the intent of the Strategy pattern. | 2 | C1 | CO4 |
| 1(e) | What is Foreign Key Mapping? | 2 | C1 | CO5 |

### Question 2 `[3 marks]` — C2 (Understanding), CO1
Distinguish **architectural design** from **detailed design**. What is the outcome of the design process, and why is the rationale of decisions recorded?

### Question 3 `[4 marks]` — C2 (Understanding), CO2
(a) A `Rectangle` class has m = 3 methods and a = 4 attributes (x, y, width, height). The attributes are used by 2, 2, 3 and 3 methods respectively. Calculate **LCOM2** and interpret the result. `[2 marks]`
(b) Explain what **WMC** measures and how the McCabe version is calculated. `[2 marks]`

### Question 4 `[3 marks]` — C2 (Understanding), CO3
Explain the **event-based** and the **pipes and filters** architectural styles. Give one example of pipes and filters.

### Question 5 `[5 marks]` — C2 (Understanding), CO4
Explain the **Strategy** pattern. Describe its intent, its participants, two benefits and one liability.

### Question 6 `[5 marks]` — C2 (Understanding), CO4
Explain the **Command** pattern. Describe its intent, any four participants, one benefit and one liability.

### Question 7 `[5 marks]` — C2 (Understanding), CO5
Explain the **Page Controller** and **Front Controller** patterns. For which kind of website does each work particularly well?

### Question 8 `[5 marks]` — C2 (Understanding), CO5
Explain **Foreign Key Mapping** and **Association Table Mapping**. Which kind of object relation does each one map? Why is a separate table needed for one of them?

---

## 4. Mapping of Questions to Course Outcomes

| Question | CO1 | CO2 | CO3 | CO4 | CO5 | Marks | Bloom |
|----------|:---:|:---:|:---:|:---:|:---:|:-----:|:-----:|
| 1(a) | ✔ | | | | | 2 | C1 |
| 1(b) | | ✔ | | | | 2 | C1 |
| 1(c) | | | ✔ | | | 2 | C1 |
| 1(d) | | | | ✔ | | 2 | C1 |
| 1(e) | | | | | ✔ | 2 | C1 |
| 2 | ✔ | | | | | 3 | C2 |
| 3 | | ✔ | | | | 4 | C2 |
| 4 | | | ✔ | | | 3 | C2 |
| 5 | | | | ✔ | | 5 | C2 |
| 6 | | | | ✔ | | 5 | C2 |
| 7 | | | | | ✔ | 5 | C2 |
| 8 | | | | | ✔ | 5 | C2 |
| **Total per CO** | **5** | **6** | **5** | **12** | **12** | **40** | |

## 5. Bloom's Taxonomy Distribution

| Level | Marks | Percentage |
|-------|:-----:|:----------:|
| C1 – Knowledge | 10 | 25% |
| C2 – Understanding | 30 | 75% |
| **Total** | **40** | **100%** |

## 6. Suggested Time Allocation

| Question | Marks | Time (min) |
|----------|:-----:|:----------:|
| Q1 | 10 | 8 |
| Q2 | 3 | 4 |
| Q3 | 4 | 7 |
| Q4 | 3 | 5 |
| Q5 | 5 | 8 |
| Q6 | 5 | 8 |
| Q7 | 5 | 8 |
| Q8 | 5 | 7 |
| Revision | – | 5 |
| **Total** | **40** | **60** |

---

## 7. Answer Hints (Marking Guide)

**Q1**
- (a) Grouping and packaging the internal details of an abstraction and making those details inaccessible to external entities.
- (b) LCOM2 = 1 − Σ(m_a_i) / (m·a), where m = number of methods, a = number of attributes, m_a_i = number of methods that use attribute a_i.
- (c) Each layer depends only on the next layer.
- (d) Define a family of algorithms, encapsulate each one and make them interchangeable; Strategy lets the algorithm vary independently from the clients that use it.
- (e) Maps an association between objects to a foreign key reference between tables (an object reference becomes a foreign key in the database).

**Q2 (3)**
- Architectural design (high-level design) describes how software is organized into components; detailed design describes the desired behavior of these components (1).
- Outcome: a set of models and artifacts that record the major decisions taken (1).
- The rationale of each nontrivial decision is recorded to enhance long-term maintainability (1).

**Q3 (4)**
- (a) Σ(m_a_i) = 2 + 2 + 3 + 3 = 10 and m·a = 12, so LCOM2 = 1 − 10/12 = 1/6 ≈ 0.17 (1). A value close to 0 (smaller is better) means high cohesion: most methods use most attributes (1).
- (b) WMC(A) = sum of the complexities Ci of the class's N methods (1). In the McCabe version, Ci = number of conditions + 1, where each if, for and while counts as 1 condition (a switch is first transformed into if conditions). Lines of code (LOC) is the alternative measure (1).

**Q4 (3)**
- Event-based: event producers and consumers; consumers register for events and the producers' events are distributed to them (1.5).
- Pipes and filters: data flows through a chain of filters, where the output of one filter is the input of the next (1). Example: `ls -l | grep "Aug" | sort | more` (0.5).

**Q5 (5)**
- Intent: define a family of algorithms, encapsulate each one, make them interchangeable (1).
- Participants: Strategy (common interface of all algorithms), ConcreteStrategy (implements the algorithm), Context (configured with a ConcreteStrategy and holds a reference to the Strategy) (1).
- Benefits, any two: Context is isolated from the algorithm's implementation details; new strategies are added without changing Context; complex conditionals in Context are avoided; algorithms can be swapped at runtime (2).
- Liability, any one: specifying a common interface for different algorithms may not be easy; strategies increase the number of objects in an application (1).

**Q6 (5)**
- Intent: encapsulate an action as an object, letting you parameterize clients with different actions, queue or log actions, and support undoable/redoable actions (1).
- Participants, any four (0.5 each): Command (interface for executing an action); ConcreteCommand (binds a Receiver to an action, implements Execute by calling the Receiver); Client (creates a ConcreteCommand and sets its receiver); Invoker (asks the command to carry out the request); Receiver (knows how to perform the operations) (2).
- Benefit, any one: decouples the invoker from the object that knows how to perform the operation; commands can be composed, queued or logged; new commands are added without changing existing classes (1).
- Liability, any one: code may become more complicated because of the new layer between invokers and receivers; a common interface for different commands may not be easy to specify (1).

**Q7 (5)**
- Page Controller: one controller module handles the request for a specific page or action of the website, tied to each action such as clicking a link or button (1.5). Works well where the navigational logic is simple (1).
- Front Controller: one controller handles all requests for the website (1). It has two parts: a Web handler that receives the requests and a command hierarchy that carries out the action (1). Works well where the navigational logic is more complex (0.5).

**Q8 (5)**
- Foreign Key Mapping: an object reference is stored as a foreign key in the database; maps one-to-one, many-to-one and one-to-many relations (e.g. Route → Driver, Route → Service, Route → Stop) (2).
- Association Table Mapping: saves a many-to-many association as a separate table holding foreign keys to the tables linked by the association (2).
- A separate table is needed for many-to-many because a single foreign key column cannot hold multiple references (1).
