# ALM_Win_TO_Ubuntu
Comments on your ticket :- --We have created user account on evolvingsols domain;
                           --User ID :: ALM_LT 
                           :: Password: Cybage@#2129 
                           --Email : ALM_LT@evolvingsols.com 
                           --IP Address :: 172.27.59.118/172.27.59.52 
                             has been added in authentication connector. 
                             --Kindly use your evolvingsols Login for authentication. 
                             --Server IP :: 172.27.172.202 and 
                             Port no: 25 
                             --https://webmail.evolvingsols.com/owa 
                             This ticket has been resolved. Please confirm the same and close the ticket. 
                             
From vipm to sysa
    Hello,

I have Jenkins setup on a local MAC machine. I am trying to configure email notifications for Jenkins Jobs but I am getting below errors on different ports.
a.       SMTP Server – webmail.evolvingsols.com
b.      Username/email – cybage_mcoe@evolvingsols.com
c.       Charset – UTF-8
                                                               i.      When SSL is checked:
1.       Port – 25
a.       Error – Unrecognized SSL Message, plain text connection. Could not connect to SMTP host: webmail.evolvingsols.com, port 25
2.       Port – 465
a.       Error – Connection Refused. Could not connect to SMTP host: webmail.evolvingsols.com, port 465
3.       Port – 587
a.       Error - Unrecognized SSL Message, plain text connection. Could not connect to SMTP host: webmail.evolvingsols.com, port 587
                                                             ii.      When SSL is unchecked
1.       Port – 25
a.       Error – com.sun.mail.smtp.SMTPSendFailedException: 451 5.7.3 Must issue a STARTTLS command first
2.       Port – 465
a.       Error – Connection Refused. Could not connect to SMTP host: webmail.evolvingsols.com, port 465
3.       Port – 587
a.       Error – com.sun.mail.smtp.SMTPSendFailedException: 530 5.7.1 Client was not authenticated

Please confirm if the SMTP server url is correct or not and which charset and port do I need to use to connect to evolvingsols.com. Also let me know if I am missing something
