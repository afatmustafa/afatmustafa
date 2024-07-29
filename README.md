```php
<?php

namespace MustafaAfat;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Miova',
                'company_website' => 'miova.com.tr',
                'position' => 'Co-Owner & Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Vuejs::class,
            Javascript::class
        ];
    }
    
    public function getCurrentlyLearning(): array
    {
         return [
            Shopify::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```

<br/>
<div align="center">
    <a href="https://afat.me" target="_blank">
<img src=https://img.shields.io/badge/afat.me-svg?style=for-the-badge alt=afat.me style="margin-bottom: 5px;" />
</a> 
<a href="https://twitter.com/afatmus" target="_blank">
<img src=https://img.shields.io/badge/twitter-%2300acee.svg?&style=for-the-badge&logo=twitter&logoColor=white alt=twitter style="margin-bottom: 5px;" />
</a>
<a href="https://linkedin.com/in/afatmustafa" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<a href="https://instagram.com/afatmustafa" target="_blank">
<img src=https://img.shields.io/badge/instagram-%23000000.svg?&style=for-the-badge&logo=instagram&logoColor=white alt=instagram style="margin-bottom: 5px;" />
</a>
</div>
