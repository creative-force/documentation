We use a purpose-molded version of ***Semantic Versioning*** to track our development. This allows us to quickly understand what is where and keep track of what is progressing and how quickly that progression is happening.

There are 3 numbers in each version number: the major version number, minor version number, and patch number, separated by periods/decimal points. [ X.X.X or Major.Minor.Patch ]

Ex. 0.0.2, 0.4.3, 0.6.0, etc.

The way this works for us is that we iterate the patch number with every edited save at least once per Forge session (at the end) where updates/changes are made. Once a level has become playable as is ready for a gameplay test (rather than just testing functionality of objectives, etc.), it receives an iteration of the minor version. The Minor Version has no bearing on whether the level is in Alpha or Beta, just that it has crossed the threshold of playability. Once a level has made it through a Beta and has received a full release, it is updated to 1.0.0.

***Progression***

The very first version is 0.0.1, with the Patch Number growing by 1 for every significant change/update/ Forge session until it reaches a playable state. The first playable version is 0.1.0. When changes are made, the Patch Number is increased, not the Minor Version Number, but once it has reached a state where it is ready for more testing, the Patch Number resets to 0 and the Minor Version Number is increased. The Major Version Number is only updated with a Full Release after the level has been through Beta Release. The level can still be updated after this as issues come to light or new Forge features are introduced (1.0.3, 1.4.0, etc.), but it is unrealistic to work towards a 2.0.0 as there really is no such thing in this type of development.

***Rule of Thumb:*** Any version with a Patch Number other than 0 is not considered playable, though it may function. Essentially, if you intend for it to be tested, the Patch Number should be 0.
