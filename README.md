This project contains a demo of our model visualization case study based on model transformation plus constraints.

The example is a very simplified class diagram.

The UML2JavaFX.atlc file contains a specification of the transformation from (a subset of) the Eclipse UML metamodel to JavaFX, accompanied by some constraints.

The src/fr/eseo/aof/example/classdiagram/UML2FX.xtend file contains an implementation of this transformation using an internal xtend-based DSL.

The latter is executable by importing the whole repository contents as an Eclipse project.
Once all required dependencies have been installed (basically latest versions of xtend & UML), the Main class can be executed as a Java application.

Finally, a video demo of a similar project is available on YouTube: https://www.youtube.com/watch?v=eo_-yCi-zyU
The two main differences between the video and this project are the following.
Firstly, instead of a simplified class diagram the video show a graph with nodes and edges.
Secondly, the demo from the video has some interactors that enable users to modify the source model, thus updating the view.


This project uses Cassowary-java for constraint optimization.
Sources and licence are available at https://github.com/pybee/cassowary-java

This project is distributed under the Eclipse Public License.
It can be found at http://www.eclipse.org/org/documents/epl-v10.php
