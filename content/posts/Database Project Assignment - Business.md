+++
title = "Database Project Assignment - Business Data Management"
tags = ["SQL", "Information Systems", "Database", "ERD", "Projects", "Business", "BSYS602"]
date = "2024-03-11"
+++


### BSYS602: Business Data Management - Workshop Individual Assignment 3 - A+ level

Below is the Workshop Individual Assignment 3 for the BSYS602 paper. If the preview does not work, click the link [here](https://drive.google.com/file/d/1Zhu-xM-T_9uY6zMno6UlVDXUwJwl5nHe/view).
{{< shortcodesnippet >}}

    <iframe src="https://drive.google.com/file/d/1Zhu-xM-T_9uY6zMno6UlVDXUwJwl5nHe/preview" width="640" height="480" allow="autoplay"></iframe>

{{< /shortcodesnippet >}}

#### Summary

This project involved

1. Analysing a case study and its business rules to design a Entity Relationship Diagram (in 2nd normal form)
2. Describing the normalisation process, normalising the ERD to 3rd normal form
3. Constructing SQL queries for the hypothetical database

{{< details "Case Study for Database Project Assignment" >}}

"Nature-Oriented Scenic Tours (NOST) provides guided tours to groups of visitors to
NZ’s North Island. In recent years, NOST has grown quickly and is having difficulty
keeping up with all the various information needs of the company. The company’s
CEO has asked you to help them design a database to manage data to support their
growing business.
Create an ERD based on the following business rules and requirements.

- NOST offers many different tours. For each tour, the tour name, approximate
length (in hours), and fees charged is needed.
- Tours are classified into five categories: family friendly, adventure, hiking,
camping, and water activities.
- Guides are identified by an employee ID, but the system should also record a
guide’s name, home address, and date of hire.
- Guides take a test to be qualified to lead specific tours. It is important to know
which guides are qualified to lead which tours and the date that they
completed the qualification test for each tour. A guide may be qualified to lead
many different tours. A tour can have many different qualified guides. New
guides may or may not be qualified to lead any tours, just as a new tour may
or may not have any qualified guides.

- Every tour must be designed to visit at least three locations. For each
location, a name, type, and official description are kept. Some locations (such
as the Hobbiton) are visited by more than one tour, while others (such as the
Glow Worm cave) are visited by a single tour. All locations are visited by at
least one tour.
- When a tour is actually given, it is referred to as an “outing.” NOST schedules
outings well in advance so they can be advertised and so employees can
understand their upcoming work schedules. A tour can have many scheduled
outings, although newly designed tours may not have any outings scheduled.
Each outing is for a single tour and is scheduled for a particular date and time.
All outings must be associated with a tour. All tours at NOST are guided tours,
so a guide must be assigned to each outing. Each outing has one and only
one guide. Guides are occasionally asked to lead an outing of a tour even if
they are not officially qualified to lead that tour. Newly hired guides may not
have been scheduled to lead any outings."
- Tourists, called “clients” by NOST, pay to join a scheduled outing. For each
client, the name, address, and telephone number are recorded. Clients may
sign up to join many different outings, and each outing can have many clients.
For each scheduled outing, NOST would like to keep track of the number of
parties who will join the scheduled outing (i.e. number of people). Information
is kept only on clients who have signed up for at least one outing, although
newly scheduled outings may not have any clients signed up yet.
- Clients are billed for a scheduled outing that they book. A bill is produced for a
client-outing booking. A bill includes date, charge amount, pay amount and
remaining balance. For example, some clients may choose to pay their fees in
allotments; therefore, NOST must keep track of the current pay amount and
remaining balance. Each booking produces one and only one bill.
{{< / details >}}
