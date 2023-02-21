# person

This is Swift code defining classes and protocols to represent persons, employees, students, and athletes.

The Personne class has two properties: nom and prenom, which represent the last and first names of a person. It has an initializer to set these properties.

The Employe class inherits from Personne and has two additional properties: code and departement. It has two initializers, one without the additional properties and one with all properties.

The Eleve class also inherits from Personne and has three properties: ecole, filiere, and niveau. It has two initializers, one without the optional properties and one with all properties.

The Sportif protocol requires two methods to be implemented: getSportPrincipal() and getAutresSports(). The EleveSportif and EmployeSportif classes both conform to this protocol and add the sport and autresSports properties. They also implement the required methods.

The code creates some instances of the classes and adds the employeeSportif1 instance to an array of Sportif objects. It then iterates over the sportifs array and checks whether each object is an instance of EleveSportif or EmployeSportif. If so, it casts the object to that type and calls its methods. Finally, it prints the Sportif objects with their main sport and other sports, if any. However, there are some syntax errors in the code, such as an unclosed bracket and comments that are not properly formatted.
