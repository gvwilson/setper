# Software Engineering: Tools, Process, Evidence, and Responsibility

<p class="subtitle">A one-semester introduction to software engineering for junior and senior undergraduates</p>

## Learner Persona

-   Shae, 20, is in the third year of an undergraduate degree in computer science.
    They didn't get much out of their high school programming class,
    but enjoyed the robotics club.
-   Shae is comfortable with object-oriented programming in Python,
    and did well in their introductory courses on databases and web programming last semester.
    They like working on homework assignments with friends,
    but had a bad experience in the team project in the web programming class.
    They program in VS Code,
    but still use print statements more than the debugger.
-   Shae found their first internship last summer exciting
    because they got to work on real problems,
    but bewildering because they felt they spent more time in meetings
    than they did doing "real" work.
    They also heard senior programmers arguing about whether AI is a boon or a curse,
    and would like to know how to answer questions like that.
-   Shae is impatient with abstract theory;
    they learn best when generalizing from practical examples.

<div class="callout" markdown="1">

This course teaches Shae how to work effectively in a small team
on a large, long-running software project,
how to find, evaluate, and apply findings from empirical studies in software engineering,
and how to recognize and meet their professional and societal responsibilities.

</div>

## Overview

-   High-level design
    -   Start with topics closest to what learners have already studied (programming)
    -   Don't ask them to (pretend to) emulate agile development when they have several other bosses
        and we have no way to observe or give feedback on their day-to-day work
    -   Prepare them to be research consumers and collaborators rather than researchers themselves
    -   Move from "consideration for your teammates" to "consideration for your fellow citizens"
        so as not to scare them away
-   Assume learners can already:
    -   Use the Unix command line
    -   Diff, commit, push, pull, and merge with Git
    -   Write Python programs that are hundreds of lines long using classes
    -   Write JavaScript programs that are dozens of lines long
    -   Install and update packages in both languages
    -   Write unit tests in both languages
    -   Write simple database queries in SQL (e.g., equi-joins)
    -   Use breakpoints in a symbolic debugger
    -   Search the web and interact with an LLM
    -   Coordinate activity using email and chat
-   Four themes:
    1.  Tools:
        linters, profilers, fuzz testers, static analyzers,
        and others that they won't have seen in earlier courses.
        -   These are small, natural steps beyond things they have already seen
        -   And even those who are most adverse to "soft" topics will accept these as valid
    2.  Process:
        effective meetings,
        gathering and tracking requirements,
        issue triage,
        incident management,
        and other activities that arise in programming in the large
        -   Because tools are only effective if you adapt your processes to them
        -   Many learners' experiences in team projects or work placements
            will make them want to know how to make teamwork hurt less
        -   Naturally motivates the question, "How do we know what actually works?"
    3.  Evidence:
        how to do empirical studies of various kinds,
        how to tell good studies from bad ones,
        and a few key findings
        -   Show why we believe claims made about process
        -   And how to tell plausible punditry from reliable, reproducible results
        -   Motivate them to be industry partners in future research projects
        -   Or to go on to grad school to answer open questions of their own
    4.  Responsibility:
        how programmers can help and harm each other,
        how software companies have harmed society,
        and how to prevent, mitigate, or remediate those harms
        -   Previous theme has prepared them to read and understand empirical findings
        -   So they are now able to appreciate studies of discrimination,
            online radicalization,
            the environmental impact of computing,
            and other sensitive topics
-   Shape
    -   Three classroom hours per week for 12 weeks…
    -   …but reserve 6 hours for overflow, guest speakers, and administration…
    -   …so 30 hour-long topics
    -   Define each one by the exercises at its end
    -   Mix of individual and collaborative assessments

## Lessons

<div id="lessons" markdown="1">

<ol>
  <li><a href="./intro/">Introduction</a></li>
</ol>

<h3>Tools</h3>

<ol>
  <li><a href="./profile/">Profiling</a></li>
  <li><a href="./fuzzing/">Fuzzing</a></li>
  <li><a href="./packaging/">Packaging</a></li>
  <li><a href="./accessibility/">Accessibility</a></li>
  <li><a href="./linting/">Static Analysis</a></li>
  <li><a href="./queueing/">Queueing Theory</a></li>
  <li><a href="./monitoring/">Monitoring</a></li>
</ol>

<h3>Process</h3>

<ol>
  <li><a href="./meetings/">Meetings</a></li>
  <li><a href="./requirements/">Requirements</a></li>
  <li><a href="./status/">Project Status</a></li>
  <li><a href="./governance/">Governance</a></li>
  <li><a href="./onboard/">Onboarding</a></li>
  <li><a href="./perfreview/">Performance Review</a></li>
  <li><a href="./offboard/">Offboarding</a></li>
</ol>

<h3>Evidence</h3>

<ol>
  <li><a href="./mining/">Mining Software Repositories</a></li>
  <li><a href="./surveys/">Surveys</a></li>
  <li><a href="./qual/">Qualitative Studies</a></li>
  <li><a href="./lying/">How to Lie With Statistics</a></li>
  <li><a href="./conway/">Conway's Law</a></li>
  <li><a href="./productivity/">Productivity and Its Disconents</a></li>
  <li><a href="./discrimination/">Discrimination</a></li>
</ol>

<h3>Responsibility</h3>

<ol>
  <li><a href="./business/">Business Models</a></li>
  <li><a href="./ip/">Intellectual Property</a></li>
  <li><a href="./fraud/">Fraud</a></li>
  <li><a href="./climate/">Environmental Impact</a></li>
  <li><a href="./speech/">Censorship and Free Speech</a></li>
  <li><a href="./labor/">Labor Rights</a></li>
  <li><a href="./licensure/">Licensure and Liability</a></li>
</ol>

<ol>
  <li><a href="./finale/">Conclusion</a></li>
</ol>

</div>

##  Appendices

<div id="appendices" markdown="1">

1.  [License](./LICENSE.md)
1.  [Code of Conduct](./CODE_OF_CONDUCT.md)
1.  [Contributing](./CONTRIBUTING.md)
1.  [Bibliography](./bibliography/)
1.  [Glossary](./glossary/)

</div>

## Acknowledgments {: #acknowledgments}

-   *[Greg Wilson][wilson-greg]* is a programmer, author, and educator based in Toronto, Canada.
    He was the co-founder and first Executive Director of Software Carpentry
    and received ACM SIGSOFT's Influential Educator Award in 2020.

<p class="center">
  <em>
    start where you are
    &middot;
    use what you have
    &middot;
    help who you can
  </em>
</p>
