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