## Dependencies

1. Install [node.js](http://nodejs.org/#download).
2. Install [MongoDB](http://www.mongodb.org/downloads).
3. Start the MongoDB server from a terminal window:
<pre>
$ mongod
</pre>
4. Install [Redis](http://redis.io/download).
5. Start the Redis Server from another terminal window:
<pre>
$ redis-server
</pre>
6. Make sure your current directory is option7_node_socketio before step 7.
<pre>
$ pwd
[your repos path]/backbone-boilerplates/option7_node_socketio
</pre>
7. Install dependencies using the node package manger (npm).
<pre>
$ sudo npm link
</pre>

## Running the Demo

1. Start the server from a different terminal window:
<pre>
$ node app
</pre>
2. Visit [http://localhost:3000](http://localhost:3000) in a web browser.

## Credit

- [Jérôme Gravel-Niquet](http://jgn.me/) - Created original demo
- [Addy Osmani](http://addyosmani.com/) - Cleanup, edits
- [James O'Reilly](http://jamesor.com/) - Added server-side tech from node.js to MongoDB.

## License

Public Domain