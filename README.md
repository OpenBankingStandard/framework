# framework

This repository forms part of the Open Banking Standard project, which is intended to build upon the work of the Open Banking Working Group (OBWG) and contribute towards the development of an Open Banking Standard. 

## Governance & Membership

A [Governance Model](./Governance.md) has been proposed but has not yet been formally adopted by the CTC. 

The initial members of the Core Technical Team (CTC) are:
* John Phenix
* Mark Stanhope
* Dave Tonge

Collaborators: 
* Jack Gavigan

Members of the CTC and Collaborators contribute to the work of the Open Banking Standard project in a personal capacity. They do not represent, and are not acting on behalf of, their respective employers.

## Communications

Individuals wishing to participate in the project should join the [Open Banking mailing list](https://groups.google.com/forum/#!forum/openbanking), which is intended for discussion of matters relating to the Open Banking Standard. Any announcements or requests for comments from the CTC will be posted to this mailing list. 

The use of Github is intended to facilitate openness, transparency, and active participation through the submission of pull requests. Discussion of pull requests can take place by commenting or [adding a reaction](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments).

## High-level Approach

The following proposals have been made but have not yet been formally adopted by the CTC.

1. **Begin developing the technical aspects of the Standard using Github.** Github is free, open and transparent - anyone who is interested in participating can do so by submitting a pull request, which can then be discussed and voted on by anyone who wishes to be involved.  

2. **Focus on three key areas to begin with: Open Data, Authentication & Authorisation, and the Account Information API** (i.e. the "read only" use case). Corresponding repositories have been created:  
 * [`open-data`](http://www.github.com/OpenBankingStandard/open-data), 
 * [`auth`](http://www.github.com/OpenBankingStandard/auth), and 
 * [`account-information-api`](http://www.github.com/OpenBankingStandard/account-information-api).  

 While working code is an essential part of developing any Standard, these repositories are intended for the development of the Standard specification. Any source code relating to the Standard (e.g. examples or a reference implementation) should be stored in separate repositories. 

 Implicitly, the Payment Initiation and Account Management use cases will be put on the back burner for the time being.  

3. **Use the [OBWG Report](obwg_report_final.pdf) as the starting point** - begin by transposing the relevant portions of the Report into markdown on Github, and iterate from there. 

 An index of which sections of the OBWG Report have been transposed into markdown is maintained [here](./Report_Index.md). 

 This repository ([`framework`](https://github.com/OpenBankingStandard/framework)) is for over-arching matters.

4. **Adopt an iterative approach.** Instead of trying to "boil the ocean", adopt a limited scope to begin with and iteratively expand the scope with each version of the Standard, in order to achieve progress towards creating a practical, usable standard.


## Workflow
To float ideas, make suggestions or seek feedback on proposed changes/additions to any of the repositories, post to the [Open Banking mailing group](https://groups.google.com/forum/#!forum/openbanking).

To contribute to any of the repositories: 
1. Branch the repository. 
2. Make your changes.
3. Push the branch.
4. Create a pull request with a description of the changes you've made.
5. Members of the community will then be able to review and comment on (or [react to](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments)) your proposed changes.
6. The Collaborators and/or CTC will review and decide whether to accept or reject the pull request. 


## Principles

* **Open** - Participation is open to all who are willing and able to contribute positively.
* **Transparent** - The Standard should be developed, and decisions should be made, in as transparent a manner as possible. 
* **Voluntary** - This initiative is currently a voluntary one. It should be assumed that anyone participating or contributing is acting in a personal capacity (and not, for example, on behalf of their employer), unless they explicitly state otherwise.
* **Collaborative** - This effort is intended to contribute towards the creation of an Open Banking Standard. We will seek to align, collaborate and cooperate with other efforts that have the same objective and garner support from the community and industry (including any initiative that arises from the [CMA's proposals](https://www.gov.uk/government/news/cma-wants-banks-to-work-harder-for-their-customers)).

---