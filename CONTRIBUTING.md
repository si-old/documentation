# StudentIngegneria IT Committee software contibution code #

## Table of contents ##

- [Code of conduct](#code-of-conduct)
- [Community contacts and places](#community-contacts-and-places)

Legal

- [Licensing](#licensing)
- [Copyright attribution](#copyright-attribution)

Contribution

- [Coding style](#coding-style)
- [Submitting patches](#submitting-patches)

Workflow

- [Developing a feature](#developing-a-feature)

## Code of conduct ##

Don't be a jerk.

## Community contacts and places ##

General discussion happens in the general discussion groups,
hosted on the [Telegram](https://telegram.org) platform.

Discussion on a specific topic should happen on Github,
in the bug trackers of the single projects.

## Licensing ##

The following is a list of the preferred licenses, divided by
category, for projects. This shall not be taken as completely
prescriptive, and additional licenses may be evaluated on a per-project
basis.

### Software ###

For software, the GNU licenses shall be used:

- [GNU GPL v3](https://www.gnu.org/licenses/gpl.txt) : for software intended to run on a client
- [GNU AGPL v3](https://www.gnu.org/licenses/agpl.txt): for software intended to run on a server
- [GNU LGPL v3](https://www.gnu.org/licenses/lgpl.txt): for software intended for use as a library

For software that cannot use the aforementioned licenses,
the following licenses should be considered:

- [2-Clause BSD License](https://github.com/StudentIngegneria/documentation/blob/master/licenses/BSD-2-Clause.txt)
- [MIT / X11 License](https://github.com/StudentIngegneria/documentation/blob/master/licenses/MIT-X11.txt)

For software intended for use as a library, the following license
may also be considered:

- [0-Clause BSD License](https://opensource.org/licenses/0BSD) (Public domain attribution)

Software shall never be released in the public domain
directly, as some jurisdictions don't recognize
the public domain (e.g. Germany).

### Art Works ###

For art works (drawings, video, and general works of art),
the following licenses shall be used:

- [CC BY-SA 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)
- [CC BY-SA-NC 4.0 International](https://creativecommons.org/licenses/by-sa-nc/4.0/)

Non-commercial licenses, non-free by their nature, shall
be used lightly and only upon unanimous approval
of the committee.

The following license may be considered for works
of art, upon approval of a majority (50%+1) of
the committee including the original author of
the work:

- [CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode) (Public domain attribution)

Art shall never be released in the public domain
directly, as some jurisdictions don't recognize
the public domain (e.g. Germany).

### Documentation ###

For software documentation, the following license shall
be used:

- [GNU FDL v1.3](https://www.gnu.org/licenses/fdl.txt)

For documentation written for software released under non-GNU licenses,
the following license shall be used:

- [CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode) (Public domain attribution)

Documentation shall never be released in the public domain
directly, as some jurisdictions don't recognize
the public domain (e.g. Germany).

## Copyright Attribution ##

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL
NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and
"OPTIONAL" in this section are to be interpreted as described in
[RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

Upon contributing to any project, the contribution
shall be conveyed to StudentIngegneria under the terms of the
StudentIngegneria Contribution License
( [SICL v1](https://github.com/StudentIngegneria/documentation/blob/master/licenses/SICL-v1.txt) ).  

By contributing to any project, you automatically agree to
convey your contribution to StudentIngegneria under the appropriate license.

## Submitting patches ##

Patches are submitted to the main repository for inclusion in form of GitHub's
Pull Requests.

### Patch guidelines ###

To be accepted a patch should contain code that compiles / works
( or whatever equivalent is appropriate for the context ) and doesn't break
other parts of the project.

In order to make your patches as easy to check as possible, try to keep them
small, clear, and atomic:  

- Only include closely related changes in one commit  
- Limit a commit to changing a single file or component unless that would break
  something somewhere else  

These rules also make it easier to find regressions, and help prevent new bugs
from slipping through.  

### Commit messages guidelines ###

- #### Regular commits ####

	Be brief: the first line has to not be more than 80 characters in
	length.

	After the first line, you may add explanatory paragraphs that tell what the
	patch accomplishes.  
	Describe your changes in the imperative mood, as if you
	are giving orders to the codebase to change its behavior,
	e.g. ``` Make THIS do THAT``` instead of
	```This patch makes THIS do THAT``` or ```Changed THIS to do THAT```.  

	Try to make sure your explanation can be understood without external
	resources.  
	Describe how the patch works and why it is needed, but do not repeat what
	the diff already shows.  

	Wrap all paragraph lines to 80 characters.

- #### Merge commits ####

	All the rules for regular commits apply, in addendum

	- The first line should begin with a tag in the form ```[ TAG ]```  
		indicating the type of patch, in accordance to the type of branch that is
		being merged.  
		e.g a merge commit from the ```feature/wonderful-thing``` branch should be
		titled like ```[FEATURE] Add wonderful thing```.
