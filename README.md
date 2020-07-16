# PHP Package Example
A quick test composer package, published on Packagist

RUN: composer require spackage/firstpackage:dev-master

then run your code here



require '../vendor/autoload.php';

use spackage\firstpackage\Index;

$greeting = new Index();

echo $greeting->greet("Hello Composer");


