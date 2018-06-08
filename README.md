# Week 10 Lab Exercises - Gone Phishin'
## Milestone 0: Kali Gone Wild

<img width="409" alt="1" src="https://user-images.githubusercontent.com/37861847/41134742-d822c70c-6a82-11e8-988c-aa8122ff4f18.PNG"> <img width="375" alt="2" src="https://user-images.githubusercontent.com/37861847/41134755-e3bb92b0-6a82-11e8-82ce-7b689664c8b9.PNG">

In this first milestone, I reconfigured my Kali VM to run on bridged mode and ran a `ifconfig` command to verify the machine recieved a 192.168.x.x IP address. 

## Milestone 1: Hello, SET
 
 <img width="362" alt="3" src="https://user-images.githubusercontent.com/37861847/41135164-33e41882-6a85-11e8-8bce-9320294c188c.PNG">

<img width="793" alt="4" src="https://user-images.githubusercontent.com/37861847/41135170-3ab5c50c-6a85-11e8-9f78-903a6f5af15d.PNG">

In this milestone, I installed SET on my Kali VM and used it to send a phishing email to my throwaway email account as displayed above. 

## Milestone 2: Try a Real Payload

<img width="382" alt="5" src="https://user-images.githubusercontent.com/37861847/41135787-108e8b76-6a88-11e8-9acd-e0dc3d9455d3.PNG">

In this milestone, I again tried sending a test phishing email to myself but this time using a payload. However, GMail has secuirty features that look out for signatures within attachments and my test email was not able to be sent as the error displays above. The goal here was to see how it takes more than a sript kiddie to send a spear phishing email attack nowadays. 

## Milestone 3: Fakebook

<img width="882" alt="7" src="https://user-images.githubusercontent.com/37861847/41139417-3ea6c596-6a9c-11e8-8e97-d369c08d098d.PNG">

In this milestone, I ran `setookkit` and cloned Facebook's login page. The attack can executed if the external IP is sent to the victim and the victim clicks on the link and logs in using his/her credentials. The credentials will then show up on the attacks terminal. In addition, one thing to notice is once the victim enters their credentials on the spoofed website, they are redirected to the legititmate Facebook site and the victim will never know. 

## Milestone 4: Cleanup

<img width="402" alt="8" src="https://user-images.githubusercontent.com/37861847/41139676-041f0490-6a9e-11e8-92f9-f464e5f54133.PNG">

In this milestone, it was time to clean up the Kali VM to avoid security risks. So, as shown above I reconfigured the Kali VM to use NAT instead of Bridged. 


