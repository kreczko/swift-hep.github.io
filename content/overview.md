---
title: "Overview"
date: 2022-01-11T20:43:28Z
draft: false
display_in_summary: false
---

## Science and strategy 

Computing contributes significantly to the cost of operating HEP experiments, with the UK currently providing 
about 13.5% of the total ATLAS computing resources, 6% for CMS, 20% for LHCb and a significant fraction expected for DUNE. 
Resources are provided as a cross-experiment initiative via GridPP with a cost of about £5M/year. 
The overall resource requirement is expected to increase in the coming years as the experiment upgrades are designed to 
increase the overall data throughput by a factor of 10. 
Only a modest increase in resources is expected due to the diminishing growth rate at equal cost of computer processing and storage. <br>

At same time the evolution of computing hardware and software technologies calls for HEP software R&D. 
In particular the hardware has evolved towards parallel architectures where it is expected that the bulk of the arithmetic 
processing is performed using single instruction multiple process (SIMP) and single instruction multiple thread (SIMT). 
Optimising software to make use of this hardware is becoming the key to increase computing efficiency. 
Scientific computing is moving towards the use of accelerator hardware, such as GPUs and FPGAs, where thousands of 
threads operate simultaneously to perform fast scientific computations. 
This is an opportunity, as real-time applications such as low latency triggers can be 
developed using commodity hardware and software tools. At the same time GPUs are a promising technology with which to run simulation and data processing 
at lower cost and better power efficiency. To unlock these potential gains an aggressive software R&D programme is needed to modernise the current 
HEP codes and optimise their performance on the heterogeneous hardware architectures that are expected to be developed in the next decade. <br>

Such developments need to be sustainable, to last for the lifetime of the current experiments, to be open source, to allow for collaboration between different teams, 
and to follow industry standards, to exploit state-of-the-art training and enable collaboration with industry to access and inform the latest technologies. <br>

Establishing a software collaboration within HEP in the UK will ensure that future investments in HEP experiments will have access to the technology needed 
to exploit the data to maximise the physics return on investment. This will also create a core of knowledge and training in skills that 
are in high-demand in UK industry.


## Timeline and funding

The SWIFT-HEP project covers this crucial 3 year period between April 2021 and March 2024 for the UK to participate and lead the development of the means to execute the next generation experiments. Funding was awarded for an average of 4 FTE software developers/ applied physicists and was awarded at various universities in the UK. 
 Staff are funded at the 50% level by SWIFT-HEP, with the remaining 50% funded by an experiment grant to conduct work specific to such experimental collaboration. This ensures transfer of knowledge and expertise from the experiments to SWIFT-HEP and vice versa. <br>
The timeline for the SWIFT-HEP project is summarised in the figure below. 
SWIFT-HEP kicked off in April 2021, after amm STFC funded pilot project (ECHEP) and some additional funding from the UKRI ExCALIBUR initiative. The funding beyond April 2024 is still under discussion, however the proposal submitted in 2020 made it clear that the project need to continue and expand for the next decade. 
<center> {{< figure src="/images/swift-timeline.png" alt="swift-hep timeline" width="600px">}} </center>

## Work packages and activities

The SWIFT-HEP work is organised in 5 work packages (WP), plus a management WP. A description and status of each WP is given in the dedicated pages. 
Each of the WPs has two conveners who facilitate communication within the UK community and interaction with external collaborators. 
[See also](/organisation/).

* WP0: Management
* WP1: Intelligent data and workflow management
* WP2: Event generators
* WP3: Simulation
* WP4: Reconstruction and trigger
* WP5: Analysis systems

Additional activities are organised by SWIFT-HEP as additional community engagement, such as training events and hackathons. Full details to be given in the "News" session on the <a href="/index.html"> Home page</a>. <br>
Participation in international workshops and meetings is essential to deliver a world-leading programme. Expertise is currently available in the UK as part of GridPP and of the experiments. SWIFT-HEP proposes to attach additional effort to this expertise to establish ourselves as a leading member of this international organisation.

## Complementary research 

The SWIFT-HEP work is centred around work that will serve the HEP experimental community by developing software tools that are between the Grid infrastructure and the frameworks that are specific to the experiments. This is described in Fig. 3, with the green layer 3 addressing cross-experiment issues. The full list of signatories is available in Appendix and shows the UK wide involvement in this initiative. The work proposal will be part of a growing international community and has as main reference points the Data Organisation Management and Access (​DOMA​) project within WLCG for the data management work and the ​HSF for the event generator, simulation, reconstruction and analysis work. <br>
The complementarity of the SWIFT-HEP work with other packages of work in the HEP community is illustrated in the figure below.
<center> {{< figure src="/images/swifthep-layers.png" alt="swift-hep Layers" width="600px">}} </center>


