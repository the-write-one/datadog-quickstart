If you want to learn more about [Datadog](http://datadog.com) you are in the right spot. Read on, it's fun, I promise.

<a href="http://www.flickr.com/photos/alq666/10125225186/" title="The view from our roofdeck">
<img src="http://farm6.staticflickr.com/5497/10125225186_825bfdb929.jpg" width="500" height="332" alt="_DSC4652"></a>

## Prerequisites - Setup the environment

You can utilize any OS/host that you would like to follow the steps and procedures.
However, we recommend one of the following approaches:

* You can spin up a fresh linux VM via Vagrant or other tools so that you donΓÇÖt run into any OS or dependency issues. [Here are instructions](https://github.com/jeremy-lq/hiring-engineers/blob/tech-writer/README.md#vagrant) for setting up a Vagrant Ubuntu 12.04 VM.
* You can utilize a Containerized approach with Docker for Linux and our dockerized Datadog Agent image.

Then, sign up for Datadog (use ΓÇ£Datadog Recruiting CandidateΓÇ¥ in the ΓÇ£CompanyΓÇ¥ field), get the Agent reporting metrics from your local machine.

## Quick Start Guide

Please see our [DataDog Quick Start Guide](QuickStart.md) for details on the following topics:

### Collecting Metrics:

* Add tags in the Agent config file and show us a screenshot of your host and its tags on the Host Map page in Datadog.
* Install a database on your machine (MongoDB, MySQL, or PostgreSQL) and then install the respective Datadog integration for that database.
* Create a custom Agent check that submits a metric named my_metric with a random value between 0 and 1000.
* Change your check's collection interval so that it only submits the metric once every 45 seconds.
* **Bonus Feature** Change the collection interval without modifying the Python check file you created?

### Visualizing Data:

Utilize the Datadog API to create a Timeboard that contains:

* Your custom metric scoped over your host.
* Any metric from the Integration on your Database with the anomaly function applied.

Include the script that we've used to create this Timemboard.

Access the Dashboard from our Dashboard List in the UI:

* Set the Timeboard's timeframe to the past 5 minutes
* Take a snapshot of this graph and use the @ notation to send it to yourself.
* **Bonus Feature**: What is the Anomaly graph displaying?

## Additional In-Depth Details:

The Datadog community has written a substantial number of high quality integrations and libraries. Publicly available
libraries are located on [this page](https://docs.datadoghq.com/developers/libraries/). With this selection in mind, the following blog post picks one selection and explains the benefits it offers our users/community. The post covers installation, configuration, usage, and best practices along with code samples where applicable. Here we also thank the contributor for their effort.

For the blog post, please see our article [Managing Errors at Saturation Point in Node.js Using DogStatsD and Hot-Shot Client](blog/blog.md).

## References

### How to get started with Datadog
* [Datadog getting started](https://docs.datadoghq.com/getting_started/)
* [Guide to graphing in Datadog](http://docs.datadoghq.com/graphing/)
* [Guide to monitoring in Datadog](https://docs.datadoghq.com/monitors/)

### The Datadog Agent and Metrics

* [Guide to the Agent](http://docs.datadoghq.com/agent/)
* [Datadog Docker-image repo](https://hub.docker.com/r/datadog/docker-dd-agent/)
* [Writing an Agent check](https://docs.datadoghq.com/agent/agent_checks/)
* [Datadog API](https://docs.datadoghq.com/api/)

### APM
* [Datadog Tracing Docs](https://docs.datadoghq.com/tracing)
* [Flask Introduction](http://flask.pocoo.org/docs/0.12/quickstart/)

### Vagrant
 * [Setting Up Vagrant](https://www.vagrantup.com/intro/getting-started/)

### Other questions:

* [Datadog Help Center](https://help.datadoghq.com/hc/en-us)
