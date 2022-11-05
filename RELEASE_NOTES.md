### Version 1.2.1
- attempting to fix OutOfMemory issue by using 6 threads to process files simultaneously (each thread will be allocated 250MB of memory)
- TODO: 
  - update FastQC build once `--memory` feature is release
  - set allocated memory to 20GB (1/5 of the njs node) `--memory 20000`

### Version 1.2.0
- Update FastQC to 0.11.9 (released 08-01-19)
- added Github Actions testing
- removed Travis-CI testing

### Version 1.1.1
- removed malformed html characters from ui name

### Version 1.1.0
- Update to Python 3

### Version 1.0.5
- altered citation format and created RELEASE_NOTES.md file
