This research presents a novel workflow for 3D character animation using pose estimation. Due to resource constraints, the workflow leverages OpenPose, a less resource-intensive alternative to DWPose, for motion capture. Similarly, SD1.5 models were used instead of the more demanding SDXL models. The workflow also incorporates IPAdapter for input handling and AnimateDiff for animation generation. Despite these compromises, the system was tested with eight combinations of motion modules and steps of ksampler, some with LCM and some without, demonstrating its efficacy in animating user-specified characters based on the user’s motion. This research contributes to the field of 3D character animation by providing a user-friendly and efficient method for character animation, even under resource constraints. Future work includes the development of a website as a wrapper for the workflow, enhancing its accessibility and practical application.