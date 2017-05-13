# Turiknox Webgains Tracking

## Overview

A simple Magento module that will allow you to integrate Webgains tracking code on the checkout success page.

## Requirements

Magento 2.1.x

## Installation

Copy the contents of the module into your Magento root directory.

Enable the module via the command line:

/path/to/php bin/magento module:enable Turiknox_Webgains

Run the database upgrade via the command line:

/path/to/php bin/magento setup:upgrade

Run the compile command and refresh the Magento cache:

/path/to/php bin/magento setup:di:compile 

/path/to/php bin/magento cache:clean

## Usage

Stores -> Configuration -> Turiknox -> Webgains Tracking
