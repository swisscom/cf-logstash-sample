# cf-logstash-sample
A sample configuration for use with the Logstash buildpack to build the ELK stack. 

## Parameters
The files `Logstash` and `conf.d/output.conf` contain parameters which need to be replaced by the corresponding values for your environment.

### `Logstash`
* `USERNAME`: the username for securing your Logstash instance
* `PASSWORD`: the password for securing your Logstash instance

### `conf.d/output.conf`
* `ELASTICSEARCH_HOST`: the hostname of your Elasticsearch instance (taken from the environment of your Logstash app)
* `ELASTICSEARCH_USER`: the user for your Elasticsearch instance (taken from the environment of your Logstash app)
* `ELASTICSEARCH_PASSWORD`: the password for your Elasticsearch instance (taken from the environment of your Logstash app)
