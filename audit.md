
# Code Audit Report

## Files Reviewed
- student_utils.py
- test_student_utils.py

## Bugs Identified and Fixed
1. Average calculation used len(marks) - 1 instead of len(marks).
2. Passing condition used > instead of >=.
3. Distinction condition was checked after lower grade conditions.

## Verification
- Total unit tests: 9
- Expected result: All 9 tests pass.
- Tests were kept unchanged during fixes.

## Conclusion
The corrected implementation matches the specified test cases.
