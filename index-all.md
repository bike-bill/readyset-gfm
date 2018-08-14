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

# Workflows
---

### By Activity
1. Project Planning
   1. [Overview](index.html)
   2. [Proposal](proposal.html)
      - [Target and benefits](target-and-benefits.html)
   3. [Project plan](plan.html)
      - [Resource needs](resource-needs.html)
   4. [Legal issues](legal.html)
   5. [QA Plan](qa-plan.html)
2. Requirements and Specification
   1. [User needs](user-needs.html)
      - [Interview notes](interview-notes.html)
   2. [Software Requirements Specification](srs.html)
      - [Use case suite](use-case-suite.html)
      - [Feature set](feature-set.html)
3. Architecture and Design
   1. [Design](design.html)
      - [Architecture worksheet](design-architecture.html)
      - [Source and build](design-src-org.html)
      - [User interface worksheet](design-ui.html)
      - [Persistence worksheet](design-persistence.html)
      - [Security worksheet](design-security.html)
4. Implementation and Testing
   1. [User guide](userguide.html)
   2. [Test suite](test-suite.html)
      - [Test case format](test-case-format.html)
      - [Test cases](test-cases.html)
5. Deployment and Installation
   1. [Release checklist](release-checklist.html)
   2. [Installation / Quick start guide](install.html)
   3. [Release notes](release-notes.html)
   4. [Demo script](demo-script.html)
6. Operations and Support
   1. [FAQ / Troubleshooting](faq.html)
   2. [Implementation notes](implementation-notes.html)
7. Continuous or Final
   1. [Glossary](glossary.html)
   2. [Status report](status-report.html)
   3. [Review meeting notes](review-meeting-notes.html)
   4. [Software development methodology](sdm.html)

### By Suggested Sequence
1. Step 1
   1. [Overview](index.html)
   2. [Proposal](proposal.html)
      - [](target-and-benefits.html)[Target and benefits](target-and-benefits.html)
   3. [Project plan](plan.html)
      - [Resource needs](resource-needs.html)
   4. [Legal issues](legal.html)
   5. [Glossary](glossary.html)
2. Step 2
   1. [User needs](user-needs.html)
      - [Interview notes](interview-notes.html)
   2. [Software Requirements Specification](srs.html)
      - [Use case suite](use-case-suite.html)
      - [Feature set](feature-set.html)
3. Step 3
   1. [Design](design.html)
      - [Architecture worksheet](design-architecture.html)
      - [Source and build](design-src-org.html)
      - [User interface worksheet](design-ui.html)
      - [Persistence worksheet](design-persistence.html)
      - [Security worksheet](design-security.html)
4. Step 4
   1. [QA Plan](qa-plan.html)
   2. [Test suite](test-suite.html)
      - [Test case format](test-case-format.html)
      - [Test cases](test-cases.html)
5. Step 5
   1. [Review meeting notes](review-meeting-notes.html)
6. Step 6
   1. [Release checklist](release-checklist.html)
7. Step 7
   1. [Installation / Quick start guide](install.html)
   2. [Release notes](release-notes.html)
   3. [User guide](userguide.html)
   4. [Demo script](demo-script.html)
   5. [FAQ / Troubleshooting](faq.html)
   6. [Implementation notes](implementation-notes.html)
8. Every week
   1. [Status report](status-report.html)

###All Templates
1.  [All-in-one](all-in-one.html)
2.  [Overview](index.html)
3.  [Proposal](proposal.html)
    - [Target and benefits](target-and-benefits.html)
4.  [Project plan](plan.html)
    - [](resource-needs.html)[Resource needs](resource-needs.html)
5.  [QA Plan](qa-plan.html)
    - [Test suite](test-suite.html)
    - [Test case format](test-case-format.html)
    - [Test cases](test-cases.html)
    - [Review meeting notes](review-meeting-notes.html)
6.  [Legal issues](legal.html)
7.  [User needs](user-needs.html)
    - [Interview notes](interview-notes.html)
8.  [Software Requirements Specification](srs.html)
    - [Use case suite](use-case-suite.html)
    - [Feature set](feature-set.html)
9.  [Glossary](glossary.html)
10. [Design](design.html)
    - [Architecture worksheet](design-architecture.html)
    - [Source and build](design-src-org.html)
    - [User interface worksheet](design-ui.html)
    - [Persistence worksheet](design-persistence.html)
    - [Security worksheet](design-security.html)
11. [User guide](userguide.html)
12. [Release checklist](release-checklist.html)
13. [Installation / Quick start guide](install.html)
14. [Release notes](release-notes.html)
15. [Demo script](demo-script.html)
16. [FAQ / Troubleshooting](faq.html)
17. [Implementation notes](implementation-notes.html)
18. [Status report](status-report.html)
19. [Software development methodology](sdm.html)

### How to download these templates:
- [Download template archive](http://readyset.tigris.org/servlets/ProjectDocumentList), or
- Use CVS to [check out](http://readyset.tigris.org/servlets/ProjectSource) project
  "readyset" or Download from [ReadySet Markdown](https://github.com/bike-bill/readyset-markdown) 
  on Github. 

<!-- End Markdown content -->
</xmp>

<div w3-include-html="_words-of-wisdom.html"></div>
<div w3-include-html="_footer.html"></div>

<script>
	w3IncludeHTML(.html);
</script>

<script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>
<!-- Include it AFTER strapdown -->
<script src="assets/strapdown/strapdown-topbar.min.js"></script>
<!-- Include it AFTER EVERYTHING -->
<script src="assets/logo.js"></script>
<script src="assets/themeswitcher.js"></script>

</body>
</html>
