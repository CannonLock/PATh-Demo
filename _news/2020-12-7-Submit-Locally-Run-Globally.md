---
title: "Submit Locally, Run Globally" 
date: 2020-12-07T12:00:00+00:00
excerpt: The PATh project offers technologies and services that enable researchers to harness *through a single interface,* and from the comfort of their “home directory”, computing capacity offered by a global and diverse collection of resources. 
--- 

<figure class="figure float-right" style="margin-left: 1em">
  <img src="{{site.baseurl}}/images/news/submitlocally.jpg" class="figure-img img-fluid rounded" alt="add alt text" width="350px">
  <figcaption class="figure-caption">OSG<br/>Credit: Miron Livny</figcaption>
</figure>

The PATh project offers technologies and services that enable researchers to harness *through a single interface,* and from the comfort of their “home directory”, computing capacity offered by a global and diverse collection of resources. 

The OSG offers via the OSG Connect service researchers with an <a href="https://www.osgconnect.net/" target="_blank">OSG account</a> and an ***Access Point to the Open Science Pool***, a globally deployed HTCondor pool. The capacity offered by this pool comes from more than 130 clusters that are part of the OSG compute federation, and make some of their capacity available to support Open Science. This includes clusters at campuses that are funded under the <a href="https://www.nsf.gov/funding/pgm_summ.jsp?pims_id=504748" target="_blank">NSF CC* program.</a>

The <a href="https://research.cs.wisc.edu/htcondor/" target="_blank">The HTCondor Software Suite (HTCSS)</a> offers the technology for these access points that can be deployed and operated by individuals, science collaborations and campuses. Researchers can use such a private/local Access Point to harness the power of locally and remotely deployed HTCondor execution points. This includes institutional and national computing systems (like the Open Science Pool) as well as commercial clouds.

***Below are some examples of how researchers enhanced their computational throughput by leveraging the “submit locally, run globally” capabilities offered by PATh Access Points.***


***AI-Driven Chemistry***
Dr. Roman Zubatyuk from the group of <a href="https://www.cmu.edu/chemistry/people/faculty/isayev.html" target="_blank">Prof. Olexandr Isayev</a> at the Carnegie Mellon University chemistry department uses the access point provided by the OSG to develop a supervised machine learning method that more quickly predicts the chemical behavior of small molecules and potential drugs. Via this single access point, he is able to deploy workers globally in support of a high-throughput “Manager-worker” application. <a href="https://agenda.hep.wisc.edu/event/1440/session/3/contribution/19/material/slides/0.pdf" target="_blank">Roman reported about his OSG experience in a presentation</a> delivered at the 2020 HTCondor Week workshop.

***Astrophysics***
The <a href="https://icecube.wisc.edu/" target="_blank">IceCube collaboration</a> has operated an HTCSS access point at the <a href="https://wipac.wisc.edu/" target="_blank">Wisconsin IceCube Particle Astrophysics Center</a> for several years. It was used to access GPU capacity offered by the OSG compute federation that includes more than 20 sites of the <a href="https://pacificresearchplatform.org/" target="_blank">Pacific Research Platform (PRP)</a>. As part of an <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1941481&HistoricalAwards=false" target="_blank">NSF EAGER project</a>, a team led by OSG Executive Director Frank Wuerthwein and Developer Igor Sfiligoi from the SDSC used this access point to study large-scale bursting of IceCube simulations on resources acquired from commercial cloud. In 2019, the team demonstrated a burst at the Supercomputing 19 conference that harnessed the capacity of 51K GPUs from three cloud providers and scattered across 26 cloud regions, a feat recognized as “the largest cloud simulation in history” in a <a href="https://icecube.wisc.edu/news/view/700" target="_blank">keynote presentation at the conference.</a>

***Bat Genomics***
<a href="https://www.amnh.org/research/staff-directory/ariadna-morales" target="_blank">Dr. Ariadna Morales,</a> used the Access Point recently deployed at the <a href="https://www.amnh.org/research" target="_blank">American Museum of Natural History (AMNH)</a> to harness the capacity of local and OSG capacity in support of her work to analyze the whole genome data of 20 bats. Ariadna, a postdoc at the AMNH, used the local Access Point to run 80K compute jobs in one year. <a href="https://indico.fnal.gov/event/22127/contributions/195603/attachments/133985/165492/osgahm20-2.2.2_-_Dinos_and_Data_2_-_Evolution_of_HPC_at_AMNH.pptx" target="_blank">More details of her experience</a> and other AMNH researchers can be found in the AMNH presentation at the <a href="https://indico.fnal.gov/event/22127/overview" target="_blank">2020 OSG All Hands Meeting.</a>

***Gravitational Waves***
When the <a href="https://www.ligo.org/" target="_blank">LIGO collaboration</a> realized the need for additional capacity to analyze the observed data that led to <a href="https://www.ligo.caltech.edu/news/ligo20171003" target="_blank">the Nobel prize-winning detection of gravitational waves</a>, they deployed an HTCSS Access Point that enabled them to expend their High Throughput computing capabilities to include capacity from the OSG federation and XRAC allocations. As an early adopter of HTCSS technologies, the additional capacity provided via the new Access Point easily integrated with the computing and data infrastructure of the collaboration. Deployed more than five years ago, this same access point remains an integral part of the LIGO distributed computing infrastructure, routinely integrating capacity offered by the OSG, international collaborators, XRAC allocations, and the capacity of the LIGO data grid. <a href="https://morgridge.org/story/high-throughput-computing-helps-ligo-confirm-einsteins-last-unproven-theory/" target="_blank">Read more here.</a>

***Drug Screening***
<a href="https://cancer.wisc.edu/research/resources/ddc/smsf/" target="_blank">The Small Molecule Screening Facility (SMSF)</a> within <a href="https://cancer.wisc.edu/research/resources/ddc/" target="_blank">UW-Madison’s Carbone Cancer Center Drug Development Core</a> has been using an access point deployed by the <a href="https://chtc.cs.wisc.edu/" target="_blank">UW-Madison Center for High Throughput Computing (CHTC)</a> to perform computational docking-based screening of potential drug molecules. In just the month of November 2020, the SMSF used almost 2M core hours provided by the OSG for two projects. In collaboration with <a href="https://www.creighton.edu/faculty-directory-profile/100609/shashank-dravid" target="_blank">Prof. Shashank Dravid</a> at Creighton University, one project aims to identify inhibitors of synaptic recruiting proteins for ionotropic glutamate receptors. This novel protein-protein interaction target required the docking of 14 million representations of 8 million molecules from the Aldrich chemical library using a consensus methodology developed by the SMSF to incorporate 6 different docking programs. Another project with <a href="https://apps.pharmacy.wisc.edu/sopdir/weiping_tang/index.php" target="_blank">Dr. Weiping Tang</a> at UW-Madison leverages the same methodology to develop novel PROTACs, that selectively degrade specific protein targets to regulate biological activity. In order to identify a ligand molecule that can recruit PROTACs to biological targets, the SMSF is screening 30 million molecules (45 million representations) and integrating 3 different docking programs. For both projects, the consensus scores from these many millions of computations will inform the selection and downstream laboratory testing of just the top ~100 candidates, streamlining the drug development process.
=======
***AI-Driven Chemistry***
Dr. Roman Zubatyuk from the group of <a href="https://www.cmu.edu/chemistry/people/faculty/isayev.html" target="_blank">Prof. Olexandr Isayev</a> at the Carnegie Mellon University chemistry department uses the access point provided by the OSG to develop a supervised machine learning method that more quickly predicts the chemical behavior of small molecules and potential drugs. Via this single access point, he is able to deploy workers globally in support of a high-throughput “Manager-worker” application. <a href="https://agenda.hep.wisc.edu/event/1440/session/3/contribution/19/material/slides/0.pdf" target="_blank">Roman reported about his OSG experience in a presentation</a> delivered at the 2020 HTCondor Week workshop.

***Astrophysics***
The <a href="https://icecube.wisc.edu/" target="_blank">IceCube collaboration</a> has operated an HTCSS access point at the <a href="https://wipac.wisc.edu/" target="_blank">Wisconsin IceCube Particle Astrophysics Center</a> for several years. It was used to access GPU capacity offered by the OSG compute federation that includes more than 20 sites of the <a href="https://pacificresearchplatform.org/" target="_blank">Pacific Research Platform (PRP)</a>. As part of an <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1941481&HistoricalAwards=false" target=_blank">NSF EAGER project</a>, a team led by OSG Executive Director Frank Wuerthwein and Developer Igor Sfiligoi from the SDSC used this access point to study large-scale bursting of IceCube simulations on resources acquired from commercial cloud. In 2019, the team demonstrated a burst at the Supercomputing 19 conference that harnessed the capacity of 51K GPUs from three cloud providers and scattered across 26 cloud regions, a feat recognized as “the largest cloud simulation in history” in a <a href="https://icecube.wisc.edu/news/view/700" target="_blank">keynote presentation at the conference.</a>

***Bat Genomics***
<a href="https://www.amnh.org/research/staff-directory/ariadna-morales" target="_blank">Dr. Ariadna Morales,</a> used the Access Point recently deployed at the <a href="https://www.amnh.org/research" target="_blank">American Museum of Natural History (AMNH)</a> to harness the capacity of local and OSG capacity in support of her work to analyze the whole genome data of 20 bats. Ariadna, a postdoc at the AMNH, used the local Access Point to run 80K compute jobs in one year. <a href="https://indico.fnal.gov/event/22127/contributions/195603/attachments/133985/165492/osgahm20-2.2.2_-_Dinos_and_Data_2_-_Evolution_of_HPC_at_AMNH.pptx" target="_blank">More details of her experience</a> and other AMNH researchers can be found in the AMNH presentation at the <a href="https://indico.fnal.gov/event/22127/overview" target="_blank">2020 OSG All Hands Meeting.</a>

***Gravitational Waves***
When the <a href="https://www.ligo.org/" target="_blank">LIGO collaboration</a> realized the need for additional capacity to analyze the observed data that led to <a href="https://www.ligo.caltech.edu/news/ligo20171003" target="blank">the Nobel prize-winning detection of gravitational waves</a>, they deployed an HTCSS Access Point that enabled them to expend their High Throughput computing capabilities to include capacity from the OSG federation and XRAC allocations. As an early adopter of HTCSS technologies, the additional capacity provided via the new Access Point easily integrated with the computing and data infrastructure of the collaboration. Deployed more than five years ago, this same access point remains an integral part of the LIGO distributed computing infrastructure, routinely integrating capacity offered by the OSG, international collaborators, XRAC allocations, and the capacity of the LIGO data grid. Read more here. (Miron acquiring link).

***Drug Screening***</br>
<a href="https://cancer.wisc.edu/research/resources/ddc/smsf/" target="_blank">The Small Molecule Screening Facility (SMSF)</a> within <a href="https://cancer.wisc.edu/research/resources/ddc/" target="_blank">UW-Madison’s Carbone Cancer Center Drug Development Core</a> has been using an access point deployed by the <a href="https://chtc.cs.wisc.edu/" target="_blank">UW-Madison Center for High Throughput Computing (CHTC)</a> to perform computational docking-based screening of potential drug molecules. In just the month of November 2020, the SMSF used almost 2M core hours provided by the OSG for two projects. In collaboration with <a href="https://www.creighton.edu/faculty-directory-profile/100609/shashank-dravid" target="_blank">Prof. Shashank Dravid</a> at Creighton University, one project aims to identify inhibitors of synaptic recruiting proteins for ionotropic glutamate receptors. This novel protein-protein interaction target required the docking of 14 million representations of 8 million molecules from the Aldrich chemical library using a consensus methodology developed by the SMSF to incorporate 6 different docking programs. Another project with <a href=https://apps.pharmacy.wisc.edu/sopdir/weiping_tang/index.php" target="_blank">Dr. Weiping Tang</a> at UW-Madison leverages the same methodology to develop novel PROTACs, that selectively degrade specific protein targets to regulate biological activity. In order to identify a ligand molecule that can recruit PROTACs to biological targets, the SMSF is screening 30 million molecules (45 million representations) and integrating 3 different docking programs. For both projects, the consensus scores from these many millions of computations will inform the selection and downstream laboratory testing of just the top ~100 candidates, streamlining the drug development process.




 
 