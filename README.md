# Eolang-exercises

Object-oriented (OO) design is a very powerful approach for modelling real-world
problem domains, but of the programming languages popularly thought of as
"OO" few readily lend themselves to authentic object thinking - at least, that
appears to be the rationale behind the development of
[eolang](https://github.com/cqfn/eo).

At first glance, the rhetoric seems far too familiar. Aggressive overselling -
_the future of OOP_, indeed - by way of catastrophism could well be mistaken 
for the bread and butter of marketing in our field. Or, as Glass pointedly put
it, ["Hype is the plague on the house of software."](https://www.goodreads.com/book/show/83792.Facts_and_Fallacies_of_Software_Engineering).
However, the developers follow up with an unusual reservation: They don't want 
their language to become mainstream. Instead, EO aims to be a tool for
demonstrating that "true" or "pure" OO is feasible.

This goal sure looks ambitious (and quite admirable, to be honest) - and given
the state of the typical project written in "OO" languages, I can definitely
empathise with their notion of inauthenticity. The paradigm is often criticised 
for design constructs that run in counter with the fundamental concepts, simply
because the program was implemented in, e.g., Java or C#.

However, eolang looks like a fun puzzle even if we ignore the philsophical
aspects. Even in normal situations, picking up a new language is likely to
alter some aspect of how you think approach some problem or another, but EO
takes this a few steps further. The syntax is obviously far from any C dialect
and many common constructs (e.g., classes, mutability and operators) are
forbidden by design.

Many of these constraints are bound to give rise to their fair share of
controversy. However, the central character -
[Yegor Bugayenko](https://www.yegor256.com/about-me.html), chairman of the
[International Conference on Code Quality (ICCQ)](https://www.iccq.ru) - ought
to hardly be a stranger to such disagreements: He has promoted and defended
these design principles for years and implemented them (discounting the
limitations of conventional languages) in more than a few open source projects.

But that's enough background. Let's get started!

## Hello world!

`mvn -f helloworld/pom.xml clean compile`

`java -cp helloworld/target/classes:helloworld/target/eo-runtime.jar org.eolang.phi.Main sandbox.app`

`mvn compile`

`java -cp target/classes:target/eo-runtime.jar org.eolang.phi.Main sandbox.app YEAR`

where `YEAR` is, e.g., 2020 or 2021.
