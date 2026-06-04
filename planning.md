# Project 1 Planning: The Unofficial Guide

> Write this document before you write any pipeline code.
> Your spec and architecture diagram are what you'll use to direct AI tools (Claude, Copilot, etc.) to generate your implementation — the more specific they are, the more useful the generated code will be.
> Update the Retrieval Approach and Chunking Strategy sections if you change your approach during implementation.
> Update this file before starting any stretch features.

---

## Domain

<!-- What domain did you choose? Why is this knowledge valuable and hard to find through official channels? -->

Student Reviews of CS Professors

## Documents

<!-- List your specific sources: URLs, subreddit names, forum threads, or file descriptions.
     Aim for at least 10 sources that together cover different subtopics or perspectives within your domain. -->

| # | Source | Description | URL or location |
|---|--------|-------------|-----------------|
| 1 | Thomas Austin | The best professors at SJSU. In every aspect of professing, he excels. I had major skill issue in the class, but the prof was chill and covered a lot of topics. First half of sem goes to Scheme, and the second half goes over a bunch of languages, you learn a new one each week. JS, ANTLR, Prolog, Ruby, Rust, Solidity, Inform, C, LaTEX. HW after every class. Tests are hard, but he seems lenient with partial credit.| https://www.ratemyprofessors.com/professor/2000580 |
| 2 | Mark Stamp | the professor is very educated in the field of security and machine learning, he has a high index and his cs 166 course is very useful and gives a fundmental understanding of infromation security , homeworks are very useful, over all this one of the few classes at sjsu cs department that are actually worth the money we are paying for. | https://www.cs.sjsu.edu/~stamp/ |
| 3 | Fabio Di Troia | Prof Fabio was amazing, funny, clear about his expectations, and caring for students. He understood students' difficulties and told us which topics to emphasize on. His lectures were well delivered. He reviewed important topics and gave us mock exams to study for the tests. The tests were not easy, make sure you pay attention and fully understand. | https://www.fabiodt.it/ |
| 4 | Ramin Moazeni | Prof. Ramin really knows his stuff and explains concepts clearly with great slides and examples. Lectures are organized, thorough, and he always connects topics to real industry use. He's approachable, patient with questions, and does helpful recaps. Assignments are challenging but super practical and helps with learning. | https://www.ratemyprofessors.com/professor/2059935 |
| 5 | Teng Moh | Does not use Canvas; you will never know your score until the end. Even though attendance is "not mandatory", the assignments are not posted anywhere online, so good luck knowing what to submit if you don't go. Grading is inconsistent. Takes off lots of points for no reason. He is late with final grades, which can screw up degree conferral if you're graduating. | https://www.cs.sjsu.edu/~tsmoh/ |
| 6 | Rob Chun | Communication is poor. The material is old and needs to be updated. Projects need to be more hands-on to have a greater impact on a student's career or output. Overall, ok, but the delivery of the lecture could improve. Yet, class can be easy as long as you study, hopefully easy A or B. | https://www.ratemyprofessors.com/professor/216637 |
| 7 | C. Ouverney | His lectures are very informative and to the point. He makes a helpful study guide and allowed a cheat sheet on exams. The online quizzes had two attempts and weren't bad. He cares a lot about the topic and is easy to work with. I'd take him again. | https://www.sjsu.edu/biology/research/ouverney-lab/index.php |
| 8 | N. Saxena | Prof Saxena is one of the sweetest, most caring professors I've had. She genuinely cares about her students, and is quite funny. The classes are fun to attend, and she teaches really well. The exams are manageable, especially if you study the content and attend the SI sessions. Would highly recommend taking her class. If you get the chance to take her, you will have a great time and learn a lot without being too stressed out. She's pro-student, a great lecturer, and assigns minimal busy work so we can focus on deep understanding. I hope I can take her again. | https://www.sjsu.edu/people/navrati.saxena/ |
| 9 | Eric Reed | Very nice professor. Short lecture videos adding up to maybe 40 minutes total? Watch the videos before lab. In person lab is graded based on attendance but still do for learning. I'm not good at math but genuinely enjoyed this class. Midterm and final are based on methods/math than coding. There is a final pair project but nothing too bad. Yay! Enjoyable class! Professor is very helpful, structures everything well, and provides clear and detailed project specs. Each week cumulatively builds on the last in a project spanning the entire quarter. Encourages students to help each other (but not collaborate) in the forums. | https://www.ratemyprofessors.com/professor/2387897 |
| 10 | Leonard Wesley | This professor seems confused about what he is teaching. He gets lost on basic points, and has lifted all his slides from other curricula. He does not seem to understand his material. He cannot follow along when students discuss their projects, and he has no clear rubric for assignments that define your entire grade. TAs grade using ChatGPT. During class: Gives good lectures; responds in class very well. Outside class: Uses websites that update their content, while he does not update his step by step instruction, resulting in major confusion and incomplete assignments. Overall: click bait assignments; tolerates academic dishonesty; slow to respond. FYI: Choose other degree OR school. Lectures, slideshow, and textbook ALL CONTRADICT EACH OTHER. Tests are open book, but difficult due to how disorganized or contradictory the info was. I can confidently say this was the worst professor I've had in my entire academic career. I advise you to avoid him.| https://www.cs.sjsu.edu/~wesley/ |

---

## Chunking Strategy

<!-- How will you split documents into chunks?
     State your chunk size (in tokens or characters), overlap size, and explain why those
     numbers fit the structure of your documents.
     A review-heavy corpus warrants different chunking than a long FAQ. -->

**Chunk size:**

**Overlap:**

**Reasoning:**

---

## Retrieval Approach

<!-- Which embedding model are you using (e.g., all-MiniLM-L6-v2 via sentence-transformers)?
     How many chunks will you retrieve per query (top-k)?
     If you were deploying this for real users and cost wasn't a constraint, what tradeoffs
     would you weigh in choosing a different embedding model — context length, multilingual
     support, accuracy on domain-specific text, latency? -->

**Embedding model:**

**Top-k:**

**Production tradeoff reflection:**

---

## Evaluation Plan

<!-- List your 5 test questions with their expected correct answers.
     Questions should be specific enough that you can judge whether the system's response
     is right or wrong. "What are good dining halls?" is too vague.
     "What do students say about wait times at [dining hall name] during lunch?" is testable. -->

| # | Question | Expected answer |
|---|----------|-----------------|
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

---

## Anticipated Challenges

<!-- What could go wrong? Name at least two specific risks with reasoning.
     Consider: noisy or inconsistent documents, missing source attribution, off-topic
     retrieval, chunks that split key information across boundaries. -->

1.

2.

---

## Architecture

<!-- Draw a diagram of your pipeline showing the five stages:
     Document Ingestion → Chunking → Embedding + Vector Store → Retrieval → Generation
     Label each stage with the tool or library you're using.
     You can use ASCII art, a Mermaid diagram, or embed a sketch as an image.
     You'll use this diagram as context when prompting AI tools to implement each stage. -->

---

## AI Tool Plan

<!-- For each part of the pipeline below, describe:
     - Which AI tool you plan to use (Claude, Copilot, ChatGPT, etc.)
     - What you'll give it as input (which sections of this planning.md, which requirements)
     - What you expect it to produce
     - How you'll verify the output matches your spec

     "I'll use AI to help me code" is not a plan.
     "I'll give Claude my Chunking Strategy section and ask it to implement chunk_text()
     with my specified chunk size and overlap" is a plan. -->

**Milestone 3 — Ingestion and chunking:**

**Milestone 4 — Embedding and retrieval:**

**Milestone 5 — Generation and interface:**
