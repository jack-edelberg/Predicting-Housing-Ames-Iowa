**Categorical**
MS SubClass: Identifies the type of dwelling involved in the sale.	

        20	1-STORY 1946 & NEWER ALL STYLES
        30	1-STORY 1945 & OLDER
        40	1-STORY W/FINISHED ATTIC ALL AGES
        45	1-1/2 STORY - UNFINISHED ALL AGES
        50	1-1/2 STORY FINISHED ALL AGES
        60	2-STORY 1946 & NEWER
        70	2-STORY 1945 & OLDER
        75	2-1/2 STORY ALL AGES
        80	SPLIT OR MULTI-LEVEL
        85	SPLIT FOYER
        90	DUPLEX - ALL STYLES AND AGES
       120	1-STORY PUD (Planned Unit Development) - 1946 & NEWER
       150	1-1/2 STORY PUD - ALL AGES
       160	2-STORY PUD - 1946 & NEWER
       180	PUD - MULTILEVEL - INCL SPLIT LEV/FOYER
       190	2 FAMILY CONVERSION - ALL STYLES AND AGES

**Categorical**
MS Zoning: Identifies the general zoning classification of the sale.
		
       A	Agriculture
       C	Commercial
       FV	Floating Village Residential
       I	Industrial
       RH	Residential High Density
       RL	Residential Low Density
       RP	Residential Low Density Park 
       RM	Residential Medium Density
	
**Used as-is**
Lot Frontage: Linear feet of street connected to property

**Used as-is**
Lot Area: Lot size in square feet

**Categorical**
Street: Type of road access to property

       Grvl	Gravel	
       Pave	Paved
       	
**Categorical**
Alley: Type of alley access to property

       Grvl	Gravel
       Pave	Paved
       NA 	No alley access
		
**Categorical**
Lot Shape: General shape of property

       Reg	Regular	
       IR1	Slightly irregular
       IR2	Moderately Irregular
       IR3	Irregular
       
**OMIT, replace with Slope**
Land Contour: Flatness of the property

       Lvl	Near Flat/Level	
       Bnk	Banked - Quick and significant rise from street grade to building
       HLS	Hillside - Significant slope from side to side
       Low	Depression
		
        
**Categorical**
Utilities: Type of utilities available
		
       AllPub	All public Utilities (E,G,W,& S)
       NoSewr	Electricity, Gas, and Water (Septic Tank)
       NoSeWa	Electricity and Gas Only
       ELO	Electricity only	
	
**Categorical**   
Lot Config: Lot configuration

       Inside	Inside lot
       Corner	Corner lot
       CulDSac	Cul-de-sac
       FR2	Frontage on 2 sides of property
       FR3	Frontage on 3 sides of property
	

**Categorical**
Land Slope: Slope of property
		
       Gtl	Gentle slope
       Mod	Moderate Slope	
       Sev	Severe Slope
	
**Categorical**
Neighborhood: Physical locations within Ames city limits

       Blmngtn	Bloomington Heights
       Blueste	Bluestem
       BrDale	Briardale
       BrkSide	Brookside
       ClearCr	Clear Creek
       CollgCr	College Creek
       Crawfor	Crawford
       Edwards	Edwards
       Gilbert	Gilbert
       IDOTRR	Iowa DOT and Rail Road
       MeadowV	Meadow Village
       Mitchel	Mitchell
       NAmes	North Ames
       NoRidge	Northridge
       NPkVill	Northpark Villa
       NridgHt	Northridge Heights
       NWAmes	Northwest Ames
       OldTown	Old Town
       SWISU	South & West of Iowa State University
       Sawyer	Sawyer
       SawyerW	Sawyer West
       Somerst	Somerset
       StoneBr	Stone Brook
       Timber	Timberland
       Veenker	Veenker
			

**Categorical, combined with condition 2**
Condition 1: Proximity to various conditions
	
      Artery	Adjacent to arterial street
     Feedr	Adjacent to feeder street	
      Norm	Normal	
       RRNn	Within 200' of North-South Railroad
       RRAn	Adjacent to North-South Railroad
      PosN	Near positive off-site feature--park, greenbelt, etc.
      PosA	Adjacent to postive off-site feature
       RRNe	Within 200' of East-West Railroad
       RRAe	Adjacent to East-West Railroad
	
**Categorical, combined with condition 1**
Condition 2: Proximity to various conditions (if more than one is present)
		
      Artery	Adjacent to arterial street
     Feedr	Adjacent to feeder street	
      Norm	Normal	
       RRNn	Within 200' of North-South Railroad
       RRAn	Adjacent to North-South Railroad
      PosN	Near positive off-site feature--park, greenbelt, etc.
      PosA	Adjacent to postive off-site feature
       RRNe	Within 200' of East-West Railroad
       RRAe	Adjacent to East-West Railroad
	

**Categorical**
Bldg Type: Type of dwelling
		
     1Fam	Single-family Detached	
     2FmCon	Two-family Conversion; originally built as one-family dwelling
     Duplx	Duplex
     TwnhsE	Townhouse End Unit
     TwnhsI	Townhouse Inside Unit

    
**OMITTED, scales with SF**
House Style: Style of dwelling
	
    1Story	One story
    1.5Fin	One and one-half story: 2nd level finished
    1.5Unf	One and one-half story: 2nd level unfinished
    2Story	Two story
    2.5Fin	Two and one-half story: 2nd level finished
    2.5Unf	Two and one-half story: 2nd level unfinished
    SFoyer	Split Foyer
    SLvl	Split Level
	
**Omit**
Overall Qual: Rates the overall material and finish of the house

       10	Very Excellent
       9	Excellent
       8	Very Good
       7	Good
       6	Above Average
       5	Average
       4	Below Average
       3	Fair
       2	Poor
       1	Very Poor
	
**Numeric**
Overall Cond: Rates the overall condition of the house

       10	Very Excellent
       9	Excellent
       8	Very Good
       7	Good
       6	Above Average	
       5	Average
       4	Below Average	
       3	Fair
       2	Poor
       1	Very Poor
		

**Converted to historical = 1 if construction data < 1930**
Year Built: Original construction date

**Converted to years since remodel**
Year Remod/Add: Remodel date (same as construction date if no remodeling or additions)

**Categorical**
Roof Style: Type of roof

       Flat	Flat
       Gable	Gable
       Gambrel	Gabrel (Barn)
       Hip	Hip
       Mansard	Mansard
       Shed	Shed
		
**Categorical**
Roof Matl: Roof material

       ClyTile	Clay or Tile
       CompShg	Standard (Composite) Shingle
       Membran	Membrane
       Metal	Metal
       Roll	Roll
       Tar&Grv	Gravel & Tar
       WdShake	Wood Shakes
       WdShngl	Wood Shingles
		
**Categorical, combined with Exterior 2nd**
Exterior 1st: Exterior covering on house

       AsbShng	Asbestos Shingles
       AsphShn	Asphalt Shingles
       BrkComm	Brick Common
       BrkFace	Brick Face
       CBlock	Cinder Block
       CemntBd	Cement Board
       HdBoard	Hard Board
       ImStucc	Imitation Stucco
       MetalSd	Metal Siding
       Other	Other
       Plywood	Plywood
       PreCast	PreCast	
       Stone	Stone
       Stucco	Stucco
       VinylSd	Vinyl Siding
       Wd Sdng	Wood Siding
       WdShing	Wood Shingles
	
**Categorical, combined with Exterior 1st**
Exterior 2nd: Exterior covering on house (if more than one material)

       AsbShng	Asbestos Shingles
       AsphShn	Asphalt Shingles
       BrkComm	Brick Common
       BrkFace	Brick Face
       CBlock	Cinder Block
       CemntBd	Cement Board
       HdBoard	Hard Board
       ImStucc	Imitation Stucco
       MetalSd	Metal Siding
       Other	Other
       Plywood	Plywood
       PreCast	PreCast
       Stone	Stone
       Stucco	Stucco
       VinylSd	Vinyl Siding
       Wd Sdng	Wood Siding
       WdShing	Wood Shingles
	
**OMITTED**
Mas Vnr Type: Masonry veneer type

       BrkCmn	Brick Common
       BrkFace	Brick Face
       CBlock	Cinder Block
       None	None
       Stone	Stone
	
**OMITTED**
Mas Vnr Area: Masonry veneer area in square feet

**Converted to numeric**
Exter Qual: Evaluates the quality of the material on the exterior 
		
2      Ex	Excellent
1      Gd	Good
0      TA	Average/Typical
-1     Fa	Fair
-2     Po	Poor
		
        
**Omitted due to duplication of information (Exter Qual)**
Exter Cond: Evaluates the present condition of the material on the exterior
		
       Ex	Excellent
       Gd	Good
       TA	Average/Typical
       Fa	Fair
       Po	Poor
		

**Categorical**
Foundation: Type of foundation
		
     BrkTil	Brick & Tile
      CBlock	Cinder Block
      PConc	Poured Contrete	
      Slab	Slab
       Stone	Stone
       Wood	Wood
		
**Omitted**
Bsmt Qual: Evaluates the height of the basement

       Ex	Excellent (100+ inches)	
       Gd	Good (90-99 inches)
       TA	Typical (80-89 inches)
       Fa	Fair (70-79 inches)
       Po	Poor (<70 inches
       NA	No Basement
		
**Converted to Numeric**
Bsmt Cond: Evaluates the general condition of the basement

2       Ex	Excellent
1       Gd	Good
0       TA	Typical - slight dampness allowed
-1       Fa	Fair - dampness or some cracking or settling
-2       Po	Poor - Severe cracking, settling, or wetness
-2       NA	No Basement
	
    
**Categorical**
Bsmt Exposure: Refers to walkout or garden level walls

       Gd	Good Exposure
       Av	Average Exposure (split levels or foyers typically score average or above)	
       Mn	Mimimum Exposure
       No	No Exposure
       NA	No Basement
	
**Categorical, summed with BsmtFin Type 2**
BsmtFin Type 1: Rating of basement finished area

       GLQ	Good Living Quarters
       ALQ	Average Living Quarters
       BLQ	Below Average Living Quarters	
       Rec	Average Rec Room
       LwQ	Low Quality
       Unf	Unfinshed
       NA	No Basement
		
**OMITTED**
BsmtFin SF 1: Type 1 finished square feet

**Categorical, summed with BsmtFin Type 1**
BsmtFin Type 2: Rating of basement finished area (if multiple types)

       GLQ	Good Living Quarters
       ALQ	Average Living Quarters
       BLQ	Below Average Living Quarters	
       Rec	Average Rec Room
       LwQ	Low Quality
       Unf	Unfinshed
       NA	No Basement

**OMITTED**
BsmtFin SF 2: Type 2 finished square feet

**Omitted**
BsmtUnf SF: Unfinished square feet of basement area

**Rolled into total SF**
Total Bsmt SF: Total square feet of basement area

**Categorical**
Heating: Type of heating
		
       Floor	Floor Furnace
       GasA	Gas forced warm air furnace
       GasW	Gas hot water or steam heat
       Grav	Gravity furnace	
       OthW	Hot water or steam heat other than gas
       Wall	Wall furnace
		
**Converted to numeric**
Heating QC: Heating quality and condition

2       Ex	Excellent
1      Gd	Good
0       TA	Average/Typical
-1       Fa	Fair
-2       Po	Poor
		
**Categorical**
Central Air: Central air conditioning

0       N	No
1       Y	Yes
		
**Categorical**
Electrical: Electrical system

       SBrkr	Standard Circuit Breakers & Romex
       FuseA	Fuse Box over 60 AMP and all Romex wiring (Average)	
       FuseF	60 AMP Fuse Box and mostly Romex wiring (Fair)
       FuseP	60 AMP Fuse Box and mostly knob & tube wiring (poor)
       Mix	Mixed
		
**Rolled into total SF**
1st Flr SF: First Floor square feet

**Rolled into total SF**
2nd Flr SF: Second floor square feet

**Omitted**
Low Qual Fin SF: Low quality finished square feet (all floors)

**Omitted**
Gr Liv Area: Above grade (ground) living area square feet

**Summed with other baths**
Bsmt Full Bath: Basement full bathrooms

**Summed with other baths**
Bsmt Half Bath: Basement half bathrooms

**Summed with other baths**
Full Bath: Full bathrooms above grade

**Summed with other baths**
Half Bath: Half baths above grade

**Used as-is**
Bedroom: Bedrooms above grade (does NOT include basement bedrooms)

**Omitted**
Kitchen: Kitchens above grade

**Converted to numeric**
Kitchen Qual: Kitchen quality

2       Ex	Excellent
1       Gd	Good
0       TA	Typical/Average
-1       Fa	Fair
-2       Po	Poor
       	
        
**Omitted**
TotRms Abv Grd: Total rooms above grade (does not include bathrooms)

**Categorical**
Functional: Home functionality (Assume typical unless deductions are warranted)

       Typ	Typical Functionality
       Min1	Minor Deductions 1
       Min2	Minor Deductions 2
       Mod	Moderate Deductions
       Maj1	Major Deductions 1
       Maj2	Major Deductions 2
       Sev	Severely Damaged
       Sal	Salvage only
		
**Used as-is**
Fireplaces: Number of fireplaces

**Categorical**
Fireplace Qu: Fireplace quality

       Ex	Excellent - Exceptional Masonry Fireplace
       Gd	Good - Masonry Fireplace in main level
       TA	Average - Prefabricated Fireplace in main living area or Masonry Fireplace in basement
       Fa	Fair - Prefabricated Fireplace in basement
       Po	Poor - Ben Franklin Stove
       NA	No Fireplace
		
**Categorical**
Garage Type: Garage location
		
       2Types	More than one type of garage
       Attchd	Attached to home
       Basment	Basement Garage
       BuiltIn	Built-In (Garage part of house - typically has room above garage)
       CarPort	Car Port
       Detchd	Detached from home
       NA	No Garage
		
**Converted to garage age**        
Garage Yr Blt: Year garage was built
		
**Omitted, replaced with garage quality**        
Garage Finish: Interior finish of the garage

       Fin	Finished
       RFn	Rough Finished	
       Unf	Unfinished
       NA	No Garage
		
**Omitted, replaced with garage area**
Garage Cars: Size of garage in car capacity

**Used as-is**
Garage Area: Size of garage in square feet

**Converted to numeric**
Garage Qual: Garage quality

2       Ex	Excellent
1       Gd	Good
0       TA	Typical/Average
-1       Fa	Fair
-2       Po	Poor
-2       NA	No Garage
		
**Omitted, duplicates Garage Qual**
Garage Cond: Garage condition

       Ex	Excellent
       Gd	Good
       TA	Typical/Average
       Fa	Fair
       Po	Poor
       NA	No Garage
		
**Categorical**
Paved Drive: Paved driveway

1       Y	Paved 
0       P	Partial Pavement
-1       N	Dirt/Gravel
		
**Used as-is**
Wood Deck SF: Wood deck area in square feet

**Combined with other porches**
Open Porch SF: Open porch area in square feet

**Combined with other porches**
Enclosed Porch: Enclosed porch area in square feet

**Combined with other porches**
3Ssn Porch: Three season porch area in square feet

**Combined with other porches**
Screen Porch: Screen porch area in square feet

**Omitted**
Pool Area: Pool area in square feet

**Converted to numeric**
Pool QC: Pool quality
		
2       Ex	Excellent
1       Gd	Good
0       TA	Average/Typical
-1       Fa	Fair
-2       NA	No Pool
		
**Categorical**
Fence: Fence quality
		
       GdPrv	Good Privacy
       MnPrv	Minimum Privacy
       GdWo	Good Wood
       MnWw	Minimum Wood/Wire
       NA	No Fence
	
**Omitted, duplicated in Misc Val**
Misc Feature: Miscellaneous feature not covered in other categories
		
       Elev	Elevator
       Gar2	2nd Garage (if not described in garage section)
       Othr	Other
       Shed	Shed (over 100 SF)
       TenC	Tennis Court
       NA	None
		
**Used as-is**
Misc Val: Value of miscellaneous feature (USD)

**Used as-is**
Mo Sold: Month Sold (MM)

**Used as-is**
Yr Sold: Year Sold (YYYY)

**Omitted**
Sale Type: Type of sale
		
       WD 	Warranty Deed - Conventional
       CWD	Warranty Deed - Cash
       VWD	Warranty Deed - VA Loan
       New	Home just constructed and sold
       COD	Court Officer Deed/Estate
       Con	Contract 15% Down payment regular terms
       ConLw	Contract Low Down payment and low interest
       ConLI	Contract Low Interest
       ConLD	Contract Low Down
       Oth	Other
		
**Categorical**
Sale Condition: Condition of sale

       Normal	Normal Sale
       Abnorml	Abnormal Sale -  trade, foreclosure, short sale
       AdjLand	Adjoining Land Purchase
       Alloca	Allocation - two linked properties with separate deeds, typically condo with a garage unit	
       Family	Sale between family members
       Partial	Home was not completed when last assessed (associated with New Homes)

**Used as-is**
SalePrice: Price of Sale (USD)
