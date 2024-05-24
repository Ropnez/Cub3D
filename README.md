# Cub3D Projesi

## İçindekiler
- [Hakkında](#hakkında)
- [Özellikler](#özellikler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Teşekkür](#teşekkür)

## Hakkında
Cub3D, 42 École programının bir parçası olarak geliştirilmiş basit bir 3D oyun motoru ve FPS oyunudur. Bu proje, temel raycasting tekniklerini ve oyun motoru geliştirme süreçlerini anlamanızı sağlamak amacıyla oluşturulmuştur.

## Özellikler
- Temel raycasting
- Basit FPS oyun mekaniği
- Harita oluşturma ve okuma
- Temel düşman AI (yapay zeka)
- Çeşitli oyun içi öğeler ve etkileşimler

## Kurulum
Cub3D'yi kendi makinenizde çalıştırmak için aşağıdaki adımları izleyin.

### Gereksinimler
- GCC veya benzeri bir C derleyicisi
- Make
- MinilibX (42 tarafından sağlanan bir grafik kütüphanesi && proje içersinde mevcut)

### Adımlar
1. Depoyu klonlayın:
    ```sh
    git clone https://github.com/ropnez/Cub3D.git
    ```
2. Proje dizinine gidin:
    ```sh
    cd cub3d
    ```
3. Projeyi derleyin:
    ```sh
    make
    ```

## Kullanım
Cub3D'yi çalıştırmak için terminalde aşağıdaki komutu kullanın:
```sh
./cub3D harita.cub
```
Cub3D, belirttiğiniz harita dosyasını kullanarak oyunu başlatır. Örneğin:
```sh
./cub3D maps/map1.cub
```

## Teşekkür

Bu projede yardımlarından dolayı aysozen'e teşekkür ederim.
