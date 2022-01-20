#commit
git add *
git commit -m "20220120 - readme"
git push -u origin master

#update
git pull origin master


##if error
#1  OpenSSL SSL_read: Connection was reset, errno 1005
git config --global http.sslVerify "false"
