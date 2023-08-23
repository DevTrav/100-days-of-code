# 100 Days Of Code - Log

### Day 0: August 7, 2023 


**Today's Progress**: began work on Django API, worked on url routiung and framework for the app. 

**Thoughts:** I really struggled with debugging the API not recognizing the rest_framework module, but, overall, I feel like I am getting better at pushing through hurddles. Django is still new for me, but I managed to figure out some basic functionality. Looking forward to diving deeper into Django and geting the API up and running.

**Link to work:** [To-do List](https://github.com/DevTrav/to-do-list/tree/main)

### Day 1: August 8, 2023 


**Today's Progress**: Debugged url.py routing issues in Django API, learned new testing technique using views.py to confirm new apps(API in my case) and main app url.py routes are working together. Also, I created a new repo for Exercism algo solutions and pushed my local Excercism install as the initial commit. I also honed some clean git flow for when you need to blowup a local repo and reflect the remote repo upstream --> git reset --hard origin/main. Then, clean untracked files in the local repo with --> git clean -xdf. Very handy.

**Thoughts:** I am really proud that I pushed through the discomfort of struggling with debugging the API. Pushing through the challenge led me to a deeper understanding of Django RESt Framework and gave me cofidence boost in my developer troubleshooting skills. 

**Link to work:** [To-do List](https://github.com/DevTrav/to-do-list/tree/main), [Exercism](https://github.com/DevTrav/exercism)

### Day 2: August 9, 2023 


**Today's Progress**: Today I earned my SQL Gold badge on HAckerRAnk! I took some time to focus on fundamentals of algorithms and SQL. 

**Thoughts:** I love how algo problems really make you drill down into logic. Regardless of chosen programming language - Euclidean Distance is calculated same the same way. I remember when solving multiple "easy" HackerRank problems in a single session was challenging. Felt good to earn the gold badge with 4 "medium" problems and take the time to really sit with the solutions.

**Link to work:** [HackerRack Gold Badge Post](https://www.linkedin.com/feed/update/urn:li:activity:7095272166350340098/)

### Day 3: August 10, 2023 


**Today's Progress**: I was contacted about a frontend job using Mapbox and Leaflet. So, I began development on a "Zillow" clone with React frontend, django backend, mapbox and leaflet for listing maps. The app will also connect to a postgres db. The django backend will assigned role-based access for realtors, Admins and users.

**Thoughts:** I am stoked about architecting something that could have a realworld use case and fun to tinker with! The db is not playing nice after install. I will need to reinstall tomorrow and find the source issue. All in all, I am reenergized and having fun coding again.

**Link to work:** [Realtor App](https://github.com/DevTrav/realtor_app.git)

### Day 4: August 11, 2023 


**Today's Progress**: I got hungup on installing and configuring PostgreSQL. Managed to get unstuck and push through. 
**Thoughts:** I am glad I pushed through to a solution. The bump in the road led me to an even faster work flow via running my Terminal.app command via Alfred, instead of opening the application. However, the solution took longer than planned to find. on a positive note, I am really proud of the architecture considerations of my realtor app and i am happy it is fullstack and allows me to practice all of my developer and DevOps skills. 

**Link to work:** [Realtor App](https://github.com/DevTrav/realtor_app.git)

### Day 5: August 12, 2023 


**Today's Progress**: I got inspired by my Day 4 hangup and stayed up (or got up early) and pressed on the get a couple of meaningful backend changes through. I added the django framework and the accounts app for role-based access. After somee sleep, I added the CORSHEADERS to the realtor app (Zillownaire) necessary for user level access to the database. I also did some algo work in Python on HackerRank.
**Thoughts:** Feeling excited to be inspired enough to stay up late and get up early! 
 I realized I have to be much more aggressive in order to see as many solutions as possible. I have to get over 200 problems to remain competative in the interview process. I also realize I need decent sleep and exercise in order to keep up the ferocity. Learning a lot about CORS safety in Django. really enjoying the framework.  

**Link to work:** [Realtor App](https://github.com/DevTrav/realtor_app.git)
### Day 6: August 13, 2023 


**Today's Progress**: I added Simple JWT to the realtor app for API authentication and url paths to use the react build as a view for the frontend UI.
 **Thoughts:**I realized somtimes to go further means going slower. I had to slow down and understand "What" I was building and not just the "How". Instead of just copy/pasting someone else's understanding of Django authentication best praactices, I needed to take a step back and sit with how/why Simple JWT works best when building a backend using Django.  Learning a lot about JWT and authentication safety in Django. Still enjoying the Django dive!

**Link to work:** [Realtor App](https://github.com/DevTrav/realtor_app.git)

### Day 7: August 14, 2023 


**Today's Progress**: Added regex for react routes and url paths to use the react build as a view for the frontend UI.
 **Thoughts:**I got a job today! Coding adjacent but a step in the right direction. Very excited.

**Link to work:** [Realtor App](https://github.com/DevTrav/realtor_app.git)

### Day 8: August 15, 2023 


**Today's Progress**: Lots of local environment debuggging to find the root cause of rest_framework_simplejwt not being imported. Found a [great article](https://python.plainenglish.io/debugging-django-with-vs-code-and-poetry-c41a7c517df0) on debugging `poetry/vs code envirnment issues. Tl;dr poetry virtual enviroments are often not automatically found(or recommended)in the IDE `Select interpreter` options for your python project. When this happens, you can run `poetry info` from the terminal to find and copy the executable path. Then, c the `Select Interpreter` search bar Added regex for react routes and url paths to use the react build as a view for the frontend UI.

App updates:
- Created UserAccountsManager class for user creation
- Created SignUpView class to use UserAccountsManager data on the login page
- Updated url paths
- Updated settings.py to use models
 **Thoughts:** I am making myself stay accountable and making sure I push code everyday. Everyday a meaningful change to the application. I am very proud that I am pushing through the discomfort. I am hoping the grind is a habbit in two more weeks of the challenge. Very excited for the me at day 100.

**Link to work:** [Realtor App](https://github.com/DevTrav/realtor_app.git)

### Day 9: August 16, 2023 


**Today's Progress**: pushed UserAccountManager API changes and performed error tests. 

App updates:
- Tested UserAccountsManager user creation via API
- Updated UserAccounts model
- Updated settings.py to use models
 **Thoughts:** I am feeling resilient. I feel like I am definitely making headway on the first app of the challenge and staying accountable - making sure I push code everyday. The Django Attribute error debug was not straight forward when checking the docs and tutorials. But through resilience, patience and  logical testing I made it through. It was very gratifying to be able to test the API and push changes today.
**Link to work:** [Realtor App](https://github.com/DevTrav/realtor_app.git)

### Day 10-11: August 17-18, 2023 


**Today's Progress**: (postmortem log for 8.17 and 8.17) pushed Realtor user model and view changes for realtor login. Made demo vid of url path and login working for Linkedin and X.

App updates:
- Tested UserAccountsManager user creation via API
- Updated UserAccounts model
- Updated settings.py to use models
 **Thoughts:** My progress and leaning by day 12 (like an aaray, day 1 begins index 0. lolz) has been tremendous. There is a lot to learn when securing a Django API but I am enjoying the ride! The community support is also very encouraging from  X and my network LinkedIn. Feeling less tired. I am hoping that is a sign that I can push through to day 100. For now, I am jsut tryting to pick interesting projects to be excited about.
**Link to work:** [Realtor App](https://github.com/DevTrav/realtor_app.git)

## Day 12: August 19, 2023 


**Today's Progress**: Pushed two Exercism algo solutions to remote. 

Objectives:
- Push two Exercism algo solutions to remote 
- Finalize Django backen and add React frontend
- Post updates on X and Linked in(demo vid or pic or gif if possible)
 **Thoughts:** Did not have as much time for algo as planned. Moving Saturday's objectives to Sunday. 
**Link to work:** [Exercism](https://github.com/DevTrav/exercism.git)

## Day 13: August 20, 2023 


**Today's Progress**: Pushed two python  Exercism algo solutions to remote. 


 **Thoughts:** Today was difficult. A close freind lost a family member. It was hard to move through coding objectives after the service. Going to allow myself to feel this moment and do what I can.  
**Link to work:** [Exercism](https://github.com/DevTrav/exercism.git)

## Day 14: August 21, 2023 


**Today's Progress**: 
- Had a classical programming tutorialwith a good friend and senior dev featuring: python classes, classmethod and staticmethod.  
- Added superuser to Django realtor app
- Set objectives for the remainder of 100DaysOfCode 


 **Thoughts:** Today was long but I'm into it! The fire is there. The skills are coming along with each day. And, my family and new coworkers are behind me. I am commited to consistency. It feels really good!
**Link to work:** [Realtor App](https://github.com/DevTrav/realtor_app.git)

## Day 15: August 22, 2023 


**Today's Progress**: Pushed two python  Exercism algo solutions to remote. 


 **Thoughts:** Today was difficult. Longer day since commuting into the office. It was hard to move through coding objectives. Going to get more sleep and hope this helps to refocus my efforts on larger projects during this time.  
**Link to work:** [Exercism](https://github.com/DevTrav/exercism.git)
