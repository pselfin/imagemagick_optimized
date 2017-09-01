# imagemagick_optimized

Версия модуля для Drupal 8

Update Imagemagick by Niklan - https://niklan.net/blog/139

# Инструкция

* Первым делом необходимо установить и включить модуль ImageMagick - https://www.drupal.org/project/imagemagick

Внимание! Нужен модуль 8.x-2.x

Versions 8.x-2.x: The module requires using Composer to manage Drupal site dependencies. Require the module via
$ composer require drupal/imagemagick:~2.0
then enable the module as usual.

*  После включения перейти на страницу /admin/config/media/image-toolkit и вы увидите что появилось чем пережимать.
* Настроить имедж меджик
* Включить модуль imagemagickniklanupd
* очистить кеш drush cr
* и кеш пресетов drush image-flush --all