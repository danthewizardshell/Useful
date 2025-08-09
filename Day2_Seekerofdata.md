

The journey to the devops engineer pt
Day 2 — Seeker of Data

Command Name: grep
Purpose: Search for specific patterns in text files or command outputs.
Example Usage:
grep -i "error" /var/log/httpd/error_log
Output Screenshot or Copy:
[Thu Aug 08 14:03:15.221995] [error] File not found: /var/www/html/index.html

Command Name: find
Purpose: Locate files or directories matching certain criteria.
Example Usage:
find /etc/httpd -name "*.conf"
Output Screenshot or Copy:
/etc/httpd/conf/httpd.conf
/etc/httpd/conf.d/ssl.conf

Command Name: cut
Purpose: Extract specific fields or columns from text data.
Example Usage:
cut -d: -f1 /etc/passwd
Output Screenshot or Copy:
root
bin
daemon
ec2-user

Command Name: awk
Purpose: Process and format text using patterns and actions.
Example Usage:
awk -F: '{ print $1, $3 }' /etc/passwd
Output Screenshot or Copy:
root 0
bin 1
daemon 2
ec2-user 1000

Quote of the Day:
"The desert hides its treasures from the hasty, but to the patient seeker it yields all that is hidden." — Muad’Dib1






