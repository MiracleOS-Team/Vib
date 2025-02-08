<div align="center">
    <img src="logo/svg/full-mono-dark.svg#gh-light-mode-only" height="64">
    <img src="logo/svg/full-mono-light.svg#gh-dark-mode-only" height="64">
    <p>Vib  is a tool that streamlines the creation of container images. It achieves this by enabling users to define a recipe consisting of a sequence of modules, each specifying a particular action required to build the image. These actions may include installing dependencies or compiling source code.
</p>
    <hr />
</div>

## Usage

To build an image using a recipe, you can use the `vib` command:

this will parse the recipe.yml to a Containerfile, which can be used to build
the image with any container image builder, such as `docker` or `podman`.
