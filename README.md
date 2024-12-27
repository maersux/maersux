```php
<?php

class About extends Me {
    private string $name = 'Marcel';
    private string $user = 'maersux';
    private int $age = 25;

    public function getSocials(): array {
        return [
            'discord' => '@maersux',
            'duolingo' => '@maersux',
            'instagram' => '@maersux',
            'twitch' => '@maersux',
            'website' => 'https//maersux.dev/'
        ];
    }
}
```
