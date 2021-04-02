# Challenges with Docker replication package

## Description

User study to assess the challenges and practices used when working with Docker technologies, namely Docker and Docker Compose. Two runs of this survey have been executed. The [first run](#first-run) of the survey was conducted with students. The [second run](#second-run) was conducted with a wider audience of professionals will allow to study how the results may generalize to experienced software developers.

## Content list

- `/data_analysis`
  - Contains the jupyter notebook used to analyse the data collected in the study.
- `/first_run`
  - Contains the survey (`survey.pdf`), raw results (`raw_results.csv`) and results filtered by experience with Dockerfiles (`filtered_results.csv`) for the first run of the survey.
- `/second_run`
  - Contains the survey (`survey.pdf`), raw results (`raw_results.csv`) and results filtered by experience with Dockerfiles (`filtered_results.csv`) for the second run of the survey.

## Procedure

This study makes use of an online questionnaire as a data collection method, to make the most effective use of the time of participants and researchers. This questionnaire can be distributed using an online _survey administration system_, such as _Google Forms_. 

### First Run

The data collection was executed in 2 stages:

1. Initially performed physically in 6 classes with an average of 26 students, taking approximately 1 hour in total. For each class the following procedure was performed:
   * The link to access the form online was written on the classroom's whiteboard.
   * The researchers briefly explained the context, goal, motivation and how the students could access the form.
   * The researchers oversaw the filling procedure until completion, and aided the participants with any doubts about how the questions were posed.
2. After the classes, the questionnaire was distributed through e-mail to the same target audience, to allow answers to be received from students that were not physically in the classroom during the first stage. The form was closed after a period of 1 week.

### Second Run

The questionnaire was distributed in the context of the [on-site research track](https://www.agilealliance.org/xp2020/call-for-submissions/call-for-onsite-research/) of the XP 2020 conference. 

To disseminate it, used the support of the conference organizers and of the _on-site research_ track in particular. The form remained open during the entire time of the conference (June 8-12, 2020) and until one week after the conference.

The survey was also distributed in communities and forums directed towards Docker, DevOps and general-purpose programming.

## Findings

- Participants generally found most Dockerfile development activities to be time consuming.
- The debugging activities of Dockerfile development, such as understanding why a container isn't working or re-building the Docker image, were generally identified as the most time-consuming, although there isn't a very large difference between all the activities. This is particularly true for the second run of the study.
- The approaches to Dockerfile development commonly rely on trial and error and manually building, raising and inspecting the images and containers under development.
- Participants from the second run of the survey, who were slightly more experienced in Dockerfile development than the participants from the second run, also mentioned more structured and formal approaches, such as testing and pipelines.
