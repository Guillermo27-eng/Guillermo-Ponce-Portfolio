# Donor CRM for the USC Institute for Advanced Catholic Studies

*Freelance Nonprofit Technology Consultant · June to August 2026 · Los Angeles, California*

## The problem
The USC Institute for Advanced Catholic Studies (IACS) relied on informal, manual methods to track and follow up with donors. Behind 300+ donor relationships were people going without timely follow-up. Donation records already lived in an Airtable base with several linked tables, but nothing told staff who to contact next, when, or with what message. Consistent outreach depended on someone remembering.

## What I did
I audited a donor operation that ran on fragmented spreadsheets, then scoped, designed, and built an AI-augmented donor management system in Airtable in two phases, then trained the team to run it without me.

- **Phase 1:** designed the donor engagement journey, restructured the data model, and built the core automations.
- **Phase 2:** refined the system with staff feedback and built in room for change requests, since the institute planned to hire new advancement staff who would want to adjust it.

### Two automation tracks
| Track | Who it serves | What it does |
|---|---|---|
| 8-Step Donor Engagement Sequence | Prospects who are actively engaged | A set order of touches with timing, owners, and email templates so follow-up happens on schedule |
| Cultivation Track | Contacts with a longer horizon | A slower rhythm of stewardship and check-ins that keeps relationships warm until they are ready |

### What is under the hood
- **39 automated workflows** covering status changes, automated emails, conditional routing, staff reminders, and touch point logging
- **An AI drafting layer** that writes a personalized follow-up for each donor in the institute's director's voice, for staff to review before anything is sent
- **A grants research pipeline** built with JavaScript and SerpAPI that searches for funding opportunities and logs them in the same base
- **A phased launch** designed so each phase could be reversed if something did not work
- **Time-delayed steps** built with formula fields and scheduled daily checks, so a reminder fires the right number of days after the last touch without a manual task list
- **A feasibility plan** for the client that separated what Airtable handles easily from what needed more deliberate setup, with a scripting fallback for the hard parts
- **Clear records** of donor status, interactions, and next steps in one place

### Built for the people who use it
I wrote the staff training and set the system up so non-technical team members can edit fields, views, and email templates themselves. I also worked through the practical setup with the institute's administrators, including the right Airtable plan for running automations, so the build could live in the client's own workspace.

## Result
IACS now has a staff-owned donor engagement system that replaces informal tracking with a repeatable sequence. The team can see who needs a touch, act on it, and log what happened, and they can change the system as their needs change.

## Tools
Airtable (tables, forms, formula fields, interfaces, scheduled automations, email automations) · scripting fallback · workflow design · staff training · project scoping

## Focus areas
Nonprofit technology · donor engagement · fundraising operations · process automation · database design · client relations

[Back to the portfolio](../../README.md)
