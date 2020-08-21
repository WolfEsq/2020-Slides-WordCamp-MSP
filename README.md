# How Hackers Exploit WordPress Websites with Pending Updates
## WordCamp MSP 2020
### [Presentation Slides](https://github.com/WolfEsq/2020-Slides-WordCamp-MSP/blob/master/How-Hackers-Exploit-Websites-with-Pending-Updates.pdf)
https://github.com/WolfEsq/2020-Slides-WordCamp-MSP/blob/master/How-Hackers-Exploit-Websites-with-Pending-Updates.pdf

### Sources and Links
Wordfence blog post about what hackers do with compromised websites:  
https://www.wordfence.com/blog/2016/04/hackers-compromised-wordpress-sites/

WordPress (.org) Documentation about updates:  
https://wordpress.org/support/article/updating-wordpress/  
https://wordpress.org/support/article/configuring-automatic-background-updates/  
https://wordpress.org/support/update-php/  

EC Council Certified Ethical Hacker program:  
https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/  

### Plugins Recommended
[Wordfence](https://wordpress.org/plugins/wordfence/) - Website firewall plugin  
[PHP Compatibility Checker](https://wordpress.org/plugins/php-compatibility-checker/) - Plugin to check your website's compatibility with the latest PHP releases  

### Tools used in presentation
[Docker Desktop](https://www.docker.com/products/docker-desktop) - used to create a virtual hacking lab  
[Kali Linux](https://www.kali.org/) - OS built for hacking  

### WPScan Vulnerability Database
https://wpvulndb.com/  
Vulnerabilities discussed in presentation:  
[WordPress 3.9-5.1 - Comment Cross-Site Scripting (XSS)](https://wpvulndb.com/vulnerabilities/9230)  
[Easy WP SMTP <= 1.3.9 - Unauthenticated Arbitrary wp_options Import](https://wpvulndb.com/vulnerabilities/9237)  
[Duplicator 1.3.24 & 1.3.26 - Unauthenticated Arbitrary File Download](https://wpvulndb.com/vulnerabilities/10078)  
