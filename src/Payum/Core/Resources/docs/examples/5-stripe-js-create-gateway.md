# 3. Stripe.Js. Create gateway. 

```php
<?php

use Payum\Stripe\StripeJsGatewayFactory;

$factory = new StripeJsGatewayFactory();

$gateway = $factory->create(array(
    'publishable_key' => 'aKey', 
    'secret_key' => 'aKey',
));
```
