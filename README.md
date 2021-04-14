# json_splitter

## Usage
Place a JSON file within the same directory as the script. The JSON file must be an Array of Objects or Multidimensional Array.

Navigate to the directory where the script exists and begin by typing python3 json-splitter.py

Enter the name of the JSON file (include the extension) when prompted, then enter the maximum number of MB for each file.

The script will complete and equally split the JSON file into the appropriate number of files to stay under the maximum size.

## Test Output
```-rwxrwxrwx 1 root root 1789 Apr 14 11:58 json-splitter.py
-rwxrwxrwx 1 root root  848 Apr 14 12:30 testjson.json
root@VRODUCTIVITY:/mnt/d/Work/Tools/json_splitter# python3 json-splitter.py
Welcome to the JSON Splitter
First, enter the name of the file you want to split
filename: testjson.json
Valid JSON file found
Enter maximum file size (MB): 1
File smaller than split size, exiting```
