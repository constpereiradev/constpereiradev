<h1>Amanda Pereira</h1>

```php
<?php

namespace AmandaPereira;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Bomix',
                'position' => 'Jovem Aprendiz'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Bootstrap::class
        ];
    }

    public function getCurrentCollege(): string
    {
        return [
            'university' => 'Universidade Federal de Mato Grosso do Sul',
            'semester' => '1°'
            'modality' => 'EaD'
        ]
    }

    public function getStatus(): string
    {
        return 'Open to learn and work.';
    }
}
```




