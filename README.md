


# Terrible Port Scanner


The Terrible Port Scanner is a simple port scanning tool written in Python. This scanner allows you to discover open ports on a target IP address or hostname.

## Features

- Scans a range of ports (50-85 by default) on the target IP address or hostname.
- Prints the open ports found during the scan.
- Provides basic error handling for potential exceptions.

## Usage

1. Ensure you have Python 3 installed on your machine.
2. Clone or download the repository to your local environment.
3. Open a terminal or command prompt.
4. Navigate to the directory where the `Tscanner.py` file is located.
5. Run the scanner using the following command:

```
python3 Tscanner.py <ip>
```

Replace `<ip>` with the target IP address or hostname you want to scan.

**Note:** The script requires only one argument, which is the target IP address or hostname. If you provide an incorrect number of arguments, an error message will be displayed.

## Example

```
$ python3 Tscanner.py example.com
--------------------------------------------------
Scanning target: 93.184.216.34
Time started: 2023-05-18 14:30:00
--------------------------------------------------
Port 53 is open
Port 80 is open
Port 443 is open
```

## Contributing

Contributions are welcome! If you have any improvements or bug fixes, feel free to open a pull request. Please ensure that your code adheres to the existing coding style and conventions.


## Disclaimer

**Use this tool responsibly and only on systems you have permission to scan. Unauthorized port scanning may violate the law. The developers of this tool are not responsible for any misuse or damage caused by this software.**
