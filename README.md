# Controlled local partial-repository archive

The release asset in this repository is an inert, researcher-owned fixture for
authorized testing of Git's local partial-clone behavior. Its local Git config
contains one promisor upload-pack command that writes only the fixed text
`MUSE_GIT_CVE_2024_32004_FIRED` into its own `.git` directory and exits.

It performs no reads, network callbacks, persistence, or writes outside the
extracted fixture directory.
