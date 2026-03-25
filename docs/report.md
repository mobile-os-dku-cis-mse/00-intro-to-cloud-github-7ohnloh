# S3 Static Website Deployment Report

## Objective
The objective of this assignment is to deploy a static website using AWS S3 and verify its functionality.

---

## Steps Taken

1. Created an S3 bucket named `john-portfolio-website-123`
2. Uploaded `index.html` and `error.html` files
3. Enabled static website hosting
4. Configured index and error documents
5. Updated bucket policy to allow public access

---

## Verification

- Successfully accessed the website via the S3 website endpoint
- Verified that the homepage loads correctly
- Tested invalid URL and confirmed `error.html` is displayed

---

## Challenges Faced

- Encountered "Access Denied" error initially
- Resolved by updating bucket policy to allow public read access

---

## Conclusion

The static website was successfully deployed using AWS S3. The system is accessible publicly and handles errors correctly.