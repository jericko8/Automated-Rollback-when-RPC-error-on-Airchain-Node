# Automated Rollback When RPC Error on Airchain Node

This script helps you perform an automatic rollback when the Airchain node encounters an RPC problem.

## Getting Started

### Prerequisites

- A Unix-based operating system (Linux, macOS)
- `wget` installed
- `screen` installed

### Installation

1. **Download the Script**

   Download the script using `wget`:

   ```bash
   wget https://raw.githubusercontent.com/jericko8/Automated-Rollback-when-RPC-error-on-Airchain-Node/main/monitoring_log.sh
   ```

2. **Make the Script Executable**

   After downloading, ensure the script is executable:

   ```bash
   chmod +x monitoring_log.sh
   ```

3. **Create a Screen Session**

   Create a new screen session to run the program:

   ```bash
   screen -S monitoring
   ```

4. **Run the Script**

   Once in the screen session, you can run the script:

   - If the script is in the current directory:

     ```bash
     ./monitoring_log.sh
     ```

   - If the script is in a different directory, provide the path:

     ```bash
     /path/to/directory/monitoring_log.sh
     ```

## Usage

- To detach from the screen session while leaving the script running, press `Ctrl + A`, then `D`.
- To reattach to the screen session later, use:

  ```bash
  screen -r monitoring
  ```

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

### Example Code Block

```bash
# Download the script
wget https://raw.githubusercontent.com/jericko8/Automated-Rollback-when-RPC-error-on-Airchain-Node/main/monitoring_log.sh

# Make it executable
chmod +x monitoring_log.sh

# Create a screen session
screen -S monitoring

# Run the script
./monitoring_log.sh
```

Dengan menekan Enter di dalam blok kode yang dibungkus dengan tiga backticks (```), Markdown akan mengenali baris baru dan memformatnya sesuai dengan yang diharapkan. Ini membuat README Anda tetap rapi dan mudah dibaca.
