Hello World! :)

This is my first React project. Tried to do bits and pieces, setting up ESlint, Prettier, Babel and Parcel. And I got everything to work fine, yaaay. :)

For security reasons, I have removed API_KEY and API_SECRET keys from .env file in the root directory of project, so obviously app will not work as it should without it.

So if you want to start the app and see it fully working, you will need to register to this website:

https://www.petfinder.com/developers/api-key

And get your own API keys, because we are using "Petfinder" API to get the animal informations. Petfinder is based in US, so it is not available all around the world, only in few countries.

Once you get your keys, you can open the .env file in the root directory, and populate API data in there.
Then navigate to rood folder from terminal, run these commands:

npm install
npm run dev

And you should have running application on your localhost.

Thanks a lot to Petfinder for making their API available for usage, credits to them.
