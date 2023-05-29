# password_hunter
search smb shares for clear text passwords
This script automatically gets all the shares from Server1 and checks each file in each share. Replace 'Server1' with your actual server name.

Please note that the Get-SmbShare cmdlet is available on Windows 8, Windows Server 2012, and later. If you are running the script on an older version of Windows, you might need to stick to the net view command and parse its output.
