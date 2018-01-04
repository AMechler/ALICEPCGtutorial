# Welcome to the Photon Conversion Group Tutorial

This tutorial is meant as an introduction to the software packages provided by the Photon Conversion Group \(PCG\). As it is still under development as is the software it does not claim completeness. However, it should provide a good start for new-comers and oldies to get started on a new topic. If you wanna help improving this documentation you are very welcome and just need to let us know and [e-mail Friederike](friederike.bock@cern.ch). She will grant you access to the documentation git as well. 

In the provided software package the reconstruction of photons within ALICE using different detectors \(EMCal, DCal, PHOS, TPC & ITS\) is handled in a common way and the neutral mesons can be extracted using different techniques. Furthermore the software can be used as analysis level QA for the corresponding detectors focussing on the quantities relevant for the corresponding photon reconstruction.

Our software is structured in 3 main parts hosted on GitHub and GitLab:

1. [**AliPhysics**](https://github.com/alisw/AliPhysics) implementation in **PWGGA/GammaConv**, which is running on the reconstructed ESD/AOD data or simulation files
2. **Afterburner** implementation which is kept and maintained in the [**PCG-Software directory**](https://gitlab.cern.ch/alice-pcg/AnalysisSoftware) and is used to analyse the output files of the AliPhysics-Tasks to extract the meson spectra \($$\pi^0, \eta, \omega$$\), $$v_n$$ and direct photon results
3. **Cocktail** implementation, which is scattered in 2 different places in AliPhysics \(**PWG/Cocktail** & **PWGGA/GammaConv**\) and which has to fed by inputs summarized in the [**Cocktail-Repository**](https://gitlab.cern.ch/alice-cocktail-EM/cocktail_input)

All three packages will be needed to complete the full meson and direct photon analysis as it is currently implemented and will be explained in the following tutorial in different sections.

To gain committer-access to the PCG-Software directory please subscribe to **_alice-pcg_ & _alice-pcg-core_** on [e-groups](https://e-groups.cern.ch/) and to get the committer access to the Cocktail repository you have to be subscribed to **_alice-cocktail-EM_**.

Furthermore, we have a repository hosting all analysis/combination notes [**PCG-Notes repository**](https://gitlab.cern.ch/alice-pcg/AnalysisNotes) where you should contribute with your own analysis note once your analysis reached an advanced stage and is targeted to be included in a publication.

Last but not least, the last GitHub repository is our GitBook tutorial repository to complete the list (which you are reading) [**PCG-tutorial**](https://github.com/FriederikeBock/ALICEPCGtutorial) which is linked to the GitBook itself [**Tutorial**](https://friederikebock.gitbooks.io/pcgtutorial/content/)

## Contacts

If there are any questions regarding this tutorial do not hesitate to ask on

* [alice-pcg-core@cern.ch](mailto:alice-pcg-core@cern.ch) 

or directly to the convenors and creators of the tutorial

* Daniel Muehlheim [d.muehlheim@cern.ch](mailto:d.muehlheim@cern.ch)
* Friederike Bock [friederike.bock@cern.ch](mailto:friederike.bock@cern.ch)
* Nicolas Schmidt [nicolas.schmidt@cern.ch](mailto:nicolas.schmidt@cern.ch)
* Mike Sas [msas@nikhef.nl](mailto:msas@nikhef.nl)

We are happy to help.

## Additional Information

**useful links**
* [AliPhysics, aliBuild, AliEn](https://dberzano.github.io/)

**twikis**: 
* [PCG](https://twiki.cern.ch/twiki/bin/view/ALICE/PWGGAPcmGroup)
* [PWGGA](https://twiki.cern.ch/twiki/bin/view/ALICE/PWGGA)
* [EMCocktail](https://twiki.cern.ch/twiki/bin/view/ALICE/EMCocktail)

