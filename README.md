MY CMDs:
$
$
$
$
$
$

$ Retiring the Cloud Storage infrastructure, we should delete the buckets, disable versioning and lifecycle rules, and revoke access controls. 
We can use the following commands to do this:

# Delete a bucket and its contents
gsutil rm -r gs://BUCKET_NAME/

# Disable versioning for a bucket
gsutil versioning set off gs://BUCKET_NAME/

# Remove lifecycle rules for a bucket
gsutil lifecycle remove gs://BUCKET_NAME/

# Revoke access controls for a bucket
gsutil iam ch -d user:USER_EMAIL gs://BUCKET_NAME/
