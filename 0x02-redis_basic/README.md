# 0x0B. Redis basic

## Description
What you should learn from this project:

---

### [0. Writing strings to Redis](./exercise.py)
* Create a Cache class. In the __init__ method, store an instance of the Redis client as a private variable named _redis and flush the instance using flushdb.


### [1. Reading from Redis and recovering original type](./exercise.py)
* Redis only allows to store string, bytes and numbers (and lists thereof). Whatever you store as single elements, it will be returned as a byte string. Hence if you store "a" as a UTF-8 string, it will be returned as b"a" when retrieved from the server.


### [2. Incrementing values](./exercise.py)
* Familiarize yourself with the INCR command and its python equivalent.


### [3. Storing lists](./exercise.py)
* Familiarize yourself with redis commands RPUSH, LPUSH, LRANGE, etc.


### [4. Retrieving lists](./exercise.py)
* In this tasks, we will implement a replay function to display the history of calls of a particular function.

---
