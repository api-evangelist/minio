<!-- fetched 2026-10-13 from https://docs.min.io/community/minio-object-store/reference/s3-api-compatibility.html by sweep-shape-compat.py; text extracted from the provider's own page -->

S3 API Compatibility | MinIO AIStor Documentation 
 MinIO AIStor MinIO AIStor Exascale data store for high-performance AI workloads, natively supporting the S3 API for objects, Iceberg for tables, and SFTP for files MinIO KMS Highly scalable key management server, for secure encryption at rest MinIO DirectPV Kubernetes CSI driver and volume manager for direct-attached storage MinIO Warp S3-compatible object store benchmarking tool for measuring throughput and latency MinIO Sidekick High-performance client-side load balancer for distributed HTTP services 
 Installation Kubernetes Install MinIO AIStor Deploy MinIO AIStor on Kubernetes 
 Deploy MinIO AIStor on Red Hat OpenShift 
 Deploy MinIO AIStor with a Private Container Registry 
 Deploy MinIO AIStor in an Airgapped Environment 
 Configure Load Balancing 
 Enable Network Encryption Operator webhook TLS 
 Enable FIPS Mode 
 Enable Server Side Encryption Server Side Encryption with MinIO KMS 
 Server Side Encryption with KES 
 Enable RDMA 
 Linux Install MinIO AIStor Install MinIO AIStor on Ubuntu Server 
 Install MinIO AIStor on Red Hat Enterprise Linux 
 Configure Load Balancing 
 Enable Network Encryption Configure TLS Network Encryption 
 Enable FIPS Mode 
 Enable Server Side Encryption Server Side Encryption with MinIO KMS 
 Server Side Encryption with KES 
 Container Deploy MinIO AIStor as a Container 
 Deploy Distributed MinIO AIStor on Docker Compose 
 Enable Network Encryption 
 macOS Deploy MinIO AIStor on macOS 
 Enable Network Encryption 
 Windows Deploy AIStor Server on Windows 
 Enable Network Encryption 
 Checklists Security checklist 
 Software checklist 
 System tuning 
 Administration What You Configure on a Bucket 
 Objects and Versioning Batch Job Expiration 
 Object Versioning Enable Object Versioning 
 Exclude Prefixes 
 Ignore Folder Objects 
 Suspend Versioning 
 Data Compression 
 Object Deletion 
 Object Locking and Immutability 
 Object Lifecycle Management Automatic Object Expiration 
 Lifecycle rule patterns 
 Object Tiering Transition objects from MinIO AIStor to a remote MinIO AIStor deployment 
 Transition objects from MinIO AIStor to Azure 
 Transition objects from MinIO AIStor to Google Cloud Storage 
 Transition objects from MinIO AIStor to S3 
 Identity and Access Management MinIO AIStor Identity Management Built-in Identity Management 
 Active Directory/LDAP Identity Management 
 OpenID Connect Identity Management 
 Keycloak Identity Provider 
 Microsoft Entra ID (Azure AD) Identity Provider 
 Okta Identity Provider 
 Kubernetes Service Account Identity 
 Identity Management Plugin 
 Access Control with Policy Management Active Directory/LDAP Access Management 
 OpenID Connect Access Management 
 Authorization Plugin 
 Replication Site Replication Initialize Site Replication 
 Add New Peer Site 
 Remove existing Peer Site 
 Restore site replication service account 
 Bucket Replication Bucket Replication Requirements 
 Enable Active-Passive Bucket Replication 
 Enable Active-Active Bucket Replication 
 Resynchronize Remote after Data Loss 
 Batch Replication 
 Bucket Notifications Publish Events to AMQP (RabbitMQ) 
 Publish Events to Elasticsearch 
 Publish Events to Kafka 
 Publish Events to MQTT 
 Publish Events to MySQL 
 Publish Events to NATS 
 Publish Events to NSQ 
 Publish Events to PostgreSQL 
 Publish Events to Redis 
 Publish Events to Webhook 
 Bucket-level Quality of Service Network QoS 
 QoS Rule Examples 
 Supported APIs for QoS 
 Batch Framework 
 Multi-Tenancy 
 Console UI Managing a Deployment 
 Managing Objects 
 Managing Security and Access 
 AIStor Tables Table Sharing Controlling access to table shares 
 Managing shared tables 
 Share a table with Databricks 
 Reverse proxies, load balancers, and scaling 
 Controlling Access to AIStor Tables 
 Table Maintenance 
 Site Replication and Disaster Recovery 
 Bucket Quotas 
 CORS Configuration 
 Upgrade Upgrade MinIO AIStor on Linux 
 Upgrade MinIO AIStor on Kubernetes (Helm) 
 Upgrade MinIO AIStor on Kubernetes with Public Registries 
 Upgrade MinIO AIStor on Kubernetes with Private Registry 
 Upgrade MinIO AIStor on Kubernetes in Airgapped Environments 
 Upgrade from open-source MinIO Upgrade from open-source MinIO on Linux 
 Upgrade from open-source MinIO on Kubernetes 
 Upgrade from open-source MinIO in Airgapped Environments 
 Troubleshooting Upgrade Issues 
 Developers Security Token Service AssumeRole 
 AssumeRoleWithCertificate 
 AssumeRoleWithClientGrants 
 AssumeRoleWithCustomToken 
 AssumeRoleWithLDAPIdentity 
 AssumeRoleWithWebIdentity 
 Software Development Kits (SDKs) Go SDK Go Client API Reference 
 Python SDK Python Client API Reference 
 Java SDK Java Client API Reference 
 .NET SDK .NET Client API Reference 
 JavaScript SDK JavaScript Client API Reference 
 Haskell SDK Haskell Client API Reference 
 C++ SDK 
 Rust SDK 
 File Transfer Protocol 
 Transfer Objects over RDMA 
 S3 API Compatibility 
 AIStor Tables AIStor Tables API Reference 
 Connecting query engines to AIStor Tables 
 Operations Core Concepts Erasure Coding 
 Healing 
 AI Workloads 
 Metrics and Logging Metrics Metrics v3 Reference 
 Alerts 
 Tables and Delta Sharing Observability 
 Monitoring and alerting using Prometheus 
 Monitoring and alerting using InfluxDB 
 Metrics version 2 
 Server Logging 
 Audit Logging Publish audit logs to HTTP webhook 
 Publish audit logs to Kafka 
 OpenTelemetry Tracing 
 S.M.A.R.T. Drive Health Monitoring 
 Healthcheck Probes 
 Debugging and Troubleshooting 
 Node Maintenance 
 Scaling Expand Available Storage Expand a MinIO AIStor Deployment on Kubernetes 
 Expand a MinIO AIStor Deployment on Linux 
 Decommission Aged Hardware Decommission AIStor Server Pool on Linux 
 Data Recovery Recover after drive failure 
 Recover after node failure 
 Recover after site failure 
 Performance Tuning 
 Benchmarking 
 Network and storage performance testing 
 RDMA Acceleration Configure the RDMA fabric 
 Deploy the RDMA server 
 Validate the RDMA deployment 
 Troubleshoot RDMA 
 Network Encryption TLS certificate management with cert-manager 
 TLS certificate troubleshooting 
 Certificate rotation 
 Storage Hardening 
 Troubleshoot System Path Growth 
 Batch Key Rotation 
 Bucket Inventory Reports Configuration Reference 
 Inventory API Reference 
 Hotfix Releases 
 Release Artifacts 
 Software Lifecycle and End-of-Life 
 Licenses 
 Reference AIStor Client AIStor Client Settings 
 Admin Commands mc admin accesskey mc admin accesskey create 
 mc admin accesskey diagnose 
 mc admin accesskey disable 
 mc admin accesskey edit 
 mc admin accesskey enable 
 mc admin accesskey info 
 mc admin accesskey list 
 mc admin accesskey rm 
 mc admin accesskey sts-revoke 
 mc admin bucket quota 
 mc admin cluster bucket mc admin cluster bucket export 
 mc admin cluster bucket import 
 mc admin cluster iam mc admin cluster iam export 
 mc admin cluster iam import 
 mc admin cluster services 
 mc admin cluster stats 
 mc admin config 
 mc admin cordon 
 mc admin decommission 
 mc admin drive mc admin drive info 
 mc admin drive top 
 mc admin group 
 mc admin heal 
 mc admin info 
 mc admin kms key 
 mc admin logs 
 mc admin maintenance hosts 
 mc admin name mc admin name get 
 mc admin name set 
 mc admin node mc admin node info 
 mc admin node top 
 mc admin object info 
 mc admin object unlock 
 mc admin policy mc admin policy attach 
 mc admin policy create 
 mc admin policy detach 
 mc admin policy entities 
 mc admin policy info 
 mc admin policy ls 
 mc admin policy rm 
 mc admin pool mc admin pool info 
 mc admin pool top 
 mc admin prometheus mc admin prometheus generate 
 mc admin prometheus metrics 
 mc admin rebalance 
 mc admin replicate mc admin replicate add 
 mc admin replicate info 
 mc admin replicate remove 
 mc admin replicate resync 
 mc admin replicate status 
 mc admin replicate update 
 mc admin scanner mc admin scanner status 
 mc admin scanner trace 
 mc admin service 
 mc admin set mc admin set info 
 mc admin set top 
 mc admin trace 
 mc admin uncordon 
 mc admin update 
 mc admin user mc admin user add 
 mc admin user disable 
 mc admin user enable 
 mc admin user info 
 mc admin user ls 
 mc admin user policy 
 mc admin user rm 
 mc admin user sts info 
 Command Quick Reference 
 mc alias mc alias export 
 mc alias import 
 mc alias list 
 mc alias remove 
 mc alias set 
 mc anonymous mc anonymous get 
 mc anonymous get-json 
 mc anonymous links 
 mc anonymous list 
 mc anonymous set 
 mc anonymous set-json 
 mc batch mc batch cancel 
 mc batch describe 
 mc batch generate 
 mc batch list 
 mc batch start 
 mc batch status 
 mc cat 
 mc cors mc cors get 
 mc cors remove 
 mc cors set 
 mc cp 
 mc diff 
 mc du 
 mc encrypt mc encrypt clear 
 mc encrypt info 
 mc encrypt set 
 mc encrypt update 
 mc event mc event add 
 mc event list 
 mc event remove 
 mc event target list 
 mc find 
 mc get 
 mc head 
 mc idp ldap mc idp ldap add 
 mc idp ldap disable 
 mc idp ldap enable 
 mc idp ldap info 
 mc idp ldap ls 
 mc idp ldap rm 
 mc idp ldap update 
 mc idp ldap accesskey mc idp ldap accesskey create 
 mc idp ldap accesskey create-with-login 
 mc idp ldap accesskey disable 
 mc idp ldap accesskey edit 
 mc idp ldap accesskey enable 
 mc idp ldap accesskey info 
 mc idp ldap accesskey ls 
 mc idp ldap accesskey rm 
 mc idp ldap accesskey sts-revoke 
 mc idp ldap policy mc idp ldap policy attach 
 mc idp ldap policy detach 
 mc idp ldap policy entities 
 mc idp openid mc idp openid add 
 mc idp openid disable 
 mc idp openid enable 
 mc idp openid info 
 mc idp openid ls 
 mc idp openid rm 
 mc idp openid update 
 mc idp openid accesskey mc idp openid accesskey create-with-login 
 mc idp openid accesskey disable 
 mc idp openid accesskey edit 
 mc idp openid accesskey enable 
 mc idp openid accesskey info 
 mc idp openid accesskey ls 
 mc idp openid accesskey rm 
 mc ilm expiry mc ilm expiry status 
 mc ilm restore 
 mc ilm rule mc ilm rule add 
 mc ilm rule edit 
 mc ilm rule export 
 mc ilm rule import 
 mc ilm rule ls 
 mc ilm rule rm 
 mc ilm tier mc ilm tier add 
 mc ilm tier check 
 mc ilm tier info 
 mc ilm tier ls 
 mc ilm tier rm 
 mc ilm tier update 
 mc inventory mc inventory cancel 
 mc inventory delete 
 mc inventory generate 
 mc inventory get 
 mc inventory list 
 mc inventory migrate-from-batch 
 mc inventory put 
 mc inventory resume 
 mc inventory status 
 mc inventory suspend 
 mc kms mc kms enable 
 mc kms key mc kms key create 
 mc kms key ls 
 mc kms key rotate 
 mc kms key stat 
 mc legalhold mc legalhold clear 
 mc legalhold info 
 mc legalhold set 
 mc license mc license info 
 mc license register 
 mc license update 
 mc log mc log api 
 mc log audit 
 mc log error 
 mc ls 
 mc mb 
 mc mirror 
 mc mv 
 mc od 
 mc ping 
 mc pipe 
 mc put 
 mc qos rule mc qos rule add 
 mc qos rule export 
 mc qos rule import 
 mc qos rule list 
 mc qos rule remove 
 mc qos status 
 mc quota mc quota clear 
 mc quota info 
 mc quota set 
 mc rb 
 mc ready 
 mc replicate mc replicate add 
 mc replicate backlog 
 mc replicate export 
 mc replicate import 
 mc replicate ls 
 mc replicate resync 
 mc replicate resync-backlog 
 mc replicate rm 
 mc replicate status 
 mc replicate update 
 mc retention mc retention clear 
 mc retention info 
 mc retention set 
 mc rm 
 mc share mc share download 
 mc share list 
 mc share upload 
 mc sql 
 mc stat 
 mc support mc support callhome 
 mc support diag 
 mc support inspect 
 mc support perf mc support perf client 
 mc support perf drive 
 mc support perf net 
 mc support perf object 
 mc support perf site-replication 
 mc support profile 
 mc support proxy 
 mc support telemetry mc support telemetry analyze 
 mc support telemetry proxy 
 mc support telemetry record 
 mc support telemetry replay 
 mc support top mc support top api 
 mc support top drive 
 mc support top locks 
 mc support top net 
 mc support top rpc 
 mc support upload 
 mc table mc table config 
 mc table create 
 mc table encrypt mc table encrypt clear 
 mc table encrypt info 
 mc table encrypt set 
 mc table list 
 mc table maintenance mc table maintenance info 
 mc table maintenance remove 
 mc table maintenance set 
 mc table maintenance status 
 mc table maintenance update 
 mc table migrate 
 mc table namespace mc table namespace create 
 mc table namespace info 
 mc table namespace list 
 mc table namespace remove 
 mc table namespace update 
 mc table register 
 mc table remove 
 mc table rename 
 mc table replicate mc table replicate backfill mc table replicate backfill cancel 
 mc table replicate backfill start 
 mc table replicate backfill status 
 mc table replicate catalog mc table replicate catalog reset 
 mc table replicate failover 
 mc table replicate resync mc table replicate resync open 
 mc table replicate resync rebuild 
 mc table replicate status 
 mc table show 
 mc table tag mc table tag list 
 mc table tag remove 
 mc table tag set 
 mc table view mc table view create 
 mc table view drop 
 mc table view exists 
 mc table view list 
 mc table view show 
 mc table warehouse mc table warehouse create 
 mc table warehouse list 
 mc table warehouse maintenance mc table warehouse maintenance info 
 mc table warehouse maintenance set 
 mc table warehouse maintenance update 
 mc table warehouse remove 
 mc table warehouse tag mc table warehouse tag list 
 mc table warehouse tag remove 
 mc table warehouse tag set 
 mc table share mc table share create 
 mc table share info 
 mc table share list 
 mc table share remove 
 mc table share token mc table share token create 
 mc table share token list 
 mc table share token remove 
 mc table share update 
 mc tag mc tag list 
 mc tag remove 
 mc tag set 
 mc tree 
 mc undo 
 mc update 
 mc version mc version enable 
 mc version info 
 mc version suspend 
 mc watch 
 AIStor Server Settings and Configurations Core Settings 
 Batch Job Settings 
 Cache Settings 
 Console Settings 
 Erasure Code Settings 
 ILM Settings 
 Metrics and Logging Settings Webhook Server Logs 
 Webhook Audit Logs 
 Kafka Audit Logs 
 Telemetry Settings 
 Audit Event Queue 
 Log and Event Stream Filters 
 Notifications Settings AMQP Notification Settings 
 Elasticsearch Notification Settings 
 Kafka Notification Settings 
 MQTT Notification Settings 
 MySQL Notification Settings 
 NATS Notification Settings 
 NSQ Notification Settings 
 PostgreSQL Notification Settings 
 Redis Notification Settings 
 Webhook Notification Settings 
 Object Lambda Function Settings 
 Root Access Settings 
 Server Side Encryption Settings 
 Site Settings 
 IAM Settings LDAP Settings 
 OpenID Settings 
 STS Settings 
 Certificate Identity Settings 
 Kubernetes Identity Settings 
 Access Management Plugin Settings 
 Identity Management Plugin Settings 
 Heal Settings 
 Replication Settings 
 Etcd Settings 
 RDMA Settings 
 AIStor Tables Settings Iceberg REST Catalog Settings 
 Delta Sharing Settings 
 Replica Catalog Settings 
 Deprecated Settings 
 Startup Configuration File 
 Thresholds and Limits 
 Scanner 
 Hardware Tests 
 Admin API v4 Query Endpoints 
 Extended Object Names 
 HTTP Endpoints Reference 
 Hardware and System Requirements Memory Requirements 
 Network Requirements 
 Storage Requirements 
 MinIO AIStor Operator Reference MinIO AIStor Custom Resource Definition (Stable) 
 MinIO AIStor Custom Resource Definition (Alpha) 
 AdminJob 
 AIStor Server Operator Helm Chart 
 AIStor Server Helm Chart 
 Spread Zone Configuration 
 Environment Variable Configuration 
 Operator Environment Variables 
 OpenTelemetry Integration 
 PVC Protection 
 Pod Disruption Budgets 
 Close Sidebar 
 Developers 
 S3 API Compatibility 
 S3 API Compatibility
 This page documents S3 APIs supported by MinIO AIStor. For reference documentation on any given API, see the corresponding documentation for Amazon S3.
 Object APIs 
 CopyObject 
 DeleteObject 
 DeleteObjects 
 DeleteObjectTagging 
 GetObject 
 GetObjectAttributes 
 GetObjectTagging 
 HeadObject 
 ListObjects 
 ListObjectsV2 
 ListObjectVersions 
 PutObject 
 PutObjectTagging 
 RestoreObject 
 SelectObjectContent 
 Conditional headers 
 MinIO AIStor supports conditional operations using the following HTTP headers:
 Header | Supported operations | 
 If-Match | GetObject, HeadObject, PutObject, CopyObject, DeleteObject, CreateMultipartUpload | 
 If-None-Match | GetObject, HeadObject, PutObject, CopyObject, CreateMultipartUpload | 
 If-Modified-Since | GetObject, HeadObject | 
 If-Unmodified-Since | GetObject, HeadObject | 
 x-amz-copy-source-if-match | CopyObject, UploadPartCopy | 
 x-amz-copy-source-if-none-match | CopyObject, UploadPartCopy | 
 x-amz-copy-source-if-modified-since | CopyObject, UploadPartCopy | 
 x-amz-copy-source-if-unmodified-since | CopyObject, UploadPartCopy | 
 DeleteObjects supports conditional deletes using the <ETag> element in the request body.
 Object locking 
 GetObjectRetention 
 PutObjectRetention 
 GetObjectLegalHold 
 PutObjectLegalHold 
 GetObjectLockConfiguration 
 PutObjectLockConfiguration 
 Unsupported object APIs 
 GetObjectAcl
 PutObjectAcl
 Multipart uploads 
 AbortMultipartUpload 
 CompleteMultipartUpload 
 CreateMultipartUpload 
 ListMultipartUploads 
 ListParts 
 UploadPart 
 UploadPartCopy 
 Differences from S3 APIs for multipart uploads 
 ListMultipartUploads requires the exact object name as a prefix.
 The AbortIncompleteMultipartUpload lifecycle action is not supported with PutBucketLifecycle .
 Bucket APIs 
 CreateBucket 
 DeleteBucket 
 DeleteBucketEncryption 
 DeleteBucketTagging 
 GetBucketEncryption 
 GetBucketLocation 
 GetBucketTagging 
 GetBucketVersioning 
 HeadBucket 
 ListBuckets 
 ListDirectoryBuckets 
 PutBucketEncryption 
 PutBucketTagging 
 PutBucketVersioning 
 PutBucketCors 
 DeleteBucketCors 
 PutBucketAnalyticsConfiguration 
 ListBucketAnalyticsConfigurations 
 DeleteBucketAnalyticsConfiguration 
 CreateSession 
 Bucket replication 
 GetBucketReplication 
 PutBucketReplication 
 DeleteBucketReplication 
 Bucket lifecycle 
 GetBucketLifecycle 
 GetBucketLifecycleConfiguration 
 PutBucketLifecycle 
 PutBucketLifecycleConfiguration 
 DeleteBucketLifecycle 
 Bucket notifications 
 GetBucketNotification 
 GetBucketNotificationConfiguration 
 PutBucketNotification 
 PutBucketNotificationConfiguration 
 Bucket policies 
 GetBucketPolicy 
 GetBucketPolicyStatus 
 PutBucketPolicy 
 DeleteBucketPolicy 
 Unsupported bucket API operations 
 GetBucketInventoryConfiguration
 PutBucketInventoryConfiguration
 DeleteBucketInventoryConfiguration
 GetBucketMetricsConfiguration
 PutBucketMetricsConfiguration
 DeleteBucketMetricsConfiguration
 PutBucketWebsite
 GetBucketLogging
 PutBucketLogging
 PutBucketAccelerateConfiguration
 DeleteBucketAccelerateConfiguration
 PutBucketRequestPayment
 DeleteBucketRequestPayment
 PutBucketAcl
 HeadBucketAcl
 GetPublicAccessBlock
 PutPublicAccessBlock
 DeletePublicAccessBlock
 GetBucketOwnershipControls
 PutBucketOwnershipControls
 DeleteBucketOwnershipControls
 GetBucketIntelligentTieringConfiguration
 PutBucketIntelligentTieringConfiguration
 ListBucketIntelligentTieringConfigurations
 DeleteBucketIntelligentTieringConfiguration
 GetBucketAnalyticsConfiguration
 MinIO AIStor alternatives for unsupported bucket API operations 
 For calls to BucketACL or ObjectACL operations, use Policies .
 For calls to BucketWebsite operations, use caddy or nginx .
 For calls to BucketAnalytics , BucketMetrics , or BucketLogging operations, use Bucket notifications .
 S3 extensions 
 MinIO AIStor extends the S3 API with additional capabilities.
 Object checksums 
 MinIO AIStor accepts a checksum on write, returns it on read, and reports it through GetObjectAttributes . Send the digest in the header for the algorithm you are using, and name that algorithm in x-amz-checksum-algorithm .
 Algorithm | Header | 
 CRC32 | x-amz-checksum-crc32 | 
 CRC32C | x-amz-checksum-crc32c | 
 CRC64NVME | x-amz-checksum-crc64nvme | 
 SHA1 | x-amz-checksum-sha1 | 
 SHA256 | x-amz-checksum-sha256 | 
 MD5 | x-amz-checksum-md5 | 
 SHA512 | x-amz-checksum-sha512 | 
 XXHASH64 | x-amz-checksum-xxhash64 | 
 XXHASH3 | x-amz-checksum-xxhash3 | 
 XXHASH128 | x-amz-checksum-xxhash128 | 
 CRC32, CRC32C, CRC64NVME, SHA1, and SHA256 are the algorithms AWS S3 defines. MD5, SHA512, XXHASH64, XXHASH3, and XXHASH128 are a MinIO AIStor extension, so a client written against AWS S3 will not recognize them.
 x-amz-checksum-type reports how the checksum covers the object:
 FULL_OBJECT — the digest covers the whole object.
 COMPOSITE — the digest is a hash of the individual part digests, so it changes when the part layout changes, even if the content does not.
 Checksums in listings 
 ListObjects , ListObjectsV2 , and ListObjectVersions report the checksum algorithm and type for each object, matching AWS S3.
 Returning the digest itself is a MinIO AIStor extension. A listing returns digests only when it requests object metadata and the caller is permitted to read the object. A caller holding s3:ListBucket alone receives the algorithm and type, but no digest.
 Checksums on objects encrypted with SSE-S3 or SSE-KMS are decrypted for the listing. An SSE-C checksum is sealed as a whole, so neither the digest nor the algorithm is readable without the client key.
 S3 over RDMA 
 On a deployment running the RDMA build, GetObject , PutObject , and UploadPart can transfer object data directly between client memory and the server over RDMA, using the AWS S3 RDMA protocol. GetObject writes into the client’s buffer; PutObject and UploadPart read from it. That buffer is usually GPU memory, which is where RDMA pays off most, but host memory works too and needs no GPU.
 The client opts in per request with a header; there is no server setting.
 Header | Direction | Description | 
 x-amz-rdma-token | Request | The client’s RDMA buffer descriptor. | 
 x-amz-rdma-reply | Response | 200 or 206 when the transfer used RDMA, 501 when the server declined. | 
 x-amz-rdma-bytes-transferred | Response | Bytes transferred out of band, when non-zero. | 
 On a successful RDMA transfer the server sets Content-Length: 0 , because the object bytes did not travel in the HTTP response.
 When the server declines, it returns an S3 error response rather than serving the object over HTTP. Retrying without the x-amz-rdma-token header is the client’s responsibility. The MinIO SDKs below handle this automatically.
 Reliable Connection clients first perform a handshake at POST /rdma/connect , exchanging descriptors through the same x-amz-rdma-token header. Dynamically Connected clients do not use this route.
 SDK support 
 S3 over RDMA is supported by the MinIO SDKs for Go, C++, Rust, and Python.
 Each of them uses NVIDIA cuObjClient to move the object payload between GPU memory and the network adapter.
 For worked examples in each language, see Transfer Objects over RDMA .
 For deployment, see RDMA acceleration .
 S3 Express mode 
 When MinIO AIStor runs in S3 Express mode , the supported S3 API surface differs from the default S3 API mode. S3 Express mode also adds the AppendObject behavior, which lets a client append data to an existing object by issuing a PutObject request with the x-amz-write-offset-bytes header. For the list of operations supported and disabled in S3 Express mode, see S3 Express mode .
 MinIO-specific error codes 
 In addition to the standard S3 error codes, MinIO AIStor returns the following MinIO-specific error codes:
 Code | HTTP status | Description | 
 NotSupported | 501 | API operation not implemented. | 
 NotImplemented | 501 | KMS not configured or feature unavailable. | 
 XMinioHealNotImplemented | 400 | Healing not available in this mode. | 
 XMinioLDAPNotEnabled | 501 | LDAP must be enabled for this operation. | 
 InvalidToken | 400 | Object Lambda output token mismatch. | 
 LambdaFunctionStatusError | 400 | Object Lambda function returned an invalid status. | 
 RDMATransferError | 503 | An S3-over-RDMA transfer failed. Retry the request, without the x-amz-rdma-token header to fall back to HTTP. | 
 KMS error codes 
 KMS-backed operations return these codes, including when the KMS itself is unreachable:
 Code | HTTP status | Description | 
 kms:NotAuthorized | 403 | The KMS credentials lack permission for the operation. | 
 kms:KeyNotFound | 404 | No key exists with the given key ID. | 
 kms:KeyAlreadyExists | 409 | A key already exists with the given key ID. | 
 kms:InvalidCiphertextException | 400 | The ciphertext could not be decrypted. The key material does not match. | 
 kms:DecryptionFailed | 503 | The decryption request could not be completed at all, for example because the KMS was unreachable. Unlike kms:InvalidCiphertextException , this does not imply invalid ciphertext. Retry the request. | 
 kms:NotSupported | 501 | The configured KMS does not support the requested functionality. | 
 kms:KeyCreationFailed | 503 | The KMS could not create the key. | 
 kms:KeyDeletionFailed | 503 | The KMS could not delete the key. | 
 kms:KeyListingFailed | 503 | The KMS could not list keys. | 
 kms:KeyGenerationFailed | 503 | The KMS could not generate a data key. | 
 A request that the client cancels while a KMS operation is in flight returns status 499 rather than a KMS error.
 Changed in RELEASE.2026-08-07T18-34-35Z
 A KMS-backed request previously returned 500 whatever the cause. It now returns 503 when the KMS is unreachable, which distinguishes a retryable outage from an invalid ciphertext, and 499 when the client cancels the request.
 Update any client retry logic or alerting rule that keys on a 500 response to a KMS-backed operation.
 Cookie Preferences 
 All rights reserved 2024-Present, MinIO, Inc.
 On this page
 Object APIs Conditional headers 
 Object locking 
 Unsupported object APIs 
 Multipart uploads 
 Bucket APIs Bucket replication 
 Bucket lifecycle 
 Bucket notifications 
 Bucket policies 
 Unsupported bucket API operations 
 MinIO AIStor alternatives for unsupported bucket API operations 
 S3 extensions Object checksums 
 S3 over RDMA 
 S3 Express mode 
 MinIO-specific error codes KMS error codes 
 Page Feedback
 Was this page helpful?
 Yes No 
 Thank you for your feedback!
 How can we improve this page?
 Your feedback Email address (optional) Optionally provide your email if you would like us to follow up on your feedback Please enter a valid email address Submit Feedback Cancel 
 Sending feedback...
 Failed to send feedback. Please try again.
 Retry
