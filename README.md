# Kinesis Advantage 360 Pro ZMK Config

This repository contains my personal ZMK configuration for the [Kinesis
Advantage 360 Pro Ergo Keyboard][1].

## Overview

My personal configuration is not using the officially provided software but
is based on my own [fork of ZMK][2] with some modifications to enable some of
the features the stock Kinesis ZMK fork provides.

The main reason for not using the stock Kinesis ZMK fork is to allow me to
use the latest ZMK versions at my own schedule to enable me to use my Advantage
360 pro for active development and contributions to ZMK.

## Features

The following is a list of features my personal [fork of ZMK][2] adds
specifically for the Advantage 360 Pro.

* LED indicator to show which Bluetooth profile is currently in use
* LED indicator to show which ZMK keymap layer is currently active
* LED indicator to show battery charge on both sides
    - \>= 50% charge = green
    - \< 50% charge = yellow
    - \< 20% charge = red

[1]: https://kinesis-ergo.com/shop/adv360pro/
[2]: https://github.com/huber-th/zmk/tree/adv360-personal

