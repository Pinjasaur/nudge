# nudge

`write` your buddies a random message. `nudge` works by checking who's online
(via `who`), filtering it to users you specify, and sending each one of them a
randomly selected message (via `write`) from an array of messages you specify.

> **NOTE:** this script is developed in an envrionment with RHEL 7.2 and bash
> 4.2.46. It _should_ work in other environments, but your mileage may vary.

## Usage

To execute, simply do `/path/to/nudge`.

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
