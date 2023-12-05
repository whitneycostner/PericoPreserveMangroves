# PericoPreserveMangroves
  Phase 1 (hydrological assessment) of mangrove restoration at Perico Preserve, Manatee County. 
  - Owner: Whitney Costner, Ecological and Marine Resources Division Manatee County

  - Project title: Mangrove Restoration Project for Perico Preserve

  - Purpose: Share raw data of hydrological assesment in complience for Tampa Bay Environmental Restoration Fund awarded in 2022

  - Date of Collection: 06.08.2023 - 10.16.2023

  - Sample Location: Perico Preserve, Manatee County FL

  - Data current as of: 12.05.2023 

  - Contact details:
        Email: whitney.costner@mymanatee.org
        Phone: (941)742-5923 ext. 6002
# Data Dictionary
  > Parameter                               Comment
    Date Time	                              Date and time of AT200 instrument reading (EDT) (mm-dd-yyyy)
    Pressure (psi)	                        Raw pressure reading from instrument
    Atm. Corrected (N/m2)                  	AT200 instrument pressure minus PSI offset converted to metric 
    Corrected Depth (m)	                    Depth = Pressure/density*acceleration due to gravity
    Corrected Depth (ft)                  	Corrected depth (m) * 3.28084
    Temp (°C)                              	AT200 instrument temperature reading
    Depth (ft)              	              AT200 instrument depth reading
    Specific Conductivity (µS/cm)           AT200 instrument specific conductivity reading
    Salinity (PSU)                         	AT200 instrument salinity reading
    Density (g/cm³)	                        AT200 instrument density reading
    Atm Pressure (mmHG)                    	Baro TROLL pressure reading
    Atm Pressure (PSI)                     	Baro TROLL pressure reading
    Atm. Temp (°C)                         	Baro TROLL temperature reading
    Baro time	                              Baro TROLL date and time of instrument reading EDT
    PSI offset                            	Atm Pressure (PSI) minus Calibration Pressure
    Water Elevation (ft) NAVD88            	Corrected depth (ft) + Sonde Elevation (ft)
    SN:                                    	Instrument serial number
    Model	                                  Instrument model
    Site	                                  Station name
    Latitude                              	Instrument latitude
    Longitude                              	Instrument longitude
    Calibration Pressure                  	Instrument zero depth pressure
    Top of Casing Cap Elevation (ft NAVD88)	Elevation measured with RTK
    Sonde Depth (inches)	                  Measurement from Casing Cap to Sensor
    Sonde Elevation (ft NAVD88)	            Top of Casing Cap Elevation minus Sonde depth (in feet)
    Total Casing Length (inches)	          Length of Casing top to bottom 
    Horizontal Accuracy (inches)	          Estimated RTK GPS horizontal accuracy reported by GPS unit (in inches)
    Vertical Accuracy (inches)	            Estimated RTK GPS vertical accuracy reported by GPS unit (in inches)
    	
    *SD1 horizontal and vertical position accuracy is approximate due to poor RTK GPS conditions.	
