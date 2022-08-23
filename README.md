```php
<?php

namespace MustafaAfat;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Verymoney',
                'position' => 'Lead Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Vuejs::class,
            Nuxtjs::class,
            Javascript::class,
            Aws::class,
            MongoDb::class,
        ];
    }
    
    public function getCurrentlyLearning(): array
    {
         return [
            Reactjs::class,
            Shopify::class,
            Deno::class,
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
<a href="https://twitter.com/afatmus" target="_blank">
<img src=https://img.shields.io/badge/twitter-%2300acee.svg?&style=for-the-badge&logo=twitter&logoColor=white alt=twitter style="margin-bottom: 5px;" />
</a>
<a href="https://dev.to/afatmustafa" target="_blank">
<img src=https://img.shields.io/badge/dev.to-%2308090A.svg?&style=for-the-badge&logo=dev.to&logoColor=white alt=devto style="margin-bottom: 5px;" />
</a>
<a href="https://linkedin.com/in/afatmustafa" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<a href="https://instagram.com/afatmustafa" target="_blank">
<img src=https://img.shields.io/badge/instagram-%23000000.svg?&style=for-the-badge&logo=instagram&logoColor=white alt=instagram style="margin-bottom: 5px;" />
</a>
<a href="https://hashnode.com/@afatmustafa" target="_blank">
<img src=https://img.shields.io/badge/hashnode-%232962FF.svg?&style=for-the-badge&logo=hashnode&logoColor=white alt=hashnode style="margin-bottom: 5px;" />
</a>  
</div>
