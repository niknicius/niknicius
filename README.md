# Vinnicius Santos
[![Linkedin Badge](https://img.shields.io/badge/-vinnicius-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/vinnicius-santos/)](https://www.linkedin.com/in/vinnicius-santos/)
[![Gmail Badge](https://img.shields.io/badge/-vinnicius.santos@dcx.ufpb.br-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:vinnicius.santos@dcx.ufpb.br)](mailto:vinnicius.santos@dcx.ufpb.br)

```php
<?php

namespace VinniciusSantos;

class About extends Me
{
    public function getCurrentWorkplaceInfo()
    {
        return [
            'workplace' => [
                'company' => 'Nelogica',
                'position' => 'Backend Software Developer',
                'type' =>  WorkType.FULL_TIME
            ]
        ];
    }
    
    public function getCurrentCollegeInfo(){
        return [
            'college' => [
                'name' => 'UFPB'
                'semester' => 9,
                'forming' => true
            ]
        ]
    }

    public function getKnowledge()
    {
        return [
            PHP::class,
            Javascript::class,
            Laravel::class,
            Java::class,
            Delphi::class,
            Angular::class,
            SpringBoot::class,
            NestJS::class,
            GraphQL::class,
            Aws::class,
        ];
    }
}
```
