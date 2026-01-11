## 🕵️ Google Dorks for OSINT
Google Dorking allows you to refine searches and uncover publicly available information that may not be easily visible through normal queries.

Google Dorking uses advanced search operators to find specific data across the web, such as exact text, exposed files like pdf, important links, sensitive directories, and more.  
You just need to type your query with a little bit of operators and words and search results will narrow down from Millions to Thousands.  


| Operator   | Description                         | Example                 |
|------------|-------------------------------------|-------------------------|
| `site:`    | Search within a specific site      | `site:example.com`      |
| `intitle:` | Find pages with specific words in the title | `intitle:"index of"` |
| `inurl:`   | Find URLs containing specific text | `inurl:admin`          |
| `filetype:`| Search for specific file types    | `filetype:pdf`         |
| `ext:`     | Same as `filetype:` but for extensions | `ext:xlsx`         |


Examples:

- **Find OSINT-related PDFs on GitHub** 
  
       site:github.com filetype:pdf osint
 
- **Find sites mentioning "Rohit" in text**     

      site:icc-cricket.com intext:rohit  
 
- **Find sites with "Virat" in the URL**  

      site:icc-cricket.com inurl:virat   

- **Find sites with "Rohit" in the title**  

      site:icc-cricket.com intitle:rohit 

 - **Find recent research papers on "cybersecurity" (excluding IEEE & Springer)**

       site:researchgate.net OR site:arxiv.org filetype:pdf "cybersecurity" -site:ieee.org -site:springer.com

- **Find real estate listings with prices but exclude broker websites**

      site:olx.in OR site:99acres.com "3BHK" "₹" -site:magicbricks.com -site:nobroker.in





Instead of all these, you can set all parameters like language, region, words to include-exclude, date range etc. from "Advanced Search" feature. 
 
[Click on tools ↣ Advanced Search](https://ibb.co/NgqmGNMc) ↣ [Customise your search](https://ibb.co/39XnzkXL)
