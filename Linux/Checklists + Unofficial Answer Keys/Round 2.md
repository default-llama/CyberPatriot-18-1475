# Forensics Questions

## Forensics Question 1

Q: what is the welcome message when connecting to ftp

6 pts

W: `ftp localhost`

A: `220 Welcome to AFA`

## Forensics Question 2

Q: what users are locked out of ftp

6 pts

W: `sudo find / -name ftpusers`, find the file named `ftpusers`

A: `rzane` and `shuntley

# Checklist

## Disable guest accounts

`sudo nano /etc/lightdm/lightdm.conf`, `allow-guest=false`

# Remove unauthorized users

- tgianopolous
- jquelling

3 pts each

# Remove non-admins

- dscott

3 pts

## Change insecure password (FAILED)

- edarby

? pts

# Create users & make them an admin

- edarby

3 pts

## Require all users to change passwords at next login

- edarby

6 pts

## Set a default minimum password length (FAILED)

? pts

## Enable IPv4 TCP SYN Cookies (FAILED)

? pts

## Enable UFW

5 pts

## Fix insecure permissions on FTP root directory (FAILED)

? pts

## Disable OpenSSH (FAILED)

? pts

## Refresh the list of Updates Automatically

4 pts

## Install Update Automatically (FAILED)

? pts

## Install Updates from Important Security Updates

? pts

## Update Software

- Systemd
- Chromium
- Vsftpd

4 pts


## Prohibited MP3 files are removed

4 pts


## Remove Prohibited Software

- Wireshark
- Zangband
- aMule

## Prohibited software aMule removed

## Prohibited software Wireshark removed
## Prohibited software Zangband removed
## FTP users may log in with SSL

