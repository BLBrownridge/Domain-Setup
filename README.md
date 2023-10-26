# Domain-Setup

1. Start from the Server Manager home page and click on "Add Roles."
<img src="https://i.imgur.com/kFg1lsg.png" height="80%" width="80%"/>

2. Follow the wizard's prompts, clicking 'Next' until you reach the "Server Selection" screen. Ensure that your PC's name is selected and then click 'Next.'
<img src="https://i.imgur.com/Jko2oKP.png" height="80%" width="80%"/>

3. Choose the role 'Active Directory Domain Services' and click 'Add Feature.'
<img src="https://i.imgur.com/ih05TuW.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/HE5yMpe.png" height="80%" width="80%"/>

4. Continue to the 'Confirmation' section, and click 'Install.'
<img src="https://i.imgur.com/5NuOSWT.png" height="80%" width="80%"/>

5. After the installation is complete, click 'Close,' and you'll see on the Server home page that the role has been added.
<img src="https://i.imgur.com/Z9n1Em0.png" height="80%" width="80%"/>

Now, it's time to configure Active Directory Domain Services for use. Please note that it does not come preconfigured:

6. Click on the flag icon with a hazard symbol and select 'Promote this server to a domain.'
<img src="https://i.imgur.com/2kLLLga.png" height="80%" width="80%"/>

7. Choose 'Add forest' and provide a name for the domain (you can use any name you prefer; for example, 'testdomain.com'), and click 'Next.'
<img src="https://i.imgur.com/DCi5HGn.png" height="80%" width="80%"/>

8. Set a password for the Domain Controller (e.g., 'Password1').
<img src="https://i.imgur.com/4CCgCv2.png" height="80%" width="80%"/>

9. Continue by clicking 'Next' until you reach the installation page and then click 'Install.' The PC will restart after this step.
<img src="https://i.imgur.com/zD6fPCV.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/OyFBduZ.png" height="80%" width="80%"/>

10. If everything proceeds as expected, you should now see 'Your Domain name/Administrator' as the login option."
<img src="https://i.imgur.com/WhGmfMG.png" height="80%" width="80%"/>
