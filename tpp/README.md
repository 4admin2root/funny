# tpp
## [website](http://www.ngolde.de/tpp.html)

A simple example

The following example is very simple, showing only a fraction of tpp's features. For more examples, download tpp and have a look at the examples subdirectory.

```
--author Andreas Krennmair
--title A simple example
--date today
This is the abstract of this presentation.
It may consist of zero or more lines, and may be as long as you want.
--newpage agenda
--heading Agenda

  * Introduction

  * Concept

  * Implementation

  * Comparison with other implementations

  * Conclusions
--newpage intro
--heading Introduction

This is the introduction. And below, that's source code.

--beginoutput
#include <stdio.h>

int main(void) {
  puts("Hello World!");
  return 0;
}
--endoutput
```
tpp example.tpp
