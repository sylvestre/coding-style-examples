Using clang-format 7 rc2

Clang-format for Mozilla:
----
BasedOnStyle: Mozilla
SortIncludes: false
BreakBeforeBraces: Custom
BraceWrapping:
  AfterEnum: true
  AfterStruct: true
  AfterFunction: true
  AfterClass: true
  SplitEmptyFunction: true
----

For the others
BasedOnStyle: XXXX

$ clang-format-7 -i 
