# Email Encryption with OpenPGP <pretty good privacy>

this a an open-source asymmetric encryption that uses 2 keys (Public and Private) to encrypt and decrypt text.

**********Note:********** OpenPGP will only work if both sender and receiver uses it.

the OpenPGP email encryption includes the following steps:

- the sender and receiver must each establish their own key pair(i.e public and private keys)
- the sender and receiver share their public keys
- the sender writes an email and encrypts it with the receiver’s public key and then sends the mail to the receiver
- the receiver receives the email and decrypts it with their private key.

# **Email Encryption and Decryption with Mailvelope**

mailvelope is a browser extension with which you can encrypt and decrypt emails using popular email accounts and web browsers. this tool performs Open PGP-compliant encryption and decryption ****

for this practice, i’ll be:

- installing mailvelope
- generating key pairs
- creating and sending an encrypted mail
- decrypting an encrypted mail

install the browser extension at: 

[Add end-to-end encryption to your webmail address with Mailvelope!](https://mailvelope.com/)

next generate key pairs

click generate key

![Untitled](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Untitled.png)

![Screenshot from 2023-05-06 00-01-54.png](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Screenshot_from_2023-05-06_00-01-54.png)

![Untitled](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Untitled%201.png)

click generate to generate another key for the receiver account

 

![Untitled](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Untitled%202.png)

login to my (sender) email account and click verify then enter your password to continue

![Untitled](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Untitled%203.png)

after inputting the correct password, the email will open

![Untitled](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Untitled%204.png)

next is to sign in gmail api to the mailvelope

click send and sign in with gmail

once completed you’ll fall back o this screen

![Untitled](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Untitled%205.png)

compose a secured mail

![Untitled](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Untitled%206.png)

it will prompt you to enter your private key (password)

![Untitled](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Untitled%207.png)

it will also prompt the receiver to enter their private key to decrypt the message

![Untitled](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Untitled%208.png)

message is decrypted

![Untitled](Email%20Encryption%20with%20OpenPGP%20pretty%20good%20privacy%205f186915001d448cac9df6b5d2c91d85/Untitled%209.png)
