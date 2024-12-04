## **Complete Guide: Configure HTTPS on CentOS**
#### Check if the http server is running or not 
`sudo systemctl status httpd`

#### Restart the http server
`sudo systemctl restart httpd`

#### Install the ssl 
`sudo yum install mod_ssl` or `sudo yum install mod24_ssl`