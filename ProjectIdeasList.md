# Bareos Google Summer of Code 2024 Project Ideas List

## Standardize Debug Message Levels

The Bareos source code uses debug messages to allow detailed logging for tracing and debugging purposes.
Currently, almost all debug message calls get the level passed as a arbitrary numeric value, where generally a higher number means more details.
The idea is to create a guideline for developers that describes which level to use.
For this a comprehensive list of currently used debug-levels should be compiled by analyzing the source code.
The next step is to change all debug message calls to use a meaningful constant instead of numeric value.

**Expected outcomes**:
* Debug message guideline section added to [developer guide](https://docs.bareos.org/DeveloperGuide.html)
* Source code changed to use meaningful constants instead of numeric values

**Skills required/preferred**:
Basic C/C++, reStructuredText

**Possible entors**: arogge, pstorz

**Expected size of project**: ~90 hours (small)

**Difficulty rating**: Easy
