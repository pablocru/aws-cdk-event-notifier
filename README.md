# AWS CDK Event Notifier

AWS CDK construct in TypeScript that sends email notifications for events, like
S3 bucket object creation and deletion, using Amazon SES managed as IaC.

## Motivation

This project started as an exercise to practice Infrastructure as Code with AWS
CDK, with the goal of demonstrating best practices (restricted IAM, templates as
assets, unit and infrastructure tests) and serving as a starting point for
larger projects that need this kind of notifications.
