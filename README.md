Manual steps performed so far:
1. create S3 buckets
   redf-serverlesstube-input
   redf-serverlesstube-output
   where redf is an private abbreviation

2. add policy from lab-1 to redf-serverlesstube-output

3. in lab 1 folder, cd to /videotranscoder, zip -r craigzip1.zip * (therefore you're inside /videotranscoder and you're zipping up its content)

4. via AWS console, upload the zip into Lambda
