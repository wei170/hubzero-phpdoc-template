# hubzero-phpdoc-template
A phpdoc responsive template for hubzero-cms api

## Overview
This is a responsive template for [phpdoc](http://www.phpdoc.org) to generate doc
for [hubzero](https://github.com/hubzero).

## Usage
1. In the hubzero-cms, 
  `$ composer require --dev phpdocumentor/phpdocumentor`

2. Copy this template into the phpDocumentor

   `$ cp -p ./ <address_of_hubzero-cms>/core/vendor/phpdocumentor/phpdocumentor/data/templates/responsive `

3. Go to the `hubzero-cms/core` directory

   `$ cd <address_of_hubzero-cms/core>`

4. Run phpDocumentor directly from your `vendor` directory in the `core` directory

	`$ ./vendor/phpdocumentor/phpdocumentor/bin/phpdoc -d ./components -d ./plugins -d ./templates -d ./vendor/hubzero/framework/src -t <address_of_doc> --title "Hubzero Api Documentation" --template="responsive" `

5. It will generates a directory for all the stuff in the hubzero/framework and hubzero-cms/core into the `<address_of_doc>`

