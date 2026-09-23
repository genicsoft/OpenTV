# opentv
opentv
OpenTV is an open-source video generation system designed to run large-scale AI video models locally. It provides a simple command-line workflow: install, pull, and run. The initial release focuses on MiniMax H3, a multimodal model capable of generating videos up to 15 seconds in 2K resolution with native stereo audio. OpenTV automatically detects available GPU VRAM and selects an appropriate quantization tier, allowing it to operate across a range of hardware. It also includes an agent integration that enables coding agents to generate videos directly, and it uses a backend generation engine to manage model weights, hardware detection, and prompt validation. 

