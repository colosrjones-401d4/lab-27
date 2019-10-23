# lab-27

# React Testing and Deployment

## AWS Deploy(http://lab27aws.s3-website.us-east-2.amazonaws.com)

## [![Netlify Status](https://api.netlify.com/api/v1/badges/ee8d5428-3894-400e-8448-1417f8a7e87d/deploy-status)](https://app.netlify.com/sites/optimistic-dubinsky-df1c0d/deploys)

## [![Build Status](https://travis-ci.org/colosrjones-401d4/lab-27.svg?branch=master)](https://travis-ci.org/colosrjones-401d4/lab-27)


## Learning Objectives

* Write and Execute Snapshot tests for a React Application
* Write and Execute Enzyme (live) tests for a React Application
* Deploy a React applicaation to AWS S3 manually
* Deploy a React application to cloudfront directly from github

### AWS Deployments
* Buckets
  * Storage containers for static assets
* Cloud Front
  * The Cloud! Your stuff all over the planet, with a secure URL
* Cloud Formation and Code Deploy
  * Deployment pipleline that connects Github, Buckets and Cloud Front

### React Testing
* **Snapshots** - Make assertions on the *exact* generated markup at any state of the application.
* **Render Testing** - Similar to snapshots, but allows for jQuery-like inspection of the virtual DOM tree
* **Shallow Testing** - Executes and renders the called/container component, but does not compose children.
* **Mounting** - Executes the full component and children. Allows for inspection of rendered Virtual DOM as well as the current state

Using a combination of approaches, you can easily "use" your application and ensure that things are changing both visually and physically (elements and state) as you expect.

