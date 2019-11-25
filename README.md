## node-split-spawn

### javascript terminal multiplexer and command runner

### Example
```
import run from 'split-spawn';

commands = [
  ['echo', 1],
  ['ls', '-lA']
];

run(commands);
```

How to exit? *Ctrl+c* or *q*

How to see output of selected command? Use arrows (up/down then enter)


## Credits:

Most code originated from: https://github.com/tomfun/node-shell-commandor
