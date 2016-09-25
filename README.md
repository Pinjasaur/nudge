# nudge

`write` your buddies a random message

## Usage

You'll want to configure the `$users` variable to specify the usernames that
you're looking to message. Since it's being piped directly to `grep` you'll
want to delimit them with pipes (`|`) for a proper regex.

The messages being sent can be configured in the `$phrases` variable.

If you'd like to be extra persistent and annoying you can setup the script to
run periodically as a cronjob.

## Contributing

Could this be improved? Fork the repo, commit your changes, and send a pull
request my way.

## Thanks

Shoutout to [@pjbirr](https://github.com/pjbirr) and
[@galordmtu](https://github.com/galordmtu) for helping with testing and such.

## License

Licensed under [MIT License](/LICENSE).
