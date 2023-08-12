# Portfolio Responsive Complete

### Portfolio Responsive Complete

- Responsive Personal Portfolio Website HTML CSS & JavaScript.
- Contains animations when scrolling.
- Smooth scrolling in each section.
- Developed first with the Mobile First methodology, then for desktop.
- Compatible with all mobile devices and with a beautiful and pleasant user interface.

S3 Bucket policy:
{
	"Version": "2008-10-17",
	"Id": "PolicyForCloudFrontPrivateContent",
	"Statement": [
		{
			"Sid": "AllowCloudFrontServicePrincipal",
			"Effect": "Allow",
			"Principal": {
				"Service": "cloudfront.amazonaws.com"
			},
			"Action": "s3:GetObject",
			"Resource": "arn:aws:s3:::parvathijampaniportfolio/*",
			"Condition": {
				"StringEquals": {
					"AWS:SourceArn": "arn:aws:cloudfront::235149775118:distribution/E22ELNIEE7C85X"
				}
			}
		}
	]
}


