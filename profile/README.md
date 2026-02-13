Modern research is more and more data driven. In theory, the data could be
reused. But often when reusing existing data the unclear legal aspects, such as
missing or undefined licensing terms, hinders researchers and the progress of
their research projects. When datasets are compiled out of multiple datasets,
provenance and especially legal status of the resulting data can be hard to
infer, more so for large datasets. Thus, the resulting complexity slows or even
prevents research. (Research) Software faces the same problems. To make data
more accessible and more reusable and thus FAIR, the complexity should be
reduced as much as possible to allow researchers to focus on their actual
research projects instead of just researching licensing.

The legal challenges researchers face in their work are manifold: Is the reuse
of existing data allowed? Do the terms fit the intended purposes of the
research project? When writing software, what libraries can they use and in
which way? Publishing either data or software is even more complex due to the
influence of dependencies on license choice.There are many follow-up questions
depending on the specific use cases. There could be special requirements for
a data use agreement which are not covered by standard licenses. There could be
terms and conditions which exclude text and data mining or limit the use of
data to a certain geographical area. All that while terms should be respected
as much as possible and even European regulation partially requiring
machine-interpretable terms in data spaces.

The Working Group on Licensing and Rule Automation (WG LARA) aims to address
these problems with automating as much of the process as possible while
building on existing solutions. Such solutions include the
[LicenseChecker](https://github.com/izus-fokus/LicenseChecker) for evaluating
legal implications of software dependencies or the [ODRL
Builder](https://github.com/IPK-BIT/odrl-builder) to easily create
machine-interpretable licensing terms along a human-readable version of the
terms, but there are also many more. Yet those tools are neither widely adapted
nor used. Being part of the NFDI Section ELSA we want to raise awareness and
adoption of these and newer tools. Currently the Working Group focuses on
checking the dependencies for software projects and creating custom data usage
agreements for data in both a machine- and human-readable representation. The
machine-readable version builds on the ODRL Standard. With using this standard
we ensure that the legal information can easily be used by platforms and in
automated or agentic tasks. We want to integrate our solutions with each other
and also into existing data-management frameworks like FAIR Digital Objects
(FDOs).

A few things are out of scope, however. This includes checking whether the
claimed rights regarding the data or software really exist, as this task is
nearly impossible to automate and usually needs input from a legal expert. We
also do not aim to develop new standard licenses or propose a solution for
enforcement.
