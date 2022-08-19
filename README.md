I haven't done the general program yet, and all I give you are scattered tools, so unzip it before using it. Call me a master program if you need it, the kind where a program can have multiple options
Be sure to decompress first!
Here are three tools you can use, the first two are what I did
If you don't have anything, please use the "Create Certificate Tool (Installation, Signing).cmd" in the folder.
If you have a certificate with a .pfx suffix, please use the "Signing Helper (requires an existing pfx certificate).cmd" in the folder.
If you have a certificate with .cer, .crt or .spc suffix and a private key file with .pvk suffix, please use "signcode.exe" in the folder and follow the steps below:
    1. "Welcome to the Digital Signature Wizard" interface: click "Next";
    2. Select the file you want to sign on the "File Selection" interface, and then select "Next";
    3. In the "Signature Options" interface, select "Custom" (otherwise you cannot sign the self-signed certificate), and then select "Next";
    4. Click "Select from File" on the "Signing Certificate" interface, select your certificate file (if you can't find it, you can change the filter conditions, each of the three suffixes is an option), you can select multiple, and then click "Next" Page";
    5. On the "Private Key" interface, select "Private Key File on Disk", then select your private key file with the .pvk suffix, select the default for all others, and then click "Next";
    6. Next, a window for entering the private key will pop up, fill in the private key set by the certificate, fill it in correctly, and then click OK or press Enter;
    7. In the "Hash Algorithm" interface, select any algorithm and click "Next";
    8. The "Other Certificates" interface is all default, select "Next";
    9. The "Data Description" interface is optional, fill in the name and official website of the program displayed on the UAC interface;
    10. On the "Timestamp data" interface, don't move, click "Next";
    11. On the "Completing the Digital Signature Wizard" interface, select "Finish";
    12. Next, a window for entering the private key will pop up, fill in the private key set by the certificate, fill it in correctly, and then select OK or press Enter;
    13. Next, a message box will pop up. If it says "Digital Signature Wizard has been successfully completed", the signature is successful;
    14. If the UAC window still displays "Unverified Publisher" after the signing is successful, please install your self-signed certificate in the system (directly open the certificate file or use "Certificate Installation Tool.cmd").
