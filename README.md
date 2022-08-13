How to verificate your download:
--------------------------------

Verificate SHA256 hash:
-----------------------

1. Download tkz_8.22-1_all.deb, SHA256SUMS, SHA256SUMS.asc, public_key.gpg.
2. Go to the directory where files was downloaded:
For example: cd /home/user/Downloads 
3. Verificate file hash: 
sha256sum --ignore-missing --check SHA256SUMS
If output is: "tkz_8.22-1_all.deb: OK" file is not corrupted.

Verificate gpg signature:
-------------------------

4. Add public key to gpg manager:
gpg --import public_key.gpg
5. Verify gpg signature:
gpg --verify SHA256SUMS.asc SHA256SUMS
If output is positive and signature was made by ,,Jakub Beno (JB - OPEN - SOURCE - PROGRAMMER - COMPANY) <jbospc.tkz@gmail.com>'' file was download from verified source.

Note:
-----
If you want a public key from verified source (someone can modify program and create their own identical signature), write to the e-mail address provided and I will send this key.
