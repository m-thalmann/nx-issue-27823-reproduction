# Reproduction Repo for Nx issue [27823](https://github.com/nrwl/nx/issues/27823)

https://github.com/nrwl/nx/issues/27823

## Steps to reproduce

1. Run `npx nx release --projects=package-b,package-c --dry-run` (or without the dry-run flag)
1. You will see that the version of package-a was bumped from 1.0.0 to 1.0.2 (should be 1.0.1!)
