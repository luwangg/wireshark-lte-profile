# Wireshark profile for LTE traffic capture and analysis
This repository provides a Wireshark configuration profile that allows the user to capture and analyze LTE (Long Term Evolution) traffic.

You can download the .ZIP file containing the configuration profile from <a href="https://github.com/davidmgarcia95/Wireshark-profile-for-LTE-traffic-capture-and-analysis/raw/master/LTE.zip">here (GitHub repository)</a>.

After you have downloaded it, unzip it. You will see a folder named LTE with several files inside it.

In order to use the profile, locate the Wireshark installation directory. In Windows systems, it should be placed in <i>C:\Program Files\Wireshark</i>. In UNIX-like systems, it should be in <i>/usr/share/wireshark</i>.

Once you have located the installation directory, open the <i>profiles</i> subdirectory, and move here the LTE folder mentioned earlier. NOTE: in UNIX-like systems, you would like to do it in a terminal and run this command with <i>sudo</i> privileges (or as root, depending on your likes):
```
mv your_downloads_directory/LTE/ /usr/share/wireshark/profiles/
```
