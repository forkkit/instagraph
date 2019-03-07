# Instagraph
> Social graph network of your instagram account.

<p align="center"><img width=100% src="https://github.com/ahmdrz/instagraph/raw/master/resources/screenshot.png"></p>

### Build (recommended)

```
$ go build -i -o instagraph
$ ./instagraph -username="" -password=""
```

##### Parameters

1. username: Username of your instagram account.
2. password: Password of your instagram account.
3. limit: Limit of users in first depth scan of your followings.
4. delay: Sleep time between each user scan.
5. users-limit: Maximum number of users in each followings scan request.

### Docker

```
$ docker pull ahmdrz/instagraph:latest
$ docker run -e INSTA_USERNAME="" -e INSTA_PASSWORD="" -p 8080:8080 ahmdrz/instagraph:latest
```

---

<p align="center"><img width=100% src="https://raw.githubusercontent.com/ahmdrz/instagraph/master/resources/screenshot2.png"></p>

---

Powered with :heart: by `sigma.js` and `ahmdrz/goinsta`.
