# Some Stable Diffusion Workflows for ComfyUI

## Stacked Workflow 1

[This JSON file](workflow1.json) is a snapshot of my multi-pass workflow for ComfyUI.

[ComfyUI](https://github.com/comfyanonymous/ComfyUI/)'s node graph-based system is very powerful but it can quickly descend into _noodle chaos_. I've tried to battle that in this workflow. Each column in the workflow is a stack with a particular focus: conditioning, generation, upscaling, fixing faces, hands, colour correction and so on. They are fed by a bus of common values which runs across the top of the graph. (Yes, some plugins offer pipes to improve this but they're not available _everywhere_...)

![Workflow 1 screenshot](workflow1-screenshot.png)

Example output. This PNG also includes the workflow.

![Workflow 1 output](workflow1-output.png)

#### Dependencies

Lots and lots.


## Pixel Art

[This JSON file](pixelart.json) is an example of using tiled controlnets to upscale pixel art.

![Workflow 1 screenshot](pixelart-screenshot.png)

Example output. This PNG also includes the workflow.

![Workflow 1 output](pixelart-output.png)
