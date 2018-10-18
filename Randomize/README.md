# Randomize
- Picks a random number of rows from a delimited data file.
- Parameters:
  - input: input file
  - number: number of rows to extract
  - separator: value separator (defaults to TAB)
  - header: file has header row (defaults to Y)
- Use:
  - GUI (Windows only): randomize.hta
  - Command line (from the folder that contains randomize.jar):
```
java.exe -cp .;../lib/routines.jar;../lib/log4j-1.2.16.jar;../lib/dom4j-1.6.1.jar;../lib/talendcsv.jar;../lib/talend_file_enhanced_20070724.jar;../lib/jxl.jar;randomize_0_1.jar; elan.randomize_0_1.Randomize --context_param input="..." --context_param number="..." etc.
```
