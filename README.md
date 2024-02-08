# Workflows for ComfyUI.
## clothing-changer
### How to Use
1. Load an image in the *Load Image* node.
2. Enter prompts in the *CLIPTextEncode* nodes.
3. Click *Queue Prompt*
4. Some parameters can be adjusted to improve results or conserve VRAM.
### Non-Checkpoint Models Used (Install via ComfyUI-Manager)
* RealESRGAN x2
* ControlNet-v1-1 (openpose; fp16)
* ControlNet-v1-1 (depth; fp16)
* ControlNet-v1-1 (normalbae; fp16) **optional**
* ViT-B SAM model
* face_yolov8m (bbox)
* hand_yolov8s (bbox)
* person_yolov8m (segm)
* hair_yolov8n-seg_60.pt (segm)
### Custom Nodes (Install via ComfyUI-Manager)
* ComfyUI Impact Pack
* ComfyUI's ControlNet Auxiliary Preprocessors
* ImagesGrid
* Extended Save Image for ComfyUI
