```Techniques and publicly available sources used to analyze email addresses for identification, correlation, exposure, and verification purposes.```

### ▶ 📧 Email OSINT Methodology & Mindset:                

    - Emails are identifiers, not proof of identity   
    - Correlation matters more than single results  
    - Always verify findings across multiple sources  
    - Avoid assumptions based on username similarity   


### ▶  Where Email OSINT Is Used:       

    - Online identity research   
    - Breach exposure analysis   
    - Username correlation    
    - Subject's online presence   
    - Linked accounts   
    - Investigative journalism and research
    
<br>
<br>

● If you want to check whether an email really exist or not, just try logging in through that Email and click forgot Password:  
         - If you get message like "reset link sent..." or "check your Recovery Mail...", it means , that email id is Valid.        

● In some email interfaces (e.g., Gmail), typing an email address in the recipient field may display a profile image or initial if the account has a public profile.   
                            
            
● To find the activity of an email and also the associated unique id , try **[Epieos](https://epieos.com/)**        
         - It gives "Google maps" and "Google plus" activity of the Email in addition to other features in free version.  
         - pro version offers several other features.  

● For checking whether a Email is active or not, try **[Verifalia](https://verifalia.com/validate-email)**          
         - Enter the email address and it will tell whether the domain is valid, accoiunt is deliverable etc.

● while investigating or signing up to unnecessary sites, always go with free email service like **[Tempmail](https://temp-mail.org/en/)**        
      - allows to receive email at a temporary address that self-destructed after a certain time elapses     
      - Receive OTPs/links send on that email

● **[Maildrop](https://maildrop.cc/)** is a free disposable email address to use anytime.   

● Telegram bot for generating temporary email addresses and checking received messages - **[Tempmail bot](https://t.me/TempMail_org_bot)**

● **[ReverseWhoIs](https://osint.sh/reversewhois/)** allow you to find domain names owned by an email address.  

<br>

### 🔍 Email OSINT via Google Dorking:    
   

| **Purpose**                              | **Google Dork Query**                      | **What It Reveals**                                       |
| ---------------------------------------- | ------------------------------------------ | --------------------------------------------------------- |
| Find public mentions of an email         | `"example@gmail.com"`                      | Exact matches of the email across indexed websites        |
| Search email in public pastes            | `site:pastebin.com "example@gmail.com"`    | Possible exposure in public paste sites                   |
| Find documents containing the email      | `filetype:pdf "example@gmail.com"`         | Reports, resumes, manuals, or documents listing the email |
| Search email in source code repositories | `site:github.com "example@gmail.com"`      | Accidental commits, issues, or documentation references   |
| Search email on forums                   | `site:reddit.com "example@gmail.com"`      | Discussions or mentions in public forums                  |
| Search archived content                  | `site:web.archive.org "example@gmail.com"` | Old or removed pages still available via archive          |
| Search email on professional platforms   | `site:linkedin.com "example@gmail.com"`    | Possible professional exposure (limited visibility)       |

<br>

### ⚠️  Limitations & False Positives:

- Emails may be recycled or abandoned   
- Breach data can be outdated or inaccurate   
- Some platforms intentionally obscure results  
- Absence of data does not imply non-existence   


