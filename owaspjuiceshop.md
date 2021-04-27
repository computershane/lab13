# TryHackMe
  https://tryhackme.com/room/owaspjuiceshop
  
<img src="OWASP_JUICE_SHOP.png"
     alt="OWASP_JUICE_SHOP_icon"
     style="float: left; margin-right: 10px;" />

# Task 1  Open for business!
Deploy the VM attached to this task to get started! You can access this machine by using your browser-based machine, or if you're connected through OpenVPN.

Machine IP```10.2.70.52```
Attack Machine```10.10.155.208```

Once the machine has loaded, access it by copying and pasting its IP into your browser; if you're using the browser-based machine, paste the machines IP into a browser on that machine.

# Task 2  Let's go on an adventure!
Question #1: What's the Administrator's email address?

Answer-```admin@juice-sh.op```

Question #2: What parameter is used for searching? 

Answer-```q```

Question #3: What show does Jim reference in his review? 

Answer-```Star Trek```

# Task 3  Inject the juice

Question #1: Log into the administrator account!

<img src="OWASP-flag-1.png"
     alt="OWASP_JUICE_flag1_icon"
     style="float: left; margin-right: 10px;" />
     
Answer-``` 32a5e0f21372bcc1000a6088b93b458e41f0e02a```

Question #2: Log into the Bender account!

Similar to what we did in Question #1, we will now log into Bender's account! Capture the login request again, but this time we will put: bender@juice-sh.op'-- as the email. 

<img src="OWASP-flag-2.png"
     alt="OWASP_JUICE_flag2_icon"
     style="float: left; margin-right: 10px;" />

Answer-```fb364762a3c102b2db932069c0e6b78e738d4066```

# Task 4  Who broke my lock?!
Question #1: Bruteforce the Administrator account's password!

