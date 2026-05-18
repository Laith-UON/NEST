# NEST
MIT License

Copyright (c) 2026  PhD student Laith Khalid Ali,University of Nottingham  

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, and sublicense, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

NEST v2.1 (Nottingham Engine for Smartphone Timestamping) is a Python GUI tool that synchronises smartphone IMU measurements with GPS timestamps. It uses Android GnssLogger .txt files as input and generates three synchronised outputs acceleration, gyroscope, and orientation for GNSS/INS integration.




HOW TO RUN THE PROGRAM

Step 1: Save the program file
Save the program as:
NEST.exe

Step 2: Run the program
Step 3: Select the input file
In the GUI window:

      1. Click the Browse button.
      2. Select the raw GnssLogger .txt file.
      3. The selected file path will appear in the input box.

Step 4: Start the synchronisation

Click:
Synchronise (Generate ALL 3 files)
The program will start processing the selected file.

Step 5: Wait for completion

During processing, the status will show:
Processing...
When the process is complete, the status will show:
Done!

The program will also display the names of the three generated output files.
                                                 1. <input_name>_acceleration.txt
                                                 2. <input_name>_gyro.txt
                                                 3. <input_name>_orientation.txt
