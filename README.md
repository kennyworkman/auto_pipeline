# Colony Screening for Automation 

This project was designed to automate the colony screening process after sequencing to produce data in a way that can be directly interpreted by robotics. For a tool that produces an excel spreadsheet visualization for a single user, see https://github.com/kennyworkman/visual_pipeline.


After cloning this repository, a command line command needs to be issued to make the bash script executable. Calling this executable with the desired/correct parameters will populate two .csv files, one designed as an input for downstream robotics and one of user interpretation of data.

## QuickStart

Type the following commands into your terminal to run this script.

```bash
git clone https://github.com/kennyworkman/auto_pipeline.git
cd auto_pipeline
chmod +x generate   
bash generate -d <insert path to directory here> -t <insert optional depth threshold here>
```

The script should then run and automatically open both populated .csv files upon completion. 
