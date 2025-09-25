---
layout: exam
---

# Practice Exam 01

1. A company collects data for temperature, humidity, and atmospheric pressure in cities across multiple continents. The average volume of data that the company collects from each site daily is 500 GB. Each site has a high-speed Internet connection.
The company wants to aggregate the data from all these global sites as quickly as possible in a single Amazon S3 bucket. The solution must minimize operational complexity.
Which solution meets these requirements

   <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: Turn on S3 Transfer Acceleration on the destination S3 bucket. Use multipart uploads to directly upload site data to the destination S3 bucket. 
      Explanation: 
      General line: Collect huge amount of the files across multiple continents
      Conditions: High speed Internet connectivity
      Task: aggregate the data from all in a single S3 bucket
      Requirements: as quick as possible, minimize operational complexity

      Correct answer A: S3 Transfer Acceleration because:
      - ideally works with objects for long-distance transfer (uses Edge Locations)
      - can speed up content transfers to and from S3 as much as 50-500%
      - use cases: mobile & web application uploads and downloads, distributed office transfers, data exchange with trusted partners. Generally for sharing of large data sets between companies, customers can set up special access to their S3 buckets with accelerated uploads to speed data exchanges and the pace of innovation.
    </details>

2. Questions 2

   <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>
