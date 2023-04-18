# Learn more about the project

## Run the project

1. Generate collusion facts for specific APK file:
```
python2 generate_facts.py -v -a /path/to/app.apk
```
2. Generate prolog program using previously generated collusion facts 
```
python2 generate_prolog.py -v
```
3. Detect collusion only for app sets that start with a specific app package:
```
python2 detect_collusion.py -a APP_PACKAGE prolog_program_filename collusion_kind
```
