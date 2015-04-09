# Railscasts Downloader

Ruby script to download all of Ryan Bate's Railscasts to your computer.

## To download

```
$ git clone https://github.com/chrischattin/railscasts-downloader.git

$ gem install nokogiri
```

Replace `SUBSCRIPTION_KEY = '****************'` with your [railscasts.com](http://railscasts.com/) subscription key.

Then,

```
$ cd railscasts-downloader

$ mkdir episodes

$ ruby download.rb
```

All of the episodes will download to:
```
$ railscasts-downloader/episodes
```

## Credits

Borrowed heavily (mostly copied) from [clekstro](https://github.com/clekstro).

## License

The [MIT License](https://github.com/chrischattin/railscasts-downloader/blob/master/LICENSE) (MIT)
