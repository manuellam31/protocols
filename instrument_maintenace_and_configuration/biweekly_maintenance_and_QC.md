# Overview

This protocol describes the ChEM-H MCAC's planned biweekly (that means once per two weeks) maintenance procedures on the [ChEM-H MCAC](https://chemh.stanford.edu/knowledge-centers/metabolic-chemistry-analysis-center) LC-MS instruments.

# Equipment
#### PPE
Safety glasses and nitrile gloves are required for this protocol.

#### QC standard: [*HPLC gradient system diagnostics mix*](http://www.sigmaaldrich.com/catalog/product/supelco/48271?lang=en&region=US),  Sigma Aldrich catalog number `48271`, removed from glass vial and put into HPLC vial.

#### Buffers for cleaning
* 50% v/v ethanol (HPLC grade or better) in water (HPLC grade or better).  Milli-Q water qualifies as HPLC grade or better.
* (optional) 70% v/v isopropanol with 30% v/v acetone and 0.1% formic acid for column washing

# Protocol
1. Ensure you have reserved time on the appropriate ChEM-H LC-MS schedule:
	* The Agilent 6545 QTOF calendar is at [GNPN ChEM-H LC-MS Schedule](https://calendar.google.com/calendar/embed?src=gnpn.chemh.lc.ms%40gmail.com&ctz=America/Los_Angeles)
	* The Agilent 6470 QQQ calendar is at [QQQ_6470](https://calendar.google.com/calendar/embed?src=3eic0r8c6jmtdf9e350dg8cl74%40group.calendar.google.com&ctz=America/Los_Angeles)
2. Top off all chromatography buffers.  If needed, make more buffers.
3. Top off all needle wash and pump seal wash "buffers".  If needed, make more working stock of these buffers.
4. Wash an appropriate reversed phase C18 column using our [column-wash protocol](reverse_phase_column_wash_protocol.md).
6. Clean spray shield and nebulizer by sonication.
	1. Turn the instrument to standby and allow the ion source to cool.
	2. Remove spray shield from the instrument and nebulizer from the instrument. 
	3. Prepare a beaker of 50% v/v methanol in HPLC-grade water that contains enough volume to cover all spray shields.
	4. Put the solvent beaker containing the spray shield in a sonicator.    Put the nebulizer needle in a very small Erlenmeyer flask or vial _that suspends the needle in the cleaning solution without letting it touch the bottom of the container._  Sonicate for 10 - 15 minutes.
	5. Wipe all visible residue from the spray shield with a lint-free cloth or kimwipe. 
	6. If all visible residue is not removed, use 4000 sandpaper to remove remaining residue by abrasion, and repeat step 6.4.
7. Clean the ion source.  
	1. Open the ion source.
	2. Wet a lint-free cloth or kimwipe with a 50% v/v mixture of methanol (or ethanol) and water, and wipe the "left" side of the ion source (i.e. the side that hinges out from the instrument) thoroughly to remove all residue.  If available, use a teflon spray bottle for this step.
	3. Wet a lint-free cloth or kimwipe with a 50% v/v mixture of methanol and water, and wipe the "right" side of the ion source (i.e. the side that is built into the main MS box) thoroughly to remove any residue.  _Never_ use a spray bottle to clean this side of the ion source.  Bulk liquids should never be allowed to enter the MS capillary.
8. Replace the spray shield.
9. Check the condition and alignment of nebulizer needle using the nebulizer adjustment fixture supplied by Agilent. 
	* Agilent's guide to using this tool is online at [http://cn.agilent.com/cs/library/usermanuals/public/G1960-90470_NebulizerAdjustmentKit.pdf](http://cn.agilent.com/cs/library/usermanuals/public/G1960-90470_NebulizerAdjustmentKit.pdf)
	1. Remove the nebulizer.  Disconnect liquid capillaries and gas tubes, but do not remove the nebulizer needle itself.
	2. Insert the nebulizer into the adjustment fixture supplied by Agilent.
	3. Inspect the nebulizer head-on, and make sure the needle tip is centered within the injection cone void.
	4. Inspect the nebulizer top-down, and make sure the needly either slightly protrudes, or is flush with, the injection cone.
	5. Replace the nebulizer.
9. Turn on and calibrate the instrument.
	* For the QTOF, run a TOF and quadrupole check tune in both positive and negative modes.
	* For the QQQ, run an autotune.
10. Run the small molecule QC standard, saving the data in the `D:\MassHunter\data\qc\` folder, using the filename like `rp_std_<DATE>_01.d` for easy comparison of present QC data with historical data.
11. Verify that peak areas and mass spectra for standards meet expectations.
	* TODO: make this step more quantitative.

CF / cf
