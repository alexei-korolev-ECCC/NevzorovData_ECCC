Alexei Korolev
Meteorological Research Division
Atmospheric Science and Technology Directorate
Environment and Climate Change Canada

# NevzorovData_ECCC

The in-situ data were collected by Environment and Climate Change Canada (ECCC) in collaboration with the National Research Council (NRC) on the NRC Convair-580 research aircraft equipped by: the Nevzorov probe (Korolev et al. 1998), Rosemount Icing Detector (Baumgardner and Rodi, 1989; Mazin et al. 2001), Forward Scattering Spectrometer Probe (FSSP) (Knollenberg, 1976, McFarquhar et al, 2017), Optical Array Probe 2DC (OAP-2DC) (Knollenberg, 1976; Baumgardner et al., 2017), and Optical Array Probe 2DP (OAP-2DP) (Knollenberg, 1976).

The ACSII data files contain the following variables

TIME  GMT time in format hhmmss
NevLWC  Nevzorov LWC (uncorrected) (g/m3) 
NevTWC  Nevzorov LWC (uncorrected) (g/m3)
F96LWC  FSSP LWC (2-32um) (g/m3)
F124LWC FSSP LWC (2-32um) (g/m3)
F96Con  FSSP conc (2-32um) (cm-3)
F124Con FSSP conc (2-32um) (cm-3)
ROSIC1  ramp voltage (V)  
Alt     barometric altitude (m)  
TAS     true air speed (m/s)
T       static temperature (C)
DewT    dew point tenperature (C)

Nevzorov data during calculation of LWC aand IWC should be corrected on the residual effect of ice on the LWC sensor and collection efficiency of ice of the TWC sensor. 

The methodology of Nevzorov probe data processing and phase discrimination was described in detail in (Korolev et al. 1998; Korolev and Strapp, 2002). The Nevzorov probe liquid water sensor measurements were corrected on the residual effect of ice (Korolev et al. 1998, 2003; Field et al., 2004) and the total water sensor measurements were corrected on the ice bouncing effect (Korolev et al. 2013). The Rosemount Icing Detector was used to identify the presence of the liquid phase and exclude false liquid signals in ice clouds. The FSSP was employed to identify the presence of liquid droplets smaller than 45 um in diameter. The OAP-2DC and 2DP were used for justification of the presence or absence of ice particles based on identification of non-circular shapes of their binary images. 
The thresholds for liquid water content and ice water content (IWC) were set as LWC > 0.01g m-3, IWC > 0.01g m-3, respectively. The phase composition of clouds was identified based on the assessment of the ice water fraction μ=IWC/(LWC+IWC). Thus, clouds with μ> 0.9 were considered as ice, clouds with μ< 0.1 were defined as liquid, and clouds 0.1 ≤μ≤ 0.9 were determined as mixed-phase clouds. 

The airborne data was collected during seven fiels campaigns in mid latitudes and Arctic. Below is a summury table describing the flight operations.

project	  dates	           operation base	            Lat/Lon          # flights
______________________________________________________________________________________                                                 
BASE	    Sep-Oct/1994	      Inuvik (NT)	          57N–74N,  113W–141W	  10
CFDE 1	  Feb-Mar/1995	      St. John’s (NL)	      45N–53N,  54W–63W	    12
CFDE 3	  Dec/1997-Feb/1998	  Ottawa (ON) 	        42N–50N,  71W–83W	    27
FIRE-ACE	Apr/1998	          Inuvik (NT)	          68N–76N,  133W–167W	  17
AIRS 1	  Dec/1999-Feb/2000	  Ottawa (ON)	          42N–46N,  74W–82W	    25
AIRS 1.5	Feb/2003	          Ottawa (ON)	          42N–46N,  74W–82W	    8
AIRS 2	  Nov/2003-Feb/2004 	Ottawa (ON)	          42N–46N,  74W–82W	    21
