### Screenshots of VPC/VNet creation and IP reservation
#### -Azure-
<img width="1470" alt="Screenshot 2024-09-21 at 11 37 27" src="https://github.com/user-attachments/assets/bcca44c8-52fb-4ead-88ef-4157c50a4d01">

#### -GCP-
<img width="1470" alt="Screenshot 2024-09-21 at 11 48 12" src="https://github.com/user-attachments/assets/5382392f-8e7f-485f-a97d-58dc647b5963">


### Documentation of the steps taken to map the IP address to a domain in both platforms
#### -Azure-
<img width="1470" alt="Screenshot 2024-09-21 at 11 57 14" src="https://github.com/user-attachments/assets/02a16c22-f9be-4354-9707-b77ff3f05265">

1. Create a DNS Zone and input all the needed information

2. Add DNS records by navigating to + Record set and input all the needed information

3. Update the domain registrar settings by updating the name servers to point to Azure DNS

4. Verify the DNS settings and then test

#### -GCP-
<img width="1470" alt="Screenshot 2024-09-21 at 12 04 18" src="https://github.com/user-attachments/assets/0ed3d08d-6ca4-4bf7-b4a1-4ead3c5cd06d">

1. Navigate to Network Services > Cloud DNS > Create Zone. Enter all needed information

2. Add the DNS record by going to Add record set and choose the record type

3. Update the domain registrar by updating the name servers to Google's

4. Verify the DNS settings and then test

Overall, the steps for Azure and GCP are very similar; however, GCP's simple interface makes the process easier for beginners. 
