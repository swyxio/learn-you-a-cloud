# learn-you-a-cloud

## official sources

AWS

- http://aws.training/ Video courses & certifications
- https://aws.amazon.com/whitepapers/ Whitepapers for those who like to read ([intro category](https://aws.amazon.com/whitepapers/?whitepapers-main.sort-by=item.additionalFields.sortDate&whitepapers-main.sort-order=desc&awsf.whitepapers-content-category=content-category%23intro))

cost vs onprem https://news.ycombinator.com/item?id=23089999#23100852


Market Share

![https://cdn.benzinga.com/files/u101977/cloud.png](https://cdn.benzinga.com/files/u101977/cloud.png)
 
## misc

base rates https://github.com/sirupsen/napkin-math
GCP vs AWS https://cloud.google.com/docs/compare/aws

AWS vs Azure https://docs.microsoft.com/en-us/azure/architecture/aws-professional/services#feedback


aws db's https://medium.com/@nicholasmwalsh/aws-databases-deep-dive-season-1-recap-61827ea7f471

azure https://burkeholland.github.io/posts/laws-of-serverless/


brian leroux - multicloud - https://shoptalkshow.com/403/

## Ideas

portability

- data
- workflow - terraform is useful even to single cloud companies. hashimoto lemmas
- workload
- traffic 

main things you want

- compute
- networking
- storage

5 things to define cloud 
 https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/five-characteristics-that-define-the-cloud-with-nicole-forsgren-phd/
on demand self service
broad network/device access
rapid elasticity
resource pooling (multitenant) 
measure service (control, optimise, report) 

## SNS + SQS

https://www.helenanderson.co.nz/aws-a-z/


Jeremy Daly vs kineseis vs sns vs sqs https://github.com/sw-yx/learn-you-a-cloud

## Serverful

- https://segment.com/blog/when-aws-autoscale-doesn-t/

![https://assets.contents.io/asset_VZAy69XEkrpT8e4p.png](https://assets.contents.io/asset_VZAy69XEkrpT8e4p.png)

## Storage

https://www.backblaze.com/blog/backblaze-b2-s3-compatible-api/

## k8s

https://caleblloyd.com/software/crds-killed-free-kubernetes-control-plane/

## Interesting Follows

- @chrismunns
- @QuinnyPig
- @theburningmonk
- @jeremy_daly
- @alexbdebrie
- https://twitter.com/AWSbrett

## Key Podcasts

- https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/episode-67-infrastructure-as-code-with-terraform-and-mitchell-hashimoto/
- https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/the-staying-power-of-kubernetes-with-kelsey-hightower/


## Fun Facts

https://medium.com/descarteslabs-team/thunder-from-the-cloud-40-000-cores-running-in-concert-on-aws-bf1610679978

AWS Supercomputer - $5,000 on the company credit card for the use of a “high-network-throughput instance block” consisting of 41,472 processor cores and 157.8 gigabytes of memory. It then worked out some software to make the collection act as a single machine. Running the standard supercomputer test suite, called LinPack, the system reached 1,926.4 teraFLOPS

compared to o $20 to $30 million. Not to mention a 6–12 month wait time.

Lambdas can optimize themselves and add slow moving persistent state by updating their own code
- https://www.youtube.com/watch?v=mYduv751N6g

## Dynamodb

- https://fauna.com/blog/a-comparison-of-scalable-database-isolation-levels

## Tricks

Storage

- lambda for secondary storage https://www.honeycomb.io/blog/secondary-storage-to-just-storage/
