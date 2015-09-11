bonita-development-environment
==============================

/!\ EARLY STAGE /!\

More detailed steps focused on Engine avalable on http://community.bonitasoft.com/blog/how-contribute-bonita-bpm-engine

A repository containing work to Setup the whole development environment of Bonita using the Oomph installer

Prerequisites:
- For Engine, none
- For Web, access to Engine artefacts
- For Studio:
    - access to Engine and Web artefacts


1 - Download Oomph installer: https://wiki.eclipse.org/Eclipse_Oomph_Installer

2 - Launch the Oomph Installer

3 - Use advanced mode

4 - Select Eclipse for Java developer and go to next page

5 - Add project https://raw.githubusercontent.com/apupier/bonita-development-environment/master/BonitaBPM.setup 

6 - Select the component you wish

(Engine in Beta stage; Web and Studio in Alpha stage, they require to have built locally dependencies)

7 - Go to the end of the wizard by providing all information

8 - Wait...

9 - If chosen Engine, Open Package Explorer -> Other Projects; Right-click on bonita-engine -> Configure -> Configure and detect nested projects...

7 - Enjoy!
