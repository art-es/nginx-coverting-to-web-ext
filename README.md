# Nginx config for converting images to webp extension

> Подключить файл webp-ext.conf в блоке http (один раз, для всех сайтов)  
``` 
http { 
    ... 
    
    include webp-ext.conf; 
} 
```

--- 

> Подключить файл webp.conf в блоке server (для каждого сайта)  
```
server {
    ...

    include webp.conf;
}
```