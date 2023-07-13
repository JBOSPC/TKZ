Verifying download:
--------------------------------

SHA512 hash verification:
-----------------------

1. Download tkz_7.23-1_amd64.deb, SHA512SUMS, SHA512SUMS.asc, public_key.gpg.
2. Go to the directory where files were downloaded, using cd:
For example: cd ~/Downloads 
3. Verify hash file: 
sha512sum --ignore-missing --check SHA512SUMS

Gpg signature verification:
-------------------------

4. Add public key to gpg manager:
gpg --import public_key.gpg
5. Verify gpg signature:
gpg --verify SHA512SUMS.asc SHA512SUMS
If output is positive signature will be: 'Jakub Beno (JB - OPEN - SOURCE - PROGRAMMER - COMPANY) <jbospc.tkz@gmail.com>'.

Note:
-----
If you want a public key from verified source (signature may have been corrupted), write an e-mail on jbospc.tkz@gmail.com.
