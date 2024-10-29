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
                'lastPosition' => [
                    'title' => 'Jovem Aprendiz',
                    'months' => 7
                 ],
                'currentPosition' -> [
                    'title' => 'Auxiliar de Desenvolvimento Junior',
                    'months' => 6
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
            Bootstrap::class,
            Advpl::class,
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




