# dumpit-sigs


## Steps to add to mac mail:

- Create a new Signature in Mail, put something in it like “TESTING SIGNATURE”
- Close Mail program by hitting `cmd+Q`
- In finder, Go > Go To Folder > ~/Library/Mail > (The highest Version, mine is V5) > MailData > Signatures
- Sort by recently modified
- The one on top should have a uuid (Some really long string with letters and numbers) and end with .mailsignature (mine was `7661BA87-1C1B-49F8-B894-D723C25E351F.mailsignature`)
- Open this in atom / brackets - look for “TESTING SIGNATURE” or whatever you added in step 1, should be in the body somewhere
- Open your coded signature html file in Atom / brackets too
- Copy the body of your sliced Signature to the .mailsignature file replacing everything after <body ….  
- Save the signature in brackets
- Right click the .signature file in finder > Get info > Check the “Locked” box -  **super important!!**
- Restart Mail
- Add new signature to your email address
- Send test email
- Win

### Testing Locally

Use the index.html file to test with live server.

`npm install -g live-server`

then you can just run

`live-server` from the directory of the files.
