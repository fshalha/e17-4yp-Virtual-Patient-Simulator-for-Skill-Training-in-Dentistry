---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e17-4yp-Virtual-Patient-Simulator-for-Skill-Training-in-Dentistry
title: Virtual Patient Simulator for Skill Training in Dentistry
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Virtual Patient Simulator for Skill Training in Dentistry

#### Team

- E/17/005, Rishard.M.I., [email](mailto:e17005@eng.pdn.ac.lk)
- E/17/327, Shalha.A.M.F., [email](mailto:e17327@eng.pdn.ac.lk)
- E/17/379, Weerasinghe.S.P.D.D.S., [email](mailto:e17379@eng.pdn.ac.lk)

#### Supervisors

- Prof. Roshan G. Ragel, [email](mailto:roshanr@eng.pdn.ac.lk)
- Dr. Upul Jayasinghe , [email](mailto:upuljm@eng.pdn.ac.lk)
- Dr. D Leuke Bandara , [email](mailto:dhanulb@dental.pdn.ac.lk)
- Dr. Titus Jayarathna , [email](mailto:titus@eng.pdn.ac.lk)

#### Table of content

1. [Abstract](#abstract)
2. [Related works](#related-works)
3. [Methodology](#methodology)
4. [Experiment Setup and Implementation](#experiment-setup-and-implementation)
5. [Results and Analysis](#results-and-analysis)
6. [Conclusion](#conclusion)
7. [Publications](#publications)
8. [Links](#links)

---

## Abstract
Our project aims to create a 3D virtual patient simulator to help dental students practice patient assessments, a crucial skill, especially during times like the pandemic when traditional hands-on learning is challenging. Regular training can be limiting and risky, but our simulator provides various scenarios safely. Building this simulator involves challenges, including complex 3D modeling and potential high costs. We used the Unity game engine for interactive features and Blender for precise modeling, creating a detailed virtual dental clinic where students can practice both outside and inside mouth examinations. They can also work with digital versions of dental tools and x-rays for different cases. Future updates will include haptic feedback for a more realistic Virtual Reality (VR) experience, with built-in grading systems to assess student performance. Early tests show our approach is cost-effective and could significantly improve dental education by preparing students better for real-world dental work.

---
## Related works

#### 1. **Game Engines in Medical Simulations**

The literature emphasizes a growing demand for affordable, high-realism virtual simulations in medical and dental education. The scarcity and high cost of commercial training tools have led to exploring alternative solutions such as game engines, advanced software systems that create highly interactive environments. Despite their potential, the use of game engines within medical education remains largely underexplored.

Functional units of these systems, like Graphics, AI, and Physics engines, offer notable advantages. The Graphics engine, in particular, is pivotal in developing 3D models, providing a more accessible platform for developers than web-based technologies. However, selecting an optimal game engine requires careful evaluation of various factors including stability, custom content creation potential, and capacity for custom medical model creation.

The literature analysis compares four renowned game engines - Unreal Engine 2, idTech 4, Source Engine, and Unity Engine. All have distinct characteristics concerning editing, content creation, and gameplay. Among them, Unity3D and Unreal Engine are most suitable for clinical simulations. Unity3D, with its extensive user base, robust 3D graphic support, platform compatibility, fair pricing, and an extensive asset store, appears most fitting for implementing a virtual simulator for clinical practices.

Although the existing literature identifies the potential of game engines in medical education, there's a significant gap in their application. To bridge this gap, the proposal is to use Unity3D to develop a virtual patient simulator, leveraging its demonstrated potential in VR training simulators. This would greatly contribute to filling the identified research gap and promoting the integration of game engine technology in medical education.

#### 2.  **Haptic-Based Virtual Simulators in Dentistry**

Haptic-based virtual simulators are a groundbreaking answer to some of the challenges in dental education. These simulators use touch-based technology to supplement visual aids, like 3D images, giving students a more realistic learning environment. Traditional teaching methods, like text or spoken explanations, can't fully describe the feeling of dental procedures, but haptic simulators fill this gap. They help improve students' practical skills while being cost-effective, easy to maintain, and long-lasting.

Three key examples of these systems are the DentSim system, the MOOG Simodont Dental Trainer, and the PerioSim haptic system. DentSim is a computer-aided dental simulator providing visual, audio, and practical inputs for a well-rounded learning experience. It tracks a student's progress in tasks like tooth preparation with immediate on-screen feedback.

In contrast, the MOOG Simodont Dental Trainer doesn't use a physical model head. It shows a 3D image of the patient's mouth and tooth, providing tactile feedback through a drill handle that responds to the student's movements.

Finally, the PerioSim haptic system offers specialized training for periodontal procedures, displaying a 3D model of the human mouth. Each of these systems offers unique benefits and different approaches to tactile feedback, creating a comprehensive learning experience covering various aspects of dental education.

However, using these systems individually may limit the overall training experience. A better approach might be to integrate these technologies into one virtual patient simulator, providing a more engaging, realistic training environment for dental students, enhancing their tactile experience, and improving their practical skills.


#### 3.  **Virtual Reality Training Simulator in Dentistry**

Virtual Reality Training Simulators (VRTS) are increasingly beneficial in dental education, allowing students to practice procedures in a realistic but virtual environment. One such VRTS uses touch-based technology, 3D software, and a special VR headset to convert medical images into 3D models students can interact with. This innovative approach offers a real-life experience using fewer resources, doesn't require continuous supervision, and still enables effective tracking of student progress.

In a similar vein, the "Intelligent Virtual Training Environment for Dental Surgery" project combines VR with Artificial Intelligence to enhance surgical training. The project focuses on providing personalized instruction, assessment, and feedback on a large scale. It includes a VR dental simulator, an intelligent tutoring system, and an accessible VR simulator for emergency management in dental surgery, all aiming to improve dental training through accessibility, increased practice opportunities, and advanced learning techniques.

Other VR technologies like Oculus Quest have shown potential in various areas such as addressing specific phobias, aiding in physical rehabilitation, and improving the administration of local anesthesia. Research suggests VR simulators can significantly enhance practical skills among students, showing potential to revolutionize education, healthcare, and psychological treatments.

However, using VR simulators also comes with challenges, including the need to validate the simulator's evaluation system, accurately predict students' skills, and compare its performance with other VR training systems. Further research in these areas will help optimize the use of VR simulators in dental education.

In addition to touch-based simulators, web-based systems utilizing Virtual Patients (VP) are gaining interest. They provide interactive scenarios and realistic patient encounters, offering a flexible and accessible platform for learners to practice clinical decision-making, diagnostic skills, and treatment planning.

#### 4.  **Problem-Based Learning in Virtual Patient Skill Training**

Problem-Based Learning (PBL) plays an essential role in virtual patient skill training. This student-focused method encourages active learning by introducing students to real-world scenarios, improving problem-solving and data analysis skills. However, traditional PBL methods often require significant personal attention from tutors, presenting a challenge due to resource and faculty constraints.

Traditional paper-based PBL methods can limit students' learning pathways, restricting their ability to make independent decisions and learn from their outcomes. As such, more modern approaches to PBL are leaning towards interactive, visually engaging methods, allowing students to experience different decision outcomes in a way that mirrors real-life situations. This not only provides a safe practice environment but also exposes students to rare diseases, enhancing their decision-making skills.

Studies suggest a correlation between PBL practice and improved exam performance, showing the effectiveness of virtual training platforms integrated with PBL in medical education. However, there is still a need for a more extensive range of dental cases within the PBL framework.

Artificial intelligence can be a significant game-changer in this field. An AI chatbot in the virtual patient simulator can expand the range of scenarios and provide a controlled, engaging, and safe learning environment. This system could efficiently engage students comfortable with digital technology, making it easier for them to adapt to technological advancements in their field. This strategy could bridge the gap in current PBL methods, providing a comprehensive, dynamic, and interactive learning experience for students in dental education.

---

## Methodology

### **System Outline**
![System Outline](images/systemoutline.png)

In this virtual training system, dental students begin by selecting a specific clinical case, which sets the context for their learning experience. Once a case is chosen, they proceed to the History Taking stage, where they collect all relevant patient history, emulating the process in a real clinical environment.

The next step involves conducting an Extra Oral View Examination, where students assess the patient's facial features for any signs indicative of dental health issues. This is followed by an examination of the Intra Oral View, which requires students to inspect the inside of the patient's mouth for a thorough oral evaluation.

Subsequently, students must decide which investigations are necessary based on the clinical scenario. This decision-making process includes analyzing the radiographs provided for the case, integrating these findings into their assessment.

With the collected data, students are then tasked with formulating a Prognosis, synthesizing the patient's history, examination results, and investigative data to predict the course and outcome of dental conditions.

Finally, the system provides Feedback to the students, reflecting on their choices and performance throughout the simulation. This feedback aims to guide students' learning, helping them understand their areas of strength and those requiring further improvement.

### **Development Methodology**

The virtual dental training system was meticulously crafted, adhering to a comprehensive development methodology:

1. **Clinical Case Formulation**

2. **History-Taking Content Development**  
   <div align="left">
     <img src="images/historytaking.gif" width="400"> <!-- Adjust the width as needed -->
   </div>

3. **Question and Answer Formulation**

4. **Virtual Patient With Mouth Defects Modeling**  
   <div align="left">
     <img src="images/mouthmodel.gif" width="400"> <!-- Adjust the width as needed -->
   </div>

5. **Dental Tool Tray Modeling**  
   <div align="left">
     <img src="images/tooltray.png" width="400"> <!-- Adjust the width as needed -->
   </div>

6. **Dental Chart Design**  
   <div align="left">
     <img src="images/dentalchart.jpeg" width="400"> <!-- Adjust the width as needed -->
   </div>

7. **Feedback Mechanism Development**

These steps leveraged technologies such as Firebase for database management and deployment, Unity and Blender for 3D simulator modeling, and React for creating an intuitive web application interface.

The development methodology for our virtual dental training system is structured to mirror the complexity and depth of real-world clinical scenarios. We began by creating a variety of clinical cases, which were meticulously cataloged in a Firebase database. The formulation of each case was carefully designed to follow the progression observed in actual dental treatments.

With the framework of cases established, we moved on to develop the content for history taking. This crucial step was crafted with the guidance and expertise of seasoned dental professionals to ensure accuracy and relevance.

Subsequently, we crafted a set of questions and answers tailored to each phase of the clinical examination, building on the foundational information presented in the prior stage of development.

The next phase involved the detailed modeling of the oral cavity, complete with various defects to reflect a realistic clinical setting. This allowed for an immersive experience that closely mimics the visual and diagnostic challenges encountered by dental practitioners.

We then turned our attention to the design of the essential dental tool tray and the dental chart. Our aim was to enable students to accurately mark defects of any shape with the corresponding color, thereby fostering a hands-on approach to identifying and documenting dental issues.

The culmination of our development process was the establishment of an evaluation criteria. This was engineered to rigorously assess the performance of students, providing a quantitative measure of their proficiency and areas for improvement within the simulated environment. This systematic approach to the system's development is intended to provide dental students with a comprehensive, realistic, and effective learning tool.

### **Feedback Mechanism in Detail**
1. **History Taking**

2. **Questionnaire**  
  
3. **Dental Chart**

4. **Final Feedback**  
 
The feedback mechanism of our system is designed to be educational yet challenging, actively engaging students in critical thinking throughout the learning process.

During the history-taking stage, the system presents a mix of relevant and non-relevant questions for each section. Students are encouraged to discern and select the appropriate questions, for which they receive positive marks, while incorrect selections result in negative marks, promoting attentiveness and decision-making akin to real-life clinical settings.

Following history taking, students interact with a 3D simulator for practical examinations. Their understanding is further tested through a questionnaire that requires accurate responses based on their observations. The system allows three attempts for each question, though marks are awarded only for the correct answers on the first attempt. Incorrect responses initially incur negative marks to emphasize the importance of accuracy. Subsequent attempts are provided for educational purposes, allowing students to learn from their mistakes without additional penalty. If a student struggles to find the right answer, the correct one is revealed after the third attempt, ensuring a continuous learning opportunity.

In the evaluation phase, where students mark the dental chart, precision is rewarded. Correct markings on the chart reflect the student's grasp of the examination and result in additional marks.

The system culminates in comprehensive feedback for each section, where students can review their first attempts alongside the correct answers, reinforcing the learning experience. Finally, the student's overall performance is quantified with a final score out of 100, providing a clear measure of their competency in the simulated environment. This meticulous approach to feedback is not only a reflection of their current knowledge but also a roadmap for areas that require further study and understanding.

## Experiment Setup and Implementation
### **Experiment Structure**
<div align="left">
 <img src="images/experimentstructure.png" width="400"> <!-- Adjust the width as needed -->
</div>

An experiment was conducted to evaluate the effectiveness of a virtual patient simulator compared to traditional teaching methods for dental undergraduate students. Participants were split into two groups: one received conventional teaching through PowerPoint presentations, and the other used a virtual patient simulator. Both groups took a pre-assessment test to gauge their initial knowledge and skills. After the respective educational interventions, a post-assessment was conducted to measure the learning outcomes. The study aimed to assess the benefits and effectiveness of simulation-based learning over traditional methods in dental education. It utilized a mixed design with two independent variables: the type of educational treatment and the time factor from pretest to posttest. This allowed for a nuanced analysis of different teaching approaches.

1.**Pre-Intervention and Post-Intervention Phases**
The study’s methodology encompassed two main phases: Pre-Intervention and Post-Intervention. Initially, the Pre-Intervention phase assessed the students’ foundational abilities in patient assessment and clinical reasoning. This was done using pre-questionnaires and pre-tests to determine their skill level and perceptions prior to using the virtual patient simulator. After the intervention, during the Post-Intervention phase, similar tools were used to evaluate any improvement or changes in the students' abilities and perceptions. The comparative analysis between the Pre- and Post-Intervention data was essential to establish the impact of the virtual patient simulator on the students' clinical skills.

2.**Questionnaire (Self-assessment)**
A comprehensive questionnaire was administered to students before and after the intervention to measure their self-perceived learning outcomes. This self-assessment aimed to gather insights into three domains: history taking, clinical examination skills, and overall patient assessment knowledge. Specifically, it focused on students' confidence in their ability to collect and interpret patient histories, their proficiency in conducting clinical examinations, and their overall perceived competence in patient assessment. Students rated their skills on a Likert scale, which provided a quantifiable measure of their self-assessment. Analyzing the responses from before and after the intervention was key to assessing the impact of the virtual patient simulator as compared to traditional teaching methods in bolstering students' clinical skills and knowledge.

3,**Tests (Pre- and Post-Intervention Assessment)**
To establish a performance baseline, a pretest was given to students on a dental case that differed from the one used during the intervention. This aimed to measure their initial patient assessment skills. Following the intervention, a post-test was conducted on the same dental case encountered during the intervention phase, whether it was through the virtual simulator or traditional methods. The post-test evaluated the students' comprehension, analytical abilities, and practical application of the knowledge to a real-world scenario. By contrasting the results of the pre- and post-tests, the study sought to quantify the educational impact of each teaching approach, with a particular focus on the effectiveness of the virtual patient simulator in improving dental clinical education outcomes.

## Results and Analysis
#### Google Form Questionnaire Test
1.**Analysis of Control Group Data**
<div align="left">
 <img src="images/control_group_googleform.png" width="700"> <!-- Adjust the width as needed -->
</div>
    
2.**Analysis of Intervention Group Data**
 <div align="left">
 <img src="images/intervention_group_googleform.png" width="700"> <!-- Adjust the width as needed -->
</div>
       
3.**Comparison Between Contro and Intervention Group Data**
<div align="left">
 <img src="images/comparison_GF.png" width="700"> <!-- Adjust the width as needed -->
</div>
          
4.**Average Ratings on the Experience Of 3D Virtual Environment**
<div align="left">
 <img src="images/average_ratings_overall.png" width="700"> <!-- Adjust the width as needed -->
</div>
#### Written Assessment Test

1.**Analysis of Written Test scores**
<div align="left">
 <img src="images/writtenTestScores.png" width="700"> <!-- Adjust the width as needed -->
</div>

2.**Comparison Between Control and Intervention Group Data**
<div align="left">
 <img src="images/comparison_TestScores.png" width="700"> <!-- Adjust the width as needed -->
</div>
  
## Conclusion

The study investigated the effectiveness of a virtual patient simulator as a teaching tool in dental education, comparing it with traditional methods. The findings showed no significant quantitative difference in enhancing history-taking, clinical examination skills, or overall patient assessment. However, qualitatively, students responded favorably to the simulator, indicating high engagement and usability. Despite the lack of significant quantitative improvements, the positive qualitative feedback suggests that the simulator could serve as an effective supplementary educational tool.

There was a notable enhancement in dental assessment skills within the intervention group, hinting at the simulator's potential when focused on particular skills. This points to the possible benefits of integrating such technologies into dental education, especially as part of a comprehensive educational strategy.

The study was limited by its small sample size and preliminary testing phase, suggesting the need for further research with a larger, diverse cohort, a mix of assessment tools, more clinical scenarios, and longer simulator interaction. While the study did not conclusively prove the simulator's superiority, it highlighted the promise of technology-enhanced learning tools in preparing dental students for clinical practice, provided they are optimized for educational use.

## Publications
[//]: # "Note: Uncomment each once you uploaded the files to the repository"


1. [Semester 7 report](./images/semester7_Intro_LR.pdf)
2. [Semester 7 slides](./images/MidPresentation-FYP.pdf)
3. [Semester 8 report](./images/semester7_Intro_LR)
2. [Semester 8 slides](./images/Finalpresentation-FYPNovember.pdf)
<!-- 5. Author 1, Author 2 and Author 3 "Research paper title" (2021). [PDF](./). -->


## Links

[//]: # ( NOTE: EDIT THIS LINKS WITH YOUR REPO DETAILS )

- [Project Repository](https://github.com/cepdnaclk/e17-4yp-Virtual-Patient-Simulator-for-Skill-Training-in-Dentistry)
- [Project Page](https://cepdnaclk.github.io/e17-4yp-Virtual-Patient-Simulator-for-Skill-Training-in-Dentistry)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)

[//]: # "Please refer this to learn more about Markdown syntax"
[//]: # "https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet"
