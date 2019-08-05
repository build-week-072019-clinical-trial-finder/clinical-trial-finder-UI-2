# clinical-trial-finder-UI
UI repo for Clinical Trial Finder

Proposal
________________


- What problem does your app solve?
The drug development process is in crisis. Returns on R&D have been decreasing for decades and fewer drugs are reaching the market. One contributing factor to this crisis is the lack of information transparency in the clinical trial market (a key part of the drug development process). 
An astounding 80% of clinical trials fail to meet recruitment timelines and 1 in 4 cancer research trials falter due to low patient recruitment. Many patients do not even know these trials exist.

- Be as specific as possible; how does your app solve the problem?
We have developed a solution that increases information transparency and helps patients (and family members) evaluate potentially life-saving clinical trials. In the process, recruiting enough participants for the study to make.

- What is the mission statement?
Helping patients connect with potentially life-saving cutting-edge empirical treatments, at the same time helping researchers find the study participants they despartely need.

Features
________________


- What features are required for your minimum viable product?

   -Visualize Active Clinical Trials on an interactive website
   -Filter by intervention (disease area) 

- What features may you wish to put in a future release?
	- Assign completion probability to each active trial (using historical trials as train data)
	- Allow users to add trials to a 'watch list' 
	- Allow users to filter based on eligibility criteria (will require extensive feature extraction)  
	- Create interactive webpage(s) to host a data storytelling project exploring characteristics of successful trials (and more) 

- What do the top 3 similar apps do for their users?
    -search for trials by condition and location

Frameworks - Libraries
________________


- What 3rd party frameworks/libraries are you considering using?

The application used React for components composition. Semantic-UI-React for styling and Redux for state management.

Node.js for backend. We used Knex for the migrations and Heroku for deployment.

- Do APIs require you to contact its maintainer to gain access?

We have built our own backend to support the APIs.

- Are you required to pay to use the API?

No
- Have you considered using Apple Frameworks? (MapKit, Healthkit, ARKit?)

No, these frameworks are beyond our current knowledge.

For Data Scientists
________________




- Describe the Established data source with at least rough data able to be provided on day 1. 
- You can gather information about the data set you’ll be working with from the project description. Be sure to collaborate with your PM, and your Backend Architect to chat about the resources you have.
- Write a description for what the DS problem is (what uncertainty/prediction are we trying to do here? Sentiment analysis? Why is this a useful solution to a problem?)
- A target (e.g. JSON format or such) for output that DS students can deliver to web/other students for them to ingest and use in the app


Target Audience
________________


- Who is your target audience? Be specific.
	Patients and their families. The app can also be used by Clinicians to help their patients look for potential cures. 

- What feedback have you gotten from potential users?

- Have you validated the problem and your solution with your target audience? How?
	One of the biggest barriers to clinical research is patient recruitment, which can lead to delays, early trial termination or withdrawal, or inconclusive data, thus affecting trial success. The barrier may be attributed to various factors, including subjects' misunderstanding about research, eligibility factors, location, or simply that the subjects are not aware of the studies. All of these can prevent eligible subjects from participating in a research study that may potentially help them. Our app is built with the hope to address these gaps, by connecting patients to recruiting trials.  

Research
________________


- Research thoroughly before writing a single line of code. Solidify the features of your app conceptually before implementation. Spend the weekend researching so you can hit the ground running on Monday.
Prototype Key Feature(s)
________________


- This is the “bread and butter” of the app, this is what makes your app yours. Calculate how long it takes to implement these features and triple the time estimated. That way you’ll have plenty of time to finish. It is preferred to drop features and spend more time working on your MVP features if needed.