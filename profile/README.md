## Hi 👋, we hope you love Business Intelligence too!

ScaledBI is an open source project, developed in the context of the EARL 2022 London conference, that illustrates how to enable data-driven decision making in organizations through domain-driven Business Intelligence (BI). It is designed to address the issues with classical BI, which can become a bottleneck in organizations due to its centralized nature.

ScaledBI illustrates how to use [ShinyProxy](https://www.shinyproxy.io/), a low cost, tool-agnostic framework for hosting and scaling BI tools such as Apache-Zeppelin, Jupyter, and R-Markdown notebooks, as well as providing IDEs such as R-Studio or Visual Studio Code. It is part of the Data Mesh initiative, which aims to establish a domain-oriented bureaucracy for developing BI within a Federated Governance structure. 

# Table of Contents
- [🏫 Introduction](#main-idea)
- [📊 Getting started with ScaledBI](#getting-started-with-scaledbi)
- [😎 About Us](#about-us)


# 🏫 Introduction <a name = "main-idea"></a>
Business Intelligence is crucial for enabling organizations to use insights from data and make informed decisions. To scale BI, it is important to establish a domain-oriented bureaucracy that can develop its own BI within a Federated Governance structure. This is exactly what ScaledBI provides.

# 📊 Getting started with ScaledBI <a name = "getting-started-with-scaledbi"></a>

The ScaledBI project consists of multiple repositories, including:

The projects consists of multiple repositories such as:

- [ShinyProxy](https://github.com/ScaledBI/shinyproxy) to orchestrate docker containers

- [PostgresSQL](https://github.com/ScaledBI/demo-postgres) containing dummy data

- [Apache-Zeppelin](https://github.com/ScaledBI/demo-zeppelin)  containing demo notebooks

- [Jupyter](https://github.com/ScaledBI/demo-jupyter) containing demo notebooks

- [Tableau](https://github.com/ScaledBI/demo-tableau) containing demo dashboard

- [R-Studio](https://github.com/ScaledBI/shinyproxy-rstudio-ide-demo) containing demo IDE

- [R-Shiny](https://github.com/ScaledBI/shinyproxy-demo) containing demo dashboard

- [R Markdowns](https://github.com/ScaledBI/demo-R-project) containing demo notebooks

To get started with ScaledBI, follow these steps:

1. Clone the demo-postgres repository and execute the following command in the /demo-postgres project to deploy a Postgres database and create the dummy data dependencies:

```bash
sh build-image.sh
```

2. Clone the ShinyProxy repository and execute the following command in the /shinyproxy project to build the ShinyProxy Docker image:

```bash
sh build-image.sh
```

3. Run ShinyProxy using Docker Compose:

```bash
docker-compose up
```

4. Open your web browser and go to http://localhost:8080. You should see the

# 😎 About Us <a name = "about-us"></a>

We are business intelligence professionals who are interested in bringing data mesh into the field of BI. Our passion for data-driven decision making led us to create ScaledBI, a summary of different approaches designed to enable organizations to adopt domain-driven Business Intelligence. By pointing out a low cost and tool-agnostic approach to hosting and scaling BI tools, we hope to address the issues with classical BI and make it easier for organizations to access the insights they need to thrive.

