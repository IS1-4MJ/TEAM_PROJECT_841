# Project Proposal
# Vestine Musonera & Joseph Islam
# November 14, 2022

1. What AI system are you interested in investigating further and why?

* lead author: Joseph Islam
* editor     : Vestine

 Our AI system is a simple handwritten. Our AI system writes the digits 0-9 in a handwritten way. 
 We are interested in a handwritten AI system to help us fill in simple numeric blanks in a handwritten format 
 as a nicety for form use and to make form use easier. If we have sufficient time, 
 we will expand this project to cover a-z 0-9 as well.

2. What content knowledge (theories and concepts) does the AI system use?

* lead author: Joseph Islam
* editor     : Vestine

 The content knowledge the AI system uses is a DCGAN and physics of drawing. 
 The project will feature a custom symbolic AI that draws slightly amiss characters using acceleration, velocity, 
 and position alongside a variable real-time continuous pen-width float. An ideal number will be used, 
 and the pen will drift towards the ideal with a random perturbance to add realism. 
 The theory at play here is that such parts suffice to generate realistic looking numbers, if a little common. 
 The project will also feature a standard DCGAN AI trained on the MNIST dataset to generate DCGAN images into 
 a pipeline that feeds such images into a writing queue to be written into a png file which can be copied 
 and pasted into a desired medium.

3. What tools, platforms, and APIs are needed to develop the AI system?

* lead author: Joseph Islam
* editor     : Vestine

 The project will use basic built in tools to represent the symbolic AI, while the project will use python, keras, 
 pandas, and numpy for the DCGAN in play here. The symbolic AI’s tools are needed to write the AI from scratch. 
 The DCGAN’s tools are needed to take advantage of Google’s already existing neural network progress 
 by using the keras package.

4. What example illustrates the basic "ingredients" of the AI system?

* lead author: Vestine 
* editor     : Joseph Islam

 Using the GitHub repository, GitBash and PyCharm to get our project repository.
 Using feature branches to make any changes to the file as collaborators and push the origin. 
 Write codes from scratch, Deep Convolutional Generative Adversarial Networks (DCGAN) and physical drawing pencil.
 Our AI system is going to use numbers from 0 to 9. 
 The prediction is to have those numbers in handwritten instead of regular numbers in our computers.
 Numeric prediction is to write any number `between 0 to 9` on a computer and get its handwritten number.  
 Classification is going to use deep learning which is going to operate on data or codes to a text handwritten 
 to an image  like a handwritten number.
 Workflow and rules will be there to show the way writing any number `between 0 to 9` displays its handwritten 

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

Our AI system will fallow:
* Explainability : Understand our AI system which is handwritten, how it works and the purpose of building that.
  Being able to explain to the audience how it works and how to build it if it is necessary.

* Integrity: Us as developers will consider the output of our AI system and the purpose of that AI system. 
   The results need to match with our predefined plan.

* Conscious development: Handwritten AI system will be beneficial with humans. 
   They will be familiar with numbers from 0-9 in handwritten using their computers. 
   That system will be fun for all ages. Comp841 classmates and Professor will work to improve our AI system by 
   asking some questions or giving us some comments.

* Reproducibility: using generating reproducible outcomes which will bring clear results. 
  The codes, the algorithm and artifacts will be clear and understandable by developers and Humans. 

* Regulations: 
  * Handwritten AI system will be controlled by us team (Vestine & Joseph), it is not going to violate any user privacy, 
  * it is going to be built in transparency, 
  * it is not going to use any bias which will help any humans to use it,
  * It is safe for environment and living being
  * Its design will have some mechanism of responsibility and accountability  

By Boucher (2020) mentioned that The Commission's High-Level Expert Group on AI asserted that trustworthy 
AI should be lawful, ethical and robust.

6. What are the ethical considerations in determining the legitimate use of the AI system?

* lead author: Joseph & Vestine
* editor     : Vestine & Joseph
 
Boucher (2020) mentioned how to apply ethics frameworks that we will use in our AI system 
* Develop rights for the digital age: we will give access to all Fall Comp841 students access to the system
  * Human dignity: our AI system will respect and honor the human
* Shift from general to specific: AI system will start with the regular numbers that typed in computer,
   * it will transform those numbers to handwritten number without drawing with a computer pencil.
   * human will play with that system by writing a number that displays handwritten 
* Shift from voluntary to binding: Our AI system should respect the law which means that it is going to fallow the rules 
   of our country. it will have more and specific interpretation.
* Establish ethics committees: Joseph and Vestine are the committee member and even any of classmates 
* Integrate ethics meaningfully: our Professor Mihaela as an expert in AI system will help to make difference
* Consider moratoriums carefully: the delaying time of using our system

  We use the categorical imperative by Immanuel Kant to determine the ethical nature of the project. 
  In particular, imagine a world in which everyone were to use our tool in its fullest to fill out forms. 
  Whenever someone would sign a form, the tool would be used. 
  This would result in anyone signing a form having identical handwriting, nullifying the uniqueness of the signature. 
  However, today, digital signatures are commonplace and signature uniques is not an ethical concern. 
  Hence, the legitimate use of the system as intended is not ethically unsound.
  misuse potential perspective would yield little due to the highly limited scope of the tool’s effect.  





