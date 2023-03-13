# [Voby](https://voby.dev)

This is voby metarepo.

## Features

Please open .meta to see list of project working on.

- **oby**: Included for debug/step into, may remove in future.
- **voby**: Voby modification for web worker,
- **voby-demo**: Demo project that split from the main repo
- ~~voby-router~~: 
- **via.js**: A fork of via.js to manipulate DOM in worker
- **via-demo**: Original demo projects in via.js but detached
- **voby-via-demo**: Original voby demo projects working in webworker (via.js)
- **vhtml**: Some modification to create text node and comment node

## Setup
Execute these in root metarepo folder

```bash
pnpm add -g meta
cd meta-voby
meta git update
```

To fetch all packages

## Update
Execute these in root metarepo folder
```bash
meta git add .
meta git commit -m "message"
meta git push
```

To fetch all packages