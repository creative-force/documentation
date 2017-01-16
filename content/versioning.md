# Importance of Versioning

Keeping track of changes has always been important even when you work on your own. Keeping track of the last modified date or the last few changes that were made have always helped individuals pick up where they left of. On a team, it becomes increasingly important to manage when changes happen to ensure that additional work is not done resulting in people wasting their time.

Versioning is not a standard in the Forge community, so we crafted our own system to improve our ability to work together.


# Semantic Versioning

We use a system inspired by ***Semantic Versioning*** (http://semver.org/) in software. In software, Semantic Versioning was introduced to communicate the level of changes that happened and the effect it would have on consumers. In our case, our consumers of the content are the other team members. We don't have a concept of backwards compatibility, so we've taken inspiration from SemVer to improve our process.


# Meaning in the Numbers

A Semantic Version is represented by three numbers:

XX.XX.XX [Major.Minor.Patch]

In our system, each number represents an important detail that helps communicate the current state of the content.

 - **Patch:** The Patch number represents a singular save. Every time a session is done by either a new individual, or a decent amount of work was put in by a person, the Patch number is incremented by one. The very first version of a piece of content is represented by **v0.0.1**, as that is the very first save of the content. This continues until the content becomes ready for playtesting. At which point we increment...
 - **Minor:** The Minor number represents a new playtestable version. When we increment the Minor number we reset the Patch number back to 0. Versions that end in a Patch number of 0 are playtestable. So the very first playtestable version is **v0.1.0**. As changes are made we continue to increment the patch number, keeping th Minor number the same until a new stable version is completed. This continues until the content is ready for a public release. At which point we increment...
 - **Major**: The Major number represents a new publicly available version. At this point, the content has gone through enough testing and modifications that it is ready for a WIP thread to be created and the content to be shared to the community. The first publicly released version is represented by **v1.0.0**. At this point we continue to make changes and and increment the Patch number for every new save, and the Minor number for every new stable playable version.


# Examples

 - **v0.0.1** - The first save of a new piece of content.
 - **v0.1.0** - The first playtestable version of a piece of content.
 - **v1.0.0** - The first publicly released version of content. May be a WIP, or something simple like a Grifball court.
 - **v0.0.14** - Content that has been change 14 times. Still not playable.
 - **v0.5.3** - The third save on the fifth playtestable version. Don't use this for testing, use **v0.5.0** instead.
 - **v1.3.0** - The third playtestable version of a publicly released WIP. This is stable because the Patch number is **0**.
 - **v2.0.0** - The second major public release, this is typically the full release of content. Sometimes content won't make it to **v2.0.0**, as it may have been released at **v1.0.0** like a Grifball court.
 - **v2.0.7** - Seven saves have happened off of the second major public release. It isn't playable at this point.
 - **v2.1.0** - More than likely an update to a fully released piece of content. Perhaps based on matchmaking feedback or the like.
