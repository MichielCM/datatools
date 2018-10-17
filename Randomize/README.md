# Randomize
- Picks a random number of rows from a delimited data file.
- Parameters:
  - input: input file
  - number: number of rows to extract
  - separator: value separator (defaults to TAB)
  - header: file has header row (defaults to Y)
- Use:
  - GUI (Windows only): Randomizer.hta
  - Command line (from the folder that contains Randomizer.jar):
```
java.exe -cp .;../lib/routines.jar;../lib/commons-collections-3.2.2.jar;../lib/log4j-1.2.15.jar;../lib/log4j-1.2.16.jar;../lib/dom4j-1.6.1.jar;../lib/thashfile.jar;../lib/talendcsv.jar;../lib/trove.jar;../lib/jakarta-oro-2.0.8.jar;../lib/talend_file_enhanced_20070724.jar;../lib/advancedPersistentLookupLib-1.0.jar;../lib/jboss-serialization.jar;pseudonomize_0_1.jar; elan.pseudonomize_0_1.Pseudonomize --context_param input="..." --context_param number="..." etc.
```
