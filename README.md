# Ozone - The Configuration Project
>_The entreprise-grade health information system that augments OpenMRS 3._

This is the official Maven project for configuring the free and open-source software flavour of Ozone, aka **Ozone FOSS**.
This Maven project makes it easy to build and package the configuration artifacts of Ozone FOSS.

:bulb: **Did you know?** There is a *pro* flavour of Ozone, aka **Ozone Pro**, that adds a number of entreprise features to Ozone FOSS.

## 1. Overview
It bundles all the configuration files of **FOSS distribution of Ozone** as a **Maven project** that the [distro project](https://github.com/ozone-his/ozone-distro) depends upon.

The configuration is separated by architectural or functional areas:

1. **Ozone**
<br/>_TBC → explain here what this Ozone config allows_
1. **OpenMRS**
<br/>A space to provide overrides and supplements to [OpenMRS 3's config](https://github.com/openmrs/openmrs-distro-referenceapplication/tree/main/distro/configuration).
1. **EIP**
<br/>Configuration for [EIP client](https://github.com/mekomsolutions/eip-client), the Spring Boot app that provides Camel messaging routes between Ozone HIS' components.
1. **Odoo**
<br/>A space to provide the Odoo configuration files to be loaded by the [Odoo Initializer add-on](https://github.com/mekomsolutions/odoo-initializer#odoo-initializer-add-on).
1. **SENAITE**
<br/>A space to provide Plone configurations that have been exported through the [ZMI](https://training.plone.org/5/mastering-plone/configuring_customizing.html#zmi-zope-management-interface) and that are automatically loaded by the [Plone Initializer](https://github.com/mekomsolutions/plone.initializer).
1. **Superset**<br/>A space to provide Superset YAML configuration files, see
   * [_Importing and Exporting Datasources_](https://superset.apache.org/docs/miscellaneous/importing-exporting-datasources/#importing-and-exporting-datasources) (Superset docs)
   * [_Apache Superset / Preset : How to import and export dashboards and dataset_](https://www.youtube.com/watch?v=hqgwOGwGOXk) (YouTube short tutorial made by Preset)

This project is separated from the Ozone distro project for development and versioning purposes, however its sole purpose is to be repackaged by the distro project. There is little value in building it separatly, however this can be done with the usual `mvn clean package`.

## 2. Try Ozone
Check [ozone-docker](https://github.com/ozone-his/ozone-docker).

## 3. Find us
[Slack](https://openmrs.slack.com/archives/C02PYQD5D0A) - [Forum](https://talk.openmrs.org/c/software/ozone-his) - [Website](http://ozone-his.com)

<sub>:information_source: Self sign-up [here](https://slack.openmrs.org/) before accessing our Slack space for the first time.</sub>
## 4. Report an issue
1. Either start a conversation on [Slack](https://openmrs.slack.com/archives/C02PYQD5D0A) about it,
1. Or start a thread on our [forum](https://talk.openmrs.org/c/software/ozone-his) about it.
