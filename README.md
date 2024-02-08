# Workflows for ComfyUI.
## clothing-changer
### How to Use
Load an image in the *Load Image* node.
Enter prompts in the *CLIPTextEncode* nodes.
Click *Queue Prompt*
Some parameters can be adjusted to improve results or conserve VRAM.
### Non-Checkpoint Models Used
* RealESRGAN x2
* ControlNet-v1-1 (openpose; fp16)
* ControlNet-v1-1 (depth; fp16)
* ControlNet-v1-1 (normalbae; fp16) **optional**
* ViT-B SAM model
* face_yolov8m (bbox)
* hand_yolov8s (bbox)
* person_yolov8m (segm)
### Custom Nodes Used
* ComfyUI Impact Pack
* ComfyUI's ControlNet Auxiliary Preprocessors
* ImagesGrid
