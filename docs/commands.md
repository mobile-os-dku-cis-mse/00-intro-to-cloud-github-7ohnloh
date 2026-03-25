# Commands Used

## Create bucket
aws s3 mb s3://john-portfolio-website-123

## Upload website files
aws s3 cp website/ s3://john-portfolio-website-123 --recursive

## Enable static website hosting
aws s3 website s3://john-portfolio-website-123 \
  --index-document index.html \
  --error-document error.html

## Verify bucket contents
aws s3 ls s3://john-portfolio-website-123

## Verify website configuration
aws s3api get-bucket-website --bucket john-portfolio-website-123