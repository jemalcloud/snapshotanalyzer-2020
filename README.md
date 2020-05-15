# snapshotanalyzer-2020

## About
Demo project to manage AWS EC2 instance snapshots.

## How to configure

In my case "shotty" or anyname you provide with config file, uses the configuration file generated from AWS cli. e.g

`aws configure --profile shotty`

## How to run it
`pipenv run python shotty/shotty.py <command> <subcommand> <--project=PROJECT>`


*command* is instances, volumes, or snapshots
*subcommand* - depends on commands=
*project* is optional
