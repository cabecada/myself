SRE at Opentable.

Not from a DBA background, but when i was given the task to help local dev team in settin up Postgres,

Within 6 months 
I was able to setup postgres cluster (one primary and multiple hot standby for reads) 
Make use of pgbouncer connection pooling
Scale the read nodes by putting them behind haproxy with health check as replication lag.
Failover or promote a hot standby to primary.
Taking database dumps and restoring them.
Migrating databases from postgres 9.6 to postgres 10 with downtime less than few minutes.
Postgres database monitoring using collectd and sensu.
Sending postgres logs to ELK stack.
Using barman to configure point in time recovery for databases.
Basic POC for ssl hardening of postgres databases.
Puppetizing the sharded postgres cluster using foreign data wrappers and exported resources.
Being able to take over primary support for postgres for SF team when the core postgres DBA was on leave.
Understand the multimaster mesh structure across zones using pg10 logical partitioning.
Follow a lot of postgres companies blogs and newsletters along with postgres mailing list to build more awareness.
Attended PGCon2018 in Bangalore to help understand the current state of the product.

Last 18 months
I was hired as an SRE at Opentable. 
The intial role was to monitor uchiwa dashboards and send mails and follow up with application team.
Even though it was boring, I used it as an oppurtunity to learnt the various components of product we use at Opentable.
I jumped into understanding why graphite based checks failed, for various teams, that helped me understand of how graphite works.
I jumped into monitoring Kibana dashboards to understand the behaviour various dashboards, that helped me understand ELK stack.
I oversaw discussions in hipchat channels wrt sensu issues, and gradually started taking part in supporting
not just Opentable sensu support, but upstream sensu support.
I had the entire sensu stack setup in my vagrant (using rabbitmq, redis, sensu-api/uchiwa, sensu-server, sensu-client).
This helped me understand not just puppetized setup of these nodes, but HA setup of each component and issues that arise 
out of that setup.
I have been very effective in communicating with cross regional teams and it was the reason the India team was made the 
owner of senusu as a product that was used at Opentable. I did upgrades of sensu across Opentable infrastrucure that involved
breaking changes.
I totally love vagrant and virtual box on my macbook pro. I setup 7-8 vms with private networking and play around
setting up different infrastructure components beyond sensu such as graphite (using synthesize), ELK + filebeat, mesos + singularity
Postgres cluster, Rabbitmq cluster, Redis cluster being haproxy and many more OSS.
I have used foreman for spinning up vms.
Have basic understanding of VMWare and using Vsphere Web to bump up server resources.



