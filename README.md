# CS370
Project Overview and My Contributions

Throughout this course, I have developed a much deeper appreciation for artificial intelligence and the amount of work that goes into creating systems capable of learning from experience. Before taking CS 370, I understood artificial intelligence primarily through the applications I encountered in everyday life. I knew that AI could recognize patterns, generate responses, and make predictions, but I had not given much thought to the mathematical foundations and decision-making processes that make those capabilities possible. Working on the Pirate Intelligent Agent project challenged me to move beyond that surface-level understanding and experience what it actually means to develop a system that learns.

The objective of this project was to create an intelligent pirate agent capable of navigating a maze to locate treasure. Although the concept initially seemed straightforward, the challenge was not simply to program the pirate to follow a predetermined path. Instead, the goal was to develop an agent that could learn which actions were most beneficial through repeated interactions with its environment. The pirate needed to evaluate its surroundings, make decisions, receive feedback, and gradually improve its ability to reach the treasure.

For this project, I was provided with starter code that established much of the underlying environment. This included the maze structure, the representation of the pirate's surroundings, and supporting functions that allowed the agent to interact with the environment. The provided code also included components for managing the agent's experiences and supporting the training process. Having these elements already established allowed me to concentrate on the learning algorithm rather than spending the entire project building the environment from scratch.

My primary responsibility was to complete the reinforcement learning portion of the project by implementing the training logic for the pirate agent. I worked with a deep Q-learning approach, which combines reinforcement learning with a neural network to estimate the value of different actions. Rather than explicitly telling the pirate which direction to move at every step, I needed to establish a process through which it could discover effective strategies.

One of the most important parts of my implementation involved balancing exploration and exploitation. During exploration, the agent selects actions that allow it to discover new possibilities, even when those actions do not immediately appear beneficial. During exploitation, it uses what it has already learned to make decisions that are more likely to produce a successful outcome. Finding an appropriate balance between these behaviors was essential because an agent that only explores may never consistently apply what it learns, while an agent that relies too heavily on existing knowledge may overlook better solutions.

I also worked with experience replay, which allows the agent to store information from previous interactions and use those experiences during training. Instead of learning exclusively from the most recent action, the model can revisit earlier experiences to improve its predictions. This helped me understand that learning is not necessarily a continuous sequence of improvements. Sometimes an agent needs to reconsider previous decisions, encounter unsuccessful outcomes, and adjust its understanding before it can perform more consistently.

Another important aspect of my work was examining the agent's performance and determining whether the training process was producing meaningful improvements. Watching the agent progress reinforced how different machine learning development is from traditional programming. In a conventional application, I might write a function, provide an input, and expect a predictable output. With reinforcement learning, the outcome depends on the agent's accumulated experiences, the training process, and the decisions it makes along the way.

By the end of the project, I had gained practical experience implementing and evaluating a learning-based solution rather than relying entirely on predetermined instructions. More importantly, I began to understand why developing intelligent systems requires patience, experimentation, and a willingness to question whether a model is actually learning what we intend it to learn.

What Computer Scientists Do and Why Their Work Matters

One of the most significant things I have learned throughout my computer science education is that the field is not simply about writing code. Programming is an important skill, but it is only one part of a much larger process. Computer scientists study problems, develop methods for solving them, evaluate different approaches, and create systems that can make complex tasks more manageable.

Before beginning my degree, I associated computer science primarily with software development. I imagined that most of the work involved learning programming languages, building applications, and fixing errors. While those responsibilities are certainly part of the profession, my coursework has shown me that computer science is fundamentally about problem-solving. The code is simply how many of those solutions are expressed.

The Pirate Intelligent Agent project demonstrated this distinction particularly well. If the objective had only been to move a character through a maze, I could have approached the problem using a series of predetermined instructions. However, that would not have addressed the larger challenge of creating an agent capable of learning how to navigate unfamiliar situations. The project required me to think about how information is represented, how decisions are evaluated, and how a system can improve without being explicitly programmed for every possible scenario.

This is what makes computer science so valuable beyond the classroom. The same principles that allow a pirate agent to learn from its environment can be applied to problems involving robotics, transportation, healthcare, cybersecurity, and countless other industries. Although the complexity and consequences of those applications vary considerably, they share a common foundation: using computational methods to understand information and make better decisions.

I find the relationship between computer science and artificial intelligence especially fascinating because it challenges our traditional understanding of what software can accomplish. We are accustomed to programs following instructions that developers have written. Machine learning introduces the possibility of creating systems that identify relationships and develop strategies based on data rather than relying exclusively on explicitly defined rules.

At the same time, this course has made me more aware of the limitations of these technologies. An intelligent system is not automatically a reliable system, and a model that performs well in one environment may struggle when conditions change. Behind every successful application are decisions about data quality, system design, testing, and the consequences of potential failures.

As I approach the completion of my computer science degree, I have started thinking more seriously about the kind of professional I want to become. I do not want to be someone who simply knows how to make software function. I want to understand why a solution works, recognize when it might fail, and consider whether it genuinely addresses the needs of the people who will depend on it.

To me, that is where the importance of computer science becomes most apparent. The work matters because technology influences how people communicate, learn, work, and make decisions. The responsibility of a computer scientist extends beyond developing something technically impressive. It also involves determining whether that technology is useful, dependable, and appropriate for the problem it is intended to solve.

How I Approach Problems as a Computer Scientist

If I had to identify one area where I have experienced the most personal growth throughout my degree, it would be my approach to unfamiliar problems.

Earlier in my education, I sometimes felt that being a good programmer meant being able to look at a problem and immediately know how to solve it. When I encountered something I did not understand, my first instinct was often to focus on finding the correct code. I wanted to get the program working, and I sometimes became so focused on the final result that I overlooked the importance of understanding the process.

My experience with the Pirate Intelligent Agent project reinforced a different perspective. I have learned that not knowing the solution immediately is a normal part of computer science. What matters is being able to break the problem into smaller pieces, identify what information is available, and develop a reasonable approach that can be tested and improved.

When I begin working on a problem now, I try to understand what the system is actually supposed to accomplish before deciding how to implement it. In the pirate project, this meant recognizing that successfully navigating the maze was only one measure of success. The larger objective was to develop an agent that could learn to make effective decisions through reinforcement learning.

Once I understood that distinction, the individual components of the project became easier to connect. The environment represented the problem the agent needed to solve. The available actions represented its possible decisions. The rewards provided feedback about the consequences of those decisions. The neural network estimated which actions were likely to produce favorable outcomes, while experience replay helped the agent learn from previous interactions.

Understanding how these pieces worked together was more valuable than simply memorizing the code required to implement them.

I have also become more comfortable with experimentation. In machine learning, there is rarely a guarantee that the first approach will produce the desired result. Training outcomes can vary, parameters can influence performance in unexpected ways, and apparent improvements do not always indicate that a model has learned a reliable strategy.

This was an adjustment for me because traditional programming often provides more immediate feedback. If a function produces the wrong result, I can usually trace the problem to a specific part of the implementation. With a learning-based system, the code may execute correctly while the model still performs poorly. That distinction forced me to think more critically about what it means for a program to work.

I learned to pay closer attention to the evidence produced during training rather than assuming that successful execution meant successful learning. Examining results, questioning unexpected behavior, and considering how different training decisions might affect performance became important parts of the development process.

Another lesson I will carry forward is the importance of understanding existing code before attempting to modify it. Because the project included starter code, I needed to become familiar with components I had not written myself. This reflects a reality of professional software development that I have come to appreciate throughout my coursework: computer scientists rarely work in complete isolation or build every system from the ground up.

Being able to read someone else's code, understand its purpose, and contribute without disrupting existing functionality is just as important as writing original code.

Perhaps the biggest change in my mindset is that I have become less concerned with finding a perfect solution immediately and more interested in developing a thoughtful process for reaching one. I now recognize that debugging, testing, researching, and revising are not interruptions to the work. They are the work.

That realization has made me more confident in my ability to approach unfamiliar technologies. I may not always know the answer when I begin, but I have developed a stronger understanding of how to investigate a problem and work toward a solution.

My Ethical Responsibilities to End Users and Organizations

Before studying artificial intelligence in greater depth, I primarily associated ethical responsibilities in computer science with protecting personal information and preventing security vulnerabilities. Those responsibilities remain extremely important, but this course has helped me recognize that ethical considerations extend much further.

When developing intelligent systems, computer scientists influence how information is interpreted, which outcomes are prioritized, and how much control users have over decisions that may affect their lives.

The Pirate Intelligent Agent project offered a relatively simple environment in which to explore these ideas. The pirate's objective was to reach the treasure, and its decisions were evaluated according to a reward system. Within that environment, success was relatively easy to define. However, real-world applications rarely have objectives that are so straightforward.

This made me think about the importance of defining what an AI system is being encouraged to accomplish.

A reinforcement learning agent attempts to maximize the rewards it receives, but that does not necessarily mean it understands the broader consequences of its behavior. If a reward system is poorly designed, the agent may discover ways to achieve a high score without accomplishing what the developer originally intended.

In a maze, an undesirable outcome might simply mean that the pirate takes an inefficient route or fails to reach the treasure. In an application involving healthcare, financial decisions, or public safety, the consequences of an incorrectly designed system could be far more serious.

As a computer scientist, I have a responsibility to consider not only whether an algorithm achieves its intended objective, but also whether that objective has been defined appropriately.

Another concern involves the data used to train intelligent systems. Throughout this course, I have learned how heavily machine learning depends on the information it receives. If training data is incomplete, inaccurate, or unrepresentative, the resulting model may produce unreliable or biased predictions.

This is particularly concerning when AI systems are used to make recommendations or decisions involving real people. A model can appear accurate when evaluated against familiar data while performing poorly for individuals or situations that were not adequately represented during training.

I believe developers have a responsibility to recognize these limitations and communicate them rather than presenting AI-generated outcomes as unquestionably correct.

Transparency is another ethical consideration that has become increasingly important to me. People should have a reasonable understanding of what a system is doing, what information it uses, and how much confidence they should place in its recommendations.

I do not believe every user needs to understand the mathematics behind a neural network. However, I do believe they deserve to know when an important decision is being influenced by artificial intelligence and whether there are opportunities to question or override that decision.

This connects to another responsibility I consider essential: preserving meaningful human oversight.

One of the most impressive aspects of reinforcement learning is that an agent can improve its behavior without receiving explicit instructions for every situation. However, increased autonomy also introduces additional responsibility for the people designing and deploying these systems.

The fact that an AI application can make a decision independently does not mean it should always be permitted to do so. The appropriate level of autonomy depends on the potential consequences of an incorrect decision.

From an organizational perspective, ethical development also means balancing innovation with reliability, security, and accountability. Organizations may be motivated to adopt AI because it promises greater efficiency or reduced operating costs, but those benefits should not come at the expense of users' safety or trust.

Computer scientists have a responsibility to communicate technical limitations honestly, test systems thoroughly, protect sensitive information, and raise concerns when a proposed solution creates unnecessary risks.

I also think there is an ethical responsibility to acknowledge uncertainty. Machine learning models are not infallible, and presenting their outputs with more confidence than the evidence supports can be misleading. Recognizing when a system should defer to human judgment is just as important as recognizing when automation can provide value.

Ultimately, I believe responsible computer science requires considering the people who will experience the consequences of our technical decisions, even when those people are not directly involved in the development process.

Personal Growth and Final Reflection

Looking back on this course, I think the most meaningful change has been in how I understand intelligence within a computational system.

Before CS 370, I viewed artificial intelligence largely in terms of its capabilities. I was interested in what these systems could produce and how they might change the way we interact with technology. After working through the course material and completing the Pirate Intelligent Agent project, I have become much more interested in what happens beneath those capabilities.

I now have a better appreciation for how learning algorithms use information, how feedback influences decision-making, and why the design of a training environment matters so much.

The pirate project was particularly valuable because it transformed concepts that initially felt abstract into something I could observe and work with. Reinforcement learning became easier to understand when I could connect it to an agent navigating a maze, making unsuccessful decisions, and gradually developing a more effective strategy.

What I found especially interesting was that mistakes were not necessarily evidence that the system had failed. In reinforcement learning, unsuccessful actions can provide information that contributes to future improvement. That idea resonated with me beyond the technical aspects of the assignment.

Throughout my computer science education, I have encountered assignments that challenged my confidence and required considerably more time than I initially expected. There have been moments when I questioned whether I fully understood a concept or whether I was approaching a problem correctly. However, looking back, those experiences often contributed the most to my development.

In some ways, my own learning process has reflected the principles explored in this project. I have tried approaches that did not work, revisited concepts I thought I understood, and gradually developed better strategies through experience.

The difference is that my growth cannot be measured through a reward function or a successful maze traversal. It is reflected in how I approach challenges, how I respond when something goes wrong, and how willing I am to keep learning when the answer is not immediately apparent.

As I move closer to completing my degree, I recognize that graduating will not mean I have mastered computer science. If anything, my coursework has made me more aware of how much there is still to explore. Technologies will continue evolving, programming practices will change, and new ethical questions will emerge as artificial intelligence becomes more integrated into everyday life.

Rather than finding that intimidating, I have started to see it as one of the reasons I am drawn to this field. Computer science offers the opportunity to keep learning while applying that knowledge to problems that matter.

The Pirate Intelligent Agent project taught me how to implement and evaluate a reinforcement learning solution, but the larger lesson was about developing a more thoughtful approach to technology. I learned that successful systems depend on more than functional code. They require carefully defined objectives, meaningful evaluation, an understanding of limitations, and consideration for the people who may eventually rely on them.

If there is one perspective I want to carry into my professional career, it is that being a capable computer scientist is not just about knowing how to build something. It is about understanding what you are building, questioning whether it works as intended, and taking responsibility for the impact it may have.

That is the kind of computer scientist I hope to continue becoming.
