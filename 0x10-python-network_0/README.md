# Project: 0x10. Python - Network #0

## Table of Contents
- [Description](#description)
- [Requirements](#requirements)
- [Scripts](#scripts)
- [Usage](#usage)
- [Advanced Tasks](#advanced-tasks)
- [Authors](#authors)
- [License](#license)

## Description
This project is part of the ALX Africa curriculum and focuses on learning about network concepts and how to interact with web resources using Python and Bash scripts. The project includesvarious tasks that involve making HTTP requests, working with cURL, and understanding the basics of URLs, HTTP methods, headers, and more.

## Requirements
- Allowed editors: vi, vim, emacs
- All scripts will be tested on Ubuntu 20.04 LTS
- Bash scripts should be exactly 3 lines long (`wc -l` file should print 3)
- All files should end with a new line
- All files must be executable
- The first line of all Bash files should be `#!/bin/bash`
- The second line of all Bash scripts should be a comment explaining what the script is doing
- All curl commands must have the option `-s` (silent mode)
- All Python scripts will be interpreted using Python 3 (version 3.8.5)
- The first line of all Python files should be `#!/usr/bin/python3`
- Code should adhere to the pycodestyle (version 2.8.*) guidelines
- All modules, classes, and functions should be documented with meaningful explanations

## Scripts
1. **0-body_size.sh**: Bash script that takes a URL, sends a request to that URL, and displays the size of the response body in bytes.
2. **1-body.sh**: Bash script that takes a URL, sends a GET request to the URL, and displays the body of the response if the response status code is 200.
3. **2-delete.sh**: Bash script that sends a DELETE request to a URL and displays the body of the response.
4. **3-methods.sh**: Bash script that takes a URL and displays all the HTTP methods that the server will accept for that URL.
5. **4-header.sh**: Bash script that takes a URL, sends a GET request to the URL, and displays the body of the response with an added header variable `X-School-User-Id: 98`.
6. **5-post_params.sh**: Bash script that takes a URL, sends a POST request to the URL with specific parameters (`email` and `subject`), and displays the body of the response.
7. **6-peak.py**: Python script that defines a function `find_peak(list_of_integers)` to find a peak in an unsorted list of integers. The script also contains information about the complexity of the algorithm.

## Usage
To use these scripts, follow the instructions provided in each task's description. Make sure to provide the necessary arguments and run the scripts on an appropriate system.

## Advanced Tasks
This project includes advanced tasks that are unlocked upon completing the mandatory tasks. These tasks involve more complex challenges related to network programming.

## Authors
- Guillaume, ALX Africa

## License
This project is licensed under the terms of the ALX License. See the [LICENSE](LICENSE) file for details.