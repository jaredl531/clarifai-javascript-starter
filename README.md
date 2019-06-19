# Clarifai JavaScript Starter
A simple quickstart example that I created to help users interact and get familiar with the Clarifai Javascript client and API. The accompanying blog post can be found [here](https://blog.clarifai.com/test-visual-recognition-models-with-clarifais-v2-api-javascript-starter).

## How to get started
Download this repo, simply invoke  
```script
$ npm install
```

## Usage

To get started, create an account at [clarifiai.com](http://clarifai.com/signup).

Once you do this you'll be able to retrieve your API Key via the [portal](https://portal.clarifai.com/apps), where you can simply click on your application to do so:

<img src="https://jared-hack-projects.s3.us-east-2.amazonaws.com/clarifai-javascript-starter/api-key.png" width="400"/>

This basic starter uses your API Key to make prediction calls and it will never expire so you only have to fill this in once.

You'll notice that the `.gitignore` file references a `keys.js` file. This is for security purposes so that you don't share your API Key with others.  Add your key to that file in the myApiKey variable:

```
var myApiKey = 'YOUR API KEY HERE';
```

You'll also notice a custom_train.js file which serves as a reference for Custom Training. Any custom models that you create (under these credentials) will appear in the dropdown menu on index.html, next to the "Custom" label.

## User Interface 

<img src="https://jared-hack-projects.s3.us-east-2.amazonaws.com/clarifai-javascript-starter/main-screen.png"/>

The left-side menu will let you predict with any of Clarifai's [public models](https://www.clarifai.com/models).<br/>

## Example Output

<img src="https://s3.amazonaws.com/jared-clarifai-stuff/Screen+Shot+2017-01-05+at+4.04.37+PM.png"/>

Note the "Add image to Application" button on the bottom left of the image. This will automatically add the image to the application that is associated with your key!
