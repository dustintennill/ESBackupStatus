# ESBackupStatus
# Purpose 
For a given Elastic Cluster return a list of indexes and indicate if they are protected in an existing snapshot. 

# Usage
backupstatus.rb index_name_or_pattern 

If you want to query a specific set of indexes, include a name/pattern here - like "winlogbeat*" or "*2021*"

# Outputs 
indexname, protected (yes/no), name of snapshot protecting the index, when protection ends

## Output Formats
Readable text (default)<br>
CSV<br>
JSON<br>

# Installation
Make sure you have the ruby elasticsearch module installed. Otherwise, I'll update once I test across more systems. 

