# My own custom ucore image

This image basically adds `brew` by adding the `ublue-brew` rpm package

- The image is cloned from https://github.com/ublue-os/image-template
- It uses the `brew` related stuff in `build_files/build.sh` from https://github.com/trjohnson19/ucore-brew

So, I have to say thank you to those who created the image-template and also to https://github.com/trjohnson19

Changes are basically in

- `Containerfile`
- `build_files/build.sh`

# Basic information of how to build this image

Basic information (taken from the README in the image-template repository) were copied to `README_original.md`



# Switch to this image

From your bootc system, run the following command substituting in your Github username and image name where noted.
```bash
sudo bootc switch ghcr.io/manfredlotz/ucore-ml-addons:latest
```
This should queue your image for the next reboot, which you can do immediately after the command finishes. You have officially set up your custom image! See the following section for an explanation of the important parts of the template for customization.

