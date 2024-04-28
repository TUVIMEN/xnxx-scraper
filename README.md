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

It works as recursive spider getting urls from every page starting from URL.
Resulting files are named by the sha256 of their url and saved to DIR.

    xnxx-scraper DIR URL
