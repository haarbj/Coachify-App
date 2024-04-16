# Coachify

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

Coachify is a specialized running app designed to facilitate communication between runners and their coaches, allowing for personalized training plans and performance monitoring. Runners can log their runs, input various metrics such as distance, pace, elevation, and perceived effort, and provide additional context or notes about each session. Coaches can then review this data, analyze trends, and offer tailored recommendations to optimize training and maximize results.

### App Evaluation
   - **Category:** Health & Fitness
   - **Mobile:** Coachify leverages mobile technology to offer a seamless and intuitive user experience. Runners can easily access the app on their smartphones or tablets, enabling them to log runs on the go, eventually sync data from wearable devices, and communicate with their coaches in real-time. Coaches, likewise, can access the platform from any device, allowing for flexibility in managing training programs and interacting with athletes.
   - **Story:** Coachify empowers runners to take their training to the next level by providing direct access to expert coaching and personalized guidance. Whether preparing for a race, aiming to improve performance, or recovering from injury, Coachify serves as a virtual training companion, offering support, motivation, and accountability every step of the way.
   - **Market:** Coachify caters to a diverse range of runners, including recreational joggers, competitive athletes, and individuals pursuing specific fitness goals. It appeals to anyone seeking professional coaching and structured training plans, regardless of their experience level or running objectives. Additionally, Coachify may attract coaches looking to expand their client base and offer remote coaching services to a broader audience.
   - **Habit:** Both runners and coaches establish habitual usage of Coachify as part of their training routine. Runners diligently log their runs, provide feedback on their performance, and follow the prescribed training plans provided by their coaches. Coaches, in turn, regularly review athlete data, adjust training schedules as needed, and provide ongoing support and motivation to ensure consistent progress and success.
   - **Scope:** Coachify's development roadmap outlines various enhancements and features aimed at improving the user experience and adding value to both runners and coaches. Key milestones include integration with popular fitness trackers and wearables, advanced analytics and performance insights, interactive training programs, and community engagement features to foster collaboration and support among users.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Run logging: Runners must be able to log their runs, including distance, duration, pace, and any additional notes.
* Personalized training plans: Users should be able to access and look at customized training plans tailored to their goals and abilities.
* User registration: Coaches and runners should be able to create a new account on Coachify.
* User authentication: Users should be able to securely log in to their Coachify accounts.

**Optional Nice-to-have Stories**

* Run route mapping: Runners can map out their running routes using GPS tracking within the app.
* Weather integration: The app can integrate weather forecasts to provide runners with real-time weather conditions during their runs.
* Wearable device compatibility: Coachify can sync with popular fitness trackers and wearable devices to collect additional data, such as heart rate and cadence.
* Social sharing: Runners can share their runs, achievements, and progress on social media platforms directly from the app.
* Group challenges: The app can facilitate group challenges and competitions to motivate runners and foster a sense of community.
* Training resources: Coachify can provide access to training articles, videos, and resources to help runners improve their performance and knowledge.
* Goal setting: Runners can set specific goals and targets within the app, with progress tracking and reminders to keep them on track.
* Performance comparisons: The app can allow runners to compare their performance with other users or benchmark standards.
* In-app purchases: Coachify can offer premium features or additional coaching services through in-app purchases or subscriptions.
* Data synchronization: The app should sync data between devices to ensure a seamless user experience.
* Coach-runner communication: Coaches and runners should be able to exchange messages, share feedback, and discuss training plans within the app.
* Performance analysis: Coaches should have access to detailed analytics and performance metrics for each runner.
* Personalized training plans: Coaches should be able to create and assign customized training plans tailored to each runner's goals and abilities.
* Notification system: The app should notify users of important updates, messages from coaches, and upcoming training sessions.

### 2. Screen Archetypes

- [ ] Login/Register
* User authentication: Users should be able to securely log in to their Coachify accounts.
* User registration: Coaches and runners should be able to create a new account on Coachify.

- [ ] Run Logging
* Run logging: Runners must be able to log their runs, including distance, duration, pace, and any additional notes.

- [ ] Training Plans
* Personalized training plans: Users should be able to access and look at customized training plans tailored to their goals and abilities.
* Personalized training plans: Coaches should be able to create and assign customized training plans tailored to each runner's goals and abilities.

- [ ] Dashboard/Home
* Data synchronization: The app should sync data between devices to ensure a seamless user experience.
* Coach-runner communication: Coaches and runners should be able to exchange messages, share feedback, and discuss training plans within the app.
* Performance analysis: Coaches should have access to detailed analytics and performance metrics for each runner.
* Notification system: The app should notify users of important updates, messages from coaches, and upcoming training sessions.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* [fill out your first tab]
* [fill out your second tab]
* [fill out your third tab]

**Flow Navigation** (Screen to Screen)

- [x] Login/Register Screen
* => Home/Dashboard

- [x] Run Logging Screen
* => Home/Dashboard

- [ ] Training Plans Screen
* => Home/Dashboard

- [x] Home/Dashboard Screen
* => Run Logging Screen
* => Training Plans Screen
* => Messages/Communication Screen
* => Settings/Profile Screen

- [ ] Messages/Communication Screen
* => Individual Chat Screen
* => Settings/Profile Screen

- [ ] Settings/Profile Screen
* => Edit Profile Screen
* => Notification Settings Screen
* => Account Settings Screen
* => Logout

## Wireframes

[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

[This section will be completed in Unit 9]

### Models

[Add table of models]

### Networking

- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
