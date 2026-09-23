# Types of Cloud Storage

| Storage Type       | Description                                                            | Primary Use Case                                                          | Cloud Provider Example |
| ------------------ | ---------------------------------------------------------------------- | ------------------------------------------------------------------------- | ---------------------- |
| **Block Storage**  | Stores data in fixed-size blocks that can be accessed separately.      | Best for virtual machines, databases, and operating system disks.         | AWS EBS                |
| **File Storage**   | Stores data as files organized in folders and directories.             | Best for shared files and applications that need a common file system.    | AWS EFS                |
| **Object Storage** | Stores data as objects together with metadata and a unique identifier. | Best for images, videos, backups, documents, and other unstructured data. | AWS S3                 |

## Why Object Storage?

Object Storage is the best choice for the client's photo-sharing application because it can handle large amounts of unstructured data such as images. It is also scalable, so the storage can grow as more users upload photos without depending on the web server's local storage.

