# Hush Line Prerequisites 

1. Raspberry Pi Imager
2. Tor Browser
3. Gmail
4. Mailvelope

## Necessary Software

### 1. Raspberry Pi Imager

Like a Macbook runs MacOS, and a Dell runs Windows, a Raspberry Pi runs Linux, which comes in many different flavors depending on your needs. Since we're using a Raspberry Pi, we'll use Raspberry Pi OS (64-bit), an operating system made just for the Pi. The Imager installs the operating system onto your microSD cardc where we'll set up Hush Line. Download it from https://www.raspberrypi.com/software/.

![1-rpi-imager](https://github.com/scidsg/project-info/assets/28545431/a426639b-a1ce-47eb-859b-c5c6d7ee5f9e)

![2-rpi-imager](https://github.com/scidsg/project-info/assets/28545431/e821ace5-4828-45fc-bf58-75d25444573d)

### 2. Tor Browser

Your Hush Line has the option to only be reachable via the Tor Browser. It's not only the most private but also the easiest to set up and deploy.

![3-tor-browser](https://github.com/scidsg/project-info/assets/28545431/dba5de25-383c-443d-b31e-8e55fc5dd8a1)

### 3. Gmail

We'll use Gmail for its high reliability. If you don't already have an account, create one. It's also not a bad idea to have an email address separate from your personal account.

#### App Passwords

Hush Line has a mail server installed to send messages to your email address. You'll need SMTP information, as well as a password. You should never use your main account password; instead, create app-specific passwords. These are essentially purpose-made 

### 4. Mailvelope

To decrypt Hush Line messages, we'll use Mailvelope, which integrates with Gmail, adding PGP functionality. You can add the extension to your browser here: https://addons.mozilla.org/en-US/firefox/addon/mailvelope/

![4-mailvelope](https://github.com/scidsg/project-info/assets/28545431/eabf6c60-50ca-40ce-b217-30fe0451cda1)

Open the extension in your browser and click "Let's Start."

![5-mailvelope](https://github.com/scidsg/project-info/assets/28545431/dd630fae-ad1e-4b0e-8760-5d3e85707f44)

## Creating Your Keys

### 5. Create your keys

Click on "Generate Keys." Give your key a name, enter your Gmail address, and create a strong password.

![6-mailvelope-setup](https://github.com/scidsg/project-info/assets/28545431/1f12555c-bf2f-4f54-8826-22460384e2cf)

![7-generate-key](https://github.com/scidsg/project-info/assets/28545431/73eb943b-5e0a-4fcd-a159-b2b688b3ab89)

![8-key-created](https://github.com/scidsg/project-info/assets/28545431/c4450938-4ab5-4446-9202-a0c2c148838d)

### 6. Verify your email address

Before using your key, you'll have to verify your email address. Look for a message from `Mailvelope Key Server` in your Gmail inbox.

![9-verify-email](https://github.com/scidsg/project-info/assets/28545431/65e11fb4-9788-4cd2-bfe3-bebed1a1d0a1)

The message is encrypted, and when opened, you'll be prompted for your Mailvelope password to read the email. After entering your password, click the link.

![10-decrypt-message](https://github.com/scidsg/project-info/assets/28545431/6cfc1efa-ddc1-4109-b7ce-72cf996e6441)

### 7. Copy your PGP key

After confirming that your email was verified, click on the supplied URL.

![11-confirmation](https://github.com/scidsg/project-info/assets/28545431/e3a55242-d5f1-47db-947b-f75d6a55809f)

Your PGP Key is in the grey box, beginning with `-----BEGIN PGP PUBLIC KEY BLOCK-----` and ending with `-----END PGP PUBLIC KEY BLOCK-----`. Copy your entire key into a notepad for easy access.

![12-public-key](https://github.com/scidsg/project-info/assets/28545431/6ba01973-8fdc-43e1-83a4-5f9152d77a66)
![13-copy-key](https://github.com/scidsg/project-info/assets/28545431/fe400d7a-8dbd-44e4-b360-4f92839caf83)

🎉 Congratulations, you can now read encrypted email directly in your Gmail inbox! 
