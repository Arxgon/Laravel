# Laravel

My Laravel Learning Path

# Pre request

- [x] PHP Language
- [x] OOP PHP
- [x] MVC Concept

# What i've done

1. Setup
   1. install xampp along with the PHP
   2. install composer
   3. install Laravel global installer
   4. Configure the Valet for windows{
      get some error for intalling this package:
      `Problem 1 - mnapoli/silly[1.7.0, ..., 1.7.1] require symfony/console ~3.0|~4.0 -> found symfony/console[v3.0.0, ..., v3.4.47, v4.0.0, ..., v4.4.37] but it conflicts with your root composer.json require (^6.0). - mnapoli/silly[1.7.2, ..., 1.7.3] require symfony/console ~3.0|~4.0|~5.0 -> found symfony/console[v3.0.0, ..., v3.4.47, v4.0.0, ..., v4.4.37, v5.0.0, ..., v5.4.3] but it conflicts with your root composer.json require (^6.0). - cretueusebiu/valet-windows[2.4.0, ..., 2.4.1] require mnapoli/silly ^1.7 -> satisfiable by mnapoli/silly[1.7.0, 1.7.1, 1.7.2, 1.7.3]. - Root composer.json requires cretueusebiu/valet-windows ^2.4 -> satisfiable by cretueusebiu/valet-windows[2.4.0, 2.4.1].`
      Resolve
      `composer require cretueusebiu/valet-windows:*`
      then add valet to the environtment path manually
      }
