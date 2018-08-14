<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8"/>
	<link type="image/png" href="assets/logo.png" rel="icon">
	<title>ReadySet Markdown</title>
</head>
<script src="https://www.w3schools.com/lib/w3data.js"></script>
<body>

<topbar style="display:none;">
	<item><a href="index.html">Overview</a></item>
	<item><a href="plan.html">Project Plan</a></item>
	<item><a href="index-all.html">Workflows</a></item>
	<menu name="Themes"><item><a id="settheme"><b>Current</b></a></item></menu>
	<toc></toc>
</topbar>

<xmp theme="readable" style="display:none;">
<!-- Markdown content here -->

# Project Plan
---

##### Project:
::[PROJECTNAME](index.html)

##### Project Time-frame:
::STARTDATE - ENDDATE

##### Attached worksheets:
- Plan &gt; [Resource needs](resource-needs.html)

##### Related Documents:

- [Project proposal](proposal.html) &gt; [Target audience and benefits](target-and-benefits.html)
- [Software development methodology](sdm.html)
- [Glossary](glossary.html)

---

**Process impact:** This plan will be used to evaluate and manage the
project. Key assumptions that affect the plan should be documented here.
The project plan should be updated throughout the life-time of the
project.

*TODO: Fill in the information above and below. Add or remove rows as
needed. Use the worksheet to help identify and scope resource needs.*

### Summary of Project
&nbsp;
#### What are the business problem, scope, and goal of this project?

For a summary of this project, see the [Project proposal](proposal.html).

#### Who will sponsor, manage, and lead the project?

- ::Sponsor: PERSON-NAME
- ::Manager: PERSON-NAME
- ::Technical lead: PERSON-NAME

#### What authority does the project manager have?

- ::Hire, dismiss, or reassign personnel in his/her department
- ::Hire contract employees or manage subcontractors
- ::Purchase equipment, software, and other needed capital
- ::Assign specific tasks to other departments
- ::Negotiate requirements and schedules with customers
- ::Negotiate with vendors, suppliers, and partners

#### What planning lessons were learned in previous releases?

::None yet. This is the first release.

- ::We can reduce training time, but it significantly increases development time.
- ::Maintaining a past release takes more than 20% of our time, due to low quality in that release.
- ::The customer seems to always change the requirements after the second demo.
- ::There are always defects. We planned time to test, but we forgot to plan time to fix the defects.
  On this project, we will actually estimate the number of undetected defects.
- ::Issue XXXX made us realize that we forgot to plan time for DEVELOPMENT-TASK.

### Summary of Methodology
&nbsp;
#### What general development approach will be used?

::THREE TO FIVE SENTENCES OR BULLETS HERE. COVER GENERAL APPROACH, IMPORTANT ASSUMPTIONS, KEY PRACTICES, AND PROJECT COORDINATION CONTROLS. 

For more information see the [Software Development Methodology](sdm.html).

#### How will the project team be organized?

- ::The development team will consist of ...
- ::The change control board will consist of ...

#### What development and collaboration tools will be use?

::We plan to use the following tools extensively through out the project:

- ::Project website
- ::Project mailing lists
- ::Issue tracking system
- ::Version control system
- ::Automated build system
- ::Automated unit test system

#### How will changes be controlled?

-   ::Requests for requirements changes will be tracked in the issue 
    tracker
-   ::The change control board ([CCB](glossary.html#ccb))
    will review requested changes and authorize work on them as
    appropriate
-   ::After the [feature
    complete](glossary.html#featurecomplete) milestone, no
    new features will be added to this release.
-   ::After the [code complete](glossary.html#codecomplete)
    milestone, no entirely new product source code will be added to
    this release.
-   ::All source code commit log messages must refer to a specific
    issue ID, after the feature complete milestone.

#### How will this plan be updated?

::This project plan will be updated as needed throughout the project.
It will be placed under version control and instructions for
accessing it will be on the [project website](index.html). Any
change to the plan will cause an automatic notification to be sent
to a project mailing list.

### Work Breakdown Structure and Estimates

*TODO: List tasks that will be needed for this project. Keep dividing
tasks into subtasks until you feel that you have enough detail to expose
risks and make reasonable estimates in ideal engineering hours.*

*TIP: Label each step uniquely to show its position in the WBS, e.g.,
Step 1.1.4.A. Use numbers for steps that you intend to do in sequence,
and use letters for steps that you intend to do in parallel. E.g., Step
1.1 comes before Steps 1.2.A and 1.2.B, but those two steps may be done
in parallel, and Step 1.3 will be done after all 1.2.\* steps have been
finished. Don't worry about renumbering if you delete a step.*

| Step      | Description                                               | Estimate |
|-----------|-----------------------------------------------------------|----------|
| 1.        | ::Preparation                                             |          |
| 1.1.      | ::Developer training                                      | 30h      |
| 2.        | ::Inception                                               |          |
| 2.1.      | ::Requirements gathering                                  | 30h      |
| 2.2.      | ::Requirements specification                              | 20h      |
| 2.3.      | ::Requirements validation                                 | 10h      |
| 3.        | ::Elaboration                                             |          |
| 3.1.      | ::High-level design                                       | 5h       |
| 3.2.      | ::Low-level design (break down by component)              |          |
| 3.2.A.    | ::Object design                                           | 10h      |
| 3.2.B.    | ::User interface design                                   | 10h      |
| 3.2.C.    | ::Database design                                         | 3h       |
| 3.3.      | ::Design review and evaluation                            | 5h       |
| 4.        | ::Construction                                            |          |
| 4.1.A.    | ::System implementation                                   |          |
| 4.1.A.1.  | ::Implement COMPONENT-NAME 1                              | 25h      |
| 4.1.A.2.  | ::Implement COMPONENT-NAME 2                              | 25h      |
| 4.1.A.3.  | ::Implement COMPONENT-NAME 3                              | 25h      |
| 4.1.A.4.  | ::Implement COMPONENT-NAME 4                              | 25h      |
| 4.1.A.5.  | ::Integrate Components (mostly done during implementation)| 5h       |
| 4.1.B.    | ::Technical documentation (break down by component)       | 10h      |
| 4.1.C.    | ::User documentation (break down by component)            | 10h      |
| 4.1.D.    | ::Testing                                                 |          |
| 4.1.D.1.  | ::Test planning                                           | 10h      |
| 4.1.D.2.  | ::Test code implementation (break down by component)      | 30h      |
| 4.1.D.3.  | ::Test execution                                          | 10h      |
| 4.2.      | ::Implementation review and evaluation                    | 15h      |
| 5.        | ::Transition                                              |          |
| 5.A.      | ::Release packaging                                       | 3h       |
| 5.B.      | ::Documentation for other groups                          | 3h       |
| 6.        | ::Reflection                                              |          |
| 6.1.      | ::Postmortem report                                       | 10h      |
|           | ::Total                                                   | 329 hours|

### Deliverables in this Release

*TODO: List project deliverables in detail, with delivery dates.*

| Deliverable Name | Description                                                   | Delivery Date |
|------------------|---------------------------------------------------------------|---------------|
| Deliverable Name | ::Description                                                 | Delivery Date |
| Deliverable Name | ::Description                                                 | Delivery Date |
| Deliverable Name | ::Description Description Description Description Description | Delivery Date |
| Deliverable Name | ::Description                                                 | Delivery Date |

### Schedule for this Release

*TODO: Make the rows in this table match the steps in your WBS above. If
you have a large number of detailed steps, you can skip the most
detailed ones. The columns of the table represent weeks of calendar
time. For each cell in the table, enter the number of hours ideal
engineering time that the team will spend on that task that week. Total
your hours across and down.*

*TIP: These hours should total to the same as the total of the hours
listed in your [resource needs](resource-needs) document. And, the
hours for each type of effort resources needed should correspond to the
sum for each type of task.*

| Task \ Week     | W-01 | W-02 | W-03 | W-04 | W-05 | W-06 | W-07 | W-08 | W-09 | W-10 | W-11 | W-12 | Task Total |
|-----------------|------|------|------|------|------|------|------|------|------|------|------|------|------------|
| ::1.            | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |
| ::2.            | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |
| ::3.            | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |
| ::4.1.A.        | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |
| ::4.1.B.        | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |
| ::4.1.C.        | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |
| ::4.1.D.        | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |
| ::4.2.          | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |
| ::5.            | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |
| ::6.            | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |
| ::Weekly Totals | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00   | 00         |

### Risk Management

*TODO: List and rank the major risks of this project, and what you plan
to do to mitigate each risk. If you don't plan to do anything to
mitigate the risk, state that. Use the risk list below, or the [risks
worksheet](risks.html).*

Please see the [risks worksheet](risks.html).

#### The main risks of this project are

1.  ::There is a potential conflict between the goals of a high-quality
    appearance and one that is completely customizable. We can only
    succeed if players find the web site appealing, and game vendors can
    customize it with no more effort than would be needed to build a
    static website. We already have a design in mind that will address
    this risk and we will review it with a web site designer who worked
    for a game vendor site.
2.  ::There are significant technical difficulties in building a web site
    and web application. This will be a risk because one person on our
    team has much experience with the relevant tools and technologies.
    Although the others will learn, we will certainly make some mistakes
    and suboptimal choices. We will address this risk by scoping the
    project such that we have enough time to train and to review the
    design and implementation.
3.  ::The schedule for this project is very short. We will manage this by
    planning a conservatively scoped functional core and series of
    functional enhancements that can be individually slipped to later
    releases if needed.
4.  ::The performance of the system will be significantly impacted by the
    decisions made during the [database design task](#3.2.C). None of
    our current team members has experience with database optimization.
    To address this, we will arrange a review meeting with an
    experienced DBA or hire a consultant from the database vendor.
5.  ::We could be underestimating known tasks. HOW TO AVOID/MITIGATE?
6.  ::We could be underestimating the impact of unknown tasks. HOW TO
    AVOID/MITIGATE?
7.  ::We could be underestimating the dependencies between tasks. HOW TO
    AVOID/MITIGATE?
8.  ::We could have misunderstood the customer's requirements. HOW TO
    AVOID/MITIGATE?
9.  ::The customer could change the requirements. HOW TO AVOID/MITIGATE?
10. ::We could face major difficulties with the technology chosen for
    this project. HOW TO AVOID/MITIGATE?
11. ::We could have low quality that demands significant rework. HOW TO
    AVOID/MITIGATE?
12. ::We could incorrectly assess our progress until it is too late
    to react. HOW TO AVOID/MITIGATE?
13. ::We could lose resources. E.g., team members could get sick, spend
    time on other projects, or quit. HOW TO AVOID/MITIGATE?
14. ::There may be a mis-alignment of stakeholder goals or expectations.
    HOW TO AVOID/MITIGATE?

### Project Planning Dependencies
&nbsp;
#### Does this project conflict or compete for resources with any other project?

::No, this is the only project that we are working on.

::Yes, and we have determined how many hours each person can actually
    dedicate to this project.

#### Are the same human or machine resources allocated to maintenance of past versions and/or planning of future versions during this release time period?

::No, this is the first release and we will not plan the next release.

::Yes, we predict that team members will spend an average of 20% of
  their time maintaining previous releases and planning future
  releases during this release time frame. Some weeks may be higher if
  an urgent patch to a previous release is needed.

#### Does this project depend on the success of any other project?

::No, this project stands alone.

::Yes, project P1 must provide library L, and project P2 must prove
  the usability of feature F, and....

#### Does any other project depend on this project?

::No, project is not producing any components that will be used in
other current projects.

::Yes, we must produce library L for our project and support users of
L in projects P1 and P2.

#### Are there any other important dependencies that will affect this project?

::No, everything is covered above.

::Yes. DETAILS....

<!-- End Markdown content -->
</xmp>

<div w3-include-html="_words-of-wisdom.html"></div>
<div w3-include-html="_footer.html"></div>

<script>
	w3IncludeHTML();
</script>

<script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>
<!-- Include it AFTER strapdown -->
<script src="assets/strapdown/strapdown-topbar.min.js"></script>
<!-- Include it AFTER EVERYTHING -->
<script src="assets/logo.js"></script>
<script src="assets/themeswitcher.js"></script>

</body>
</html>
