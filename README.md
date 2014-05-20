Sublime Jest
============

Sublime Text helpers for [Jest](http://facebook.github.io/jest/). 

For now, the package consists on snippets only, any ideas or feature requests, let me know, or add a pull request!

## Snippet example

###trigger
```
snippet
```

All snippets are also available in CoffeeScript.

## Snippets

###amf
```
jest.autoMockOff();
```

###amo
```
jest.autoMockOn();
```

###cat
```
jest.clearAllTimers();
```

###dm
```
jest.dontMock("${1:module}");${0}
```

###gmfm
```
jest.genMockFromModule(${1:moduleObj});${0}
```

###gmf
```
jest.getMockFunction();
```

###jm
```
jest.mock("${1:moduleName}");${0}
```

###rat
```
jest.runAllTicks();
```

###ratr
```
jest.runAllTimers();
```

###ropt
```
jest.runOnlyPendingTimers();
```

###sm
```
jest.setMock("${1:moduleName}", ${2:moduleExports});${0}
```
