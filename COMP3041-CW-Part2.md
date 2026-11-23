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

Pandai affects both the people who use it and people who never open it. For each 
group, we set out the features that affect them, how, and the evidence.

### 2.1 Direct Stakeholders

Direct stakeholders use Pandai or make decisions about it.

**Students (Issues 1–4).** Students aged 6 to 18 are Pandai's primary users and 
are affected by every issue we identified. They register with only a name, 
username and password, with no parent step, and are then asked for a home 
address in exchange for gifts and rewards, although this step can be skipped 
(Figure 3.1a). They also chat with Ask Pbot, which could not explain how 
conversations are stored [Fig: pbot]. Their routines are shaped by 
gamification: coins expire within 36 hours unless a quiz is submitted, national 
leaderboards display their names and photos, and rewards include gaming 
credits [Fig: coins], [Fig: leaderboard], [Fig: vouchers]. Such mechanics risk 
shifting motivation from learning towards compulsive engagement (Radesky et al., 
2022).

**Registered parents (Issues 1, 3 and 4).** Parents link to a child using only 
a six-digit PIN, with no proof of guardianship, and can then switch into the 
child's account without the child being notified (Figures 3.1b, 3.1d). The 
coin-expiry prompt directs them towards a Premium subscription [Fig: coins]. 
They also face contradictory disclosures: Google Play states that no data is 
shared with third parties, while the App Store lists data used to track users 
across other companies' apps [Fig: labels]. This prevents an informed choice 
about their child's data (Arkalakis et al., 2024).

**Pandai Education Sdn Bhd and its developers (Issues 1–4).** The company 
benefits commercially from easy sign-up and engagement-driven retention. Its 
developers build the countdowns, locked chapters and AI features, yet business 
decisions such as linking coin retention to subscriptions rest with management. 
This places developers under the Code's duties to protect privacy and avoid 
deception (ACM/IEEE-CS, 1999, Clauses 1.03, 1.06).

**Business partners (Issues 2–4).** The Ministry of Education has worked with 
Pandai to introduce its AI tools in schools (500 Global, 2025), lending the app 
public credibility and sharing responsibility for its data practices. Reward 
partners reach young users through gaming vouchers [Fig: vouchers]. The privacy 
policy also permits sharing data with unnamed third parties for 
"personalisation" and "behavioural analysis" (Pandai Education Sdn Bhd, 2020), 
so families cannot tell which companies receive their children's data.

### 2.2 Indirect Stakeholders

Indirect stakeholders never use Pandai themselves but are still affected by how 
it is designed.

**Legal guardians who have not registered (Issue 1).** Pandai's privacy policy 
deems personal data relating to minors to be given "with the consent of the 
minor's legal guardian", and treats the child's registration as that consent 
(Pandai Education Sdn Bhd, 2020; Figure 3.1c). A guardian who has never heard of 
Pandai therefore has consent recorded on their behalf. Their child can register 
with no parent step and be asked for a home address (Figure 3.1a), so household 
data may be collected without the guardian's knowledge. Guardians also cannot 
control who gains access: any adult who obtains the child's PIN can link to the 
account and switch into it, and more than one adult can do so (Figures 3.1b, 
3.1f). Although accounts can be deleted, this is only possible from inside the 
app (Figure 3.1h), which an unregistered guardian may not know exists.

**Schools and non-using teachers (Issues 2 and 4).** As Pandai's work with the 
Ministry brings it into classrooms (500 Global, 2025), schools and teachers who 
never use the app may still be expected to recommend it. Yet Ask Pbot could not 
explain how chats are stored [Fig: pbot], and the privacy policy, unchanged 
since 2020, never mentions AI (Figure 3.1c). Schools may therefore be 
encouraging a tool whose handling of pupils' data they cannot explain to parents.