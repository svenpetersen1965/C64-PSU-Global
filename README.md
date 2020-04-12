# C64-PSU-Global
A replacement PSU for the Commodore C64, which works with 230V/115V.

<img src="https://github.com/svenpetersen1965/C64-PSU-Global/blob/master/Rev.%200/pictures/2913_psu_global.JPG" width="300" alt="C64 PSU Global  (PCB only)">

For using this PSU, a suitable enclosure is required. It must not be connected to 230V while 115V mains is selected.

This PSU is designed for a low price at a decent comfort and for providing a PSU that can be switched between 230V and 115V mains.

The testing of Rev. 0 is still preliminary. The PSU was successfully tested with all ASSYs, that I have (250407, 250425, 250466, 250469). The panel meter current measurement worked, but the reading of all panelmeters was off, because those seem to have a bad quality. In Rev. 1 (yet to be released), the current measurement was dropped. The jumpers for bridging the current measurement should be replaced with short wire bridges in Rev. 0.

The changes in <b>Rev. 1<7b> are the dropped current measurement. The freed space was used for wider copper traces. The complete documentation, test documents are released now. The documentatin of Rev. 0 will stay incomplete, most of the Rev. 1 documentation applies to Rev. 0 as well.  

Find some info on the required cable making <a href="http://tech.guitarsite.de/cable_making.html">on my website</a>

# Case
The case is designed. At 24°C room temperature the temperature measured above the transformer reached 44°C while powering an ASSY 250425 C64. This is not critical, since the critical temperature for PLA is 55°C-60°C. In case you need to operate the power supply in higher ambient temperatures, you should consider PETG or ABS for printing or install the PSU in a metal case.

The case was designed to fit the <a href="https://github.com/svenpetersen1965/Illuminated-Commmodore-logo">illuminated Commodore Logo</a> or <a href="https://github.com/svenpetersen1965/Illuminated-64-logo">64 Logo</a> (in my repository).  

<img src="https://github.com/svenpetersen1965/C64-PSU-Global/blob/master/Case/Rev%200/pictures/C64PSU_Global_2020-Jan-25_09-02-46PM-000_CustomizedView5472657207.jpg" width="300" alt="C64 PSU Global case">

Since there is a version of the PSU for 230V only and one version that can be switched between 115V and 230V, which requires a mains voltage selector switch, there are two versions for the bottom shell.

<img src="https://github.com/svenpetersen1965/C64-PSU-Global/blob/master/Case/Rev%200/pictures/C64PSU_Global_2020-Mar-13_10-27-42AM-000_CustomizedView16251881473.png" width="300" alt="C64 PSU Global bottom shells">
