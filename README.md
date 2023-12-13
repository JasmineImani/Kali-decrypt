<p align="center">
<img src="https://i.imgur.com/uxaU4CG.png" height="30%" width="60%" alt="Kali Linux logo"/>
</p>

<h1>Kali Linux - Decrypting a file</h1>
This tutorial outlines how to decrypt a file.<br />


<h2>Environments and Technologies Used</h2>

- Oracle VirtualBox
- Kali Linux

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Decryption Steps</h2>

<p>
<img src="https://imgur.com/3rPNAr1.png" height="80%" width="80%" alt="decrypt Steps"/>
</p>
<p>
Earlier, we used the decryption key to view the plaintext content of an encrypted file, encryptiontest.cpt. Now we’ll decrypt the file itself so that its plaintext content is viewable without decryption to anyone with read access.

1. To decrypt encryptiontest.cpt, you should use the -d or –decrypt option. Run the following command to decrypt the file. (ccrypt -d encryptiontest.cpt)
2. When prompted to enter your decryption key, type new key you used for encryption, and then press Enter.
3. Run the following command to list the files to see if the decrypted file is listed. (ls)

</p>
<br />

<p>
<img src="https://imgur.com/cDyOc6Z.png" height="80%" width="80%" alt="VM Box Steps"/>
</p>
<p>

Now reopen the file in nano to confirm that the content is decrypted. Type nano encryptiontest, and then press Enter. Your file’s plaintext content is displayed, confirming that you decrypted the file.
  
</p>
<br />
