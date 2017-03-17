# HTTP Response Sender

A simple function that will send PSR-7 `ResponseInterface` headers and body.

## Usage

```php
// Import the send() function for usage.
use function Http\Response\send;

// Any ResponseInterface instance can be used.
$notFound = $responseFactory->createResponse(404);

// Send headers and body.
send($notFound);
```

## License 

MIT
