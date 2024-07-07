### How much the Crab pulsar has slowed down since launch of AstroSat? Finding rate of spin down rate of Crab pulsar with AstroSat LAXPC and CZTI observations.

Crab pulsar is one of the brightest X-ray sources in the sky. It is a fast rotating neutron star with a rotation period of ~33 ms emitting pulses of radiation over the entire range of electromagnetic spectrum from radio to X-ray and Gamma-rays. As the pulsar loses energy, its rotation slows down leading to increase in rotation period. By looking at the periodicity in the emission from the Crab pulsar, the rotation period and its change with time can be obtained. For example, the Jodrell Bank Center for astrophysics keep a record of monthly rotation frequencies and their change using radio observations. <br>

Being a steady and bright X-ray source used as a standard calibration source, ISRO’s AstroSat has made several observations of the Crab since its launch in 2015. The LAXPC and CZTI instruments of AstroSat are capable to measure the X-ray pulsations from this source and can be used to measure the rotation period. If a single observation is long, it is even possible to measure rotation periods during different time intervals of the observation and measure the rate of slow down of the pulse period.<br>

## Objectives
The challenge is to use observations of the Crab pulsar over the years with AstroSat LAXPC and CZTI to measure the change in rotation period of the pulsar with time.<br>

Find out whether this spin down rate in 2015 is the same as in subsequent years or is it changing with time.<br>

If there is change in spin down rate with time, compute this rate of change and compare it against that radio measurements.<br>

## Expected Outcomes
Pulse period of Crab as a function of time for the period 2016 to 2024 with at least one point per year.

## Dataset Required:
AstroSat data is available for download from AstroSat data archive portal of Indian Space Science Data Center (ISSDC) at https://astrobrowse.issdc.gov.in/astro_archive/archive/Home.jsp See AstroSat Science Support Cell (ASSC) page at http://astrosat-ssc.iucaa.in/data_and_analysis for more details on the data analysis.

## Suggested Tools/Technologies:
It is suggested to use the AstroSat specific analysis software mentioned on the respective instrument website at the AstroSat Science Support Cell as well as standard analysis software such as HEASoft from HEASARC .

## Expected Solution / Steps to be followed to achieve the objectives:
Select long observations of Crab spanning few tens of kiloseconds in different years.<br>
In order to get the pulse profiles of fast rotating pulsars like Crab, the photon arrival times need to be corrected for relative location and velocity of the observer. This is usually done by converting the photon arrival times to that at the solar system barycentre and is known as barycentric correction.

## Evaluation Parameters:
Accuracy: Precision of the determined pulse period for individual observation.<br>
Relevance: Agreement of the pulse period derivative with the historical value of the period derivative.<br>
User Experience: Understanding of basic X-ray astronomical data reduction and timing analysis.<br>
