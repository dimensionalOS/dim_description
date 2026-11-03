# DimOS robot descriptions

Robot model assets consumed by DimOS through `RobotDescriptionSource`. Consumers pin a Git commit for reproducible loading.

## OpenYAM single arm

`openyam_single/` contains the supplied URDF, MuJoCo MJCF, visual and collision meshes, materials, and preview. The files are preserved from the supplied `openyam_single` export. See its README for model limitations, including estimated inertials.

`SHA256SUMS` records the SHA-256 digest of every supplied file. Verify with `sha256sum --check SHA256SUMS`.
