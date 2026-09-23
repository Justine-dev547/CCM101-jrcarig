# Mission Reflection

This laboratory activity helped me understand why object storage is commonly used for large amounts of files such as photos. Object storage is better suited for storing millions of photos because it is designed to handle unstructured data and can scale as the amount of data increases. Unlike a traditional block storage hard drive, object storage can organize files as objects with metadata and unique identifiers, making it easier to manage a large collection of images.

Using Docker also made the deployment of MinIO easier for me. Instead of installing and configuring every component manually, I only needed to run one Docker command to download and start the MinIO server. Docker also helped keep the MinIO environment separated from the rest of the system. This made the deployment faster and easier to repeat.

A bucket in cloud storage is a container where objects or files are stored. In this activity, I created a bucket named `client-photos`, which served as the storage location for the sample file that I uploaded. It helped me understand how cloud storage organizes files.

Large enterprise companies can protect their object storage data in different ways. They can use replication, backups, redundancy, and multiple storage servers or locations. If one physical server crashes, copies of the data can still be available from other servers. This helps reduce the possibility of permanent data loss.

My confidence in using the Linux command line is also growing. At first, commands such as Docker commands looked complicated, but after following the steps and checking the results using `docker ps`, I became more comfortable. I learned that the command line can be very useful for deploying and managing cloud services. This activity also gave me more experience with Docker, MinIO, and cloud storage.

