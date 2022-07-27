### Hi there 👋
```php
<?php

namespace Putra;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'PT.Kompas Media Nusantara',
                'position' => 'Software Engineer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Golang::class,
            Laravel::class,
            Javascript::class,
            Docker::class,
            Firestore::class,
            MySQL::class,
            Redis::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Code, Sleep, Repeat!';
    }
}
```

<!--
**putrapratamanst/putrapratamanst** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
