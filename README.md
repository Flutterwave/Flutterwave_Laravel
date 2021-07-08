<p align="center">
    <img title="Flutterwave" height="200" src="https://flutterwave.com/images/logo-colored.svg" width="50%"/>
</p>

# The Official Flutterwave Laravel Package

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Total Downloads][ico-downloads]][link-downloads]

<!-- [![Build Status][ico-travis]][link-travis]
[![Scrutinizer Code Quality][ico-code-quality]][link-code-quality]
[![Code Coverage][ico-coverage]][link-coverage]
[![Code Intelligence Status][ico-code-intelligence]][link-code-intelligence] -->

> Integrate Flutterwave payment gateway easily with Laravel

-   Go to [Flutterwave Rave Live](https://rave.flutterwave.com/) to get your **`LIVE`** public and private key
-   Go to [Flutterwave Rave Sandbox](https://ravesandbox.flutterwave.com/) to get your **`TEST`** public and private key

## Documentation

1. you need to require the package with composer.

`composer require flutterwavedev/flutterwavelaravel`

2. make sure your register the service provider. Open up config/app.php and add the providers array.

`Flutterwave\Rave\RaveServiceProvider::class`

3. make sure you add Flutterwave to the aliases

`'Flutterwave' => KingFlamez\Rave\Facades\Rave::class`

4. run the command on your terminal

`php artisan vendor:publish --provider="Flutterwave\Rave\RaveServiceProvider"`

##Sample Project using this package

find a sample project [here](https://github.com/bajoski34/flwstore)

## ToDo

-   Support Direct Charges
-   Support Tokenized payment

## Credits

-   [Oluwole Adebiyi (Flamez)][link-author]
-   [Emmanuel Okeke](https://github.com/emmanix2002)
-   [Adebayo Mustafa](https://github.com/AdebsAlert)
-   [Tunde Aromire](https://github.com/toondaey)
-   [Ifunanya Ikemma](https://github.com/Iphytech)
-   [Abhishek Prakash](https://github.com/abhishek6262)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
