# CPY Command Package

The `cpy` command is a convenient tool that allows users to send text or files to the `copy-paste.online` service directly from the command line. This README provides instructions on how to install and use the `cpy` command on CentOS 7.

## Installation

To install the `cpy` command on CentOS 7, follow these steps:

1. Download the RPM package:
   ```bash
   wget https://copy-paste.online/cmd/cpy-1.0-1.el7.x86_64.rpm
   ```

2. Install the RPM package:
   ```bash
   sudo rpm -ivh cpy-1.0-1.el7.x86_64.rpm
   ```

3. Ensure that the `jq` tool is installed, as it's a required dependency:
   ```bash
   sudo yum install jq
   ```

## Usage

To use the `cpy` command, simply provide the text or file path as an argument:

- For text:
  ```bash
  cpy "Your text here"
  ```

- For files:
  ```bash
  cpy /path/to/your/file.txt
  ```

If the operation is successful, you'll receive a message indicating the success status. For files, the message will confirm that the file paste was successful.

## Support

For any issues or questions related to the `cpy` command, please [contact us](mailto:support@copy-paste.online).
```
