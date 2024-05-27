# REDIS-Holy Grail Exercise


## Description of the project:
I've developed an app that utilizes the HOLY GRAIL pattern, integrating Redis with both the front-end and back-end functionalities. I've specifically employed version 3 of Redis. 

One notable challenge I encountered revolved around getting Redis to function smoothly. I've utilized Redis version 3, ensuring compatibility between Docker and Redis versions. If there's a need to upgrade to Redis 4, it's essential to refer to the following information to ensure seamless operation of your app: [Redis Node.js Client: Migrating from v3 to v4](https://github.com/redis/node-redis/blob/HEAD/docs/v3-to-v4.md).

## How to Run:

To get started, clone this code to your local directory and then execute the following commands in your command line interface (CLI):


```bash
docker run -d --name some-redis -p 6379:6379 redis:3
npm i redis@3
node index.js
```

Afterward, you can access the code at the link <localhost:3000>. Additionally, utilize <localhost:3000/data> to retrieve data and <localhost:3000/update/{replacefornameofsection}/{replaceforvalue}> to update values for each section of the holy grail. Ensure you're using Node version 16 or higher after running the commands above (you can check the version with `node -v` and switch to version 16 using `npm use 16`).

## Improvemnets to work on:

I want integrate nodemon in this app. Nodemon is a handy tool that automatically saves updates in the code and reloads, ultimately saving me valuable time.

## License information:
MIT license.

## Support
If you have any questions, please don't hesitate to contact me Julieth at my email address <juliethpbautista@gmail.com>. Also I'm open to your ideas and suggestions, and I'm confident that our combined talents could lead to exciting and innovative results. If you're interested in discussing potential projects or exchanging ideas, please let me know.

Let's start a conversation and see where our collaboration might take us.


