# Launching a Website using AWS Networking Services

## Architecture

<p align="center">
  <img src="https://github.com/IndraT97/launched-Website-using-AWS-Services/blob/master/Architecture.png">
</p>

* ***Route 53 -*** *AWS service for domain registration, DNS routing, and health checking*
* ***Amazon CloudFront -*** *Fast, secure, and global content delivery network (CDN) service*
* ***S3 Storage -*** *Scalable cloud storage service for data backup and archival*
* ***AWS Certificate Manager -*** *Manages SSL/TLS certificates for secure AWS service communication*

### High Level Steps

- Purchased a domain from hostinger.com (indrajeetthakare.cloud)
- Created a static website using S3
- Setting up Name of the bucket to be domain name
- Created a certificate from the Amazon Certificate Manager for the DNS purchased
- Created a Cloudfront Distribution
- Created a hosted zone in the Route 53

## Website Demo

<p align="center">
  <img src="https://github.com/IndraT97/launched-Website-using-AWS-Services/blob/master/Website.png">
</p>
