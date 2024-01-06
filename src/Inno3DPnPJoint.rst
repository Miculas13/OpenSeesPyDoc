.. include:: sub.txt

=======================
Inno3DPnPJoint Element
=======================

This command is used to construct a 3D beam-column-joint element object for the 3D innovative plug-and-play steel tubular joint configuration proposed within the `INNO3DJOINTS <https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/org-details/960532413/project/749959/program/31061225/details>`_ project.


.. function:: element('Inno3DPnPJoint', eleTag, *eleNodes, *SprMatTags)
   :noindex:

   ===================================   ===========================================================================
   ``eleTag`` |int|                      unique element object tag
   ``eleNodes`` |listi|                  a list of five element nodes
   ``SprMatTags`` |listi|                a list of 32 uniaxial material tags (one tag / component)
   ===================================   ===========================================================================


.. image:: /_static/I3DJ_allSprings_001.png


.. seealso::

	More information available in the following reference:
	
	#. C.V. Miculaş, Innovative plug and play joints for hybrid tubular constructions (Ph.D. thesis), University of Coimbra, Portugal, 2023, https://estudogeral.uc.pt/handle/10316/110990


	#. C. V. Miculaş, R. J. Costa, L. S. da Silva, R. Simões, H. Craveiro, T. Tankova, 3D macro-element for innovative plug-and-play joints, J. Constructional Steel Research 214 (2024), https://doi.org/10.1016/j.jcsr.2023.108436


	#. C.V. Miculaş, R.J. Costa, L. Simões da Silva, R. Simões, H. Craveiro, T. Tankova, Macro-modelling of the three-dimensional interaction between the faces of a steel tubular column joint, in: F. Di Trapani, C. Demartino, G.C. Marano, G. Monti (Eds.), Proceedings of the 2022 Eurasian OpenSees Days, Springer Nature Switzerland, Cham, 2023, pp. 408–422, http://dx.doi.org/10.1007/978-3-031-30125-4_37
	
	
.. note::
	
	Code developed by: Cristian V. Miculaș  (github user name: cvmiculas)
	
	Element conceptualization: Cristian V. Miculaș (cristian.miculas@uc.pt), Ricardo J. Costa (rjcosta@dec.uc.pt) and Luís Simões da Silva (luisss@dec.uc.pt)
	
	Affiliation: Civil Engineering Department, ISISE, University of Coimbra, Portugal
	
	Acknowledgements: This work has been supported in part by national funds through FCT – Foundation for Science and Technology, Portugal, under grant agreement SFRH/BD/138151/2018 awarded to Cristian V. Miculaş