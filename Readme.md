# Defra flood warning layout

Defra page template for showing flood warnings in the Gov.uk Prototype kit

## How to install

`npm install cathydutton/layout-defra-flood-warning#master`

## How to include

`{% set floodWarningClass = "alert" %}
{% set floodWarningTitle = "Flooding is possible - be prepared" %}`

`{% set floodWarningClass = "warning" %}
{% set floodWarningTitle = "Flooding expected - Take action" %}`

`{% set floodWarningClass = "severe" %}
{% set floodWarningTitle = "Danger to life" %}`


`{% extends 'layout-defra-flood-warning.html' %}`


## License

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").