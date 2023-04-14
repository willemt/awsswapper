# AWS Swapper

awsswapper is a Python package that simplifies the process of switching between different AWS accounts. It enables you to manage multiple AWS profiles and regions more easily, allowing you to perform operations on different accounts with a simple command.

# Installation

To install awsswapper, run the following command:

```bash
pip install awsswapper
```

# Usage

The primary command for awsswapper is swap. Use it to switch between profiles and regions.

To switch to a specific profile and region, run:

```bash
awsswapper swap <profile_name> --region <region_name>
```

For example, to switch to profile1 with the ap-southeast-2 region, use:

```bash
awsswapper swap profile1 --region ap-southeast-2
```

## Listing Profiles
To list available AWS profiles, run:

```bash
awsswapper list-profiles
```

# Configuration

awsswapper relies on the standard AWS CLI configuration files. Ensure that your AWS credentials and profiles are properly set up in the following files:

- ~/.aws/credentials: Contains your access keys and secret access keys
- ~/.aws/config: Contains profile configurations, including default regions

# License

This project is licensed under the MIT License. See the LICENSE file for more details.

# Disclaimer

This tool is not affiliated with, sponsored, or endorsed by Amazon Web Services, Inc.
