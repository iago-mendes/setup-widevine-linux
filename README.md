# Steps

1. Download `libffmpeg.so`
	```sh
	curl -L https://raw.githubusercontent.com/iago-mendes/setup-widevine-linux/main/download/libffmpeg.so > ~/Downloads/libffmpeg.so
	```

2. Copy `libffmpeg.so` to the browser folder
	> change `$BROWSER_FOLDER` with the desired browser folder
	```sh
	sudo cp libffmpeg.so $BROWSER_FOLDER
	```

---

## Possible browser folders

- Opera
	> /usr/lib/x86_64-linux-gnu/opera