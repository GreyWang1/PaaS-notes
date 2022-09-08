#commit
git add *
git commit -m "20220120 - readme"
git push -u origin master

#update
git pull origin master


##if error
#fatal: unable to access 'https://github.com/GreyWang1/PaaS-notes.git/':
#OpenSSL SSL_read: Connection was reset, errno 10054
git config --global http.sslVerify "false"
