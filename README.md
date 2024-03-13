<h1>Olá! Bem vindo ao meu perfil no GitHub.</h1>



<div align="center">
  <a href="https://github.com/constpereiradev">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=constpereiradev&layout=compact&langs_count=7&theme=dracula"/>
 

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
                'position' => 'Trainee'         
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
        ]
    }

    public function getStatus(): string
    {
        return 'Open to learn and work.';
    }
}
```




