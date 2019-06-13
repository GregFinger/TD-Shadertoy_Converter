# TD-Shadertoy_Converter

The .tox component has 6 inputs. The first input is the shader code DAT. The second input is for an audio CHOP. The remaining four are TOP inputs. These inputs can be 2D textures or cubemaps. 

The .tox component has 3 pages of custom parameters:
1. The first page sets the iChannel[0-3] inputs, which you can choose 2D Texture, Cubemap or Audio. Set these according to what the shadertoy source had setup. 
2. The second page sets the resolution of the output, has an adjustment for the speed of iTime, turns off/on mouse control (which the mouse interactivity happens within the TD window) and adjusts the gain for the audio inputs.
3. The third page is for the custom uniforms you add to the shader:

   First add any custom uniform to the shader code. Then right-click the .tox component and "Customize Component..." to launch the custom parameter window. Under the "Uniforms" page add your custom uniforms as parameters. Remember that the "label" text should be the exact same as what you add to the shader. Also the size should match your uniform size. Once you are finished adding them, click the "Set Custom Uniform" button on the actual parameters page.

The component came preloaded with this shader: https://www.shadertoy.com/view/MtXSD7
