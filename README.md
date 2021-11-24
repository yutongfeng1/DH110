# Benefiting Arizona
#### Yutong Feng | DH110 Fall 2021

## Design Challenge
During the COVID19 pandemic, many families have been struggling due to financial difficulties, plagued with medical bills and risk of unemployment. Through a brief navigation of the Arizona State Government websites, I found that help and resources are too hard to find. Online services and applications are already limited; when hidden in menu options and designed in hidden corners with unintuitive interactions, the design blocks families from the assistance that they need.

I am interested in creating a portal for families, where all government documents, applications, services, and benefits can be managed in one space. Through user research, competitive analysis, persona and journey mapping, I delivered an interactive prototype. This prototype was focused on three key actions to solve current usability problems and improve catastrophic interface problems on the landing page dashboard, where users can view at a glance all available benefit programs.

The three key tasks, validated by user insights, are:
 * to select programs only based on your elibility - Elibility Filter,
 * to compare and contrast programs at a glance - Compare Programs,
 * to mark programs to view for later - Bookmark.

Instead of experiencing the confusing workflow and having to jump between websites, users will be able to not only apply for these applications but to be informed of what each benefit entails on one website. Users will be able to select the information they are most interested in, view these information in a time-efficient and focused manner, and to be able to save and reaccess this information anytime.

## Problem Statement
#### HMW create a government portal for users to browse and apply for benefits in one place?

## UX Research
### Competitor Analysis
In this project, my design challenge is to improve the user experience for government portals. Through research, I find that there is an existing portal called [Health-e-Arizona Plus Portal](https://www.healthearizonaplus.gov/Login/Default). This is a website where applicants can apply for coverage, benefit programs, and government services, such as nutrition benefits, medical coverage, and cash assistance. Applicants are allowed to create accounts to submit applications, view receipts, renew and manage their existing benefits. In order to understand the current ecosystem, I decide it is essential that I heuristically evaluate this website and perform usability testings of key taskflows in order to have a grasp of what I have to do to improve the overall user experience. 

<img src="https://yutongfeng1.github.io/DH110/assignment01/BCover.png" alt="Landing Page" height = "440px"/>
  
  
#### [Heuristic Evaluation](https://github.com/yutongfeng1/DH110/blob/def40afaffc86b3a9e5e92ff5810e0e98d004697/assignment01/A01-Heuristic_Evaluation.md)

During the heuristic evaluation of the Health-e-Arizona Plus website, I identified usability issues concerning lack of visibility of system status (#1), mismatch between system and the real world (#2), lack of consistency (#4), bad UI design (#8), and failures to help users to recognize and recover from errors (#9). With these principles in mind, I defined the scope of what improvements need to be made from the current standpoint. 

#### [Usability Testing](https://github.com/yutongfeng1/DH110/blob/0ef641679d63c68a6d013b29270ddebd4b8f8307/assignment02/A02-UT.md)

Furthermore, I performed an usability testing on the Health-e-Arizona Plus website to explore more detailed usability errors in the workflow. I tested the tasks: 1) screen for eligibility, 2) register account and begin application, 3) search for interview information. These three tasks are measured on the metrics of effectiveness, efficiency, and satisfaction. The usability testing provided insights overlooked in the general heuristic evaluation and highlighted the need to refine labels to better communicate to the user and simplify the taskflow to prevent errors users can not recover from. 


### User Research: Contextual Inquiry

After a clear understanding of the competitor website, I move on to define what target user group we need to serve, and what needs or goals do they have that we must satisfy in this redesign project. I chose to focus on the population of new-grad individuals who look for additional financial support post graduation. 

In the primary context of doing research at home about these programs and the application process via a personal laptop, I performed user research with the combination of participatory observation and interview. Two key activities, performed on the Health-e-Arizona Plus portal were observed: 1) searching for existing benefit programs and 2) evaluating a program to apply for. For the interview, I asked the user about their habits in accessing government information online, whilst targeting their general attitude and experience with filling in government applications. 

4 key insights were concluded:

 1️⃣ User perceives a strong correlation between aesthetically pleasing UI and security/legitimacy. 
 
 2️⃣ User feels overwhelmed not only by the sheer amount of information presented, but the fact that some key information are presented only in later steps. 
 
 3️⃣ User adores the screening tool that defines their eligibility for programs, but wish it was more emphasized and accessible. 
 
 4️⃣ User is dissatisfied with the current taskflow that is too inefficient and redundant. 
 
 With these insights, I undertsood the need for the redesign to accentuate **simplicity, acccessibility, and efficiency**. The contextual inquiry allowed me to identify two key features to improve: 1) Eligibility Filter, and 2) Compare/Contrast Tool. 
 
[read more about my user research...](https://github.com/yutongfeng1/DH110/blob/0ef641679d63c68a6d013b29270ddebd4b8f8307/assignment03/A03-User_Research.md)


## Storytelling
Before jumping into the actual design, it is important that we truly emphasize with the target users' pain points, behaviors, thoughts, and feelings. Therefore, to optimize the human-centeredness of this project without pre-existing assumptions and biases, I created persona, empathy maps, user scenarios, and journey maps. 

### Persona & Empathy Maps
#### Persona 1: Christina Lee
<img src="https://yutongfeng1.github.io/DH110/assignment04/Christina Persona.png" alt="Christina's Persona Sheet - Demographics, Bio, Core Needs, Frustrations" width = "800px"/>

#### Christina's Empathy Map
<img src="https://yutongfeng1.github.io/DH110/assignment04/Christina's Empathy Map.png" alt="Christina's Empathy Map" width = "800px"/>

#### Persona 2: Luke Granados
<img src="https://yutongfeng1.github.io/DH110/assignment04/Luke Persona.png" alt="Luke's Persona Sheet - Demographics, Bio, Core Needs, Frustrations" width = "800px"/>

#### Luke's Empathy Map
<img src="https://yutongfeng1.github.io/DH110/assignment04/Luke's Empathy Map.png" alt="Luke's Empathy Map" width = "800px"/>
  
### Journey Mapping

#### Christina's Journey Map: Eligibility Filter
<img src="https://yutongfeng1.github.io/DH110/assignment04/Christina's Journey Map.png" alt="Christina's Journey Map" width = "800px"/>

#### Luke's Journey Map: Compare/Contrast Feature
<img src="https://yutongfeng1.github.io/DH110/assignment04/Luke's Journey Map.png" alt="Luke's Journey Map" width = "800px"/>

[read more about the user scenarios...](https://github.com/yutongfeng1/DH110/blob/0ef641679d63c68a6d013b29270ddebd4b8f8307/assignment04/A04-Persona.md)

## Wireframing
After integrating user research insights with the persona and journey mapping insights, I've decided on three tasks and features to support in this redesign:
 1. Eligibility Filter
 2. Compare Programs
 3. Bookmark Programs

### Low-Fidelity Prototype and Wireflow
I began with a low-cost "paper" prototype to visualize and test the structural elements of the product. This helped me invision the final product by designing the brief functionalities, testing features and taskflow with users, and creating simple interactions. 

#### Wireflow
<img src="https://yutongfeng1.github.io/DH110/assignment05/wireframeflow.jpg" alt="wireflow of how all three tasks tie-in together" width = "850px"/>

After drawing the low-fidelity wireframes and creating a wireflow, I tested the prototype with a user to understand whether my assumptions were aligning with the experience of the users'. 

#### Prototype Test
<img src="https://yutongfeng1.github.io/DH110/assignment05/prototypetest.jpg" alt="how the user interacted with the low-fi prototype" width = "850px"/>

The prototyping test was valuable as it highlights a list of areas I need to improve for the high-fidelity prototype:
 1. Clearer copy on main actionables
 2. Create hierarchy of features: "compare programs" should be only available after the user has added the eligibility filter
 3. Develop ways for the system to explain what each feature means
 4. How to better present bulky information -> consider switch from mobile to web-app.

With the insights from the prototype test, I iterated the wireframes of the MVP flow and transferred them onto Figma. This digitized design was presented to the user for his feedback on the visual UI elements. 

<img src="https://yutongfeng1.github.io/DH110/assignment05/iterate1.jpg" alt="low-fi wireframes on eligibility filters and compare programs" width = "700px"/>

[read more about my low-fidelity wireframing process...](https://github.com/yutongfeng1/DH110/blob/0ef641679d63c68a6d013b29270ddebd4b8f8307/assignment05/A05-LowFiPrototype.md)

### Graphic Design Variations
In the low-fi wireframing process, I laid out the basic skeleton, actionables, taskflow, and key functionalities. Now, it is important that I create a consistent design library that I can work with to create the high-fidelity prototype. I implemented a grid to determine the information structure for the elements and explored typography which then informed the shape and sizes of the buttons and cards. Both light and dark color themes were developed that would be fitting for the intendend legitimacy of the website and all existing states of interactive buttons.

#### Design Iterations
Layout
<img src="https://yutongfeng1.github.io/DH110/assignment06/Layout.jpg" alt="Layout Grid of the Screens" width = "850px"/>

Typography
<img src="https://yutongfeng1.github.io/DH110/assignment06/Font Variations.jpg" alt="Iterations on Typography" width = "850px"/>

Shape
<img src="https://yutongfeng1.github.io/DH110/assignment06/Shape Variations.jpg" alt="Different roundness of buttons and cards" width = "850px"/>

Color
<img src="https://yutongfeng1.github.io/DH110/assignment06/Colors.jpg" alt="Light and Dark Color Theme" width = "850px"/>

#### Final Style Guide
A brief run down:
 * Layout: 6x6 with 12px gutter 100x margin
 * Shapes: 24px roundness
 * Font: New York and DM Sans
 * Color: Presentative of Arizona however clean and mostly of low saturation. Color combinations are tested and the color contrasts were all accessible. 

<img src="https://yutongfeng1.github.io/DH110/assignment06/StyleGuide.jpg" alt="Design Style Guide of Interface" width = "850px"/>

[read more about interface design iterations...](https://github.com/yutongfeng1/DH110/blob/0ef641679d63c68a6d013b29270ddebd4b8f8307/assignment06/A06-InterfaceDesign.md)

## High-Fidelity Prototype
Feedback from the impression test on the graphic design elements of the product validates the design as secure, legitimate, and professional. The next step is to create an interactive, high-fidelity prototype that would allow me not only to test the inituitiveness of the interactions, but to see if improved graphics and UI components help support a better user experience and faciliate the user's understanding of the taskflow. 

With the Eligibility Filter and Compare Programs features most valuable and desirable to the product, they will be the center of the focus for the prototype.

#### High-fidelity Interface
<img src="https://yutongfeng1.github.io/DH110/assignment07/interface.png" alt="interface design of product" width = "850px"/>

#### Wirefliow
<img src="https://yutongfeng1.github.io/DH110/assignment07/wireflow.png" alt="wireflow for the two tasks" width = "850px"/>

#### [Interactive Prototype](https://www.figma.com/proto/JSKqJ6KhHVMF8IhV1pzBKE/DH110-A06?page-id=0%3A1&node-id=50%3A486&viewport=241%2C48%2C0.25&scaling=contain&starting-point-node-id=50%3A486)

[read more about my high-fidelity prototyping process...](https://github.com/yutongfeng1/DH110/blob/0ef641679d63c68a6d013b29270ddebd4b8f8307/assignment07/A07-InteractivePrototype.md)


## Usability Testing
I performed four cognitive walkthroughs with a power user and with three other DH110 students during classtime. For each of their interactions with the prototype, I asked the questions: 1) Is this the outcome they expected to achieve?, 2) Did the user know how they could achieve the right outcome?, 3) Additional comments about the UI design. 

The four users worked through the eligibility filter and compare programs features. Usability testing illuminate 5 key insights:


  ✅ Button copies are much clearer than ones propoesd earlier. The user is able to understand the outcome that can be achieve by these buttons.
 
  ✅ Users were able to achieve MVP taskflows for both tasks without error.

  ✅ Users interacted with the bookmark function and understood the hierarchy that exists with eligiblity filter being most valuable and the bookmark feature being less significant.

  💔 3/5 Users dislike the layout of the compare programs page that lacks negative space, directionality, nor clear information hierarchy. 

  💔 3/5 Users dislike the logo. Though they understand the need for a clean and legitimate label, they feel that the logo design does not match the minimalistic, light layout. 
 
 
My take aways from the cognitive walkthrough allowed me to make ammendments to the design, such as upgrading the design of the logo with a more trendy-looking color gradient, reorganizing the layout of the compare programs page, and refining the prototype to reflect a viable product (e.g., adding additional screens in wireflows to make sure that users are located in the right pages and progress feedback is clean). 

## Pitch Presentation Video
[View here on Youtube]
  
## Conclusion

It was really comprehensive to experience the entirety of the UX design process from competitive analysis, user research, persona and user scenario mapping, low-fidelity wireframes, interface design iterations, high-fidelity prototype, usability testing, to even the final pitch presentation. I know that not one product follows the exactly the same methodology for research methods nor design process, therefore this was really meaningful to have the experience of planning and conducting UX methodologies of which I've never done before for other projects, such as contextual inquiries, impression testings, and cognitive walkthroughs. For each step in the process, I thought it was meaningful that we were able to define what the step meant for our project and our design vision and to authentically engage with the materials as well as our users. 

Over the entire design process, I do think that usability testing is the hardest to create and facilitate. It was hard to come up with unbiased responses to the users' questions and it was hard to come up with neutral, non-leading questions on the spot when the user just did something spontaneous or interesting. I found it also hard to design the perfect path for the user to complete the task beforehand, and I really have had the priviledge of an opportunity to practice this craft during this experience. The process I enjoyed the most was low-fidelity wireframing and wireflow testing - the conversations that were elicited throughout the wireflow testing was insightful and gaveway to many of the great, key design decisions I've made in the high-fidelity prototype. It was a pity that I did not have the time to do more usability testings and iterations on this project; success metrics, deliverable results, and user feedback should be key points that I should focus on moving forward. Nonetheless, it was a pleasure to redesign a government website that can help transform and improve the lives of many, and I was relieved to have received many positive feedback on my final high-fidelity interactive prototype. I love to hear that I have simplifed with workflow, transformed the UI with minimalistic elements, and inituive interactions allowed users to catch the sense of security and legitimacy of this website. With more experiences in designing professional platforms and website information structures, I hope that in the future I will be able to work on extensive projects with great social impacts like this. 
