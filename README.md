# generate-it-asyncapi-models-to-json

WARNING: This is currently a proof of concept set of templates and is liable to many changes. Please fork this repository should you want to use these templates.

## What it does
When building an event fully/partially based architecture system with https://github.com/acrontum/generate-it-asyncapi-rabbitmq-fanout it can be helpful to have a generated mock somewhere in your orchestration for testing purposes.

This set of templates will generate an object of all the sub and pub model definitions and run through https://github.com/acrontum/generate-it-mockers.

This can then allow the automation of prefabricated objects to pass around for testing purposes without having to manually build and maintain such objects.

As stated at the top of this readme, this is current only a POC; the name and structure is liable to change.