1)CREATE TWO USER LOGIN VICTIM WITH WRONG CREDENTIALS-  CHANGE TRUE FALSE & ID'S
https://hackerone.com/reports/1709881
2)if you find a admin panel with forgot password then look response for any endpoints link with admin or fuzz those endpoints
https://hackerone.com/reports/2043552
3)ask for 2fa or otp after login with correct credentials. Try to login with correct credentials then page goes to 2fa/otp - click back & login again back again - loop mode on😂  until break something.
https://hackerone.com/reports/1747978
4)if find a option to go to the pre login page like choose cars or mars  then check video on this poc 
https://hackerone.com/reports/1063298

5)steal sso token via upload svg in some of the subdomain
https://hackerone.com/reports/265943
6)verify email bypass by look anything that's lookup email using other parameters to get the token in response. If the program is opensource check all the param in github repo.
https://0d-amr.medium.com/bypass-email-verification-in-mozilla-2ab45ac36c42
7)rate limit bypass by sending without stop the intruder😵‍💫
https://mokhansec.medium.com/the-2-200-ato-most-bug-hunters-overlooked-by-closing-intruder-too-soon-505f21d56732
