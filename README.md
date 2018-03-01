![Alt text](screenshots/success1.PNG?raw=true "category_client View")
![Alt text](screenshots/Server.PNG?raw=true "category_server View")

# Introduction

This project provides linux server environment for previous 'Build an Item Catalog Application' project
Server side configuration : Linux(ubuntu) + Apache2 + postgreSQL + python3

# Necessary meetups

i. The IP address and SSH port so your server can be accessed by the reviewer.
 * Public IP: 54.199.232.245
 * SSH port : 2200

ii. The complete URL to your hosted web application.
 * address : [http://ec2-54-199-232-245.ap-northeast-1.compute.amazonaws.com](http://ec2-54-199-232-245.ap-northeast-1.compute.amazonaws.com)
 
iii. A summary of software you installed and configuration changes made.
iv. A list of any third-party resources you made use of to complete this project.
 * `Amazon Lightsail` - accessible Ubuntu Linux server
 * Change `ufw settings` - SSH port to 2200, allow HTTP, NTP as required
 * Configure `local timezone` to UTC
 * `ssh-keygen` - key pair to login as `grader` user
 * `Apache2`, `python3 mod_wsgi` for server
 * `PostgreSQL` - Make db by psql
 * `git` - To clone the old git project `ud_nano_webdev_catalogAPI`

# Environment

* `Amazon Lightsail` basic `ubuntu` server
* Requires `Apache2`
* Requires `postgreSQL`

# Path

* All realted files are in `/var/www/FlaskApp`

# Notes to Reviewer

* -----BEGIN RSA PRIVATE KEY-----
MIIEpAIBAAKCAQEAycVg0vN89xPnr8txXkVLuB8l4nqn92s7be2kvnC1nopbNV/R
6Ywtp+KSfYvhev8/4uFBozkOa/I2HoZEpSJIj5zD0fKrQc9ENM3z/G7WHhetAVOY
7QTzhK+sE6hiJw2+roa2lCJ7653FxWdvcdJbxXgxQ5Q3vSaCNXNGuXFLFNywYHyH
84d9Dmi4Bdpw1Ybgv4z34HuUhubCnLR6uU6HWwIuZ7SegotfKtLwwiZXCvZl/Pws
0o8pQJ90V0Gp3RDo1w8kDIyhPTaRju1AWVjJrZiZpZCSTcdwVxiQ41DtAsilrIsV
DxaqwnGNs81VhmKe9AOezc9p6thBCLV2BPFSBwIDAQABAoIBAHHH4WL0NcsrKWLj
6clMcHei8P03R9LpYHkMIvPVoUWHJgoCP+Bg0To0NYGgyQVQPVmWxynhOfW7f7NU
6g7pN1vs/iw9mT+iPwc8ANOgORR9K21tE/bM7PotCm+Ha9o0EQxgIUOF8rWaofVA
8AKSqne/4KAITCpZNeIoYICgl8Np86QdBnM1FyYicPA+SuAo0LX0E621nQfoRWXu
rPG6ogrlSlh5SNTd9z4ut9YzYPgofwRW3RE6vA0p8DSy+E6Jj84bnRCzAdKNELlm
8oHIYGzGogQWiWtq/4HR4NVwGrzrtoqWNLhbcl0BTJiQhOvbHBWnrxs66nZ+3FEe
FMuTtkECgYEA4/ah5FWUueDkf4vcHMiMgDIPKEQO0SGYT0Os6PqYEFuz6H3HGTdL
nafTA52FghYntIfdEA/HOYdfa8rNZRFrtvpz2JRSyVAGQonxSnfbot9+DOrPeD7Z
BMgsIC6SuoDLdr6tTvURVYCX57qpnSrfXczdTiAsbED5k9ZZ+dmrq+ECgYEA4pYV
xxagTug1RDoTpEvnnqzkkzrpcY6RfNfeaP2lrq+7vQLDeMvwjyF+94Gimp7ce8ug
WJMY3LzNwbH4LAq66JAWop2cPMlHsvq09azEvYjuO3+2QCn1HLPz1zWJWaiovYhY
rUrR9u33iLbx0mLsooitEvWmOJFRg11poy8geucCgYBTAiPBOUiGxtVtfEgSUxSW
OaQ7TUz36fvEISh9TYLBsiK4rdQp4nCuX8X+swVCcT7UBgUBLD2nPRwJ7DcObmGC
p4A3hQsAMxuUbxZlv29Cx47mtToG1xu/GgS3Uz4qm2t7OcNx1NsS/1hRES9iA5KC
XW7YW+7RHHfE1XC+Afz5AQKBgQCE5Q4k1Kp1XVBQkdePV02kDTeK+tSMW9gM5vd1
kL8qM7vi4coQAV04NacoN4pNMbuTiByllrDQVpQ/dMhf3HM/j7MW8WX/aPZ6jPyx
0wEZQUSo9QDJpVIz4X+0y5uhUICXmW6ZRPbc4zl5oAM5J/guZAdOxXEWYHT0nUcm
BLACJQKBgQCVnyLogryyuutnsDnSJQf45V5Bs/hHcBI8DsrVKRTZS79twmlNrFTc
m69f44WYnZbSq+bBf+cQrFHg3VdTaoobpG7DsxtHIDf3vpk9+K2Fl9SkjHaPIuzf
8gAxik0YSy1t/jm73g8lf2UtWhIhsRtNWbO0EPm6+DjFMOhbcsu/+Q==
-----END RSA PRIVATE KEY-----


* PW : grader
