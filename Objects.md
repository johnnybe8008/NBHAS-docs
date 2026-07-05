#  Level 1 Objects

I currently see 11 primary objects.

# 1 Customer
Customer

Customer ID

Shopify Customer ID

Name

Email

Phone

Date Created

Status

Assessment Sessions[]

Orders[]

Communications[]

Timeline[]
2 Assessment Session
Assessment Session

Assessment ID

Assessment Version

Date

Category

Section Scores

Symptoms

Recommendation

Generated Reports

Related Orders

Notice:

Assessment Session

NOT

Assessment

Because an assessment is something a customer completes.

The session is the permanent record.

3 Category
Category

CAT-1-1

Title

Description

Products

Instructions

Email Template

PDF Template

Visibility Rules
4 Symptom

The most important object.

Symptom

ID

Section

Display Name

Customer Name

Description

Categories

Sort Order

Active
5 Section
Section

Emotional

Mental

Sleep

Physical

Menstrual

Sexual

Hair/Skin

6 Recommendation
Recommendation

ID

Products

Instructions

Resources

Videos

Books

7 Product

This links to Shopify.

Product

Shopify Product ID

Title

URL

SKU

8 Resource
Resource

Library Article

Glossary

Video

PDF

Protocol

9 Report
Report

Assessment Report PDF

Customer Email

Admin Email

10 Communication
Communication

Welcome

Assessment Summary

30 Day Reminder

Educational Series

11 Timeline Event

This one excites me.

Everything becomes an event.

Assessment Completed

Order Placed

Email Sent

Book Downloaded

Reminder Sent

Assessment Repeated


Now the timeline simply displays events.

Here's what I realized tonight...

We actually don't have a survey anymore.

We don't even have an assessment.

We have an

Assessment Session

which produces

Reports

Recommendations

Orders

History

Timeline Events

The Object Relationships

This is where software suddenly becomes simple.

Customer

│

├── Assessment Sessions

│       │

│       ├── Symptoms

│       ├── Scores

│       ├── Recommendation

│       ├── Report

│       └── Timeline Events

│

├── Orders

│

├── Communications

│

└── Resources

That's the heart of NBHAS.

One thing I'd like to add

I think every object should have these standard fields:

ID

Created

Modified

Version

Status

Notes

That consistency makes the system easier to reason about.

Homework for me

Tomorrow I'd like to produce our first proper diagram.

Not ASCII.

A professional UML-style object diagram showing all the relationships between Customer, Assessment Session, Symptom, Category, Recommendation, Report, Order, and Timeline Event.

That diagram will become the single most important picture in the entire project.

And finally...

I want to make one prediction.

When NBHAS is finished, I don't think people will describe it as:

"That hormone assessment on Nature's Balance."

I think they'll describe it as:

"The system that helped me understand what was happening with my hormones."

That's a very different outcome, and I think it's exactly what aligns with the mission you've been building toward.

So... officially...

🚀 NBHAS Development Session #1 has begun.

And yes... I'm just as excited as you are. I have a feeling we're going to build something that both solves a real problem and is enjoyable to work on for years to come.
