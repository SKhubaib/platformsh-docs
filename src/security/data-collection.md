# Data Collection

As part of our normal business operations we do collect various pieces of data.

In GDPR terms:

* Article 4: Our accounts system contains some (routine) Article 4 items (name, address, phone, etc.) in order to allow us to bill your account appropriately.  This information can be verified, changed, and deleted by [logging into your account](https://accounts.platform.sh/).
* Article 9: We don't capture and store any Article 9 special identifiers (such as race, religion, sexual orientation, or other attributes that are irrelevant to our business). 
* Article 30: The only Article 30 items we keep are IP address and Log files. These reside on AWS/Azure/Orange (depending on your hosting), and may be sent to Sentry.io when there are crashes.

## Application Logs

Application logs are immutable to Customers to prevent tampering. These logs are secured behind key-based SSH so that only the Customer and our relevant teams have access.

## System logs

Platform.sh records routine system logs but we don't access Customer-specific system logs (or the Customer environment) unless requested to do so to help solve a problem. Later this year we will be rolling out better logging and log segregation to allow a Customer to get easier access to the logs they need.
## Vendor Data Sharing

We have identified and mapped all data we collect and share vendors (such as AWS, Azure, and Orange) so we know what we capture and where it goes. All of our vendors have been vetted for security and GDPR compliance and contract amendments and DPAs have been put in place where applicable.