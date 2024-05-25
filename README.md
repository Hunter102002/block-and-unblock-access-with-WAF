# Managing CloudFront Distribution Access Using AWS WAF

## Objective

The project aimed to manage access to an Amazon CloudFront distribution using AWS Web Application Firewall (WAF). The goal was to block and unblock access to the CloudFront distribution based on specific criteria, enhancing the security and control over content delivery. This project demonstrated advanced skills in AWS resource management, WAF rule configuration, and secure access control.

### Skills Learned

- Configuring AWS WAF: Setting up and managing AWS WAF rules to control access to CloudFront distributions.
- Managing CloudFront Distributions: Creating and configuring CloudFront distributions for content delivery.
- Secure Access Control: Implementing security measures to block and unblock access based on defined criteria.
- Resource Management: Managing AWS resources, including WAF, CloudFront distributions, and related services.
- Rule-Based Security: Creating and applying rules in AWS WAF to filter and monitor HTTP and HTTPS requests.

### Tools Used

- Amazon Web Services (AWS): For provisioning and managing WAF, CloudFront distributions, and related resources.
- AWS WAF: For setting up and managing web application firewall rules.
- AWS Management Console: For configuring and managing all AWS resources.


### Outcome
This project successfully demonstrated the ability to manage access to a CloudFront distribution using AWS WAF, showcasing advanced skills in secure access control, WAF rule configuration, and resource management. By leveraging AWS WAF, the project ensured that access to the CloudFront distribution was controlled and monitored effectively, aligning with best practices for secure and efficient content delivery in the cloud.

## Steps

Create a Cloud Formation stack

<img width="1178" alt="Screenshot 2024-05-21 at 9 36 28 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/a5477ae1-9281-498f-abf2-1bbc6742660c">

Create a web ACL with rules

<img width="198" alt="Screenshot 2024-05-21 at 9 37 13 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/96600465-4e61-409a-b4cf-7da33db4b13f">


<img width="1129" alt="Screenshot 2024-05-21 at 9 37 45 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/9faaac14-eaf1-440a-bcb3-37f01429a192">


<img width="1131" alt="Screenshot 2024-05-21 at 9 38 36 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/4c9d199c-0236-4338-9f4d-e9e9e51de32e">

<img width="802" alt="Screenshot 2024-05-21 at 9 41 22 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/c4f66e79-89bb-4943-b353-f0e6eb447ea0">


<img width="800" alt="Screenshot 2024-05-21 at 9 42 25 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/4a69003c-29b3-4173-acab-094a6b481808">


<img width="797" alt="Screenshot 2024-05-21 at 9 44 31 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/1a13eac0-a136-4bec-bf36-e2d253a26c55">

Verify Web ACL

<img width="1128" alt="Screenshot 2024-05-21 at 9 45 06 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/9a1594c5-5a23-4d05-91cd-96404ed9aa3f">

Create EC2 Instance

<img width="1228" alt="Screenshot 2024-05-21 at 9 45 43 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/7278b0eb-369a-4937-9486-646c6054aa4c">

Connect to instance and finish setup 

<img width="1470" alt="Screenshot 2024-05-21 at 9 48 05 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/74d7ba14-3bc3-45c5-a199-6ca025f11197">

Test


<img width="553" alt="Screenshot 2024-05-21 at 9 50 04 PM" src="https://github.com/Hunter102002/block-and-unblock-access-with-WAF/assets/98543129/b37eb773-0bbe-4670-b277-0736da01310e">
