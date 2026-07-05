NBHAS System Design Specification
Chapter 1
Project Charter
Project Name

Nature's Balance Hormone Assessment System

NBHAS

Version 2.0

Status

Architecture

Vision Statement

NBHAS exists to provide every customer with a personalized hormone assessment that combines education, product recommendations, historical tracking, and ongoing support within a single integrated platform.

Mission

To create the industry's most comprehensive hormone assessment platform by integrating:

Assessment
Education
Product Recommendation
Customer History
Assessment History
Progress Tracking
Shopify Commerce
Automated Follow-up
Guiding Principles

Every design decision must satisfy these principles.

Principle 1

Customer First

The assessment should always provide value to the customer.

Principle 2

Single Source of Truth

Every piece of information exists only once.

Examples:

One symptom database.

One category database.

One recommendation engine.

One customer record.

Principle 3

Assessment Sessions are Permanent

An Assessment Session is never edited.

Corrections are made by creating a new Assessment Session.

Historical records remain unchanged forever.

Principle 4

Everything is Connected

Assessments

↓

Customers

↓

Orders

↓

Products

↓

Reports

↓

Education

↓

Follow-up

Everything becomes one customer journey.

Principle 5

Configuration Before Code

Whenever possible:

Do NOT hard-code.

Store:

Categories
Symptoms
Products
Resources
Email Templates
Recommendations

as configuration.

Principle 6

Shopify is the Commerce Engine

NBHAS owns the assessment.

Shopify owns:

Customers

Orders

Products

Marketing

Payments

NBHAS integrates with Shopify.

It does not replace Shopify.

Principle 7

Future Expansion

The architecture must support future additions including:

Men's Assessment
Thyroid Assessment
Adrenal Assessment
Practitioner Portal
Mobile App

without redesigning the system.

Customer Promise

Every completed assessment will provide:

✓ Clear next steps

✓ Personalized recommendations

✓ Educational material

✓ Downloadable report

✓ Progress tracking

✓ Long-term support

Administrator Promise

NBHAS will provide administrators with:

Complete customer timeline

Assessment history

Order history

Progress history

Reports

Recommendations

Follow-up reminders

Version Philosophy

Major Version

Architecture changes

Minor Version

Features

Revision

Bug fixes

Example

NBHAS

2.0.0

Architecture Release

2.1.0

Customer Dashboard

2.2.0

Assessment Comparison

2.3.0

Practitioner Portal

Project Motto

Helping women understand their hormones through personalized assessments, education, and long-term progress tracking.

I would like to add one principle of my own

This isn't technical—it's about how we build.

Principle 8 — Explainability

Every recommendation made by NBHAS should be explainable.

For example, if the assessment recommends the Estradiol & Progesterone Pack, the customer should see why that recommendation was made in the context of the HQL Protocol—not as a diagnosis, but as an explanation of how their selected category and symptom pattern relate to the recommended starting protocol. That transparency builds trust and helps customers understand the reasoning behind the recommendation.

And finally...

I'd like to create one sentence that appears at the bottom of every specification document:

"If a feature does not improve the customer journey, simplify administration, or strengthen the integrity of the assessment history, it does not belong in NBHAS."
