Video Cutter
Overview
This Python script allows you to cut long videos into 5-second clips and store them in another directory. It uses the moviepy library to perform video processing.

Requirements
Python 3.x
moviepy library
Install the required library using the following command:

bash
Copy code
pip install moviepy
Usage
Clone the repository or download the script (video_cutter.py).

Modify the script to set the correct paths for the input and output directories:

python
Copy code
input_directory = "path/to/input/directory"
output_directory = "path/to/output/directory"
Run the script:

bash
Copy code
python video_cutter.py
The script will cut each video in the input directory into 5-second clips and save them in the specified output directory.

File Formats
The script currently supports videos in the following formats:

MP4
AVI
MKV
If your videos are in a different format, you may need to adjust the script accordingly.

Note
Ensure that the output directory exists before running the script. If it doesn't exist, the script will attempt to create it.

License
