# TwMonitor

QuickNDirty monitoring of kws/hashtags from twitter : send self-mails using smtp server for new tweets matching search (use of search api)

## Note :

tweets filtered if contains URL and a valid email -- filtering conditions have still to be generalized and customizable

## Use :

 - Get a twitter dev account and app token
 - Have TwitterSearch python package installed ;
 - Required conf file :
    key:$KEY
    secret:$SECRET
    token:$TOKEN
    token_secret:$TOKEN_SECRET
    mail:$MAIL
    pwd:$PASSWORD
    smtp_host:$SMTP
    smtp_port:$SMTP_PORT

 - run by hand or put in cron
  
