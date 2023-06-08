# GENEA Challenge 2023 visualizations

This page contains the main information you need to know about the GENEA Challenge 2023 visualization tool used for evaluation of challenge stimuli.

<p align="center">
  <img src="demo.gif" alt="example from visualization server">
  <br>
  <i>Example output from the visualization server. The indicators above the speakers hint to the viewer that the speaker is engaged in "active speech".</i>
</p>

## Description
The visualization tool is an open-source project that you can access and use to render videos of your BVH files for the GENEA Challenge 2023.
The rendering takes place inside Blender, by interfacing with Blender's API through a Python script.
In order to preview the output of your gesture generation systems, you will have to use the GENEA Challenge 2023 Visualizer that is publicly available and documented in its own [GitHub repository](https://github.com/TeoNikolov/genea_visualizer).
**The GENEA Challenge evaluation will be based on this visualization pipeline**, so it will be useful to familiarize yourself with it.

## Using the visualizer

Currently, we support one way for using the GENEA visualizer, which is thoroughly documented in the [repo](https://github.com/TeoNikolov/genea_visualizer).
Please clone the repo from and follow the instructions inside the `README.md` file.

**Blender script**

Ultimately, the visualization process boils down to launching Blender, and calling its API from a Python script. This script is responsible for importing BVH data in Blender, retargeting it to the GENEA avatar, setting up the scene layout, and rendering the video. You can use this script directly inside of Blender, or through the command line. This is the most versatile way for you to experiment with the tool, and play around inside Blender!

If you have any questions, or encounter issues, please refer to the documentation in the visualizer repository, and consider opening an issue if it fails to address it. Alternatively, use the other means of communication, such as email or Slack.
