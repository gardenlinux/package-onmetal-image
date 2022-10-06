# Garden Linux package onmetal-image

Garden Linux package build for [onmetal-image](https://github.com/onmetal/onmetal-image)

## Notes

* The upstream tarball is coming from [onmetal-image](https://github.com/onmetal/onmetal-image) itself.
  * It's uploaded to this Git repo via pristine-lfs.
  * Since there is no release published yet, the version defaults to 0.0
  * In order to simplify the package build, the upstream tarball is extended
    by a vendor directory containing all required go modules.
    * FIXME: This should be fixed by packaging all required go modules.
