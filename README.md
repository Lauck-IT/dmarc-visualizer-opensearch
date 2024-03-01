# dmarc-visualizer

Analyse and visualize DMARC results using open-source tools.

* [parsedmarc](https://github.com/domainaware/parsedmarc) for parsing DMARC reports,
* [OpenSearch](https://opensearch.org/) to store aggregated data.
* [Grafana](https://grafana.com/) to visualize the aggregated reports.

## Usage

This repo was forked from https://github.com/debricked/dmarc-visualizer and was modified
to work with OpenSearch. The original blog post, https://debricked.com/blog/2020/05/14/analyse-and-visualize-dmarc-results-using-open-source-tools/
gives a good idea on how to use the repo. The only thing you will need on top of that
is copying `parsedmarc/parsedmarc.sample.ini` to `parsedmarc/parsedmarc.ini`.

## Screenshot

![Screenshot of Grafana dashboard](/big_screenshot.png?raw=true)
