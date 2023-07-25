# google-tag-manager

## Overview

**Google Tag Manager** is a [Tag Management System](https://en.wikipedia.org/wiki/Tag_management_system) (TMS) that allows you to quickly and easily update measurement codes and related code fragments, collectively known as **Tags**, on your Website or Mobile App.

Once the small segment of Tag Manager Code has been added to your Project, you can safely and easily deploy Analytics and Measurement Tag Configurations from a Web-Based User Interface.

https://marketingplatform.google.com/about/tag-manager/

## Usage

[Helm](https://helm.sh) must be installed to use this Chart.

Please refer to Helm's [Documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add gtm https://jobtome-labs.github.io/google-tag-manager

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of this Chart.

You can then run `helm search repo gtm` to see the Chart.

To install the Google Tag Manager Chart:

    helm install gtm gtm/google-tag-manager

To uninstall the Chart:

    helm delete gtm
