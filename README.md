```php
<?php

class About extends Me {
    private string $name = 'Marcel';
    private string $user = 'maersux';
    private int $age = 24;

    public function getSocials() {
        return [
            'instagram': '@maersux',
            'twitch': '@maersux'
        ];
    }
}
```
