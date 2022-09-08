# Hand-gesture-volume-control

## About:

MediaPipe Hands is a high-fidelity hand and finger tracking solution.
It employs machine learning (ML) to infer 21 3D landmarks of a hand from just a single frame.
The pipeline is implemented as a MediaPipe graph that uses a hand landmark tracking subgraph from the hand landmark module, and renders using a dedicated hand renderer subgraph.
The hand landmark tracking subgraph internally uses a hand landmark subgraph from the same module and a palm detection subgraph from the palm detection module.

This project implements "mediapipe" library to detect the strategic landmarks on the hand and 
extract the coordinates of each of the points. Specific landmarks (4 and 8) are then considered for the volume control
and using inbuilt math libraries, the dynamically changing distance between these landmarks is considered as the metric 
for changing the volume of the system.
