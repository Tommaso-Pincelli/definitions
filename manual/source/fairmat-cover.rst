.. _FairmatCover:

=======================
FAIRmat-NeXus Proposal
=======================

.. index::
   IntroductionCover
   OurScope
   Outreach
   WhatIsNew


.. _IntroductionCover:

The FAIRmat proposal to NeXus is an effort by the community of scientists connected to the `FAIRmat consortium <https://www.fairmat-nfdi.eu/fairmat/fairmat_/consortium>`_
to refine and expand the structure of NeXus. As a project that aims at creating an infrastructure 
for experimental data to be findable, accessible, interoperable and reusable (F.A.I.R.) in the fields of condensed-matter physics
and the chemical physics of solids, FAIRmat has adopted NeXus as the common format.

`NeXus <https://www.nexusformat.org/>`_ is a common data exchange format developed for neutron, X-ray, and muon experiments. 
NeXus is built on top of the scientific data format HDF5 and adds domain-specific rules for organizing data 
within HDF5 files (:ref:`application.definitions`) in addition to a dictionary of well-defined domain-specific 
field names (:ref:`base.class.definitions`). The combination of these two structures allows it to have sufficient flexibility to cover any 
experimental technique and instrumentation, while ensuring rigorous, application specific structures that can be accessed automatically.
The documentation available here includes part of the contents of the NeXus User Manual (available `here <https://manual.nexusformat.org/user_manual.html>`_),
reported here for the convenience of the user, but restricted to the parts most pertinent to our proposal. For more extensive information,
please visit the original manual. 

.. _OurScope:

Our scope and perspective
#########################

Thanks to an active cooperative approach across a wide variety of experimental 
techniques, the FAIRmat project has an extraordinary opportunity to expand greatly the set of data/metadata accurately 
described via NeXus. With a closely-connected team of domain experts, we
will achieve such expansion while at the same time maintainig a consistent structure across different
techniques and methods, striving for the maximum simplicity of use.

Achieving a standardized and FAIR data structure has a wide spectrum of advantages, ranging from radical
progress in scientific transparency to the development of new, far-reaching tools that can be shared across
the whole scientific community. The convenience of such tools can range from guaranteeing data reusability within a single lab, 
to the open-source availability of ready-to-use, community-generated advanced analysis software. Perhaps the grandest resource, however, 
is the inclusion of experimental datasets in the `NOMAD Laboratory <https://nomad-lab.eu/about/scope>`_: 
a data infrastructure that already hosts the largest computational material science repository in the world, 
a homogeneous and machine readable archive, a human accessible encyclopedia and artificial intelligence access.

.. _Outreach:

Outreach to the community
##########################

A data infrastructure is not effective if it is not easy to integrate seamlessly in the day-to-day workflow
of a laboratory. For this reason, we approach our newly developed NeXus proposal as a community-driven development.
We have drafted an accurate and consistent expansion of NeXus capabilities for a number of lab-based techniques. 

If your data is generated with these techniques and you are interested in producing FAIR data and accessing the FAIRmat tools, 
we invite you to try our proposed structure out. If you find any conflicts or inconsitencies, please signal them to us using the
comment section. You will contribute to the creation of a more effective NeXus structure, and it is our firm belief that, with enough contributors,
we will obtain a consistent and practical structure. 
If you do not find your technique, and would be interested in participating to the development of a standard, please contact us 
directly at (?).

You are free to choose at which point in the workflow you wish to convert the data to NeXus, as its flexibility allows to
describe raw data, pre-processed data and fully processed data. As an entry step, we suggest to use a test dataset
that is fully processed and already published (or, alternatively, of negligible scientific content). These datasets, indeed, require often the most 
extensive metadata description, but are most easily converted to NeXus, with minimal to no impact on the data processing pipeline.

In fact, a low barrier (but high yield!) way to participate to FAIRmat consists in converting only fully processed datasets that 
are used for a publication, and publishing them via FAIRmat only when your manuscript is in press. This makes the task of 
converting to NeXus much more sporadic than fairifying raw data, to the point that it may be even acceptable not to automate it. At the same time, 
it guarantees full control on the data until publication. We are confident that if you take this approach, more appetite will come with eating,
and you will be naturally inclined to gradually integrate FAIRmat structures and tools further in your workflow. 

.. _WhatIsNew:

What is New?
##############

The NeXus data format has four components:

:ref:`Mpes-Structure` A set of base classes and application definitions for 
    the ecosystem of experiments dealing with photoemission, encompassing XPS, ARPES, HAXPES etc.
