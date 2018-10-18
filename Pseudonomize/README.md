# Pseudonimize
- Pseudonimizes a number of delimited data files.
- Optionally generates a mapping for IDs and pseudo-IDs.
- Optionally adds a random number of days to dates.
- Prerequisites:
  - Main file should have unique IDs in its first column.
  - All other files should use the first column as foreign key.
  - A maximum of 100 columns per file is supported.
- Parameters:
  - folder: should contain all files
  - input: main file with unique IDs
  - separator: value separator (defaults to TAB)
  - header: file has header row (defaults to Y)
  - dateFormat: java SimpleDateFormat value to detect dates
  - saveMapping: saves a CSV file with ID to pseudo-ID mapping (defaults to N)
- Use:
  - GUI (Windows only): pseudonomize.hta
  - Command line (from the folder that contains pseudonomize.jar):
```
java.exe -cp .;../lib/routines.jar;../lib/commons-collections-3.2.2.jar;../lib/log4j-1.2.15.jar;../lib/log4j-1.2.16.jar;../lib/dom4j-1.6.1.jar;../lib/thashfile.jar;../lib/talendcsv.jar;../lib/trove.jar;../lib/jakarta-oro-2.0.8.jar;../lib/talend_file_enhanced_20070724.jar;../lib/advancedPersistentLookupLib-1.0.jar;../lib/jboss-serialization.jar;pseudonomize_0_1.jar; elan.pseudonomize_0_1.Pseudonomize --context_param folder="..." --context_param input="..." etc.
```
