# GR_Burst_PHdetection
My objective is to detect phase difference between a noisy burst of 200ms containing 500Hz and a reference 500Hz.
I'm interested in your feedback: what/how to improve the detection in this flowgraph.
<img width="1118" height="200" alt="Interest" src="https://github.com/user-attachments/assets/b4514c95-135d-4f3d-bd20-8a2ac5d86563" />

From top to bottom the flowgraph:
1. a noisy burst signal is generated (Signal of interest) based on a reference signal (SigRef).
2. A multiply conjugate transfers the difference of both signal to DC where a  phase difference is extracted and averaged.

Note that for debugging with each burst an accumulating phase shift in the Signal of interest can be set with the variable "ShiftSteps".

I'm interested in your feedback: what/how to improve the detection.
Thanks!<img width="1254" height="846" alt="Compass" src="https://github.com/user-attachments/assets/45caf970-bd20-4b3d-9cde-add3d03f71c0" />
