# PDAP
Profile Data Analysis Program that does an in depth analysis of Radiosonde Profile Data 

PDAP DEVELOPER: -----------ALEX CHAMBERS - IDAHO
Program functions:
    -Rise Rate Analysis-----------------------------(Alex Chambers-Idaho)
    -Altitude Analysis------------------------------(Alex Chambers-Idaho)
    -RI-Planetary Boundary Layer--------------------(Hannah Woody & Keaton Blair-Montana)
    -VPT-Planetary Boundary Layer-------------------(Hannah Woody & Keaton Blair-Montana)
    -PT-Planetary Boundary Layer--------------------(Hannah Woody & Keaton Blair-Montana)
    -SH-Planetary Boundary Layer--------------------(Hannah Woody & Keaton Blair-Montana)
    -Radiosonde Geo-tracking------------------------(Lauren Perla & Alex Chambers- Idaho)
    -Lapse Rate Calculations (NEEDS REFINEMENT)-----(Main: Shirley Davidson-Montana & Leah Davidson-Idaho;
        Contributors for Python Version: Alex Chambers & Malach Rivkin-Idaho)
    -Tropopause Incorperation-----------------------(Alex Chambers-Idaho)
    -Consecutive Profile Running--------------------(Keaton Blair-Montana)
    -Save to a predetermined location---------------(Keaton Blair-Montana)
    -Numerical Analysis saved to text file----------(Alex Chambers-Idaho)
                                                     
Program functions developed by members from 
    -University of Idaho
    -University of Montana
    
    Operational Instructions:
    
    1) If running Anaconda/Spyder, download indicated modules (If not Anaconda/Spyder, may need to download more than indicated)
    2) Place Profile Data into a designated folder (can have one or multiple)
    3) Run Program
    4) Windows Explorer should open- select folder containing profile to analyze
    5) Follow Instructions in python console for save features
        -If you want to save outputs, type 'Y' for yes
        -If save path should be same as folder profile came from, type 'Y' for yes
        -If you wish to save to different folder, type 'N' for no, and select folder to save to
    6) Program will run over the number of profiles in the selected folder, and save accordingly
    
    **NOTE: all graphs will include profile name in title,
            and all saved graphs and documents will include profile name in filename for easy identification
