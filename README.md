# smartedu
# Grant Acess
 gcloud projects add-iam-policy-binding tactile-visitor-469118-d8 \
  --member="serviceAccount:github-actions-deployer@tactile-visitor-469118-d8.iam.gserviceaccount.com" \
  --role="roles/compute.securityAdmin"

gcloud projects add-iam-policy-binding tactile-visitor-469118-d8 \
  --member="serviceAccount:github-actions-deployer@tactile-visitor-469118-d8.iam.gserviceaccount.com" \
  --role="roles/compute.viewer"
