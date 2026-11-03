# Design Your Shot

> Higgsfield lets you pick a shot. This lets you design one.

An open-source ComfyUI take on Higgsfield Cinema Studio. Instead of choosing a camera move from a preset menu, you describe your own shot, inspired by Masaaki Yuasa's ultra-wide, exaggerated-perspective camera work, and MiniMax H3 brings it to life.

## Workflow
- Load Image (first frame)
- **MiniMax H3 First-Last-Frame to Video** (core model)
- Save Video

## How to use
1. Open ComfyUI (Comfy Cloud works; partner nodes need a paid plan).
2. Load `workflow.json`.
3. Upload your first-frame image (optionally a last frame).
4. Write your camera direction in the prompt, e.g. "Ultra-wide 14mm lens, Masaaki Yuasa style, low swooping orbit, dramatic push-in."
5. Run. Output: a 5s 768P clip.

## Roadmap
- Pose capture from your own video (GVHMR mocap) into a 3D scene
- Programmable camera moves (orbit, push, crane, follow) with a true 14mm lens
- Render precise first/last frames, then generate the shot with H3

## License
MIT
