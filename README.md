# sm-log-exporter

Export [StreamMachine](https://github.com/StreamMachine/StreamMachine) session
logs from Elasticsearch as W3C or SoundExchange files, for importing to
external analytics systems.

## Prereqs

* Node.js (~0.10)
* HTTP access to the Elasticsearch server with SM logs

## Use examples
./runner-cmd --server http://elasticsearch:9200 --index your-index --start 2017-03-01 --end 2017-03-31 --format soundexchange --zone 'America/Argentina/Buenos_Aires' > soundexchange.log
