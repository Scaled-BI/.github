<p align="center">
    <img src="images/ScaledBI.png" alt="scaledbi-banner">
</p>


## Hi 👋, we hope you love Business Intelligence too!

ScaledBI has been developed in the context of the [EARL 2022 London](https://www.ascent.io/earl) conference to illustrate the idea of distributed and domain-driven Business Intelligence.  Thus, ScaledBI fits right into the various [Data Mesh](https://www.oreilly.com/library/view/data-mesh/9781492092384/) initiatives across organizations.

The project consists of various examples of how to deploy apps using [ShinyProxy](https://www.shinyproxy.io/). We made an attempt to consolidate various web-based interactive computing platforms into one common umbrella which we call ScaledBI.

**Overall ScaledBI is an open source project to illustrate how to enanble your organization to make data-driven decisions.**

# Table of Contents
- [🏫 Introduction](#main-idea)
- [📊 Getting started with ScaledBI](#getting-started-with-scaledbi)
- [😎 About Us](#about-us)


# 🏫 Introduction <a name = "main-idea"></a>
In comparison to other quantitative fields such as Machine Learning, Data Science or Data Engineering, Business Intelligence (BI) doesn't appeal that sexy. However, Business Intelligence is crucial to enable organizations to use insights from data and make informed decisions. In order to meet this expectation, it must possess certain characteristics and, above all, be scalable.

### Issues with *Classical BI*
Imagine being a part of an organization, which has a central BI team responsible for delivering data products such as shared datasets, analyses, reports and dashboards based on some agreed requirements. Given that centralized nature, the BI team is not able to handle all the analytical questions quickly enough and may become a bottleneck.
### Alternative way doing BI
In comparison to the to the centralized way of doing BI, the domain-driven approach underscores the role of various domains by enabling them to design, build, and run their data applications within a *standardized infrastructure*.

### Scaling Business Intelligence
Accordingly, to be able to scale Business Intelligence, the first step is to establish a domain-oriented bureaucracy that can develop its own Business Intelligence within a Federated Goverence. It is exactly this Federated Goverence that ScaledBI provides. 
**That is, a low cost, tool-agnostic framework, which is able to host and scale Apache-Zeppelin, Jupyter and R-Markdown notebooks as well as providing IDEs such as R-Studio or Visual Studio Code**


# 📊 Getting started with ScaledBI <a name = "getting-started-with-scaledbi"></a>


## Overview
The projects consists of multiple repositories such as:

- [ShinyProxy](https://github.com/ScaledBI/shinyproxy) to orchestrate docker containers

- [PostgresSQL](https://github.com/ScaledBI/demo-postgres) containing dummy data

- [Apache-Zeppelin](https://github.com/ScaledBI/demo-zeppelin)  containing demo notebooks

- [Jupyter](https://github.com/ScaledBI/demo-jupyter) containing demo notebooks

- [Tableau](https://github.com/ScaledBI/demo-tableau) containing demo dashboard

- [R-Studio](https://github.com/ScaledBI/shinyproxy-rstudio-ide-demo) containing demo IDE

- [R-Shiny](https://github.com/ScaledBI/shinyproxy-demo) containing demo dashboard

- [R Markdowns](https://github.com/ScaledBI/demo-R-project) containing demo notebooks

## Quick Installation 
**(via Docker and Docker-Compose)**

Simply clone [demo-postgres](https://github.com/ScaledBI/demo-postgres) and execute
in the `/demo-postgres` project the following
```sh
sh build-image.sh
```
which deployes a postgres-db and creates the dummy data dependencies.

Next clone [ShinyProxy](https://github.com/ScaledBI/shinyproxy) and execute

in the `/shinyproxy` project the following

```sh
sh build-image.sh
```
which downloads *shinyproxy-2.6.1.jar* For more on configuring and orchestration of your BI please visit [ShinyProxy](https://www.shinyproxy.io/documentation/configuration/)

Next open http://localhost:8080/ and fill in *simple* [credentials](https://github.com/ScaledBI/shinyproxy/blob/main/application.yml#L16)

