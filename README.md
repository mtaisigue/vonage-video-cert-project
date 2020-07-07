## Video certification

1. Clone the repository
2. Add your Tokbox API KEY & SECRET to `video/application_server/routes/tkbx.js` and `video/web_client/js/app.js`.
3. Install `http-server` and serve the client files

```
npm install -g http-server
cd video/web_client
http-server . 
```
4.`cd` into `video/application_server/` and run `npm install && npm start`

Note: check the output from ```http-server .``` command, Usually it is ```127.0.0.1:8080``` for the next step.

5. Open a browser and type 127.0.0.1:8080, Repeat this step using a different browser. You should be able to see your self in both cases.

# CST Training EMEA

Training session February 2020

### Prerequisites

#### Nexmo CLI

Open your terminal and type `npm install nexmo-cli@beta -g`

Set up the Nexmo CLI to use your Nexmo API Key and API Secret. You can get these from the settings page in the Nexmo Dashboard.

Run the following command in a terminal, while replacing `api_key` and `api_secret` with your own:

`nexmo setup api_key api_secret`

#### Ngrok

Ngrok is a service that will expose your server to the outside world-

Install ngrok https://ngrok.com/ and run an http tunnel using the following command:

```
./ngrok http PORT_NUMBER
```

#### IDE

You can use your favorite IDE. We recommend: https://code.visualstudio.com/

## Voice

Voice hands-on: [go!](./voice/README.md)

## Video

Video hands-on: [go!](./video/README.md)
