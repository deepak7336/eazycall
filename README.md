## Running the Web App on your Local Device

To run the web app in your local device, run the following commands in your terminal (macOS) or command prompt (Windows) :-

-Clone the GitHub repository into your local device by running the following command:

```bash
cd folder-you-want-to-download-code-in

git clone https://github.com/deepak7336/eazycall.git

cd eazycall
```

-Now that you're in the project folder, open terminal to download the needed node modules:

```bash
npm install
```

-Now run the server by running the following command:

```bash
npm start
```

The server should be running at <strong>localhost:3000</strong><br>
If localhost:3000 shows busy on your device, run the following commands:

```bash
sudo lsof -i :3000

kill -9 <PID>
```

Now localhost:3000 is free to run this application.
<br>
<br>
-To access the web app, in your project code folder, navigate to public/landing-page and from there open landing.html on any browser of your preference (Chrome recommended for best experience).<br><br>

## Technologies Used

1. Node.js
2. HTML
3. CSS
4. Bootstrap
5. JavaScript
6. WebRTC
7. Socket.io

## Future Possible Functionalities

1. Add a sign up/authentication page
2. Improve upon the Adapt functionality in the web app
3. Add an additional feature of breakout rooms
4. Increase Scalability
