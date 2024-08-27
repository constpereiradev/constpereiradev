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
                'lastPosition' => 'Jovem Aprendiz',
                'currentPosition' -> 'Auxiliar de Desenvolvimento Junior',
                'months' => '11'         
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
            'semester' => '2°',
            'modality' => 'EaD'
        ]
    }

    public function getStatus(): string
    {
        return 'Open to learn and work.';
    }
}
```




