# xnxx-scraper

A bash script for scraping xnxx videos metadata in json.

## Requirements

 - [reliq](https://github.com/TUVIMEN/reliq)
 - [jq](https://github.com/stedolan/jq)

## Installation

    install -m 755 xnxx-scraper /usr/bin

## Json format

Here's example of a [video](video-example.json).

## Usage

Data is saved into files named by the sha256sum of their url.

Download metadata of video to DIR

    xnxx-scraper -d DIR URL URL URL

Pass video URLS into the recursive spider using 8 threads

    xnxx-scraper -t 8 -V URL URL URL

Get some help

    xnxx-scraper -h
