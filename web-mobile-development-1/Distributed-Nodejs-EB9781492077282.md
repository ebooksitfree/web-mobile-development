![Cover image for Distributed Node.js](https://imgdetail.ebookreading.net/cover/cover/20200920/EB9781492077282.jpg)

[Distributed Node.js](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_1.html "Distributed Node.js")
====================================================================================================================

Author : [Thomas Hunter II](https://ebookreading.net/search/author/Thomas+Hunter+II)

Release Date : 2021/04/01

Book Description
-----------------


    
    Node.js is used by many companies for building performant backend services without sacrificing developer efficiency. Thanks to its approachable API and familiar syntax, Node.js is loved by engineers and used by startups and Fortune 500s alike. Backed by the world's largest package repository, its enterprise foothold is only expected to grow.
In this hands-on guide, author Thomas Hunter II proves that Node.js is just as capable as traditional enterprise platforms for building services that are observable, scalable, and resilient. Intermediate to advanced Node.js developers will find themselves integrating application code with a breadth of tooling from each layer of a modern service stack.
Learn why running redundant copies of the same Node.js service is necessaryKnow which protocol to choose, depending on the situationFine-tune your application containers for use in productionTrack down errors in a distributed setting to determine which service is at faultSimplify app code and increase performance by offloading work to a reverse proxyBuild dashboards to monitor service health and throughputFind out why so many different tools are required when operating in an enterprise environment
  

Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_4.html#idm45615666400968)
    1. [Target Audience](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_4.html#idm45615666237144)
    1. [Goals](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_4.html#idm45615666390040)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_4.html#idm45615666476664)
    1. [Using Code Examples](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_4.html#idm45615666529928)
    1. [O???Reilly Online Learning](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_4.html#idm45615666523544)
    1. [How to Contact Us](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_4.html#idm45615666517448)
    1. [Acknowledgments](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_4.html#idm45615666516888)
1. [1. Why Distributed?](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_5.html#ch_introduction)
    1. [Single-Threaded Nature of JavaScript](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_5.html#ch_introduction_sec)
    1. [Quick Node.js Overview](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_5.html#ch_introduction_sec)
    1. [Sample Applications](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_5.html#ch_introduction_sec)
1. [2. Protocols](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#ch_protocols)
    1. [Request and Response with HTTP](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#ch_protocols_sec_ht)
        1. [HTTP Payloads](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615657234216)
        1. [HTTP Semantics](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615656677640)
        1. [HTTP Compression](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615656617368)
        1. [HTTPS / TLS](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#ch_protocols_sec_ht)
        1. [JSON over HTTP](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615656396328)
        1. [The Dangers of Serializing POJOs](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615656395928)
    1. [API Facade with GraphQL](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#ch_protocols_sec_gr)
        1. [GraphQL Schema](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#ch_protocols_sec_gr)
        1. [Queries and Responses](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615655160920)
        1. [GraphQL Producer](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615655155848)
        1. [GraphQL Consumer](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615655065672)
    1. [RPC with gRPC](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#ch_protocols_sec_gr)
        1. [Protocol Buffers](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615654258872)
        1. [gRPC Producer](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615654258280)
        1. [gRPC Consumer](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_6.html#idm45615654136360)
1. [3. Scaling](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#ch_scaling)
    1. [The Cluster Module](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#ch_scaling_sec_clus)
        1. [A Simple Example](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#idm45615653285576)
        1. [Request Dispatching](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#idm45615653284952)
        1. [Cluster Shortcomings](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#idm45615652983000)
    1. [Reverse proxies with HAProxy](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#ch_scaling_sec_rp)
        1. [Introduction to HAProxy](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#idm45615652497208)
        1. [Load Balancing and Health Checks](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#ch_scaling_sec_rp_s)
        1. [Compression](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#idm45615652461112)
        1. [TLS Termination](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#idm45615652208536)
        1. [Rate Limiting and Back Pressure](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#idm45615652207944)
    1. [SLA and Load Testing](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#ch_scaling_sec_bm)
        1. [Introduction to Autocannon](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#ch_scaling_sec_bm_s)
        1. [Running a Baseline Load Test](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#idm45615651854376)
        1. [Reverse Proxy Concerns](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#ch_scaling_sec_bm_s)
        1. [Protocol Concerns](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#idm45615651572856)
        1. [Formulating an SLA](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_7.html#idm45615651461736)
1. [4. Observability](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#ch_monitoring)
    1. [Environments](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#ch_monitoring_sec_e)
    1. [Logging with ELK](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#ch_monitoring_sec_l)
        1. [Running ELK via Docker](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615651113112)
        1. [Transmitting Logs from Node.js](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615651081416)
        1. [Creating a Kibana Dashboard](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615651080888)
        1. [Running Ad-Hoc Queries](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615650451032)
    1. [Metrics with Graphite, StatsD, and Grafana](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#ch_monitoring_sec_m)
        1. [Running via Docker](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615650352424)
        1. [Transmitting Metrics from Node.js](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615650318936)
        1. [Creating a Grafana Dashboard](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615650318312)
        1. [Node.js Health Indicators](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615649940616)
    1. [Distributed Request Tracing with Zipkin](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#ch_monitoring_sec_t)
        1. [How Does Zipkin Work?](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615649617736)
        1. [Running Zipkin via Docker](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615649617144)
        1. [Transmitting Traces from Node.js](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615655506600)
        1. [Visualizing a Request Tree](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615649417160)
        1. [Visualizing Microservice Dependencies](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615648869304)
    1. [Health Checks](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#ch_monitoring_sec_h)
        1. [Building a Health Check](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615648801704)
        1. [Testing the Health Check](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615648801112)
    1. [Alerting with Cabot](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#ch_monitoring_sec_a)
        1. [Create a Twilio Trial Account](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615648697528)
        1. [Running Cabot via Docker](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#ch_monitoring_sec_a)
        1. [Creating a Health Check](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_8.html#idm45615648689352)
1. [5. Containers](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#ch_containers)
    1. [Introduction to Docker](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#idm45615648130472)
    1. [Containerizing a Node.js Service](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#ch_containers_subse)
        1. [Dependency Stage](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#idm45615647895688)
        1. [Release Stage](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#idm45615647874968)
        1. [From Image to Container](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#idm45615647874376)
        1. [Rebuilding and Versioning an Image](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#idm45615647824680)
    1. [Basic Orchestration with Docker Compose](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#idm45615648128296)
        1. [Composing Node.js Services](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#idm45615647507624)
    1. [Internal Docker Registry](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#ch_containers_subse)
        1. [Running the Docker Registry](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#idm45615647258088)
        1. [Pushing and Pulling to the Registry](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#idm45615647257464)
        1. [Running a Docker Registry UI](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_9.html#idm45615647149384)
1. [6. Deployments](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#ch_deployments)
    1. [Build Pipeline with Travis CI](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615646927288)
        1. [Creating a Basic Project](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615646919032)
        1. [Configuring Travis CI](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615646918440)
        1. [Testing a Pull Request](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615646500840)
    1. [Automated Testing](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#ch_deployments_sec_)
        1. [Unit Tests](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615646407272)
        1. [Integration Tests](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615646406648)
        1. [Code Coverage Enforcement](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615646188984)
    1. [Deploying to Heroku](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#ch_deployments_sec_)
        1. [Create a Heroku App](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615645404696)
        1. [Configure Travis CI](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615645404072)
        1. [Deploy your Application](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615645371096)
    1. [Modules, Packages, and SemVer](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#ch_deployments_sec_)
        1. [Node.js Modules](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#ch_deployments_sec_)
        1. [SemVer (Semantic Versioning)](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#ch_deployments_sec_)
        1. [npm Packages and the npm CLI](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#ch_deployments_sec_)
    1. [Internal npm Registry](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#ch_deployments_sec_)
        1. [Installing Verdaccio](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615644564888)
        1. [Configuring npm to use Verdaccio](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615644557992)
        1. [Publishing to Verdaccio](https://ebookreading.net/view/book/Distributed+Node.js-EB9781492077282_10.html#idm45615644550984)
