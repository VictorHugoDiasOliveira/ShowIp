# ShowIp

ShowIp is a simple utility to display the IP address of your system's primary network interface.

## Setup Instructions

Follow the steps below to configure and use the myip script.

### Grant Executable Permissions

Ensure the myip script has the appropriate permissions to be executed. Run the following command:

```bash
sudo chmod +x myip
```

### Move the Script to the System Path

Move the myip script to a directory included in your system’s PATH, such as /bin/, to make it accessible from anywhere:

```bash
sudo mv myip /bin/
```

## Usage

Once configured, you can display your IP address by simply typing myip in the terminal:

```bash
myip
```