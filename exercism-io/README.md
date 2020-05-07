## What is this regarding?

Coding practice of [TypeScript](https://www.typescriptlang.org/) from the [Exercism.io TypeScript track](https://exercism.io/tracks/typescript).

#### Installing Exercism binary CLI

* 1st - [Go to the releases page](https://github.com/exercism/cli/releases/tag/v3.0.13).
* 2nd - Extract the file and move it to the `~/bin` folder.
* 3rd - Check the output of `~/bin/exercism`.
* 4th - Add this path to your `$PATH` by running `echo 'export PATH=~/bin:$PATH' >> ~/.bash_profile` and then reload it running `source ~/.bash_profile`
* 5th - Check if the output of `exercism` is the same of the __3rd__ step.

#### Configuring the CLI

```bash
$ exercism configure --token=<Your exercism personal token>
```

##### Solving the exercises

* 1st  
```bash
$ exercism download --exercise=hello-world --track=typescript
```

* 2nd - Solve it locally, follow the instructions given.

* 3nd  
```bash
$ exercism submit /path/to/file [/path/to/file2 ...]
```
