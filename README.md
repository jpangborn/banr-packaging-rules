Banner Packaging Rules
======================

PHEAA Estimate
--------------

The PHEAA Estimate rule will generate a PHEAA estimate for the student. This rule assumes that the Cost of Attendance is greater than $32,000. If the COA is lower, additional sequences will need to be added. 

Merit Scholarship from Cohort Code
----------------------------------

This rule will lookup the amount of a merit scholarship if stored in a corhort code in the Admissions application. This rule assumes that there will only be one admissions application per term code, and that the admissions application for the highest term code in the aid year is the active application.

Equity Award
------------

### Background

In our process, we used equity packaging to determine the percentage of need met for each packaging group. This percentage was the equity level. A number of funds were treated as equity funds for the purpose of meeting the equity level, but some of those funds were award regardless of the current equity level. The primary example is that Pell, SEOG, and our merit scholarships were treated as equity funds for the purpose of determining the equity level, but often awarding these funds would exceed the equity level. Banner does enable this. In true equity packaging, the equity funds cannot exceed the equity level. The way around is to batch post the SEOG and merit scholarship, but this has downsides. A major downside is the increase in jobs that need to be run for the packaging process. It also means that you cannot select the Automatic Packaging option from the Options menu to run a complete package for the student.

### The Solution

Algorithmic Packaging allows us to award the appropriate funds at the correct levels. You start by awarding all of the necessary funds that need to have specific amounts and are going to be determining the equity level and then use the equity award rule to award any equity funds. The equity rule will determine the equity percent at the time of awarding this fund. You will need a sequence for each equity percent used. You will also need to add any funds to be counted in determine the equity level. 