# Page Speed Report

A lightweight page-speed reporting tool powered by the Google PageSpeed Insights API. Check up to five URLs in one report and compare mobile and desktop Lighthouse results.

## Features

- Choose a page type: Home, Product, Collection / category, Webpage, Blog, or Other.
- Add up to five URLs per report.
- View Performance, Accessibility, Best Practices, and SEO scores.
- Review key Lighthouse metrics and optimization opportunities.
- Download results as CSV or JSON, or print the report to PDF.

## Run locally

Open `index.html` in a modern browser, enter one or more `https://` page URLs, and select **Run page report**. The tool sends requests directly to the Google PageSpeed Insights API; an internet connection is required.

## API key security

The current page calls the PageSpeed Insights API from browser JavaScript. Any API key embedded in client-side code is visible to visitors and in network requests. Restrict the key in Google Cloud to the PageSpeed Insights API and suitable usage limits. For a production deployment, keep the key on a server and have the page call a server-side endpoint instead. Do not commit API keys to a public repository.

## Live site

Check it out: https://codebykavi-hub.github.io/page-speed/
