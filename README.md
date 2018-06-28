Intermediate filament (IF) tracking dataset
====

## General information

The dataset consists of 5 image sequences in the format TIFF. Each of them contains a ground truth trajectories at ./Sequence/[Sequence ID]/ground_truth . 
The ground truth trajectory data is stored in ZIP-files, which contain CSV-files describing the position of a filament.
The name of a CSV-file corresponds to an index of the frame in a sequence.
Each CSV-file contains two columns: x- and y-coordinate of a filament curve.

More information about the dataset is in the table below:


|  Sequence ID  | Number of Frames | Number of Annotations |  Folder Name  |
|:-------------:|:----------------:|:---------------------:|:-------------:|
| 1             | 27               | 100                   | ./Sequences/1 |
| 2             | 50               | 100                   | ./Sequences/2 |
| 3             | 50               | 50                    | ./Sequences/3 |
| 4             | 50               | 50                    | ./Sequences/4 |
| 5             | 50               | 50                    | ./Sequences/5 |


## How to pull

Currently under development
