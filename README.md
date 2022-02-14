# CloudComputing
http://cs4843websiteproject.s3-website.us-east-2.amazonaws.com

The EC2 infrastructure includes one instance named httpdec2 that holds a security groups named launch-wizard-2,
this holds 3 inbound rules that allow public access to the site. These are used to create the AMI which is named demoHTTPserver2,
this is the VM used to deploy the services used in my EC2. The S3 holds all of my objects to create the site including my images,
pages, and videos. The permissions allow for public access to the static site.
