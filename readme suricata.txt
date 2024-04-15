Installation Steps

We use kali linux to install suricata in this workshop. we can also use ubuntu to install suricata. 

step1: open terminal and run the following command: sudo apt-get update

step 2: install suricata: the command is: sudo apt install suricata

step 3: sudo systemctl start suricata

step 4: we can verify the installation by using the following command: sudo suricata --status

step 5: configuring suricata. 
sudo nano /etc/suricata/suricata.yaml
(Making necessary configurations, such as network interfaces, rulesets, and logging options.)

If you feel like suricata.yaml is showing errors, you can auto setup file by: (./configure && make && sudo make install-conf) 

step 6: Restart suricata 
sudo systemctl restart suricata

