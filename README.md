*#########SMTP_4*
*###DESCRIPTION* :
SMTP stands for 'Simple Mail Transfer Protocol'.It is a connection oriented,text-based network protocol.
It is responsible for feeding and forwarding e-mails from sender to recipient.

THIS IS A SMTP PROTOCOL, WHERE CLIENT SEND MORE THAN ONE EMAIL IN THE SAME SESSION. THE MAIL CONTENT IS BEEN TAKEN FROM THE FILES AND 
SUBJECT OF THE MAIL IS THE FILE NAME.
THE PROGRAM IS BEEN INVOKED AS ./ASN1.py -f<FROM EMAIL ADDRESS>-d<RECIPIENT-1 EMAIL ADDRESS>,<RECIPIENT-2 EMAIL ADDRESS>...,-i<FILE1>,
<FILE2>...,-s<SERVER IP ADDRESS>
EXAMPLE INVOCATION(CREATE TWO FILES ASSIGNMENTQ2.txt AND ASSIGNMENTQ4.txt with some contents in it)
./SMTP_4 -f sahana6@gmail.com -d swathichennakrishna@gmail.com,soujanyakrishnamurthy@gmail.com -i ASSIGNMENTQ2.txt,ASSIGNMENTQ4.txt 
-s 10.30.26.21

