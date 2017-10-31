# blog-tutorial-flat-unpacked

Hello, this is an example repository to demonstrate COPR SCM abilities.
Content of this repository is flat and unpacked.

**Flat** means there are no subpackages in the repository. In other words,
there are no subdirectories that would themselves contain a spec file.

**Unpacked** means the application source files are not packed into a tarball
that would be referenced by a Source directive in the spec file. Instead,
the sources are kept as developer made them and they will be packed into
the tarball named after 'Source0' later during the build process. We need
to get the sources packed at some point to be able to build an installable
RPM from them.
