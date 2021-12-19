# CI Plans

## Unity

```diagram
                ❌          ❌            ❌
PR/Release -> Tests    -> Builds  -> Publishing
              Takhisis    iOS        GH Release
              Nuitari     Android    Appstore Conntect
              Gilean                 Google Play
```

### Takhisis

Сервис проверки 3д моделей и их разверток

Критерии проверки:

- следование конвенции
- кол-во полигонов
- оптимизация (например, есть ли полигоны которые можно объединить в один)
- адекватность развертки (эмпирический критерий)
- корректность пивота (эмпирический критерий)

https://github.com/gradientspace/geometry3Sharp

### Nuitari

Сервис проверки кода:

- следование конвенции
- тесты

### Gilean

Сервис проверки проекта

- следование конвенции
- отсутствие дубликатов ассетов
 