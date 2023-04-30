MY CMDs:
## 1.Create a new project in the Google Cloud Console:

gcloud projects create [PROJECT_NAME] --name=[DISPLAY_NAME]
Replace [PROJECT_NAME] with a unique name for your project and [DISPLAY_NAME] with a user-friendly display name.

# Set the GCP project ID:
gcloud config set project <project-id>

#Delete your GCP project:
gcloud projects delete [PROJECT_ID]

# Create a Cloud Storage bucket:
gsutil mb gs://<bucket-name>

# List all of the buckets in your project:
gcloud storage buckets list

# Delete a bucket
gcloud storage buckets delete <bucket-name>                                 (regular bucket)

# Set the default storage class for the bucket:
gsutil defstorageclass set <storage-class> gs://<bucket-name>

# Configure access control for the bucket:
gsutil iam ch <permission> <user-or-group> gs://<bucket-name>
$
# Upload files to your bucket by running the command :
gsutil cp <local-file> gs://<bucket-name>/<remote-file>"
$

## 2. Retiring the Cloud Storage infrastructure, we should delete the buckets, disable versioning and lifecycle rules, and revoke access controls. 
We can use the following commands to do this, all listed are for cloud storage's buckets, not regular bucket)

# Delete a bucket and its contents.                                     (Cloud Storage's bucket)
gsutil rm -r gs://BUCKET_NAME/

# Disable versioning for a bucket:
gsutil versioning set off gs://BUCKET_NAME/

# Remove lifecycle rules for a bucket:
gsutil lifecycle remove gs://BUCKET_NAME/

# Revoke access controls for a bucket
gsutil iam ch -d user:USER_EMAIL gs://BUCKET_NAME/

# Modify the access control list for your bucket.
gsutil acl


