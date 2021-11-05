# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: QuantLib

*Write a paragraph describing what the software does and who its
primary audience is.*

QuantLib is a quantitative financial modeling project written in C++. I've used a version
of it in C# that was much less comprehensive, though I ultimately had to abandon using it due to
its inflexibility with my code base's types. The software is aimed at anyone interested in
quantitative finance, and many large financial institutions have "borrowed" from the code base,
though I know very few who have integrated it in its entirety. About 10% of it is differential
equations, but with a strong ephasis on SDEs.

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL | https://github.com/lballabio/QuantLib |
| Main/documentation website | https://www.quantlib.org/docs.shtml |
| Year project was started | 2001 |
| Number of contributors in the past year | 35 |
| Number of contributors in the lifetime of the project | 126 |
| Number of distinct affiliations |  |
| Where do development discussions take place? | An email list: https://www.quantlib.org/mailinglists.shtml  |
| Typical number of emails/comments per week? | 1-2 a month in the developer side, and 10/week for users  |
| Typical number of commits per week? |  |
| Typical commit size | Median looks like ~10 lines |
| How does the project accept contributions? | Pull requests   |
| Does the project have an automated test suite? | Yes? Boost's |
| Does the project use continuous integration? | I'm not sure. They accept pull requests very often, but I don't know if that goes straight to the deployed version or not. |
| Are any legal/licensing steps required to contribute? | no, but I do have questions. |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [x] I have installed the software
- [x] I have run at least one example
- [x] I have run the test suite
- [x] The test suite passes

### Notes/concerns/risks

While reading the licensing, I just got confused about the relationship between
retaining copyright for the contributers while also being copyleft?

Also, I just didn't know what type of command to run to fimd commits per week,
nor do I know how to distingusih a contributor from their affiliations.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
