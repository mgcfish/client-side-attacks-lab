- Web skills primer (2 hours): 
  - Basic JavaScript skills e.g. control flow, 
  - DOM interactions (iterating over elements, changing the UI), 
  - event handlers, 
  - XmlHttpRequests + Fetch function
- CORS Abuse (1.5 hours): 
  - Demo of the same origin policy, what kinds of attacks it blocks (XHR/Fetch requests from a malicious site). 
  - Allow-Origin:*, and what it permits.
  - **Lab 1**: Origin reflection misconfiguration (wide open CORS policy with credentials) - Data harvesting from a malicious site.  - 
  - **Lab 2**: More limited CORS misconfiguration (subdomains reflected only) - Attacking from a more vulnerable site.  - 45-minute Lunch Break (1 hour, because it always runs late)  - 
- Basic CSRF (1.5 hours) - How it works, what kind of controls stop it (tokens, origin/referrer checking, multi-stage interactions). 
  - **Lab 3**: Password change via CSRF (unobfuscated)
  - **Lab 4**: Modify the password change to be obfuscated/hidden from the user
  - **Lab 5**: Running the CSRF on a two-stage transaction (confirmation page)  - 
  - **_Lab 6a_**: Same as 5, but the second request requires the response from the first.
- Clickjacking/UI Redress (1 hour) - It's a circumstantial attack. When is it dangerous? CSS/JavaScript skills for setting up the exploit.
  - **Lab 6b**: CSRF + Clickjacking - using a UI redress to get past the confirmation page from Lab 6a.  
- XSS (remaining time) - Basic script injection, actually one of the most well-understood types of attack.
  - **Lab 7**: Swapping interfaces with hidden divs, faking a session timeout and login.
  - **Lab 8**: Pivoting the script to non-vulnerable pages through iframe same-origin behavior.
  - **Lab 9**: Identifying and injecting into vulnerable browser plugins. 