# Static-website-hosting
Static websites deliver HTML, JavaScript, images, video and other files to your website visitors. Static websites are very low cost, provide high-levels of reliability, require almost no IT administration, and scale to handle enterprise-level traffic with no additional wor
In the Buckets list, choose the name of the bucket that you want to use to host a static website I created bucket name Brain floss
Choose Properties
Choose Use this bucket to host a website
In Index document, enter the file name of the index document, typically index.html
(Optional) If you want to provide your own custom error document for 4XX class errors, in Error document, enter the custom error document file name
Choose Save changes.

Amazon S3 enables static website hosting for your bucket. At the bottom of the page, under Static website hosting, you see the website endpoint for your bucket
Upload the index document to your bucket
Upload other files for your website, including optional custom error documents
Step 2: Editing S3 Block Public Access settings
Choose the name of the bucket that you have configured as a static website.I created Brain Floss

Choose Permissions.

Under Block public access (bucket settings), choose Edit.

Clear Block all public access, and choose Save changes.
Step 3: Adding a bucket policy
Under Buckets, choose the name of your bucket.Brainfloss

Choose Permissions.

Under Bucket Policy, choose Edit.

To grant public read access for your website, copy the following bucket policy, and paste it in the Bucket policy editor
Choose Save changes
Step 4: Testing your website endpoint
Under Buckets, choose the name of your bucket.

Choose Properties.

At the bottom of the page, under Static website hosting, choose your Bucket website endpoint
