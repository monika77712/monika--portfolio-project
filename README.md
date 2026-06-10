## 🔗 Live Demo
**CloudFront URL:**  https://d3i3fxn0ih04lc.cloudfront.net/


## 🛠️ AWS Architecture  
User → CloudFront (HTTPS + Global CDN) → S3 Bucket (Private with OAC)

## 🔐 Security Implementation
Used Origin Access Control so S3 bucket is 100% private. Only CloudFront can access it.
Bucket Policy: [`bucket-policy.json`](./bucket-policy.json)

## 📋 Tech Stack
- **Amazon S3** - Static website hosting
- **Amazon CloudFront** - HTTPS, Caching, DDoS Protection  
- **OAC** - Zero public S3 exposure

## 💰 Cost
$0/month - AWS Free Tier



