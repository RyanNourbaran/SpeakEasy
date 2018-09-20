# HTN_2018

#Inspiration
From students to the most seasoned professionals, presenting to a crowd of people can be tough. What if you knew how you were truly doing, and could actively make the effort to learn and improve as your deliver more and more presentations?

With SpeakEasy, now you can.

#What it does
Provide analytics and cue recommendations towards conveying engaging, well-delivered presentations. SpeakEasy does this in two stages: 1. by providing a real time, 'heads-up' display for presenters, and 2. providing personalized analytics for presenters to allow them to see the big picture.

1. Real-time heads-up display
Our real-time 'heads up' display provides a display overlaid onto a video feed of a presenter's audience. The presenter will have real time information about: audience engagement, perceived emotions in the crowd, voice projection sufficiency, and more.

2. Post-presentation analytics
Our post presentation analytics dashboard let's a presenter evaluate their own performance after the fact. Users are able to view useful metrics such as: emotion/engagement distribution over time, frequency of use of 'filler' or 'crutch' words (such as 'ah', 'um', 'like', 'uh'), and are provided a tailored presentation media recommendations of exemplar works for users to draw insight or inspiration from (per presentation).

#How we built it
Our team created a cross platform web application (yes it works on your phone!) using Vue.js, Flask, and Python.

#Challenges we ran into
Our team had never used Vue.js and Flask before, and had limited experience with the computer vision and machine learning necessary for the visual and vocal processing required for our user outputs. While our initial set-up was relatively obstacle free, we ran into several server-side challenges, which we were able to collectively solve, with the support of Hack the North mentor guidance. Setting up data pipelines and processing large amounts of synthetic data (open data) for our recommendation engine was also challenging, given our tight time constraints and relatively limited domain knowledge.

#Accomplishments that we're proud of
We're proud of having created an MVP, from concept to production, in just 36 hours! Our team was formed very shortly before the hackathon began, and our members came from a variety of countries and backgrounds. In particular, we were proud of having ...

Built a fully functional web application developed using Vue.js and Flask, with a connected Firebase Realtime Database in 36 hours.
Used several Microsoft Azure APIs for facial and emotion detection, as well as speech to text (STT).
User tested our real-time application with over 50 other Hack the North hackers and organizers, with excitement and enthusiasm for the concept!
Developed a machine learning recommendation engine (using to provide exemplars of good, related presentations for users, based on their historical and most recent performance.
Consumed over 22 cans of Red Bull (collectively, of course).
What we learned
Loads of things. Below are our most striking accomplishments in the past 36 hours:

Addressing lack of training data by exploring open data sets (both text and video).
How to fuse a statistical and machine learning model to tailor results to a specific use case.
What's next for SpeakEasy
Developing the tool further. Our team sees potential for adoption in real world scenarios, especially as we see the rise of technology taking a greater role in everyday life. In the 36 hours we've had at Hack the North 2018, our proof of concept application has only skimmed the surface in the limitless possibilities available with the use of our tool.

#In particular, some items on our development horizon are, among others:

Leveraging actively learning machine learning models to identify adequate levels non-engagement, and targeted recommendations as to how to improve audience engagement.
Developing a bespoke facial detection and activity tracking model. We believe that being able to target specific causes for disinterest or non-engagement (such as conversations with seat neighbours) is of great interest to presenters.
Further making use of 'crutch' or 'filler' words and providing real-time cues to avoid using such words.
Integrating the use of motion detecting and/or camera hardware in order to provide feedback on body posture, hand gestures, mal-habits (such as shuffling on the spot), and more.
We see this project with strong applicability for the following demographic groups:

Stand-up comedians and similar entertainers
Motivational and professional speakers
Keynote presenters
Students who may use this application passively for presentation dry-runs, etc.
Built With
python
scikit-learn
vue.js
flask
azure
firebase
google-cloud
d3.js
