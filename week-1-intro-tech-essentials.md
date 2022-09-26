# Week 1: Introduction and Technical Essentials

---

## AWS Partner: Accreditation (technical)  (4 hours)

- Fundamental, technical knowledge of AWS cloud computing, global infrastructure, services, solutions, migration, and security.

### Objectives

- [ ] Articulate the value of key AWS services and features.
- [ ] Apply AWS services toward customer solutions.
- [ ] Adopt AWS architectural and cost optimization best practices.
- [ ] Present AWS solutions to customers.
- [ ] Demonstrate the value of constructing proofs of concept (POCs).
- [ ] Assemble an action plan for successful customer engagements.
- [ ] Identify APN resources for APN Partners.

### Meet Maria

- AWS Solution Architect at APN Partner
- Work in pre-sales technical assessments

### Cloud Computing Overview

#### Benefits of Cloud Computing

- Traditional on-premises - maintain physical servers
- On-demand delivery of compute power, database, storage, application, and other IT resources via the internet with pay-as-you-go pricing
- Cloud service provider owns and maintains hardware, users provision resources they need
- Agility
  - Easy access to a broad range of tech
  - Faster innovation
  - Quickly spin-up resources as needed
  - Deploy in minutes
  - Faster experimentation / testing / implementation
- Elasticity
  - No need to overprovision resources for peak loads
  - Use resources actually needed
  - Autoscale up and down as needs change
- Cost savings
  - Change CAPEX to OPEX
  - Economies of scale
- Deploy globally in minutes
  - Worldwide infrastructure
  - Deploy in multiple physical locations
  - Physically closer to user, reduce latency
- AWS Products
  - Compute
  - storage
  - database
  - analytics
  - networking
  - mobile
  - developer tools
  - management tools
  - IoT
  - security
  - enterprise applications

### AWS GLobal Infrastructure

- Multiple regions worldwide
- Completely isolated from other regions
- Fault tolerance
- Isolated from each other
- Multiple Availability Zones (AZs) within regions
  - Separate, but connected with low-latency fiber
- Local ZOnes
  - Compute, storage, and database close to large population centers
  - Wavelength Zones - 5g edge computing
  - Direct Connect Locations
    - Connect directly to AWS via private network
  - Cloudfront
    - Web service
    - Regional edge caches

### Compute

- Develop, deploy, run, and scale
- EC2 (Elastic Compute Cloud)
  - Secure
  - sizable
  - Over 400 instances with different cores, memory, os
- EC2 Auto Scaling
- Elastic Load Balancing
- Elastic Container Service (ECS)
  - Managed cluster
  - Docker
  - Fargate
    - Serverless pay as you go
    - ECS / EKS
- Elastic Kubernetes Service (EKS)
  - EC2 or Fargate
  - Automanages availability and scalability
- Lambda
  - Compute service
  - Serverless
  - Event-driven
- Benefits
  - Elasticity
    - Increase and decrease within minutes instead of hours or days
    - Maintain availability
    - Automatically scale up and down to maximize performance and minimize costs
  - Complete control
  - Flexibility
    - Many instance types
  - Integrated
    - Rith other AWS sercices
  - Reliable
    - High availability
  - Secure
    - Secure architecture
  - Cost Effective
    - Pay for what you use
  - Easy
    - Dashboard
    - CLI
    - SDK
- Instance types
  - Hardware and softare
  - Categories
    - General Putpose
      - mac
      - A
      - T
      - M
    - COmpute Optimized
    - Memory Optimized
    - Accelerated Computing
      - Coprocessors
      - Graphics
      - Pattern matching
      - Floating point operations
    - Storage Optimized
      - High sequential read/write access
  - Sizes
    - Nano
    - Small
    - Medium
    - large
    - xlarge
    - 2xlarge
  - AMI
    - Initial image
      - Linux
      - mac
      - Window
      - From AWS, AWS marketplace, user community, or own.
  - Autoscaling Group
    - Minimum
    - Maximum
    - Desired Capacity
  - Elastic Load Balancing
    - Automatically distributes traffic across multiple EC2 instances
    - Increases availability and fault tolerance
    - Configure health checks
    - Offload encryption and decryption
    - Application Load Balances
      - HTTP
      - Application Level
    - Network Load balancers
    - Gateway Load Balancers

### Storage

- Every time a server is set up, there needs to be storage
- S3 - object store
  - Storage for the internet
  - Store and retrieve any amount of data from anywhere
  - Glacier
    - Secure, digital backup and archive
- AWS Storage Gateway
  - Hybrid cloud storage
  - Connect on-premises applications to AWS storage
  - File Gateway
    - NFS and SMB
  - Volume Gateway
    - iSCSI
  - Tape Gateway
    - VTL
- EBS - block store
  - Like hard drive for instance
  - Persistent
  - Durable
  - Block-level
  - Network attached storage
  - Independent of instance on / off
  - Automatically replicated within AZ
  - Can only be attached to one instance at a time
  - Can be reattached from new instance
  - Snapshots stored in S3
    - Instantiate new volumes
    - Copied across regions
- EFS - file store
  - Network file system
  - Shared file system
  - Mount to multiple EC2 instances
- FSx for Windows File Server
  - Managed service
  - Windows file system
  - SMB

---

## Introduction to AWS AOrganizations (6 min)

---

## AWS Technical Essentials (4 hours)

---

## SAA Week 1 Content Review

---

## Building your first Amazon VPC (1 hour)

---

## Launching Amazon EC2 Instancess (1 hour)