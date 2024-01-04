.. include:: sub.txt

=======================
Inno3DPnPJoint Element
=======================

This command is used to construct a three-dimensional beam-column-joint element object for the 3D innovative plug-and-play steel tubular joints proposed within the `INNO3DJOINTS <https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/org-details/960532413/project/749959/program/31061225/details>`_ project.



.. function:: element('Inno3DPnPJoint', eleTag, *eleNodes, *SprMatTags)
   :noindex:

   ===================================   ===========================================================================
   ``eleTag`` |int|                      unique element object tag
   ``eleNodes`` |listi|                  a list of four element nodes
   ``SprMatTags`` |listi|                a list of 32 uniaxial material tags (one tag / component)
   ===================================   ===========================================================================

.. seealso::


   `PhD Thesis <https://estudogeral.uc.pt/handle/10316/110990>`_
   `article 1  <https://doi.org/10.1016/j.jcsr.2023.108436>`_
   `article 2  <https://doi.org/10.1007/978-3-031-30125-4_37>`_
