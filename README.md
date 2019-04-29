# Jervis Example Project

a dummy change

This project serves as a dummy project to test GitHub integration changes made
to:

- [Jervis][jervis]
- [Jenkins Bootstrap for Jervis][bootstrap]

This project template originates from [groovy-gradle-seed][kata-seed].

# Manually Building

    ./gradlew clean check cobertura groovydoc Jar

# CI building

Is described in [`.jervis.yml`](.jervis.yml) and [`Jenkinsfile`](Jenkinsfile).

Documentation for the CI build is located at:

- https://github.com/samrocketman/jervis/wiki
- https://github.com/samrocketman/jervis/wiki/Pipeline-support

[bootstrap]: https://github.com/samrocketman/jenkins-bootstrap-jervis
[jervis]: https://github.com/samrocketman/jervis
[kata-seed]: https://github.com/kata-seeds/groovy-gradle-seed
