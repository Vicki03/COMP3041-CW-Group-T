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

Students (minors aged 6–18). As Pandai’s primary end-users, students interact directly with every feature that we have identified. When signing up, children register with only a username and password without parental verification, and the profile screen subsequently prompts them for their home address under the promise of physical "gifts and rewards." In the learning interface, students interact with Ask Pbot, an AI study buddy that admitted during walkthrough testing that it does not know how chat conversations are stored or used, while readily answering off-topic entertainment queries. Furthermore, student learning routines are governed by aggressive gamification: virtual coins expire within 36 hours unless a quiz is submitted, chapters are locked behind star requirements, unblurred national leaderboards publish children's real names and photos, and reward catalogs offer commercial gaming credits (Mobile Legends, PUBG, Roblox). These mechanics exploit loss aversion and social comparison, inducing stress and shifting student motivation from self-directed study to compulsive engagement (Radesky et al., 2022).

Registered parents and guardians. Parents who create accounts to oversee learning or purchase subscriptions are affected by onboarding, monetization, and disclosure practices. In the parent portal, linking a child requires only an unverified six-digit student PIN with no proof of legal guardianship, and the dashboard allows parents to silently switch into and monitor the child's session without the child's knowledge. Financially, the 36-hour coin-expiry prompt explicitly directs users to buy a Premium subscription to keep coins permanently, while high-value gaming vouchers are restricted behind paid tiers, creating child-driven financial pressure on household budgets. In terms of transparency, parents face contradictory disclosures: Google Play’s Data safety section states that no data is shared with third parties, whereas the iOS App Store indicates personal data is collected for cross-app tracking. These conflicting declarations prevent parents from making an informed risk assessment regarding their child’s digital safety (Arkalakis et al., 2024).

Pandai Education Sdn Bhd and its developers. The operating company and its technical workforce design, maintain, and monetize the platform. Company management benefits commercially from low-friction student onboarding and gamified retention loops that drive subscription revenue. However, these practices create serious regulatory and reputational liabilities: Pandai’s published privacy policy has not been updated since October 2020, omits Ask Pbot entirely, and directly contradicts app store data declarations. For software engineers, implementing artificial countdown timers, star-gated curriculum locks, and opaque AI integrations without data-retention controls places them in direct professional conflict with their duty to protect user privacy and avoid deceptive software design (ACM/IEEE-CS, 1999, Clauses 1.03, 1.06).

Third-party advertising and analytics partners. Pandai’s privacy policy permits data sharing with third parties for "personalisation" and "behavioural analysis," while its App Store label declares that user identifiers are shared to track children across other companies' apps. These commercial partners receive granular behavioral and device data from a captive audience of minors. However, because the Google Play label claims zero third-party data sharing and the privacy policy names no specific corporate recipients or ad networks, these partners operate with complete opacity and zero direct accountability to families.


### Indirect Stakeholders

Indirect stakeholders never use Pandai themselves but are still affected by how it is designed. We identify two groups.

**Legal guardians who have not registered.** Pandai’s privacy policy deems that any personal data relating to minors is given “with the consent of the minor’s legal guardian”, and that this consent is provided by the child’s registration (Pandai Education Sdn Bhd, 2020; Figure 3). A guardian who never opens the app therefore has deemed consent attached to their name. In our walkthrough, a student could register with only a name, username and password, with no parent step, and was then asked for a home address (Figures 1a, 1c). The guardian’s household address can thus be collected without their knowledge. This is the practice behind Issue 1. The guardian also has no say over who gets access: another adult can link to the child with only a six-digit PIN and then switch into the child’s account (Figure 2). The harm is a loss of control over data about their own child and home, which the policy’s unexplained export and deletion promises do not restore.

**Schools, teachers and the Ministry of Education.** Pandai is partnering with the Ministry to introduce its AI tools in schools (500 Global, 2025). Teachers who do not use Pandai personally and schools that adopt it are affected by Issue 2 and Issue 4. Ask Pbot could not say how chats are stored (Figure 4b), and the privacy policy has not been updated since 2020 and never mentions AI (Figure 3). Education authorities may therefore be endorsing a tool whose handling of pupils’ data they cannot fully explain to parents. This also affects trust in public education. Where use is encouraged by schools, families may feel they cannot refuse.

