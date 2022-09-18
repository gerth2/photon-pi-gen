This repository is used to generate base linux images, and is updated fairly infrequently. Whenever a build is done, it pulls against the latest linux kernel.

To achieve proper dependency management, we will make fixed releases and save the .iso images, then reference them from the main photonvision repo.

Photonvision release image generation is now done in the [main repository](https://github.com/photonvision/photonvision) upon tagged releases by loading the iso, updating the photonvision-specific files, and re-saving as another iso.
