# CS-552: Modern Natural Language Processing

### Course Description
Natural language processing is ubiquitous in modern intelligent technologies, serving as a foundation for language translators, virtual assistants, search engines, and many more. In this course, we cover the foundations of modern methods for natural language processing, such as word embeddings, recurrent neural networks, transformers, and pretraining, and how they can be applied to important tasks in the field, such as machine translation and text classification. We also cover issues with these state-of-the-art approaches (such as robustness, interpretability, sensitivity), identify their failure modes in different NLP applications, and discuss analysis and mitigation techniques for these issues. 

#### Quick access links:
- [Platforms](#class)
- [Lecture Schedule](#lectures)
- [Exercise Schedule](#exercises)
- [Grading](#evaluation)
- [Contact](#contact)


<a name="class"></a>
## Class

| Platform           | Where & when                                              |
|:-------------------|:----------------------------------------------------------|
| Lectures           | **Wednesdays: 9:15-11:00am** [[CM2](https://plan.epfl.ch//?room==CM%201%202)] & **Thursdays: 1:15-2:00pm** [[CE1](https://plan.epfl.ch//?room==CE%201%201)] |
| Exercises Session  | **Thursdays: 2:15-4:00pm** [[CE1](https://plan.epfl.ch//?room==CE%201%201)] |
| Project Assistance <br />(not every week) | **Wednesdays: 11:15am-12:00pm** [[CM2](https://plan.epfl.ch//?room==CM%201%202)] |
| Forum              | Ed Forum [[link](https://edstem.org/eu/courses/379/discussion/)]                                       | 
| Moodle             | Annoucements [[link](https://moodle.epfl.ch/course/view.php?id=17143)]              |

All lectures will be given in person and live streamed on Zoom. The link to the Zoom is available on the course Moodle page. Lectures will be recorded and uploaded to SwitchTube.

<a name="lectures"></a>
## Lecture Schedule

| Week    | Date    |  Topic                                                                 |  Instructor                        |
|:------------|:--------|:-------------------------------------------------------------------------------------|:----------------------------------:|
| **Week 1**  | 22 Feb <br />23 Feb  |  Introduction + Building a simple neural classifier  <br />Neural LMs: word embeddings    [[slides][1s], [readings][1r]]    |  Antoine Bosselut                  |
|             |                      |                                                                                                             |                                    |
| **Week 2**  |  1 Mar <br />2 Mar   |  Classical and Fixed-context Language Models <br />Recurrent Neural Networks              [[slides][2s], [readings][2r]]    |  Antoine Bosselut                  |
|             |                      |                                                                                                             |                                    |
| **Week 3**  |  8 Mar <br />9 Mar   |  LSTMs and Sequence-to-sequence models <br />Theoretical properties of RNNs               [[slides][3s], [readings][3r]]    |  Antoine Bosselut <br />Gail Weiss |
|             |                      |                                                                                                             |                                    |
| **Week 4**  | 15 Mar <br />16 Mar  |  Attention + Transformers <br />Transformers                                              [[slides][4s], [readings][4r]]    |  Antoine Bosselut                  |
|             |                      |                                                                                                             |                                    |
| **Week 5**  | 22 Mar <br />23 Mar  |  Pretraining: ELMo, BERT  <br />Transfer Learning: Introduction                           [[slides][5s], [readings][5r]]    |  Antoine Bosselut                  |
|             |                      |                                                                                                             |                                    |
| **Week 6**  | 29 Mar <br />30 Mar  |  Transfer Learning: Dataset Biases  <br />Transfer Learning: Prompts                                        |  Antoine Bosselut                  |
|             |                      |                                                                                                             |                                    |
| **Week 7**  |  5 Apr  <br />6 Apr  |  Text Generation                                                                                            |  Antoine Bosselut                  |
|             |                      |                                                                                                             |                                    |
| **Week 8**  |                      |  ***EASTER BREAK***                                                                                         |  Antoine Bosselut                  |  
|             |                      |                                                                                                             |                                    |
| **Week 9**  | 19 Apr <br />20 Apr  |  In-Context Learning <br />                                                                                 |  Antoine Bosselut                  |
|             |                      |                                                                                                             |                                    |
| **Week 10** | 26 Apr <br />27 Apr  |  Scaling Laws + Model Compression <br />***No class***                                                      |  Antoine Bosselut <br />Reza Banaei  |
|             |                      |                                                                                                             |                                    |
| **Week 11** |  3 May <br />4 May   |  Ethics in NLP <br />Ethics in NLP                                                                          |  Antoine Bosselut                  |
|             |                      |                                                                                                             |                                    |
| **Week 12** | 10 May <br />11 May  |  Interpretability & Analysis of Language Models <br />***No class***                                        |  Antoine Bosselut                  |
|             |                      |                                                                                                             |                                    |
| **Week 13** | 17 May <br />18 May  |  Reading Comprehension & Open-domain QA <br />Language & Knowledge Graphs                                   |  Antoine Bosselut  <br />Angelika Romanou                |
|             |                      |                                                                                                             |                                    |
| **Week 14** | 24 May <br />25 May  |  Tokenization + Multilingual LMs  <br />***No class***                                                      |  Negar Foroutan                    |
|             |                      |                                                                                                             |                                    |
| **Week 15** | 31 May <br />1 Jun   |  Language & Vision <br />Language & Vision + Wrap-up                                                        |  Syrielle Montariol <br />Antoine Bosselut |

<a name="exercises"></a>
## Exercise Schedule

| Week    | Date    |  Topic                                                                                    |  Instructor                                                         |
|:------------|:--------|:--------------------------------------------------------------------------------------|:-------------------------------------------------------------------:|
| **Week 1**  | 23 Feb  |  Setup + Word embeddings  [[code][1e]]                                                |  Angelika Romanou <br />Sepideh Mamooler <br />Simin Fan            |
|             |         |                                                                                       |                                                                     |
| **Week 2**  |  2 Mar  |  Word embeddings review <br />Classical & Fixed-context Language Models [[code][2e]]  |  Angelika Romanou <br />Mohammedreza Banaei <br />Sepideh Mamooler  |
|             |         |                                                                                       |                                                                     |
| **Week 3**  |  9 Mar  |  Language Models Review <br />Sequence-to-sequence models [[code][3e]]                |  Mohammedreza Banaei <br />Sepideh Mamooler <br />Simin Fan         |
|             |         |                                                                                       |                                                                     |
| **Week 4**  | 16 Mar  |  Sequence-to-sequence models review <br />Attention + Transformers   [[code][4e]]     |  Sepideh Mamooler <br />Mete Ismayil <br />Simin Fan                |
|             |         |                                                                                       |                                                                     |
| **Week 5**  | 23 Mar  |  Transformers Review <br />Pretraining: ELMo, BERT    [[code][5e]]                    |  Simin Fan <br />Sepideh Mamooler <br />Molly Petersen              |
|             |         |                                                                                       |                                                                     |
| **Week 6**  | 30 Mar  |  Pretraining Review <br />Transfer Learning: Dataset Biases                           |  Molly Petersen <br />Mete Ismayil <br />Sepideh Mamooler           |
|             |         |                                                                                       |                                                                     |
| **Week 7**  |  6 Apr  |  Transfer Learning Review <br />Text Generation                                       |  Molly Petersen <br />Deniz Bayazit <br />Sepideh Mamooler          |
|             |         |                                                                                       |                                                                     |
| **Week 8**  | 13 Apr  |  ***EASTER BREAK***                                                                   |                                                                     |  
|             |         |                                                                                       |                                                                     |
| **Week 9**  | 20 Apr  |  Text Generation Review <br />In-context Learning                                     |  Deniz Bayazit <br />Silin Gao <br />Sepideh Mamooler               |
|             |         |                                                                                       |                                                                     |
| **Week 10** | 27 Apr  |  In-context Learning Review <br />Milestone 1 Discussion                              |  Silin Gao <br />TA meetings on-demand                                    |
|             |         |                                                                                       |                                                                     |
| **Week 11** |  4 May  |  Project                                                                              |  TA meetings on-demand                                              |
|             |         |                                                                                       |                                                                     |
| **Week 12** | 11 May  |  Milestone 2 Discussion <br />Project                                                 |  Silin Gao <br />TA meetings on-demand                              |
|             |         |                                                                                       |                                                                     |
| **Week 13** | 18 May  |  Project                                                                              |  TA meetings on-demand                                              |
|             |         |                                                                                       |                                                                     |
| **Week 14** | 25 May  |  Milestone 3 Discussion <br />Project                                                 |  Deniz Bayazit <br />TA meetings on-demand                          |
|             |         |                                                                                       |                                                                     |
| **Week 15** | 1 Jun   |  Project                                                                              |  TA meetings on-demand                                              |


### Exercises Session format:
- TAs will provide a small discussion over the **last week's exercises**, answering any questions and explaining the solutions. _(10-15mins)_
- TAs will present **this week's exercise**. _(5mins)_ 
- Students will be solving this week's exercises and TAs will provide answers and clarification if needed.

_**Note**: Please make sure you have already done the setup prerequisites to run the coding parts of the exercises. You can find the instructions [here]()._

<a name="evaluation"></a>
## Grading:
Your grade in the course will be computed according to the following guidelines:

### Assignments (40%):
There will be three assignments throughout the course. They will be released and due according to the following schedule:

#### Assignment 1 (10%)
Link for the assignment [[here][1a]].
- Released: 10 Mar 2023
- Due: 24 Mar 2023

#### Assignment 2 (15%)
Link for the assignment [[here][2a]].
- Released: 24 Mar 2023
- Due: 7 Apr 2023 

#### Assignment 3 (15%)
- Released: 7 Apr 2023
- Due: 28 Apr 2023

Assignments will be released on Moodle and announced on Ed.

### Project (60%):
The project will involve using large-scale language models (100B+ parameters) and medium-scale (300M parameters) in the domain of education.  The project will be divided into a proposal, three milestones and a final submission. Each milestone will be worth 10% of the final grade with the remaining 30% being allocated to the final report. Each time will be supervised by one of the course TAs or AEs. More details on the content of the project and the deliverables of each milestone will be released at a later date.

#### Proposal (5%):
- For the proposal, students will be responsible for delivering a Project Plan for executing the goals of the project, as well as submitting a list of relevant literature, demonstrating they have identified academic papers that are relevant for each of the portions of the milestones of the project. Each student in the group should review one of these papers and submit it with Milestone 1.
- Due: 21 Apr 2023

#### Milestone 1 (10%):
- Exact parameters of Milestone 1 will be released in future weeks. 
- Due: 5 May 2023

#### Milestone 2 (10%):
- Exact parameters of Milestone 2 will be released in future weeks. 
- Due: 19 May 2023

#### Milestone 3 (5%):
- Exact parameters of Milestone 3 will be released in future weeks. 
- Due: 4 Jun 2023

#### Final Deliverable (30%):
- The final report, code, and date will be due on June 15th. Students are welcome to turn in their materials ahead of time on June 4th as soon as the semester ends.
- Due: 15 Jun 2023

### Late Days Policy
All assignments and milestones are due at 11:59 PM on their due date. As we understand that circumstances can make it challenging to abide by these due dates, you will receive 6 late days over the course of the semester to be allocated to the assignments and project milestones as you see fit. No further extensions will be granted. The only exception to this rule is for the final report, code, and data. No extensions will be granted beyond June 15th.


<a name="contact"></a>
## Contacts

**Lecturer**: [Antoine Bosselut](https://people.epfl.ch/antoine.bosselut).

**Teaching assistants**: [Mohammadreza Banaei](https://people.epfl.ch/mohammadreza.banaei?lang=en), [Deniz Bayazit](https://people.epfl.ch/deniz.bayazit?lang=en), [Zeming (Eric) Chen](https://people.epfl.ch/zeming.chen?lang=en), [Simin Fan](https://people.epfl.ch/simin.fan?lang=en), [Silin Gao](https://people.epfl.ch/silin.gao?lang=en), [Angelika Romanou](https://people.epfl.ch/angelika.romanou?lang=en)

Please contact us for any organizational questions or questions related to the course content.


[1s]:https://github.com/epfl-nlp/cs-552-modern-nlp/tree/main/Lectures/Week%201
[2s]:https://github.com/epfl-nlp/cs-552-modern-nlp/tree/main/Lectures/Week%202
[3s]:https://github.com/epfl-nlp/cs-552-modern-nlp/tree/main/Lectures/Week%203
[4s]:https://github.com/epfl-nlp/cs-552-modern-nlp/tree/main/Lectures/Week%204
[5s]:https://github.com/epfl-nlp/cs-552-modern-nlp/tree/main/Lectures/Week%205

[1e]:https://github.com/epfl-nlp/cs-552-modern-nlp/tree/main/Exercises/Week%201%20-%20Word%20Embeddings
[2e]:https://github.com/epfl-nlp/cs-552-modern-nlp/tree/main/Exercises/Week%202%20-%20N-gram%20%26%20Neural%20Language%20Models
[3e]:https://github.com/epfl-nlp/cs-552-modern-nlp/tree/main/Exercises/Week%203%20-%20RNN
[4e]:https://github.com/epfl-nlp/cs-552-modern-nlp/tree/main/Exercises/Week%204%20-%20Transformer%20%26%20Attention
[5e]:https://github.com/epfl-nlp/cs-552-modern-nlp/tree/main/Exercises/Week%205%20-%20BERT

[1a]:https://moodle.epfl.ch/mod/forum/discuss.php?d=87286
[2a]:https://moodle.epfl.ch/mod/forum/discuss.php?d=87999


[1r]:https://github.com/epfl-nlp/cs-552-modern-nlp/blob/main/Lectures/Week%201/README.md
[2r]:https://github.com/epfl-nlp/cs-552-modern-nlp/blob/main/Lectures/Week%202/README.md
[3r]:https://github.com/epfl-nlp/cs-552-modern-nlp/blob/main/Lectures/Week%203/README.md
[4r]:https://github.com/epfl-nlp/cs-552-modern-nlp/blob/main/Lectures/Week%204/README.md
[5r]:https://github.com/epfl-nlp/cs-552-modern-nlp/blob/main/Lectures/Week%205/README.md

