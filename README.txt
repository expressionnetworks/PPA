PATH PROFILE ANALYSIS

Usage: ppa (options)

		       -m Metric units (Default = Imperial)
		       -tla Tx latitude
		       -tlo Tx longitude (W) Positive value 0 to 360)
		       -th Tx Height
		       -rla Rx latitude
		       -rlo Rx longitude (W) Positive value 0 to 360)
		       -rh Rx Height (m or f)
		       -fz Fresnel zone clearance percentage (default = 60)
		       -f frequency for Fresnel zone calculation (MHz)
		       -w Effective radiated power in Watts. Default=0
		       -p Polarisation. Default=1 (Vertical). 0=Horizontal
		       -d sdf file directory path (overrides path in ~/.ppa_path file)
		       -x PNG graph width (default = 800)
		       -y PNG graph height (default = 200)
		       -n Normalise graph
		       -v Output value. 1=Path loss dB, 2=Rxd power dBm (default),3=Field strength dBuV/m
		       -o PNG filename. Return PNG will be called $filename_R.png

Test:
Execute the following on command line
/path/to/ppa -tla 30 -tlo 85 -rla 30.1 -rlo 85 -rh 20 -w110  -o /path/to/output -v 1

Example:
./ppa -tla 30 -tlo 85 -rla 30.1 -rlo 85 -rh 20 -w110  -o ./test/example -v 1

	Will output intermediate files to current working directory
	Will create 4 files in folder ./test:
		- example.txt
		- example.png
		- example_R.txt
		- example_R.png
