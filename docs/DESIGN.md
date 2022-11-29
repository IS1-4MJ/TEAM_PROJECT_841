Content and Organization

    Introduction
        What AI system are you interested in investigating further?
            We are interested in comparing symbolic and deep learning approaches
            to a snake game as our AI project. The Snake in the snake game
            is on a board, which is the environment. The Snake turns left, right, up, or down
            as its actions. The snake acts with full autonomy post release and attempts to grow as much as possible,
            which represents a goal. ALl of these aspects comprise and comply with the 
            European commission 2021 definition of an AI.
        Why is it of interest to you?
            The Snake game AI is of interest to us because the Snake game AI
            is a simple example of a path-finding AI. A path-finding AI is an
            AI which finds a path from the AI agent's current position to a target
            position. Such a path could be found simply using the A* algorithm,
            as presented, but such a path could also be found using a deep
            neural network. We explore the differences between these two
            approaches in this project.
        What specifically you'll focus on? WHat's the overall guiding question
            your study will pursue?
            Our study will particularly be focused on what the key performance
            differences between the A* algorithm and the deep learning algorithm
            are. We will also investigate the similarities. Our question is what 
            are the similarities and differences between the neural component and
            the symbolic component?
            

  Theoretical Background

    - What areas or fields of AI provide the theoretical framework of the AI system?
        The search subfield of Symbolic AI provides the theoretical framework of 
        the AI system via the A* Algorithm. Symbolic AI is AI that reduces the 
        search space of an options set. The A* Algorithm is a search 
        algorithm designed to solve the graph traversal's shortest path problem.
        A* pilots the snake head towards food in this pygame implementation of Snake.
        
        Similarly, this project makes use of a connectivistic Deep Neural 
        network to train a snake to find food in a similar set. A deep 
        neural network is a kind neural network, which is a Directed 
        Acyclic Graph (DAG). Such a graph, as a neural network, has weights as edges, an input array,
        and an output activation function. Connecting many neural networks 
        together into one big neural network makes a deep neural network, at a
        high level; More technically, A deep neural network is a neural network
        with 2 or more layers.

    - What are the key concepts and techniques that the AI system is based on?
        The key concepts and techniques that the AI system is based on are
        the deep neural network and the A* search algorithm.

    - Include appropriate references that desacribe the field, key concepts, and techniques
        - Deep Neural Networks: Boucher, Philip. Artificial Intelligence: How Does It Work, Why Does It Matter, 
                   and What We Can Do about It? LU: Publications Office, 2020. https://data.europa.eu/doi/10.2861/44572.
        - A Star Algorithm: https://en.wikipedia.org/wiki/A*_search_algorithm

Development Approach
    
    What tools, platforms, APIs, libraries, datasets are available and needed 
    to develop the AI System? 
        All code for our project is publically available. Two such code are:
            - https://github.com/Karthikeyanc2/Autonomous-snake-game-with-A-star-algorithm-in-PYTHON
                Which features pygame and numpy.
            - https://github.com/patrickloeber/snake-ai-pytorch
                Which features the numpy and pytorch Python modules.
Working Example

    Snake game is a Deep reinforcement learning using two componets wich are environment (game its self)
    and agent (snake). it use an adaptive path finding a star algorhtm to effeciently play the game. 
    it uses the dimensions array which are zeros (open space), ones (either snake's tail or objects) and negative 
    ones(food). the array is constantly updated depending on the location of the food and the movement of the snake.
    

Discussion and Evaluation

    The considerations for developing a safe and trustworthy AI:
        Accessibility: Who has access to the code? is the code properly sourced?
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

The ethical considerations in determining the legitimate use of the AI system
    
    Boucher (2020) mentioned how to apply ethics frameworks that we will use in our AI system 
    Develop rights for the digital age:  access  to the system
        Human dignity: AI system should be respect and honor the human
    Shift from general to specific: AI system needs to start with the regular general codes and ends with snake game.
    Shift from voluntary to binding: AI system should respect the law with more specific interpretation.
    Establish ethics committees: the group that is in charge to control the snake game
    Integrate ethics meaningfully: the experts in AI system  help to make difference
    Consider moratoriums carefully: the delaying time of using our system

    BEGIN JOSEPH
    - Privacy and surveillance
        - Proper attribution of sources has been dealt. No data is collected.
    - manipulation of behavior
        - there are no users which are intended to play the game, so there is no
           possibility for manipulation of behavior.
    - Opacity of AI
        - Our Deep learning AI suffers inexplicability, yet such 
        inexplicability is inconsequential, because no societal artifacts appear
        in our system.
        - Our A* AI follows an explicit procedure, so non-opaque.
        - Assume atrocious manipulation, the AI doesn't perform as well as a hamming cycle.
    - Bias
        - There is no social phoenomena, and so there is no bias 
    - Automation / Employment
        There is clear automation of the game, but there is room for improvement,
        because the AI does not perform well, so there is no chance for interaction
        with SNAKE competitions, and so no chance for unemployment derived from
        our AI.
    - Autonomous Systems
        - The Ai is in control of itself and is responsible for its own actions.
        - No ethical consideration is made, because the objects of priority are 
          not agents themselves.
    - Machine Ethics
        The Snake AI is not capable of repurposement so is not a subject. 
        The snake AI is therefore an object. 
    - Artificial Moral Agents
        The snake is technically an ethical impact agent, because
        the snake AI simply plays an inconsequential game; No ethical patients
        are present.
    END JOSEPH


