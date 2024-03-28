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

- Purchase a domain from hostinger.com (indrajeetthakare.cloud)
- Create a static website using S3
- Name of the bucket can be domain name
- Create a certificate from the Amazon Certificate Manager for the DNS purchased
- Create a Cloudfront Distribution
- Create a hosted zone in the Route 53

## Website

<p align="center">
  <img src="https://github.com/IndraT97/launched-Website-using-AWS-Services/blob/master/Website.png">
</p>
