# DEAK-calculus-tool
This is the compiled version of the D.EAK calculus using the Calculus toolbox, consisting of the shallow and deep Isabelle embeddings and the UI for manipulating proof tress o the D.EAK calculus.

No Isabelle installation is required, however, to run the UI, [Scala](http://www.scala-lang.org) and [Java](https://java.com/en/) need to be installed.


To run, first download the project or clone it via git, navigate to the project folder in terminal and run `./build.py` to compile the Scala and Java classes. Once compiled, run `make gui` to launch the UI.

The formalization of the strucutre and the rules of the D.EAK calculus is encoded in a [JSON file](http://github.com/goodlyrottenapple/calculus-toolbox/blob/master/DEAK.json) found in the [calculus-toolbox repository](http://github.com/goodlyrottenapple/calculus-toolbox/)
