# Run Script on Server

This script copies a file to a remote server and executes it using SSH.

## Prerequisites

- `bash` shell
- `scp` and `ssh` utilities
- SSH access to the remote server

## Configuration

- Modify `server_ip`, `user`, and `ssh_key` variables in the script to match your server's configuration.
- Ensure the SSH key specified in the `ssh_key` variable has the necessary permissions and is authorized on the remote server.

## Usage

```bash
./run_on_server.sh <file_to_run_in_server>
```
