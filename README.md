# IT Engineer Challenge
This is technical test for the IT engineer, I answerd all questions
# About the test
The test includes:
1. Pc configuration & maintenance
2. Troubleshooting
3. Cloud Migration & Management (Scaleway)
4. Cloudflare configuration
5. Global IT support
6. IT inventory & standardlization
# My goal:
To show that i can:
- Cnonfigure and support computer
- Solve technical problems
- work witch clood tools
- write the bash command :
# !/bin/bash
# Update the system
echo "Updating system..."
sudo apt update -y
sudo apt upgrade -y
# Make a backup of important folders
echo "Creating backup..."
tar -czf /tmp/backup.tar.gz /home
# Upload the backup to Scaleway 
echo "Uploading to Scaleway..."
aws s3 cp /tmp/backup.tar.gz s3://my-scaleway-bucket/
# Clean up
rm /tmp/backup.tar.gz
echo "All done!"
