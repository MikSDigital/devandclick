Nice Symfony tutorial:
========================
* https://www.youtube.com/watch?v=2ngvCQd-l74&list=PLzPK7Fy3SN2cvLglujdweDKNMNQhHDbTT

1. use psr-4 autoload in composer.json:
  ```json
        "psr-4": {
            "AppBundle\\": "src/AppBundle",
            "EcommerceBundle\\" : "src/Ecommerce/EcommerceBundle"
        },
```

2. php bin/console generate:bundle into src/Ecommerce folder

3. composer dump-autoload