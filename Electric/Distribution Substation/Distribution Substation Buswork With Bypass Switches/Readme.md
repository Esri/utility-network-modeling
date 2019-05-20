## GN Configuration Info
  - This is an example of modeling the low side of a Distribution Substation's buswork.  The low side is medium voltage and used in the Distribution Substation Tier.  This exampled is called a "Double Bus Double Breaker" as it contains two busses and each circuit can be feed from one of two different breakers, provding redundency.  In this example the two buses could be feed from the Power Transformer or from two different Power Transformers (not shown).  You will notice that each Breaker has "Switches" on either side of the breaker.  This allows for isolating the breaker for repairs and supports the creation of switch orders as all of the equipment involved in switching is represented in the diagram.  Also, if switching diagrams are created from OMS, this allows all of the required information to be loaded to the OMS from GIS without manipulating the GIS data.
##UN Detail Configuration Info
  - Notes
  - Advantages
     - Support for OMS or Switch Order generation
     - Support for Operational view of data, using bypass switches
  - Disadvantages
