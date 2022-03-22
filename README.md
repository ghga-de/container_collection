# container_collection
A collection of general purpose docker containers.

The image recipes are located in [./images](./images/).
The version of an image can be set by updating the `.version` file
located next to each `Dockerfile`.

All images are automatically build and pushed to Docker Hub.
Please Note: To avoid overwriting existing images, the build process is performed when the specified version does not already exist on Docker Hub. Thus, please update the `.version` file whenever you would like to trigger the build process for a specific image.

