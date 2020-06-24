docker run -p 9001:9000 --name minio   -d -e "MINIO_ACCESS_KEY=ACCESS_KEY"   -e "MINIO_SECRET_KEY=SECRET_KEY"   -v /mnt/data:/data   minio/minio server /data
