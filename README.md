# PNDemo
A demo for using push notification
<p float="left">
  <img src="https://github.com/rayray199085/PNDemo/blob/master/images/11564720432_.pic.jpg" width="30%" height="30%">
    <img src="https://github.com/rayray199085/PNDemo/blob/master/images/21564720433_.pic.jpg" width="30%" height="30%">
</p> 
---
# A demo for using push notification
----
### 1. Prepare a CSR (Certificate Signing Request)
----
### 2. Create a new App id and bind the demo project
----
### 3. Enable Push Notifications service
----
### 4. Create certificate for Development SSL Certificate. (Actually, Production SSL Certificate shoulded be created when developing a real app)
----
### 5. Use CSR to create the above certificate
----
### 6. Download the file whose name is "aps_development.cer"
----
### 7. Double click this file and import it to keychain
----
### 8. Find the new certificate in keychain and export it, in this case, its name is "Apple Development IOS Push Services: com.stephencao.project.PNDemo"
----
### 9. The file's suffix is ".p12" and password is optional, this file is used by some kinds of server.
----
### 10. Create a "iOS App Development" for this demo in Provisioning Profiles
----
### 11. Download and double click to load it
----
### 12. In Xcode, setup team first
----
### 13. Turn on push notifications settings in capabilities
----
### 14. In code signing, setup Provisioning Profile's debug option to PNDemo
----
### 15. Setup Code Signing Identity's debug option to iPhone Developer
----
### 16. Switch from targets to project and do the same settings like step 14 and 15
----
### 17. In Appdelegate, setup notification basic settings 
----
### 18. Use "http://pushtry.com" to push notification, p12 file should be uploaded
----
### 19. Or use "Easy Apns Provider" to push notification, "aps_development.cer" is necessary here
----
### 20. Device token will be print out when running the demo on a device
----
### 21. Fill notification content
----
### 22. Done!
----
