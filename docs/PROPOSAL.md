# Project Proposal
# Vestine Musonera & Joseph Islam
# November 29, 2022

1. What AI system are you interested in investigating further and why?

* lead author: Joseph Islam
  * editor     : Vestine

   We are interested in comparing symbolic and deep learning approaches to a snake game as our AI project. 
   The Snake in the snake game is on a board, which is the environment. 
   The Snake turns left, right, up, or down as its actions. 
   The snake acts with full autonomy post release and attempts to grow as much as possible, 
   which represents a goal. ALl of these aspects comprise and comply with the European commission 2021 definition of an AI

2. What content knowledge (theories and concepts) does the AI system use?

* lead author: Joseph Islam
* editor     : Vestine

 The search subfield of Symbolic AI provides the theoretical framework of the AI system via the A* Algorithm. 
 Symbolic AI is AI that reduces the search space of an options set. 
 `A*` Algorithm is a search algorithm designed to solve the graph traversal's shortest path problem.
 A* pilots the snake head towards food in this pygame implementation of Snake.

 Similarly, this project makes use of a connectivistic Deep Neural network to train a snake to find food 
 in a similar set. A deep neural network is a kind neural network, which is a Directed Acyclic Graph (DAG). 
 Such a graph, as a neural network, has weights as edges, an input array, and an output activation function. 
 Connecting many neural networks together into one big neural network makes a deep neural network, at a high level; 
 More technically, A deep neural network is a neural network with 2 or more layers.

 The key concepts and techniques that the AI system is based on are the deep neural network and 
 the A* search algorithm.

3. What tools, platforms, and APIs are needed to develop the AI system?

* lead author: Joseph Islam
* editor     : Vestine

 All code for our project is publically available. Two such code are:
            - https://github.com/Karthikeyanc2/Autonomous-snake-game-with-A-star-algorithm-in-PYTHON
                Which features pygame and numpy.
            - https://github.com/patrickloeber/snake-ai-pytorch
                Which features the numpy and pytorch Python modules.

4. What example illustrates the basic "ingredients" of the AI system?

* lead author: Vestine 
* editor     : Joseph Islam

 Snake game is a Deep reinforcement learning using two components which are environment (game its self)
    and agent (snake). It uses an adaptive path finding a star algorthm to efficiently play the game. 
    it uses the dimensions array which are zeros (open space), ones (either snake's tail or objects) and negative 
    ones(food). the array is constantly updated depending on the location of the food and the movement of the snake.
    

5. What are the considerations for developing a safe and trustworthy AI system?

* lead author:Vestine 
* editor     : Joseph

European Commission (2019) mentioned 7 key requirements that AI system should meet:

* Human agency and oversight: to empower human beings, 
  * allowing them to make informed decisions and fostering their fundamental rights. 
  * proper oversight mechanisms need to be ensured, which can be achieved through human-in-the-loop, human-on-the-loop, 
  * and human-in-command approaches
* Technical Robustness and safety: AI systems need to be resilient and secure. 
  * They need to be safe, 
  * ensuring a fall back plan in case something goes wrong, 
  * as well as being accurate, reliable and reproducible. 
    * That is the only way to ensure that also unintentional harm can be minimized and prevented
* Privacy and data governance: besides ensuring full respect for privacy and data protection, 
  * adequate data governance mechanisms must also be ensured, 
  * taking into account the quality and integrity of the data, 
  * and ensuring legitimised access to data
* Transparency: the data, system and AI business models should be transparent. 
  * Traceability mechanisms can help achieving this. 
  * AI systems and their decisions should be explained in a manner adapted to the stakeholder concerned. 
  * Humans need to be aware that they are interacting with an AI system, 
  * and must be informed of the system’s capabilities and limitations.
* Diversity, non-discrimination and fairness: Unfair bias must be avoided,  
  * it could have multiple negative implications, from the marginalization of vulnerable groups, 
  * to the exacerbation of prejudice and discrimination. 
  * Fostering diversity, AI systems should be accessible to all, regardless of any disability, 
  * and involve relevant stakeholders throughout their entire life circle.
* Societal and environmental well-being: AI systems should benefit all human beings, including future generations. 
  * It must hence be ensured that they are sustainable and environmentally friendly. 
  * they should take into account the environment, including other living beings, 
  * and their social and societal impact should be carefully considered. 
* Accountability: Mechanisms should be put in place to ensure responsibility 
  * and accountability for AI systems and their outcomes. 
  * Auditability, which enables the assessment of algorithms, data and design processes plays a key role therein, 
  * especially in critical applications. Moreover, adequate an accessible redress should be ensured.

 The considerations for developing a safe and trustworthy AI:
    European Commission (2022), mentionned 7 key requirements that AI systems should meet in order
    to be deemed trustworthy: Human agency and oversight, Technical Robustness and safety, Privacy and data governance,
    Transparency, Diversity, non-discrimination and fairness, Societal and environmental well-being, Accountability.
    
    The AI snake game will fallows:

    Explainability : Understand snake game, how it works and the purpose of building that.
                     Being able to explain to the audience how it works and how to build it if it is necessary.

    Integrity: Us as developers will consider the output of our AI system and the purpose of that AI system. 
               The results need to match with our predefined plan.

    Conscious development: snake game AI system is beneficial with humans.
    That system is fun for all ages. 

    Reproducibility: using generating reproducible outcomes which will bring clear results. 
    The codes, the algorithm and artifacts are clear and understandable by developers and Humans. 

    Regulations: 
    *  it does not violate any user privacy, 
    * it is built in transparency,
    * it does not use any bias which will help any humans to use it,
    * It is safe for environment and living being
    * Its design have some mechanism of responsibility and accountability  

    By Boucher (2020) mentioned that The Commission's High-Level Expert Group on AI asserted that trustworthy 
    AI should be lawful, ethical and robust.

6. What are the ethical considerations in determining the legitimate use of the AI system?

* lead author: Joseph & Vestine
* editor     : Vestine & Joseph
 
 Boucher (2020) mentioned how to apply ethics frameworks that we will use in our AI system.

    Develop rights for the digital age:  access  to the system
        Human dignity: AI system should be respect and honor the human
    Shift from general to specific: AI system needs to start with the regular general codes and ends with snake game.
    Shift from voluntary to binding: AI system should respect the law with more specific interpretation.
    Establish ethics committees: the group that is in charge to control the snake game
    Integrate ethics meaningfully: the experts in AI system  help to make difference
    Consider moratoriums carefully: the delaying time of using our system





