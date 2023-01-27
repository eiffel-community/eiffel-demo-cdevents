<!---
   Copyright 2018 Ericsson AB.
   For a full list of individual contributors, please see the commit history.

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
--->

# Repository checklist
After copying the contents of this repo into the new repo-to-be, follow the below steps:

1. Update README.md.
   1. Replace the logo and the alt text of the logo image element. You can find logo template here:  https://github.com/eiffel-community/community/blob/master/resources/eiffel-community-logos.xcf
   1. Change the first heading and the description of the repository.
   1. Keep the rest of the README.md intact (license notice, links to contribution guidelines et cetera).
1. As per https://github.com/eiffel-community/.github/blob/master/CODE_OF_CONDUCT.md, go to the settings menu, make sure options tab is selected, scroll down to the Merge Button header and make sure that only "Allow squash merging" checkbox is ticked (un-tick the other two).
1. Create a repo-name-maintainers team in the eiffel-community organization.
   1. Make all members of the team maintainers (so they can add new maintainers as needed).
   1. Give the team write access to the new repository.
1. Create a maintainers' mailing list. There are no requirements on mailing list providers, but it needs to be invite only, readable by members only, but accept mails from non-members. [Google Groups](http://groups.google.com/) can easily set up such mailing lists.
   1. Add all [TC members](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee-members) as owners in this mailing list.
1. Update https://github.com/eiffel-community/community/blob/master/PROJECTS.md with a new line for this repository.
1. Update CODEOWNERS file with the correct maintainer list.
