python upload_job.py -filename job.py -bucket s3-glue-hudi-bucket-lab -awsprofile default

aws glue start-job-run --job-name "glue-job-hudi-resource"