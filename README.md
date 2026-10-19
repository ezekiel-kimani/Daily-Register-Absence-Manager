# Daily Register and Absence Manager

**An AI-powered school attendance support app built with AWS PartyRock**

## Project overview

The Daily Register and Absence Manager is a prototype designed to help teachers manage some of the work that follows student absences. It takes school and lesson details, information about absent students, and their cumulative missed days, then generates parent email templates, student makeup assignments, and a risk assessment indicator to help teachers identify cases that may need attention.

I built this app during the Udacity AWS AI & ML Scholars Challenge in June 2026. My goal was to explore how an AI application could make a repetitive school administration task easier to manage.

## The problem I wanted to address

When students miss lessons, teachers may need to communicate with parents, identify missed work, prepare catch-up assignments, and consider whether repeated absences require further attention. Preparing these materials individually can take time, especially when several students are involved.

In some cases, students may miss classes while their parents believe they are attending school as expected. This can leave parents unaware of their children's absences and delay the support needed to help them catch up.

The app also aimed to help teachers keep parents informed about their children's progress and missed work in a timely manner, making it easier for parents to understand how their children were doing and where additional support might be needed.

I wanted to bring these related tasks into one reusable app instead of having to write a new, detailed prompt every time I needed the same types of output.

## How I built it

I used AWS PartyRock, a tool for building AI-powered applications, by describing the problem and prompting it to generate a starting point. I then worked with the generated app to meet the project requirements.

The intended workflow brought together three outputs:

- **Parent communication:** Email templates teachers can review and adapt before contacting parents.
- **Makeup assignments:** Suggested work to help students catch up on missed lessons.
- **Risk assessment:** An indicator intended to help teachers identify students whose repeated absences may warrant follow-up.

The app was designed around separate input fields and output widgets, allowing the teacher to provide information and review the resulting materials in an organized format.

This was a prompt-guided, no-code app-building exercise. PartyRock generated the application structure and AI-powered functionality; my contribution was defining the use case, describing the required behavior through prompts, guiding the app toward that workflow, testing the results, and completing the challenge submission.


## How the workflow fits together

The app follows a simple workflow. The teacher provides the school name, class, class teacher, student name, absent students, lessons missed, and cumulative missed days.

AWS PartyRock processes the information and generates three separate outputs:

- **Parent email templates:** Help teachers communicate about student absences and missed work.



- **Student makeup assignments:** Help students catch up on lessons they have missed.



- **Risk assessment indicators:** Help teachers identify repeated absences that may need further attention.

## What I learned

One of the main lessons was the difference between asking a chatbot a question and designing an app for a task that needs to be repeated.

A chatbot can generate an email or suggest catch-up work, but a reusable app can organize the inputs and present different outputs in separate widgets. That structure makes the workflow easier to repeat without rewriting the entire prompt each time.

The project also helped me practise translating a real-world problem into a clear application idea, specifying inputs and outputs, and evaluating whether an AI-generated solution addresses the intended need.

## Testing and submission

I tested the app using different inputs and reviewed the outputs it generated. During testing, it worked smoothly, producing organized parent email templates, student makeup assignments, and risk assessment indicators.

The project also required comparing the app with a regular chatbot. In my reflection, I noted that the app separated emails, assignments, and risk assessments into individual widgets rather than combining everything into one long response. This made the workflow easier to reuse without repeatedly writing the same detailed instructions.

- **Submission status:** Passed
- **Submission date:** 15 June 2026
- **Programme:** Udacity AWS AI & ML Scholars Challenge
- **Build platform:** AWS PartyRock

## Limitations and responsible use

The risk assessment is an indicator to support a teacher's review, not a validated prediction of academic failure. The app should not be treated as a substitute for professional judgment, and its suggestions should be checked before use.

Parent communications and makeup assignments should also be reviewed for accuracy, appropriateness, and the student's actual learning needs. Attendance information is sensitive, so a real school deployment would require appropriate privacy and access controls.

The app generates parent communication templates; it should not be described as automatically sending real-time updates or continuously tracking student progress.

## Project status

The project submission passed the Udacity review on 15 June 2026. As the app was created during the AWS AI & ML Scholars Challenge, the original public PartyRock link is no longer available. This documentation captures the project's purpose, building process, intended workflow, observed outputs, and key learnings from the challenge.

## Certificate

This project was completed as part of the Udacity AWS AI & ML Scholars Challenge in June 2026.

The certificate provides supporting evidence of my completion of the programme through which I developed this project.

**Programme:** Udacity AWS AI & ML Scholars Challenge

## Acknowledgment

Built as part of the Udacity AWS AI & ML Scholars Challenge, using AWS PartyRock.
