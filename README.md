# csv_merge
Bash and Command Line CSV merge scripts plus how to install Bash on Windows

# To install Bash on Windows https://itsfoss.com/install-bash-on-windows/

# Alternatively, Windows users can use the command line.
# To do so, type "cmd" in the windows search
# The script is then "type file1.csv file2.csv > outputfile.csv"
# For more on navigating the command line on Windows https://www.digitalcitizen.life/command-prompt-how-use-basic-commands

# To launch terminal on Mac, search for "terminal" in Spotlight. For more detail https://macpaw.com/how-to/use-terminal-on-mac

# Data downloaded at https://www.faa.gov/uas/resources/public_records/uas_sightings_report/

# Bash on windows files are at  /mnt/c/Users/Ben/Documents/.

# More navigation help at https://help.ubuntu.com/community/UsingTheTerminal

# Generic script is cat file1.csv file2.csv > merged_file.csv

$ cat 1_FY2019_Q3.csv 2_FY2019_Q2.csv 3_FY2019_Q1.csv 4_FY2018_Q4.csv 5_FY2018_Q3.csv 6_FY2018_Q2.csv 7_FY2018_Q1.csv 8_FY2017_Q4.csv 9_FY2017_Q3.csv 10_FY2017_Q2.csv 11_FY2017_Q1.csv 12_FY2016_Q4.csv 13_FY2016_Q3.csv 14_FY2016_Q2_Part.csv 15_Aug2015-Jan2016.csv 16_Nov2014-Aug2015.csv > Nov2014_June2019_UAS_Sightings.csv
