# Chocolatey Package List
This is my personal package list.  
You can create your own with `choco export -o packages.config` to transfer all your installs to a new computer.  
I don't think my personal list is that usefull for all the people in the world. But you might find some interesting apps.


## How to Use

### Prerequisites

- Windows 11 (or Windows with PowerShell)
- [Chocolatey](https://chocolatey.org/install) installed on your machine

### Steps to Install Packages from `packages.config`

1. **Clone or download** this repository on your new PC.

2. **Open PowerShell as Administrator**.

3. **Navigate to the folder** where `packages.config` is located.

4. **Run the following command** to install all packages listed in `packages.config`:

   ```powershell
   choco install packages.config -y
