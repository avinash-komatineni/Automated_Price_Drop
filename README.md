To Configure and Use the Application: 

To set up and use the application: 
- Deploy the `cloudFormation.yaml` script using AWS CloudFormation to automatically create all the necessary services. 
- Upload `lambda_function.zip` to an S3 bucket. 
- EventBridge (CloudWatch Events) will automatically trigger the Lambda function at predefined intervals. 

That's it! The application will now periodically scrape Amazon.com for iPad prices and send notifications when a price drop is detected.

For additional insights into the code, please refer to the Report.pdf document.
