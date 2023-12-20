# Keylogger

## Overview

The Keylogger script is a Python-based tool that captures and logs keystrokes using the pynput library. It's designed to run in the background, monitoring keyboard inputs and storing them in a log file. Below is an overview of the script's features, prerequisites, installation steps, and usage instructions.

## Features

- **Keystroke Logging:** Captures and logs keystrokes made on the target machine.
- **Background Execution:** Runs discreetly in the background, unnoticed by the user.
- **Persistent Logging:** Appends keystrokes to a log file ('keyfile.txt') for later analysis.

## Prerequisites

- Python should installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).
- pynput library installed. Install it using the following command:
    ```bash
    pip install pynput
    ```

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/dinakar0745/Key-Logger.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Key-Logger
    ```

3. Install dependencies:

    ```bash
    pip install pynput
    ```

## Usage

1. Run the script:

    ```bash
    python main.py
    ```
2. Background Monitoring:
The script will silently monitor keystrokes in the background.

## Example Output

```bash
(dev) C:\Users\Dinak\Desktop\Projects\logger>python main.py
Key.shift

'H'

'e'

'l'

'l'

'o'

Key.space

Key.backspace

Key.shift_r

Key.enter

Key.ctrl_l

'\x03'
```

## Contributing

Contributions to the Keylogger-Script are welcome. Feel free to submit bug reports, feature requests, or improvements through the project repository.

## Disclaimer
The use of keyloggers for unauthorized access or any malicious intent is strictly prohibited. This script is intended for educational and ethical purposes only. Users should adhere to legal and ethical standards when utilizing this tool. The script author and contributors are not responsible for any misuse or illegal activities.