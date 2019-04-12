# Google Authenticator compatible 2-Factor Auth in Java

This project serves as an example of how to build a 2fa support into your website or app. It is the companion code to [this blog entry](http://www.asaph.org/2016/04/google-authenticator-2fa-java.html).

## Requirements:

- Java 8
- Maven 3.x
- Google Authenticator app (available free in the Apple App Store and Google Play)

## Building

To complile the code and package into a jar run:

```shell
mvn clean install
```

## Running

To execute the example code run:

```shell
mvn exec:java
```

1. Note the path shown for the generated QR code PNG file and open that file in your web browser (or any other image viewer).
2. Use the Google Authenticator app on your mobile device to scan the QR code.
3. Confirm that the 6 digit codes generated by the example code match the 6 digit codes generated by the Google Authenticator app.
4. Press ctrl-c at any time to terminate the example program.

## License

All code is licensed under the commercial-friendly [BSD 2-Clause "Simplified" License](LICENSE).

