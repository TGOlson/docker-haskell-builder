Spike on creating a simple haskell build system.

#### Steps

* Copy `.env.sample` to `.env` and change any necessary values.
* Run `./build` to compile executable.
* Run `docker run -it simple` to run compiled executable.

Note: Haskell project in `work/` was generated using Stack's 'simple' template (command: `stack new simple work`).

TODO:
* How to handle multiple executables or running tests.
