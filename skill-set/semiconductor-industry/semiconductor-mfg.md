#	Semiconductor Manufacturing & Semiconductor Manufacturing Equipment Semiconductor Manufacturers



##	Integrated Device Manufacturers (IDMs)



+ [From Wikipedia, list of integrated device manufacturers (IDMs)](https://en.wikipedia.org/wiki/Integrated_device_manufacturer)
+ [From Wikipedia, list of semiconductor IP core vendors](https://en.wikipedia.org/wiki/List_of_semiconductor_IP_core_vendors)
+ [From Wikipedia, list of fabless semiconductor IC design companies](https://en.wikipedia.org/wiki/Fabless_manufacturing)
+ 
+ 
+ 
+ 
+ 
+ 
+ 
+ 
+ 
+ 
+ 





##	Semiconductor Manufacturing





###	Notes on Semiconductor Manufacturing


Aspects of semiconductor manufacturing related to technology CAD (TCAD):
+ ion implantation
+ diffusion
+ oxidation
+ dry/wet etching
+ deposition
+ ***optical lithography, photolithography, or optical photolithography***, and next-generation lithography (NGL) techniques for optical lithography
	- ***computational lithography***, or computational scaling
		* Mathematical and algorithmic approaches to improve attainable resolution from optical lithography.
		* For 22 nm semiconductor manufacturing process technology nodes and beyond.
		* To fix problems with:
			+ 193 nm deep UV optical lithography.
		* includes DFM techniques, such as:
			+ resolution enhancement technologies, RET
				- scattering bars
				- phase-shoft masks
				- multiple/double patterning
			+ optical proximity correction, OPC
			+ source mask optimization
				- or, complex modeling of the lens system and photoresist
					* aims to improve chip manufacturability and manufacturing yield
					* use signature of scanner to improve:
						+ OPC model
						+ polarization characteristics of the lens pupil
						+ Jones matrix of the stepper lens
						+ optical parameters of the photoresist stack
						+ diffusion through the photoresist
						+ stepper illumination control variables
	- multiple patterning, or multi-patterning
	- classifications:
		* ultraviolet lithography, UV lithography
		* X-ray lithography
		* EUV lithography
	- EUV lithography, extreme ultraviolet lithography, EUVL
		* 13.5 nm extreme ultraviolet lithography
		* assist features
		* source mask optimization
		* phase shift masks
		* EUV photoresist exposure
		* contamination effects
			+ resist outgassing
			+ tin deposition
			+ hydrogen blistering
			+ resist erosion
			+ membrane
		* mask defects
		* throughput scaling issues
			+ EUV stochastic issues
		* used with multile patterning
		* single patterning extension, anamorphic high-NA (NA, numerical aperture)
	- deep UV immersion lithography, immersion lithography
	- X-ray lithography
	- BEUV lithography, or beyond extreme ultraviolet lithography
		* about 6.7 nm wavelength
	- maskless lithography, MPL
		* electronic beam lithography, e-beam lithography, EBL
		* plasmonic direct writing lithography
		* optical maskless lithography
			+ multiphoton lithography, ***direct laser writing***, direct laser lithography
	- quantum optical lithography, QOL
	- other non-mainstream lithography techniques
		* nanoimprint lithography
			+ thermoplastic nanoimprint lithography
			+ photo nanoimprint lithography
			+ resist-free direct thermal nanoimprint lithography
		* molecular self-assembly lithography
		* stencil lithography
		* charged-beam lithography
			+ ion beam lithography, or ion-beam lithography, or ion-projection lithography
				- ion beam proximity lithography, IBL
				- focused ion beam lithography, FIB
				- similar to:
					* electronic beam lithography
				- electron-projection lithography
		* magnetolithography, ML
			+ photoresist-less and photomaskless lithography
			+ backside lithography
		* plasmonic lithography, plasmonic nanolithography, plasmonic photolithography
		* ***soft lithography***
			+ use elastomeric stamps, molds, and conformable photomasks to fabricate or replicate structures
			* PDMS lithography
			* microcontact printing
			* multilayer soft lithography
		* laser printing lithography
			+ laser printing of single nanoparticles
		* nanosphere lithography, NSL
		* direct-write lithography process
			+ proton beam lithography, or p-beam writing, or proton beam writing
		* multiphoton lithography, direct laser lithography, direct laser writing
		* ***scanning probe lithography, SPL***
			+ mechanical/thermo-mechanical SPL, m-SPL
			+ thermal SPL, t-SPL
			+ thermo-chemical SPL, tc-SPL, or thermochemical nanolithography, TCNL
			+ dip-pen SPL, dp-SPL, or dip-pen nanolithography, DPN
				- thermal dip-pen lithography
				- beam pen lithography
			+ local oxidation lithography, o-SPL
			+ bias-induced SPL, b-SPL
			+ current-induced SPL, c-SPL
			+ thermally-assisted magnetic SPL, tam-SPL
		* local oxidation nanolithography, LON
		* interference lithography, or holographic lithography
			+ not maskless lithography
			+ no 1:1 imaging system in between
			+ electron holographic lithography
			+ atom holographic lithography
		* nanofountain darwing, or nanofountain probe
+ silicidation
+ modeling mechanics of semiconductor manufacturing processes
+ CMP, chemical-mechanical polishing, chemical-mechanical planarization
+ annealing (diffusion and dopant activation)
+ epitaxy








main categories of wafer processing are:
+ deposition
	- PVD, physical vapor deposition	
	- CVD, chemical vapor deposition
	- ECD, electrochemical deposition
	- MBE, molecular beam epitaxy
	- ALD, atomic layer deposition
	- oxide layer formation
		* thermal oxidation
		* LOCOS, LOCal Oxidation of Silicon
+ removal (of material from the wafer)
	- etching
		* dry etching
		* wet etching
+ patterning (to shape or alter deposited materials via lithography)
	- optical photolithography
		* coat wafers with the chemical photoresist
		* stepper that focuses, aligns, and moves masks
+ modification of electrical properties
	- doping transistor sources and drains
		* using diffusion furnaces
		* using ion implantation
	- furnance annealing (for old technology nodes) and rapid thermal annealing (RTA, for modern technology nodes) 
	- UVP, UV processing
		* expose low-k insulators to ultraviolet light to reduce their dielectric constant
		* oxidation, to create semiconductor-insulator junctions
			+ LOCOS, LOCal Oxidation of Silicon
				- for manufacturing MOSFETs







FEOL processing, front-end-of-line processing, or front-end surface engineering
+ Notes:
	- 1st portion of the semiconductor manufacturing process
		* form/create the devices (such as transistors, capacitors, resistors, ...) directly in the silicon as patterns
			+ or, patterned in the semiconductor
		* from the patterning of devices on the semiconductor wafer till the deposition of metal interconnection layers (not including the 1st metal layer deposition)
+ optional step for advanced technology nodes:
	- straining step to deposit silicon variant, such as silicon-germanium (SiGe)
+ epitaxy
	- for crystal growth or material deposition to form new crystalline layers with one/multiple well-defined orientations with respect to the crystalline seed layer
	- this creates/grows an ultrapure, virtually defect-free silicon layer
+ select type of wafer to be used
+ CMP, chemical-mechanical polishing, chemical-mechanical planarization
+ cleaning of the wafer
+ STI, shallow trench isolation
+ well formation
+ gate module formation
+ source and drain module formation





Gate oxide and implants, between FEOL and BEOL:
+ grow gate dielectric (silicon dioxide)
+ patterning of the gate
+ patterning of the source and drain regions
+ implantation or diffusion of dopants to obtain the desired complementary electrical properties









BEOL processing, back-end-of-line processing
+ Notes:
	- "back end of chip fabrication" includes:
		* packaging
		* testing
	- 2nd portion of the semiconductor manufacturing process
		* connect individual components/devices (such as transistors, capacitors, & resistors) to each other using wires on the wafer, the metalization layer
		* starts from the 1st deposited layer of metal on the metal
			+ or, when the 1st layer of metal is deposited on the wafer
		* interconnect wires
		* contacts/pads
		* insulating layers (or dielectrics, or dielectric structures)
		* metal levels
		* bonding sites for chip-to-package connections
		* vias
+ silicidation of source and drain regions an dthe polysilicon region
+ create metal interconnecting wires that are isolated by dielectric layers
	- Add a dielectric (1st, lower layer is pre-metal dielectric, PMD) to isolate eta from silicon and polysilicon
	- Process with CMP, chemical-mechanical polishing, chemical-mechanical planarization
	- make holes in PMD
		* make contacts in the holes
	- add metal layer 1
	- add a 2nd dielectric, inter-metal dielectric (IMD)
	- make vias through dielectric to connect lower metal with higher metal
		* fill vias by metal CVD process
		* repeat steps from adding metal layer to filling vias via metal CVD process to obtain all metal layers
	- add final passivation layer to protect the IC.
+ interconnects are made from subtractive aluminium
	- deposit blanket films of aluminum
	- pattern the films of aluminum
	- etch the films of aluminum, such that isolated wires are left








Wafer testing, post-BEOL, prior to die preparation (for IC packaging and IC testing)
+ synonyms of wafer testing:
	- wafer final test, WFT
	- electronic die sort, EDS
	- circuit probe, CP
+ use wafer test metrology equipment to check if prior semiconductor manufacturing steps have not damaged the wafers.
	- IC testing for functional defects,bywafer prober 
+ virtual metrology
	- for predicting wafer properties using statistical methods, without having to perform the physical measurement itself







Steps for wafer processing are:
+ wet cleans
	- cleaning by solvents, such as:
		* acetone
		* trichloroethylene
		* ultrapure water
	- piranha solution
	- RCA clean
		* performed before high-temperature processing steps of silicon wafers in semiconductor manufacturing
			+ oxidation
			+ diffusion
			+ CVD, chemical vapor deposition
		* involves the following:
			+ removal of the organic contaminants
				- organic clean + particle clean
			+ removal of thin oxide layer
				- optional oxide strip
			+ removal of ionic contamination (ionic clean)
+ surface passivation
+ photolithography
+ ion implantation
+ etching (for microfabrication)
	- dry etching
		* plasma etching
		* RIE, reactive-ion etching
			+ deep reactive-ion etching
			+ ALE, atomic layer etching
	- wet etching
		* buffered oxide etch
+ plasma ashing
+ thermal treatments
	- rapid thermal anneal
	- furnance anneals
	- thermal oxidation
+ CVD, chemical vapor deposition
+ ALD, atomic layer deposition
+ PVD, physical vapor deposition
+ MBE, molecular beam epitaxy
+ laser lift-off, LED protection
+ ECD, electrochemical deposition
	- electroplating
+ CMP, chemical-mechanical polishing, chemical-mechanical planarization
+ wafer testing
	- via automated test equipment, ATE
	- binning
	- laser trimming
+ Wright etch, or Wright-Jenkins etch






steps in wafer fabrication:
+ grow field oxide
+ etch oxide for pMOSFET
+ diffuse n-well
+ etch oxide for nMOSFET
+ grow gate oxide
+ deposit polysilicon
+ etch polysilicon and oxide
+ implant sources and drains
+ grow nitride
+ deposit metal
+ etch metal







steps for etching step/process:
+ prepare wafer
+ apply photoresist
+ align photomask
+ expose to UV light
+ develop and remove photoresist exposes to UV light
+ etch exposed oxide
+ remove remaining photoresist











Steps for die preparation are:
+ through-silicon, via semiconductor manufacturing for 3-D ICs
+ wafer mounting
+ wafer backgrinding and polishing
	- synonyms of wafer backgrinding:
		* backlap
		* backfinish
		* wafer thinning
+ wafer bonding and wafer stacking, 3-D ICs and MEMS
+ redistribution layer manufacturing, for WLCSP packages (or wafer-level packaging)
+ wafer bumping
	- for flip chip BGA, flip chip ball grid array
	- for WLCSP packages (or wafer-level packaging)
+ die cutting or wafer dicing
	- separate the dies from the wafer











Steps for IC packaging are:
+ die attachment
+ IC bonding
	- wire bonding
	- thermosonic bonding
	- flip chip, controlled collapse chip connection, C4
	- tape-automated bonding
	- down bonding
	- quilt packaging, QP
	- film attaching
	- spacing attaching
+ IC encapsulation, integrated heat spreader installation, or IHS installation
	- molding
	- baking
	- electroplating
	- baking marking, or silkscreen printing
	- trim and form
	- laser marking
+ wafer bonding
	- packaging for MEMS and NEMS
+ IC testing











Additional informations about semiconductor manufacturing:
+ self-aligned gate
	- use gate electrode as mask for doping source and drain regions, so that the source and drain regions would be "self-aligned" to gate terminal/channel/electrode
+ [Density-functional theory (DFT)](https://en.wikipedia.org/wiki/Density_functional_theory)
	- "Density-functional theory (DFT) is a computational quantum mechanical modelling method used in physics, chemistry and materials science to investigate the electronic structure (or nuclear structure) (principally the ground state) of many-body systems, in particular atoms, molecules, and the condensed phases. Using this theory, the properties of a many-electron system can be determined by using functionals, i.e. functions of another function. In the case of DFT, these are functionals of the spatially dependent electron density. DFT is among the most popular and versatile methods available in condensed-matter physics, computational physics, and computational chemistry."
+ semiconductor metrology instruments
	- Enable (statistical) quality control, or statistical process control, for the semiconductor manufacturing processes.
	- A subset of applied, technical, or industrial metrology.
	- Semiconductor inspection processes.
	- Types of semiconductor metrology instruments:
		* wafer probers
			- atomic force microscopy???
		* imaging stations
		* ellipsometers
		* CD-SEMs, critical-dimension scanning electron microscope
			- includes backscattering
				- via BSE, back-scattered electron detector
		* reflectometers
			* MBIR, model-based infrared reflectometry
		* resistance probes
		* resistance high-energy electron diffraction (RHEED) system
		* X-ray diffractometers
			+ CD-SAXS, critical-dimension X-ray scanning metrology technology
				- measures:
					* average shape of periodic nanostructures
					* edge roughness
					* pitch walking
		* technologies that I don't know how to classify:
			+ OCD metrology, optical critical dimension metrology
				- scatterometry
				- spectroscopic ellipsometry
					* non-destructive optical technique
					* can measure properties of thin-film structures in logic and memory chips
				- can be combined with TEM, transmission electron microscope, for better cost-effectiveness
				- disadvantages:
					* time consuming, hence a longer time-to-market (TTM)
					* costly
		* Examples of semiconductor metrology instruments include:
			+ ion mills
			+ C-V systems
			+ interferometers
			+ source measure units (SME) magnetometers
			+ optical and imaging systems
			+ profilometers
		* Use cases for semiconductor metrology instruments:
			+ measurement of the line width and hole diameter of a circuit pattern at a specified location of a semiconductor wafer, using CD-SEM
			+ measurement of the thickness of the thin films on the surface of a semiconductor wafer (e.g., using ellopsometer)
			+ metrology system to check the accuracy of the accuracy of the overlay (i.e., overlay tool)
			+ broadly:
				- semiconductor failure analysis
				- semiconductor physical characterization
				- semiconductor chemical characterization
				- electrostatic discharge (ESD) qualification
				- memory device metrology and analysis
				- power semiconductor device analysis
				- semiconductor manufacturing yield ramp and metrology
		* Address challenges ranging from:
			+ SADP, self-aligned double patterning
			+ SAQP, self-aligned quadruple patterning
			+ EUV lithography
			+ measurement-intensive OPC mask correction
			+ emerging 3-D architectures
			+ Facilitate statistical process control for these advanced semiconductor manufacturing technologies.
		* Recommended approach:
			+ hybrid metrology, since each category of instruments has its advantages and disadvantages
		* References:
			+ https://www.globalspec.com/learnmore/manufacturing_process_equipment/vacuum_equipment/thin_film_equipment/semiconductor_metrology_instruments
















###	Semiconductor Manufacturing Companies


Lists of semiconductor manufacturing companies:
+ [Semiconductor manufacturing companies, from Wikipedia](https://en.wikipedia.org/wiki/List_of_integrated_circuit_manufacturers)
	- https://en.wikipedia.org/wiki/Foundry_model
	- https://en.wikipedia.org/wiki/List_of_semiconductor_fabrication_plants
	- [From Wikipedia, list of the top semiconductor companies in terms of the most revenue](https://en.wikipedia.org/wiki/Semiconductor_industry)
+ [List of top semiconductor companies, from Statista Inc.](https://www.statista.com/statistics/270590/global-revenue-generated-by-semiconductor-vendors-since-2009/)
+ [Members of the Semiconductor Industry Association](https://www.semiconductors.org/about/members/)
	- [From Semiconductor Industry Association](https://www.semiconductors.org/events/a-review-of-the-2021-semiconductor-market-and-a-look-to-2022/)
+ [From Gartner, "Top 10 Semiconductor Vendors by Revenue, Worldwide, 2021"](https://www.gartner.com/en/newsroom/press-releases/2022-01-19-gartner-says-worldwide-semiconductor-revenue-grew-25-point-one-percent-in-2021-exceeding-500-billion-for-the-first-time)
+ [***2022 semiconductor industry outlook***](https://www2.deloitte.com/us/en/pages/technology-media-and-telecommunications/articles/semiconductor-industry-outlook.html)
+ [From Visual Capitalist, list of semiconductor manufacturing companies](https://www.visualcapitalist.com/top-10-semiconductor-companies-by-market-share/)




Semiconductor manufacturing companies to pay attention to:
+ Applied Materials, Inc.: Santa Clara, CA.








###	Skill Sets for Semiconductor Manufacturing



+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.

















##	Semiconductor Manufacturing Equipment Semiconductor Manufacturers



Notes about semiconductor manufacturing equipment manufacturers:
+ semiconductor metrology instruments:
	- a subset of applied, technical, or industrial metrology.







List of semiconductor manufacturing equipment manufacturers, including companies that manufacture automated test equipment (ATE, or automatic test equipment) and other electronic test equipment
+ [From Wikipedia, "Semiconductor equipment sales leaders by year"](https://en.wikipedia.org/wiki/Semiconductor_equipment_sales_leaders_by_year)
+ [companies that manufacture ATEs](https://finance.yahoo.com/news/global-automated-test-equipment-market-174500066.html)









Skill sets to work for semiconductor manufacturing equipment manufacturers
+ Thermo Fisher Scientific Inc.:
	- https://www.thermofisher.com/us/en/home/semiconductors.html.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.















