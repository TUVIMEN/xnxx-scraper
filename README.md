# xnxx-scraper

A bash script for archiving xnxx videos metadata in json.

## Requirements

 - [hgrep](https://github.com/TUVIMEN/hgrep)
 - [jq](https://github.com/stedolan/jq)

## Installation

    install -m 755 xnxx-scraper /usr/bin

## Json format

Here's example of a [video](video-example.json).

## Usage

It works as recursive spider getting urls from every page starting from URL.
Resulting files are named by the sha256 of their url and saved to DIR.

    xnxx-scraper DIR URL
