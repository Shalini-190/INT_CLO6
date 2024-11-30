# Cloud Storage and CDN Integration

## Project Overview
This project demonstrates the implementation of a cloud storage solution integrated with a Content Delivery Network (CDN) to optimize global content delivery speed. 

## Features
- Store files in Amazon S3.
- Integrate with AWS CloudFront for CDN functionality.
- Configure caching rules for optimized performance.
- Test content delivery speed across regions using monitoring tools.

## Components
1. **Amazon S3**:
   - Stores static files for global delivery.
   - Configured with appropriate storage class and access policies.
2. **AWS CloudFront**:
   - Distributes content globally.
   - Configured with caching rules to improve performance.

## Setup Instructions
1. **S3 Bucket Setup**:
   - Create an S3 bucket and upload static files.
   - Configure bucket policies for public or private access as needed.
2. **CloudFront Setup**:
   - Link the S3 bucket to CloudFront as the origin.
   - Set up caching behaviors for optimized performance.
3. **Testing**:
   - Use AWS CloudWatch for monitoring.
   - Conduct regional speed tests using tools like WebPageTest or Pingdom.

## Testing Results
- See [testing/speed-test-results.md](./testing/speed-test-results.md) for regional speed insights.

## Tools Used
- **AWS S3** for storage.
- **AWS CloudFront** for CDN.
- **CloudWatch** for performance monitoring.
- **Pingdom/WebPageTest** for speed testing.

---

## Repository Structure
