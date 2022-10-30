# Stable-Diffusion-for-Blender
A Blender UI for Stable Diffusion. Everything runs locally on your machine, so all the power of Blender and Stable Diffusion is completely in your hands.

# Important notes:
1. This is not an add-on yet. For now, it's just a Python script you can copy and paste into a Blender file. I'm looking into converting this into an add-on.
2. This script installs Python packages to the version of Python that is built into Blender. 
3. Therefore, **it will not work for versions of Blender installed through most app stores,** and you might need to change some permissions for Blender versions that were installed through an executable. It works best on 
4. This script has only been tested on Windows 11, running Blender 3.3, extracted from a .zip file.
5. Please file an issue if you have any trouble using this script.

# Instructions
1. Copy and paste this file into Blender and run it as a script.
2. A dialog appears in the "Scene" section of the Properties editor, usually under "Rigid Body World", titled "Stable Diffusion"
3. Hit the "Install Stable Diffusion" if you haven't already done so.
4. Fill in the `prompt`, `negative_prompt`, and `filename` as desired.
5. Hit "Generate Image" to create the image. It should be a Blender image now.
