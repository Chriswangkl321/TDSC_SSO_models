# TIFS_SSO_models
SSO Models are written in applied-pi calculus

Prerequisite: ProVerif<br />
Installation reference: http://prosecco.gforge.inria.fr/personal/bblanche/proverif/manual.pdf

Model File Preparation: copy the content in framework.pv into the beginnig of the model file to be verified. <br />Note that the input file to ProVerif need to be in .pv format.

Once Proverif and model file are ready, run ProVerif to check the protocol model using the following command:<br />
./proverif ⟨filename⟩.pv