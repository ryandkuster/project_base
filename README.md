## project_base
A simple project directory framework for bioinformatic analyses

## set up
Clone this framework locally for easy organization and version management of your projects. Just rename the project_base folder, initialize, and start backing up your work.

## simple storage scheme
The "analysis' and 'data' folders will typically contain raw or intermediate files that exceed the storage capacity offered by github. Place these files into the 'large_data' directories if needed.

## document your analyses
Each analysis that requires its own scripts should be assigned to the 'approach' folders provided (these are placeholder names to preserve structure). It is good to document each individual approach with its own documentation as well as corresponding scripts and markdown/notebook. Ideally, each script will give documentation relative to the 'raw_data/large_files/' directory that would require users to only have the raw data on their own instance to repeat the necessary steps.
