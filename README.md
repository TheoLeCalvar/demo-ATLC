This project contains a demo of our model visualization case study based on model transformation plus constraints.

The example is a very simplified class diagram.

The UML2JavaFX.atlc file contains a specification of the transformation from (a subset of) the Eclipse UML metamodel to JavaFX, accompanied by some constraints.

The src/fr/eseo/aof/example/classdiagram/UML2FX.xtend file contains an implementation of this transformation using an internal xtend-based DSL.

The latter is executable by importing the whole repository contents as an Eclipse project.
Once all required dependencies have been installed (basically latest versions of xtend & UML), the Main class can be executed as a Java application.

A video demo of this class diagram example is available on YouTube:
[![AOF + Constraints Class Diagram](https://img.youtube.com/vi/6EEQadNmsjQ/0.jpg)](https://www.youtube.com/watch?v=6EEQadNmsjQ "AOF + Constraints Class Diagram")


Videos of other projects based on our approach are also available:
- A sequence diagram demo: 
[![AOF + Constraints](https://img.youtube.com/vi/mmZyETDKnFk/0.jpg)](https://www.youtube.com/watch?v=mmZyETDKnFk "AOF + Constraints Sequence Diagram")
- A graph & edge demo: 
[![AOF + Constraints](https://img.youtube.com/vi/eo_-yCi-zyU/0.jpg)](https://www.youtube.com/watch?v=eo_-yCi-zyU "AOF + Constraints Graf")

The graph & edge demo uses some interactors to enable users to modify the source model, thus updating the view.


This project uses Cassowary-java for constraint optimization.
Sources and licence are available at https://github.com/pybee/cassowary-java

This project is distributed under the Eclipse Public License.
It can be found at http://www.eclipse.org/org/documents/epl-v10.php
