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
                'firstPosition' => [
                    'company' => 'Bomix',
                    'title' => 'Jovem Aprendiz de Desenvolvimento',
                    'months' => 7
                 ],
                'secondPosition' -> [
                    'company' => 'Bomix',
                    'title' => 'Auxiliar de Desenvolvimento Junior',
                    'months' => 7
                ],
                'currentPosition' => [
                    'company' => 'Blue',
                    'title' => 'Desenvolvedor Backend Junior',
                ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Symfony::class,
            Sqlsrv::class,
            MySQL::class,
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




