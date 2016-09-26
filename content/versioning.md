We use a purpose-molded version of ***Semantic Versioning*** to track our development. This allows us to quickly understand what is where and keep track of what is progressing and how quickly that progression is happening.

There are 3 numbers in each version number: the major version number, minor version number, and patch number, separated by periods/decimal points. [ X.X.X or Major.Minor.Patch ]

Ex. 0.0.2, 0.4.3, 0.6.0, etc.

The way this works for us is that we iterate the patch number with every edited save at least once per Forge session (at the end) where updates/changes are made. Once a level has become playable as is ready for a gameplay test (rather than just testing functionality of objectives, etc.), it receives an iteration of the minor version. The Minor Version has no bearing on whether the level is in Alpha or Beta, just that it has crossed the threshold of playability. Once a level has made it through a Beta and has received a full release, it is updated to 1.0.0.

***Progression***

The very first version is 0.0.1, with the Patch Number growing by 1 for every significant change/update/ Forge session until it reaches a playable state. The first playable version is 0.1.0. When changes are made, the Patch Number is increased, not the Minor Version Number, but once it has reached a state where it is ready for more testing, the Patch Number resets to 0 and the Minor Version Number is increased. The Major Version Number is only updated with a Full Release after the level has been through Beta Release. The level can still be updated after this as issues come to light or new Forge features are introduced (1.0.3, 1.4.0, etc.), but it is unrealistic to work towards a 2.0.0 as there really is no such thing in this type of development.

***Rule of Thumb:*** Any version with a Patch Number other than 0 is not considered playable, though it may function. Essentially, if you intend for it to be tested, the Patch Number should be 0.

---

So versioning... a VERY important concept. This should be figured out across the board so everyone working with everyone else understands the standard and can just know what each version means.

So first things first, I wanted to introduce everyone to SemVer: http://semver.org/

I learned Semantic Versioning from software engineering and I think it is a powerful tool. Here is how I see it:

 - The first number is your Major versions, these are the versions you advertise to people they download once and have the full experience down pact. This can be Prototypes, Alphas, Betas, Release Candidates, Releases. Doesn't matter what each number means (like 0 isn't always prototype, and 1 isn't always Release). The point is the spirit and goals of the number. It is a Major release.
 - The second number is the Minor version. These are releases to a smaller extent. They are little updates to the map that are completed... feature sets if you'd like. Like "I added a ramp to the top of red base but not blue and I also updated the top center drop down". 0.4.X means you are working off of sort of the "fourth feature set" of stuff for this content, but haven't yet released something for public consumption (designated by the 0).
 - The third number is a patch number. This designates your progress on stuff. My thought process is if this ends in a 0 it is a playable version, otherwise it is still going through updates. This is the number that is incremented every time you save.

So some examples:

1.0.0 - First big playable public release
1.3.0 - Third feature set update to the first public release that is playable.
1.3.14 - The 14th update since the Third feature set... next playable update would be 1.4.0
0.0.1 - The first time you save the map.
0.1.0 - The first playable version of the map that isn't intended to be public.
0.0.123 - Still nothing to play but lots of updates to it (don't do this).

I've also wanted to introduce the concept of Rough Drafts like ideation on a current build. I was thinking something like 1.X.23. It isn't intended to be public it was just something where everyone jumped on and through ideas down or you put weapons to try different things or tons of infinite grenade weapon pads or something. Any thoughts on this in particular?
