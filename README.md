How to verificate your download:
--------------------------------

Verificate SHA512 hash:
-----------------------

1. Download tkz_8.22-1_all.deb, SHA512SUMS, SHA512SUMS.asc, public_key.gpg.
2. Go to the directory where files was downloaded:
For example: cd /home/user/Downloads 
3. Verificate hash file: 
sha256sum --ignore-missing --check SHA512SUMS
If output is: "tkz_12.22-1_all.deb: OK" file is not corrupted.

Verificate gpg signature:
-------------------------

4. Add public key to gpg manager:
gpg --import public_key.gpg
5. Verify gpg signature:
gpg --verify SHA512SUMS.asc SHA512SUMS
If output is positive and signature was made by ,,Jakub Beno (JB - OPEN - SOURCE - PROGRAMMER - COMPANY) <jbospc.tkz@gmail.com>'' file was downloaded from verified source.

Note:
-----
If you want a public key from verified source (signature may have been corrupted), write an e-mail to provided adress.
