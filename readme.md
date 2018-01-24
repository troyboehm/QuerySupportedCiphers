vi /var/tmp/ciphersupport.sh
copy and paste the entire script into the file Make note of the server IP address and port and adjust for the target.

save the file ':wq' if using vi

make the file executable.

chmod u+x /var/tmp/ciphersupport.sh
Run the file depending on your location in the directory structure

./ciphertest  <ipadderoftestmachine>
./ciphertest 10.20.4.51
or
/var/tmp/ciphertest <ipadderoftestmachine>
/var/tmp/ciphertest 10.20.4.51