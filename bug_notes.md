
# Bug Notes

1. Average calculation
   - Bug: Divided by len(marks) - 1.
   - Fix: Divide by len(marks).

2. Passing boundary
   - Bug: Used > instead of >=.
   - Fix: Use mark >= PASS_MARK.

3. Grade ordering
   - Bug: Distinction was checked after First.
   - Fix: Check average >= 90 first.
