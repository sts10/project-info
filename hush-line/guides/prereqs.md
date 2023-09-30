# Hush Line Prerequisites 

1. Download Raspberry Pi Imager from https://www.raspberrypi.com/software/.
![screenshot_20230929173042](https://github.com/scidsg/project-info/assets/28545431/71212600-e64f-474d-9caa-9ba057f4081d)
![screenshot_20230929173113](https://github.com/scidsg/project-info/assets/28545431/1d813d03-9176-4f27-b553-cc490207b49e)

2. Download Tor Browser.
![screenshot_20230929173058](https://github.com/scidsg/project-info/assets/28545431/149be05c-6448-4b3e-add9-d9f386802d1e)

3. Create a Gmail account.
We'll use Gmail for their high reliability. 

4. Add the Mailvelope extention to your browser.
To decrypt Hush Line messages, we'll use a service called Mailvelope that integrates with Gmail adding PGP functionality.
![screenshot_20230929173044](https://github.com/scidsg/project-info/assets/28545431/72d84eb4-a0e1-4e3d-9a99-bbd84c4f5020)

5. Open the extension in your browser and click "Let's Start."
![screenshot_20230929173138](https://github.com/scidsg/project-info/assets/28545431/e41cdca1-f4f2-422e-9e4b-ab9da26c81ed)

6. Click "Generate Key."
Give the key a name, enter your Gmail address, and create a strong password.
![screenshot_20230929173142](https://github.com/scidsg/project-info/assets/28545431/eb6c414e-cfd6-41e4-9acc-fc5e057b8178)
![screenshot_20230929173218](https://github.com/scidsg/project-info/assets/28545431/f180932d-8103-44d3-b62e-4844f485d03b)
![screenshot_20230929173229](https://github.com/scidsg/project-info/assets/28545431/06307ea2-80fe-436e-912b-9899737bbf8d)

7. Verify your email address.
Before your key can be used you'll have to verify your email address. Back in your Gmail inbox, look for a message from `Mailvelope Key Server`.
![screenshot_20230929173256](https://github.com/scidsg/project-info/assets/28545431/df721dcd-452e-4221-ac93-f07af8da4812)

When you click on the email you'll be prompted for your Mailvelope password
![screenshot_20230929173305](https://github.com/scidsg/project-info/assets/28545431/0feb2414-97ef-46d7-8e22-606273c4e3b1)

Click the inline link to verify your email address.
![screenshot_20230929173309](https://github.com/scidsg/project-info/assets/28545431/74f5a887-8457-4f4c-a19b-5e8f3c197849)

8. Copy your PGP key.
After receiving confirmation that your email was verified, click on the supplied URL.
![screenshot_20230929173514](https://github.com/scidsg/project-info/assets/28545431/b81856e7-0e0e-469f-88a3-847e6641d10d)

Your PGP Key is in the grey box, beginning with `-----BEGIN PGP PUBLIC KEY BLOCK-----` and ending with `-----END PGP PUBLIC KEY BLOCK-----`. Copy your entire key into to notepad.
![screenshot_20230929173518](https://github.com/scidsg/project-info/assets/28545431/c755e823-3b5a-4636-8a4d-b8919b3701c2)
![screenshot_20230929173529](https://github.com/scidsg/project-info/assets/28545431/4abf344c-dff2-47c2-8af3-d8a11d8ca2bf)

🎉 Congratulations, you can now read encrypted email directly in your Gmail inbox! 
