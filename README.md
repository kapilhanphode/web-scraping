# Web-Scraping-Project

## Web Scraping has many names, such as Web Harvesting, Screen Scraping, and others. It is a method of extracting large quantities of data from websites and storing it at a particular location (a local file in your computer or a database in a table). 

## First, we need to navigate to the target webpage by making HTTP requests and downloading the response.

So start with importing the required libraries (i.e., requests and BeautifulSoup). Now, setting up the URL and header variable. The first variable reserve the URLs to crawl, and the second variable reserve your request User-agent id, which is for authentication at the time of making HTTP requests.

# Importing required libraries
from flask import Flask, render_template, request,jsonify
from flask_cors import CORS,cross_origin
import requests
from bs4 import BeautifulSoup as bs
from urllib.request import urlopen as uReq
