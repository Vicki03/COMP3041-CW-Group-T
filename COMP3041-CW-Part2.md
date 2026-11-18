# An Ethical Review of Pandai: Children, Data and Learning in a Malaysian EdTech App

**Module:** COMP3041 Professional Ethics  
**Module Convenor:** Dr. Nabil El Ioini  
**Group:** T  

| Name | Student ID |
|---|---|
|Ong Wei Xuan | 20617520|
|Adrian Lee Joon Yin |20611251 |
|Yumna Akif Ali | 20698295|


---

## 1. Introduction

Pandai is a Malaysian learning app, developed by Pandai Education Sdn Bhd, that 
offers curriculum-aligned quizzes, live tuition, an AI study assistant via Ask Pbot 
and gamified rewards to students from Year 1 to Form 5 (Pandai Education Sdn Bhd, 
n.d.-a). Founded in January 2020, it grew rapidly during pandemic school closures 
(EdTechReview, 2022). It follows a freemium model where a basic version is free, while 
full access requires a monthly Premium subscription (Pandai Education Sdn Bhd, n.d.-b).

Its audience is overwhelmingly young. Three-quarters of its users are primary 
students aged 7 to 12, and around a quarter live in rural areas (MIT Solve, n.d.). 
Parents and teachers are secondary users, with dedicated dashboards for monitoring 
students and setting work.

Pandai is significant in Malaysia for three reasons. First, it operates at scale, 
with the company reporting over one million users (BFM, 2025). Second, it is 
expanding into public education, partnering with the Ministry of Education to 
introduce its AI tools in schools (500 Global, 2025). Third, it has a commercial 
interest in engagement: its CEO has stated an aim to increase daily usage from 
57 to 90 minutes (EdTechReview, 2022). Given its large child user base and its 
interest in their time, Pandai deserves a careful ethical review.

In Part 1, we identified four issues, which are children's data and consent, AI chatbot 
transparency, behaviour shaping through rewards, and inconsistent privacy 
disclosures. This report extends that work with new first-hand evidence, 
evaluates each issue against the Software Engineering Code of Ethics 
(ACM/IEEE-CS, 1999), and applies Kantian deontology and utilitarianism where the 
Code falls short.


## 2. Stakeholders

### Direct Stakeholders




### Indirect Stakeholders

Indirect stakeholders never use Pandai themselves but are still affected by how it is designed. We identify two groups.

**Legal guardians who have not registered.** Pandai’s privacy policy deems that any personal data relating to minors is given “with the consent of the minor’s legal guardian”, and that this consent is provided by the child’s registration (Pandai Education Sdn Bhd, 2020; Figure 3). A guardian who never opens the app therefore has deemed consent attached to their name. In our walkthrough, a student could register with only a name, username and password, with no parent step, and was then asked for a home address (Figures 1a, 1c). The guardian’s household address can thus be collected without their knowledge. This is the practice behind Issue 1. The guardian also has no say over who gets access: another adult can link to the child with only a six-digit PIN and then switch into the child’s account (Figure 2). The harm is a loss of control over data about their own child and home, which the policy’s unexplained export and deletion promises do not restore.

**Schools, teachers and the Ministry of Education.** Pandai is partnering with the Ministry to introduce its AI tools in schools (500 Global, 2025). Teachers who do not use Pandai personally and schools that adopt it are affected by Issue 2 and Issue 4. Ask Pbot could not say how chats are stored (Figure 4b), and the privacy policy has not been updated since 2020 and never mentions AI (Figure 3). Education authorities may therefore be endorsing a tool whose handling of pupils’ data they cannot fully explain to parents. This also affects trust in public education. Where use is encouraged by schools, families may feel they cannot refuse.

