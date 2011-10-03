Module: Commerce PayDollar
Author: Pratomo Ardianto


Description
===========
Integrates PayDollar as a payment gateway for Drupal Commerce (http://drupal.org/project/commerce) - Drupal 7 by using credit card,
which support for VISA, MasterCard, American Express, JCB, and Diners Club.
Provides an options to select between live and test environment of PayDollar payment.

Note:
Currently is not supported for 3D Transaction yet.
As I actually need to experience more with this type of payment.


Requirements
============

* Commerce



Installation
============

* Copy the 'commerce_paydollar' module directory in to your Drupal
  sites/all/modules directory as usual.

* Enable the module from the Modules -> Commerce PayDollar section


Setup
=====
* Go to Store -> Configuration -> Payment methods -> enable PayDollar.

* Edit PayDollar settings and select whether you want to operate in the test or the
  live environment, input your merchant id and hash password (provided by PayDollar)
  and select whether you want transactions to use 3D Transaction or not.


