# mafk

```
mafk gen react-app postgres-server
```

so then mafk will look for generators in node_modules with a mafk.json in them.

that JSON will describe it's name, and which files to use to generate code


```
{
  name: 'react-app',
  files: ['filename', ],
  commands: [{ name, sed or jscodemod}, ]
}
```