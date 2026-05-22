# Looply
A web application that helps users stay focused, stay motivated and track their productivity. 

## Features
Session setup: CRUD operations on tags and motivational messages  
Creating session: choosing round duration, number of rounds and number of repetitions; optionally, adding tags to better organize sessions  
Session state actions: Pause/Continue session, Done(as early done) session, Cancel(as quit) session  
Statistics preview: based on selected tags, shows time spent on weekly report  
Reward moment: After completing session, users receive virtual flower which can be planted anywhere on virtual garden(screen)  

## Tech Stack
  Backend:
  - NestJS 
  - TypeORM
  - PostgreSQL
  - Passport.js
  - Typescript
    
  Frontend:
  - Angular
  - Angular Material
  - NgRx – state management
  - rxJS
  - Chart.js
  - ng2-charts
  - Typescript

## Preview
### Login/Register page
![alt text](<login page.PNG>)

### Started session - round 1/4, round duration = 50min, with initial message
![started session](<started session.PNG>)

### Session setup - tags and motivational messages manipulation
![alt text](<settings tab.PNG>)

### Garden tab = rewards for successfully completed sessions
![alt text](<garden tab.PNG>)
