-----------------------------
|||||||||||||||||||||||||||||
Step #1:
|||||||||||||||||||||||||||||
-----------------------------
$ mongod --port 27017 --dbpath C:\wamp\www\whateverjs\storage\database\dev
[or] 
$ mongod --storageEngine=mmapv1 --port=27017 --dbpath=C:\wamp\www\whateverjs\storage\database\dev
(RECOMMENDED)
[or] 
$ mongod --storageEngine mmapv1 --port 27017 --dbpath C:\wamp\www\whateverjs\storage\database\dev
-----------------------------

-----------------------------
|||||||||||||||||||||||||||||
| Step #2: 
|||||||||||||||||||||||||||||
-----------------------------
$ node app.js
-----------------------------

