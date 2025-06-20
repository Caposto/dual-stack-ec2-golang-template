# Dualstack EC2 Instance Template in Golang

# TODO: LICENSE

This project is inspired by Jan Schaumman's blog post: [Creating AWS IPv4/IPv6 Dual Stack EC2 Instances](https://www.netmeister.org/blog/ec2-ipv6.html).

With this code, a user should be able to fill in some infromation in a yaml file, and than use the AWS CDK to deploy theproper AWS services into a certain region. Once those resources are deployed, the user will be able to create a dual stack EC2 instance in that region that can use both IPv4 and IPv6.

## Getting Started

### Prerequisites
* Install and configure the AWS CDK CLI. [Docs](https://docs.aws.amazon.com/cdk/v2/guide/getting-started.html)

## Architecture

# Welcome to your CDK Go project!

This is a blank project for CDK development with Go.

The `cdk.json` file tells the CDK toolkit how to execute your app.

## Useful commands

 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template
 * `go test`         run unit tests