<html>
<p align="center"> 
  <img src="rsts/images/flyte-and-lf.png" alt="Flyte and LF AI & Data Logo" width="300">
</p>

<h1 align="center">
  Flyte
</h1>

<p align="center">
  Flyte is a <b>workflow automation</b> platform for <b>complex</b>, <b>mission-critical data</b>, and <b>ML processes</b> at scale 
</p>

<p align="center">
  <a href="https://github.com/flyteorg/flyte/releases/latest">
    <img src="https://img.shields.io/github/release/flyteorg/flyte.svg" alt="Current Release" />
  </a>
  <a href="https://github.com/flyteorg/flyte/actions/workflows/sandbox.yml">
    <img src="https://github.com/flyteorg/flyte/actions/workflows/sandbox.yml/badge.svg" alt="Sandbox Build" />
  </a>
  <a href="https://github.com/flyteorg/flyte/actions/workflows/tests.yml">
    <img src="https://github.com/flyteorg/flyte/actions/workflows/tests.yml/badge.svg" alt="End-to-End Tests" />
  </a>
  <a href="http://www.apache.org/licenses/LICENSE-2.0.html">
    <img src="https://img.shields.io/badge/LICENSE-Apache2.0-ff69b4.svg" alt="License" />
  </a>
  <img src="https://img.shields.io/github/commit-activity/w/flyteorg/flyte.svg?style=plastic" alt="Commit Activity" />
  <img src="https://img.shields.io/github/commits-since/flyteorg/flyte/latest.svg?style=plastic" alt="Commits since Last Release" />
  <img src="https://img.shields.io/github/milestones/closed/flyteorg/flyte?style=plastic" alt="GitHub Milestones Completed" />
  <img src="https://img.shields.io/github/milestones/progress-percent/flyteorg/flyte/18?style=plastic" alt="GitHub Next Milestone Percentage" />
  <a href="https://flyte.rtfd.io">
    <img src="https://readthedocs.org/projects/flyte/badge/?version=latest&style=plastic" alt="Docs" />
  </a>
  <a href="https://bestpractices.coreinfrastructure.org/projects/4670"><img src="https://bestpractices.coreinfrastructure.org/projects/4670/badge"></a> 
  <img src="https://img.shields.io/twitter/follow/flyteorg?label=Follow&style=social" alt="Twitter Follow" />
  <a href="https://artifacthub.io/packages/search?repo=flyte">
    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/flyte" alt="Flyte Helm Chart" />
  </a> 
  <a href="https://slack.flyte.org">
    <img src="https://img.shields.io/badge/slack-join_chat-white.svg?logo=slack&style=social" alt="Join Flyte Slack" />
  </a>
</p>

<h3 align="center">
  <a href="https://flyte.org">Home Page</a>
  <span> · </span>
  <a href="#quickstart">Quick Start</a>
  <span> · </span>
  <a href="https://docs.flyte.org/">Documentation</a>
  <span> · </span>
  <a href="#roadmap">Live Roadmap</a>
  <span> · </span>
  <a href="#rfc">RFC's & Proposals</a>
  <span> · </span>
  <a href="#features">Features</a>
  <span> · </span>
  <a href="#community--resources">Community & Resources</a>
  <span> · </span>
  <a href="CHANGELOG/">Changelogs</a>
  <span> · </span>  
  <a href="#component-repos">Components</a>
</h3>

</html>

## 💥 Introduction

Flyte is a structured programming and distributed processing platform that enables highly concurrent, scalable, and maintainable workflows for `Machine Learning` and `Data Processing`. It is a fabric that connects disparate computation backends using a type-safe data dependency graph. It records all changes to a pipeline, making it possible to rewind time. It also stores
a history of all executions and provides an intuitive UI, CLI, and REST/gRPC API to interact with the computation.

Flyte is more than a workflow engine -- it uses `workflow` as a core concept, and `task` (a single unit of execution) as a top-level concept. Multiple tasks arranged in a data
producer-consumer order creates a workflow.

`Workflows` and `Tasks` can be written in any language, with out-of-the-box support for [Python](https://github.com/flyteorg/flytekit), [Java and Scala](https://github.com/spotify/flytekit-java).
Flyte was designed to manage the complexity that arises in Data and ML teams and ensure they keep up their high velocity of delivering business impacting features. One way it achieves this is by separating
the control-plane from the user-plane. Thus, every organization can offer Flyte as a service to their end-users where the service is managed by folks who are more infrastructure-focused, while the users use the intuitive interface of Flytekit.


## ⏳ Five Reasons to Use Flyte
- Kubernetes-Native Workflow Automation Platform
- Ergonomic SDK's in Python, Java & Scala
- Versioned, Auditable & Reproducible Pipelines
- Data Aware and Strongly Typed
- Resource Aware and deployed to scale with your organization

<html>
<h2 id="quickstart"> 
  🚀 Quick Start
</h2>
</html>

With [Docker installed](https://docs.docker.com/get-docker/) and [Flytectl installed](https://docs.flyte.org/projects/flytectl/en/stable/index.html), run the following command:

```bash
  flytectl sandbox start
```

This creates a local Flyte sandbox. Once the sandbox is ready, you should see the following message: `Flyte is ready! Flyte UI is available at http://localhost:30081/console`.

Visit http://localhost:30081/console to view the Flyte dashboard.

Here is a quick visual tour of the console:

![Flyte console Example](https://github.com/flyteorg/flyte/raw/static-resources/img/first-run-console-2.gif)

To dig deeper into Flyte, refer to the [Documentation](https://docs.flyte.org/en/latest/index.html).

## ⭐️ Current Deployments & Contributors
<!-- **NOTE**
Please maintain an alphabetical order in the following list -->

- [appliedAI Initiative](https://appliedai.de)
- [Blackshark.ai](https://blackshark.ai/)
- [Freenome](https://www.freenome.com/)
- [Gojek](https://www.gojek.io/)
- [Intel](https://www.intel.com/)
- [LatchBio](https://www.latch.bio/)
- [Level 5 Global Autonomous (Woven Planet)](https://level-5.global/)
- [Lyft](https://www.lyft.com/)
- [MethaneSAT](https://www.methanesat.org/)
- [RunX.dev](https://runx.dev/)
- [Spotify](https://www.spotify.com/)
- [Striveworks](https://striveworks.us/)
- [Union.ai](https://union.ai/)
- [USU Group](https://www.usu.com/)
- [Wolt](https://www.wolt.com)


<html>
<h2 id="roadmap"> 
   🛣️  Live Roadmap
</h2>
</html>

Live roadmap for the project can be found @[Github Live Roadmap](https://github.com/orgs/flyteorg/projects/3).

<html>
<h2 id="features"> 
  🔥 Features
</h2>
</html>

<details>

- Used at _Scale_ in production by **500+** on one deployment. Used in production at multiple firms. Proved to scale to more than **1 million** executions, and **40+ million** containers
- Data Aware and Resource Aware (Allows organizations to separate concerns - users can use the API, platforms/infra teams can manage the deployments and scaling)
- Enables **collaboration across your organization** by:
  - Executing distributed data pipelines/workflows
  - Making it easy to stitch together workflows from different teams and domain experts and share them across teams
  - Comparing results of training workflows over time and across pipelines
  - Simplifying the complexity of multi-step, multi-owner workflows
- **[Get Started quickly](https://docs.flyte.org/en/latest/getting_started.html)** -- start locally and scale to the cloud instantly
- **gRPC / REST** interface to define and execute tasks and workflows
- **Typesafe** construction of pipelines -- each task has an interface characterized by its input and output, so illegal construction of pipelines fails during declaration, rather than at runtime
- Supports multiple **[data types](https://docs.flyte.org/projects/cookbook/en/latest/auto/type_system/index.html)** for machine learning and data processing pipelines, such as Blobs (images, arbitrary files), Directories, Schema (columnar structured data), collections, maps, etc.
- Memoization and Lineage tracking
- Provides logging and observability
- Workflow features:
  - Start with one task, convert to a pipeline, attach **[multiple schedules](https://docs.flyte.org/projects/cookbook/en/latest/auto/deployment/workflow/lp_schedules.html)**, trigger using a programmatic API, or on-demand
  - Parallel step execution
  - Extensible backend to add **[customized plugin](https://docs.flyte.org/projects/cookbook/en/latest/auto/core/extend_flyte/custom_task_plugin.html)** experience (with simplified user experience)
  - **[Branching](https://docs.flyte.org/projects/cookbook/en/latest/auto/core/control_flow/run_conditions.html)**
  - Workflow of workflows - **[subworkflows](https://docs.flyte.org/projects/cookbook/en/latest/auto/core/control_flow/subworkflows.html)** (a workflow can be embedded within one node of the top-level workflow)
  - Distributed **remote child workflows** (a remote workflow can be triggered and statically verified at compile time)
  - **[Array Tasks](https://docs.flyte.org/projects/cookbook/en/latest/auto/core/control_flow/map_task.html)** (map a function over a large dataset -- ensures controlled execution of thousands of containers)
  - **[Dynamic workflows](https://docs.flyte.org/projects/cookbook/en/latest/auto/core/control_flow/dynamics.html)** creation and execution with runtime type safety
  - [Flytekit plugins](https://docs.flyte.org/projects/cookbook/en/latest/plugins.html) with first-class support in Python
  - Arbitrary Flytekit-less containers tasks ([RawContainer](https://docs.flyte.org/projects/cookbook/en/latest/auto/core/containerization/raw_container.html))
- Guaranteed **[reproducibility](https://docs.flyte.org/projects/cookbook/en/latest/auto/core/flyte_basics/task_cache.html)** of pipelines via:
- **Multi-cloud support** (AWS, GCP, and others)
- No single point of failure, and is resilient by design
- Automated notifications to Slack, Email, and Pagerduty
- [Multi K8s cluster support](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/kubernetes/pod/index.html)
- Out of the box support to run **[Spark jobs on K8s](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/kubernetes/k8s_spark/index.html)**, **[Hive queries](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/external_services/hive/index.html)**, etc.
- Snappy Console & Golang CLI (Flytectl)
- Written in **Golang** and optimized for jobs that run for a long period of time.
- [Grafana templates](https://grafana.com/orgs/flyte) (user/system observability)
- Deploy with Helm and Kustomize

</details>

## 🔌 Available Plugins

<details>

- Containers
- [K8s Pods](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/kubernetes/pod/index.html)
- AWS Batch ArrayJobs
- K8s Pod Arrays
- K8s Spark (native [Pyspark](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/kubernetes/k8s_spark/index.html) and Java/Scala)
- AWS Athena
- [Qubole Hive](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/external_services/hive/index.html)
- Presto Queries
- Distributed Pytorch (K8s Native) -- [Pytorch Operator](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/kubernetes/kfpytorch/index.html)
- Sagemaker ([builtin algorithms](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/aws/sagemaker_training/sagemaker_builtin_algo_training.html) & [custom models](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/aws/sagemaker_training/sagemaker_custom_training.html))
- Distributed Tensorflow (K8s Native)
- Papermill notebook execution ([Python](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/flytekit_plugins/papermilltasks/index.html) and Spark)
- [Type safe and data checking for Pandas dataframe](https://docs.flyte.org/projects/cookbook/en/latest/auto/integrations/flytekit_plugins/pandera_examples/index.html) using Pandera
- Versioned datastores using DoltHub and Dolt
- Use SQLAlchemy to query any relational database 
- Build your own plugins that use library containers
- Snowflake queries

</details>

<html>
<h2 id="component-repos"> 
  📦 Component Repos 
</h2>
</html>

<details>

| Repo                                                         | Language      | Purpose                                        | Status           |
| ------------------------------------------------------------ | ------------- | ---------------------------------------------- | ---------------- |
| [flyte](https://github.com/flyteorg/flyte)                   | Kustomize,RST | deployment, documentation, issues              | Production-grade |
| [flyteidl](https://github.com/flyteorg/flyteidl)             | Protobuf      | gRPC/REST API, Workflow language spec          | Production-grade |
| [flytepropeller](https://github.com/flyteorg/flytepropeller) | Go            | execution engine                               | Production-grade |
| [flyteadmin](https://github.com/flyteorg/flyteadmin)         | Go            | control plane                                  | Production-grade |
| [flytekit](https://github.com/flyteorg/flytekit)             | Python        | python SDK and tools                           | Production-grade |
| [flyteconsole](https://github.com/flyteorg/flyteconsole)     | Typescript    | Flyte UI                                       | Production-grade |
| [datacatalog](https://github.com/flyteorg/datacatalog)       | Go            | manage input & output artifacts                | Production-grade |
| [flyteplugins](https://github.com/flyteorg/flyteplugins)     | Go            | Flyte Backend plugins                          | Production-grade |
| [flytecopilot](https://github.com/flyteorg/flytecopilot)     | Go            | Sidecar to manage input/output for sdk-less    | Production-grade |
| [flytestdlib](https://github.com/flyteorg/flytestdlib)       | Go            | standard library                               | Production-grade |
| [flytesnacks](https://github.com/flyteorg/flytesnacks)       | Python        | examples, tips, and tricks                     | Maintained       |
| [flytekit-java](https://github.com/flyteorg/flytekit-java)   | Java/Scala    | Java & scala SDK for authoring Flyte workflows | Incubating       |
| [flytectl](https://github.com/flyteorg/flytectl)             | Go            | A standalone Flyte CLI                         | Production-grade |
| [homebrew-tap](https://github.com/flyteorg/homebrew-tap)     | Ruby          | Tap for downloadable flyte tools (cli etc)     | Production-grade |
| [bazel-rules](https://github.com/flyteorg/bazelrules_flyte)  | skylark/py    | Use Bazel to build Flyte workflows and tasks   | Incubating       |

</details>

## Functional Tests Matrix

We run a suite of [tests](https://github.com/flyteorg/flytesnacks/blob/master/cookbook/flyte_tests_manifest.json) to ensure that basic functionality and a subset of the integrations work across a variety of release versions. Those tests are run in a cluster where specific versions of the Flyte components (such as flyteconsole, flyteadmin, datacatalog, and flytepropeller) are installed, including the released versions and also the latest versions in the case of the nighly runs.

The table below has different release versions as the columns and the result of each test suite as rows:

<details open>
<center>

| workflow group                  | nightly                                                                                                            | v0.19.1                                                                                                            | v0.19.0                                                                                                            | v0.18.2                                                                                                            |
|---------------------------------|--------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| core                            | ![core](https://byob.yarr.is/unionai/gh-badges/nightly/core)                                                       | ![core](https://byob.yarr.is/unionai/gh-badges/v0.19.1/core)                                                       | ![core](https://byob.yarr.is/unionai/gh-badges/v0.19.0/core)                                                       | ![core](https://byob.yarr.is/unionai/gh-badges/v0.18.2/core)                                                       |
| integrations-hive               | ![integration-hive](https://byob.yarr.is/unionai/gh-badges/nightly/integrations-hive)                              | ![integration-hive](https://byob.yarr.is/unionai/gh-badges/v0.19.1/integrations-hive)                              | ![integration-hive](https://byob.yarr.is/unionai/gh-badges/v0.19.0/integrations-hive)                              | ![integration-hive](https://byob.yarr.is/unionai/gh-badges/v0.18.2/integrations-hive)                              |
| integrations-k8s-spark          | ![integrations-k8s-spark](https://byob.yarr.is/unionai/gh-badges/nightly/integrations-k8s-spark)                   | ![integrations-k8s-spark](https://byob.yarr.is/unionai/gh-badges/v0.19.1/integrations-k8s-spark)                   | ![integrations-k8s-spark](https://byob.yarr.is/unionai/gh-badges/v0.19.0/integrations-k8s-spark)                   | ![integrations-k8s-spark](https://byob.yarr.is/unionai/gh-badges/v0.18.2/integrations-k8s-spark)                   |
| integrations-kfpytorch          | ![integrations-kfpytorch](https://byob.yarr.is/unionai/gh-badges/nightly/integrations-kfpytorch)                   | ![integrations-kfpytorch](https://byob.yarr.is/unionai/gh-badges/v0.19.1/integrations-kfpytorch)                   | ![integrations-kfpytorch](https://byob.yarr.is/unionai/gh-badges/v0.19.0/integrations-kfpytorch)                   | ![integrations-kfpytorch](https://byob.yarr.is/unionai/gh-badges/v0.18.2/integrations-kfpytorch)                   |
| integrations-pod                | ![integrations-pod](https://byob.yarr.is/unionai/gh-badges/nightly/integrations-pod)                               | ![integrations-pod](https://byob.yarr.is/unionai/gh-badges/v0.19.1/integrations-pod)                               | ![integrations-pod](https://byob.yarr.is/unionai/gh-badges/v0.19.0/integrations-pod)                               | ![integrations-pod](https://byob.yarr.is/unionai/gh-badges/v0.18.2/integrations-pod)                               |
| integrations-pandera_examples   | ![integrations-pandera_examples](https://byob.yarr.is/unionai/gh-badges/nightly/integrations-pandera_examples)     | ![integrations-pandera_examples](https://byob.yarr.is/unionai/gh-badges/v0.19.1/integrations-pandera_examples)     | ![integrations-pandera_examples](https://byob.yarr.is/unionai/gh-badges/v0.19.0/integrations-pandera_examples)     | ![integrations-pandera_examples](https://byob.yarr.is/unionai/gh-badges/v0.18.2/integrations-pandera_examples)     |
| integrations-papermilltasks     | ![integrations-papermilltasks](https://byob.yarr.is/unionai/gh-badges/nightly/integrations-papermilltasks)         | ![integrations-papermilltasks](https://byob.yarr.is/unionai/gh-badges/v0.19.1/integrations-papermilltasks)         | ![integrations-papermilltasks](https://byob.yarr.is/unionai/gh-badges/v0.19.0/integrations-papermilltasks)         | ![integrations-papermilltasks](https://byob.yarr.is/unionai/gh-badges/v0.18.2/integrations-papermilltasks)         |
| integrations-greatexpectations  | ![integrations-greatexpectations](https://byob.yarr.is/unionai/gh-badges/nightly/integrations-greatexpectations)   | ![integrations-greatexpectations](https://byob.yarr.is/unionai/gh-badges/v0.19.1/integrations-greatexpectations)   | ![integrations-greatexpectations](https://byob.yarr.is/unionai/gh-badges/v0.19.0/integrations-greatexpectations)   | ![integrations-greatexpectations](https://byob.yarr.is/unionai/gh-badges/v0.18.2/integrations-greatexpectations)   |
| integrations-sagemaker-pytorch  | ![integrations-sagemaker-pytorch](https://byob.yarr.is/unionai/gh-badges/nightly/integrations-sagemaker-pytorch)   | ![integrations-sagemaker-pytorch](https://byob.yarr.is/unionai/gh-badges/v0.19.1/integrations-sagemaker-pytorch)   | ![integrations-sagemaker-pytorch](https://byob.yarr.is/unionai/gh-badges/v0.19.0/integrations-sagemaker-pytorch)   | ![integrations-sagemaker-pytorch](https://byob.yarr.is/unionai/gh-badges/v0.18.2/integrations-sagemaker-pytorch)   |
| integrations-sagemaker-training | ![integrations-sagemaker-training](https://byob.yarr.is/unionai/gh-badges/nightly/integrations-sagemaker-training) | ![integrations-sagemaker-training](https://byob.yarr.is/unionai/gh-badges/v0.19.1/integrations-sagemaker-training) | ![integrations-sagemaker-training](https://byob.yarr.is/unionai/gh-badges/v0.19.0/integrations-sagemaker-training) | ![integrations-sagemaker-training](https://byob.yarr.is/unionai/gh-badges/v0.18.2/integrations-sagemaker-training) |

</center>
</details>

<html>
<h2 id="rfc"> 
   🛣️  RFC's (Request for Commments) & Proposals
</h2>
</html>

Flyte is a Community Driven and Community Owned Software. It is managed using
a steering committee and encourages collaboration. The community has a long
roadmap for Flyte, but they know that there might be some other interesting
ideas, extensions or additions that you may want to propose. This is done
usually starting with a 
- [Github Issue](https://github.com/flyteorg/flyte/issues) - We maintain issues for all repos in the main flyte repo.
- Writing down your proposal using a [Documented RFC process](rfc/.)

For small changes, RFCs are not required, but for larger changes, RFC's are
  encouraged. You are welcome to drop into the Slack channel and talk to the community,
if you want to test the waters, before proposing.


<html>
<h2 id="community--resources"> 
  🤝 Community & Resources
</h2>
</html>

Here are some resources to help you learn more about Flyte.

### Communication Channels

- [Slack](https://slack.flyte.org)
- [Email list](https://groups.google.com/u/0/a/flyte.org/g/users)
- [Twitter](https://twitter.com/flyteorg) 
- [LinkedIn Discussion Group](https://www.linkedin.com/groups/13962256/)
- [GitHub Discussions](https://github.com/flyteorg/flyte/discussions)

### Biweekly Community Sync

- 📣 **Flyte OSS Community Sync** Every other Tuesday, 9:00 am - 10:00 am PT. Check out the [calendar](https://www.addevent.com/calendar/kE355955), and register to stay up-to-date with our meeting times. Or join us on [Zoom](https://us04web.zoom.us/j/71298741279?pwd=TDR1RUppQmxGaDRFdzBOa2lHN1dsZz09).
- Upcoming meeting agenda, previous meeting notes, and a backlog of topics are captured in this [document](https://docs.google.com/document/d/1Jb6eOPOzvTaHjtPEVy7OR2O5qK1MhEs3vv56DX2dacM/edit#heading=h.c5ha25xc546e).
- If you'd like to revisit any previous community sync meetings, you can access the video recordings on [Flyte's YouTube channel](https://www.youtube.com/channel/UCNduEoLOToNo3nFVly-vUTQ).

### Office Hours

Ask us anything Flyte, weekly on Wednesdays:
- 7:00-7:30 am PT ([Invite and Zoom Link](https://www.addevent.com/event/zF10349020/))
- 9:00-9:30 pm PT ([Invite and Zoom link](https://www.addevent.com/event/dQ10349168/))

### Blog Posts

- [Flyte blog site](https://blog.flyte.org/)

### Newsletter

- [Flyte Monthly](https://www.getrevue.co/profile/flyte)

### Conference Talks & Podcasts

<details>

### Conferences

2019  
- Kubecon 2019 - Flyte: Cloud Native Machine Learning and Data Processing Platform [video](https://www.youtube.com/watch?v=KdUJGSP1h9U) | [deck](https://kccncna19.sched.com/event/UaYY/flyte-cloud-native-machine-learning-data-processing-platform-ketan-umare-haytham-abuelfutuh-lyft)
- Kubecon 2019 - Running LargeScale Stateful workloads on Kubernetes at Lyft [video](https://www.youtube.com/watch?v=ECeVQoble0g)
- re:invent 2019 - Implementing ML workflows with Kubernetes and Amazon Sagemaker [video](https://youtu.be/G-wzIQQJKaE)
- Cloud-native machine learning at Lyft with AWS Batch and Amazon EKS [video](https://youtu.be/n_rRb8u1GSM)

2020  
- OSS + ELC NA 2020 [splash](https://ossna2020.sched.com/event/313cec91aa38a430a25f9571039874b8)
- Datacouncil [video](https://www.youtube.com/watch?v=1BjXC5TZAiI) | [splash](https://docs.google.com/document/d/1ZsCDOZ5ZJBPWzCNc45FhNtYQOxYHz0PAu9lrtDVnUpw/edit)
- FB AI@Scale [Making MLOps & DataOps a reality](https://www.facebook.com/atscaleevents/videos/ai-scale-flyte-making-mlops-and-dataops-a-reality/1047312585732459/)
- [GAIC 2020](http://www.globalbigdataconference.com/seattle/global-artificial-intelligence-virtual-conference-122/speaker-details/ketan-umare-113746.html)

2021  
- OSPOCon 2021:
  - Building and Growing an Open Source Community for an Incubating Project [video](https://www.youtube.com/watch?v=DhXlTzCDeGI&list=PLbzoR-pLrL6q8QMGJ4dFnqejkHDm76kJV&index=37)
  - Enforcing Data Quality in Data Processing and ML Pipelines with Flyte and Pandera [video](https://www.youtube.com/watch?v=IB3KrIk4ics&list=PLbzoR-pLrL6q8QMGJ4dFnqejkHDm76kJV&index=84)
  - Self-serve Feature Engineering Platform Using Flyte and Feast [video](https://www.youtube.com/watch?v=Km2ii0F8Yl0&list=PLbzoR-pLrL6q8QMGJ4dFnqejkHDm76kJV&index=215)
  - Efficient Data Parallel Distributed Training with Flyte, Spark & Horovod [video](https://www.youtube.com/watch?v=gF3cVTdgLUY&list=PLbzoR-pLrL6q8QMGJ4dFnqejkHDm76kJV&index=77)
- KubeCon+CloudNativeCon North America 2021 - How Spotify Leverages Flyte To Coordinate Financial Analytics Company-Wide [session](https://sched.co/lV59)
- PyData Global 2021 - Robust, End-to-end Online Machine Learning Applications with Flytekit, Pandera and Streamlit [video](https://www.youtube.com/watch?v=yblbP7lI2IM)
- ODSC West Reconnect - Deep Dive Into Flyte [workshop](https://odsc.com/speakers/deep-dive-into-flyte/) 

2022
- DataCouncil Austin - Type-Safe Data Processing and Machine Learning Pipelines with Flyte and Pandera [session](https://www.datacouncil.ai/talks/type-safe-data-processing-and-machine-learning-pipelines-with-flyte-and-pandera?hsLang=en)  
  
### Podcasts

- TWIML&AI - [Scalable and Maintainable ML Workflows at Lyft - Flyte](https://twimlai.com/twiml-talk-343-scalable-and-maintainable-workflows-at-lyft-with-flyte-w-haytham-abuelfutuh-and-ketan-umare/)
- Software Engineering Daily - [Flyte: Lyft Data Processing Platform](https://softwareengineeringdaily.com/2020/03/12/flyte-lyft-data-processing-platform-with-allyson-gale-and-ketan-umare/)
- MLOps Coffee session - [Flyte: an open-source tool for scalable, extensible, and portable workflows](https://anchor.fm/mlops/episodes/MLOps-Coffee-Sessions-12-Flyte-an-open-source-tool-for-scalable--extensible---and-portable-workflows-eksa5k)
- Open Data Science - [West Warm Up session with Ketan Umare - Creator of Flyte](https://twitter.com/odsc/status/1451594432369758212)

</details>


## 💖 All Contributors

A big thank you to the community for making Flyte possible!

<!-- CONTRIBUTORS START -->
[![953358](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/953358?v=4&w=50&h=50&mask=circle)](https://github.com/katrogan)[![37090125](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/37090125?v=4&w=50&h=50&mask=circle)](https://github.com/lyft-metaservice-3)[![7597118](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/7597118?v=4&w=50&h=50&mask=circle)](https://github.com/matthewphsmith)[![27159](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/27159?v=4&w=50&h=50&mask=circle)](https://github.com/EngHabu)[![29843943](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/29843943?v=4&w=50&h=50&mask=circle)](https://github.com/goreleaserbot)[![78108056](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/78108056?v=4&w=50&h=50&mask=circle)](https://github.com/flyte-bot)[![158892](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/158892?v=4&w=50&h=50&mask=circle)](https://github.com/honnix)[![10830562](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/10830562?v=4&w=50&h=50&mask=circle)](https://github.com/evalsocket)[![18408237](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/18408237?v=4&w=50&h=50&mask=circle)](https://github.com/anandswaminathan)[![2896568](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/2896568?v=4&w=50&h=50&mask=circle)](https://github.com/wild-endeavor)[![1518524](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1518524?v=4&w=50&h=50&mask=circle)](https://github.com/bnsblue)[![27777173](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/27777173?v=4&w=50&h=50&mask=circle)](https://github.com/samhita-alla)[![8888115](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/8888115?v=4&w=50&h=50&mask=circle)](https://github.com/hamersaw)[![16888709](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/16888709?v=4&w=50&h=50&mask=circle)](https://github.com/kumare3)[![37936015](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/37936015?v=4&w=50&h=50&mask=circle)](https://github.com/pingsutw)[![6562898](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/6562898?v=4&w=50&h=50&mask=circle)](https://github.com/ckiosidis)[![8805803](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/8805803?v=4&w=50&h=50&mask=circle)](https://github.com/alexlipa91)[![5032356](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/5032356?v=4&w=50&h=50&mask=circle)](https://github.com/brucearctor)[![653394](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/653394?v=4&w=50&h=50&mask=circle)](https://github.com/eapolinario)[![8122852](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/8122852?v=4&w=50&h=50&mask=circle)](https://github.com/ariefrahmansyah)[![3880645](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/3880645?v=4&w=50&h=50&mask=circle)](https://github.com/jonathanburns)[![3936213](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/3936213?v=4&w=50&h=50&mask=circle)](https://github.com/lu4nm3)[![26174213](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/26174213?v=4&w=50&h=50&mask=circle)](https://github.com/lyft-metaservice-2)[![77798312](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/77798312?v=4&w=50&h=50&mask=circle)](https://github.com/pmahindrakar-oss)[![9142716](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/9142716?v=4&w=50&h=50&mask=circle)](https://github.com/2uasimojo)[![5487021](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/5487021?v=4&w=50&h=50&mask=circle)](https://github.com/veggiemonk)[![1815175](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1815175?v=4&w=50&h=50&mask=circle)](https://github.com/schottra)[![2816689](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/2816689?v=4&w=50&h=50&mask=circle)](https://github.com/cosmicBboy)[![19375241](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/19375241?v=4&w=50&h=50&mask=circle)](https://github.com/migueltol22)[![6239450](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/6239450?v=4&w=50&h=50&mask=circle)](https://github.com/mayitbeegh)[![6065051](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/6065051?v=4&w=50&h=50&mask=circle)](https://github.com/milton0825)[![70988](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/70988?v=4&w=50&h=50&mask=circle)](https://github.com/slai)[![16090976](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/16090976?v=4&w=50&h=50&mask=circle)](https://github.com/surindersinghp)[![53313394](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/53313394?v=4&w=50&h=50&mask=circle)](https://github.com/kosigz-lyft)[![4967458](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/4967458?v=4&w=50&h=50&mask=circle)](https://github.com/chanadian)[![467927](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/467927?v=4&w=50&h=50&mask=circle)](https://github.com/kanterov)[![248688](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/248688?v=4&w=50&h=50&mask=circle)](https://github.com/hanzo)[![1330233](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1330233?v=4&w=50&h=50&mask=circle)](https://github.com/igorvalko)[![5026554](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/5026554?v=4&w=50&h=50&mask=circle)](https://github.com/vsbus)[![34587798](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/34587798?v=4&w=50&h=50&mask=circle)](https://github.com/akhurana001)[![38207208](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/38207208?v=4&w=50&h=50&mask=circle)](https://github.com/tnsetting)[![8200209](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/8200209?v=4&w=50&h=50&mask=circle)](https://github.com/catalinii)[![10869815](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/10869815?v=4&w=50&h=50&mask=circle)](https://github.com/jeevb)[![43587819](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/43587819?v=4&w=50&h=50&mask=circle)](https://github.com/chetcode)[![163899](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/163899?v=4&w=50&h=50&mask=circle)](https://github.com/regadas)[![1316881](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1316881?v=4&w=50&h=50&mask=circle)](https://github.com/akashkatipally)[![1360529](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1360529?v=4&w=50&h=50&mask=circle)](https://github.com/clairemcginty)[![2538760](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/2538760?v=4&w=50&h=50&mask=circle)](https://github.com/akumor)[![155087](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/155087?v=4&w=50&h=50&mask=circle)](https://github.com/derwiki)[![1399455](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1399455?v=4&w=50&h=50&mask=circle)](https://github.com/th0114nd)[![1810591](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1810591?v=4&w=50&h=50&mask=circle)](https://github.com/asottile)[![19733683](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/19733683?v=4&w=50&h=50&mask=circle)](https://github.com/snyk-bot)[![80421934](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/80421934?v=4&w=50&h=50&mask=circle)](https://github.com/SandraGH5)[![12219405](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/12219405?v=4&w=50&h=50&mask=circle)](https://github.com/fediazgon)[![3939659](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/3939659?v=4&w=50&h=50&mask=circle)](https://github.com/sbrunk)[![6774758](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/6774758?v=4&w=50&h=50&mask=circle)](https://github.com/ddhirajkumar)[![18337807](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/18337807?v=4&w=50&h=50&mask=circle)](https://github.com/max-hoffman)[![9609986](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/9609986?v=4&w=50&h=50&mask=circle)](https://github.com/sonjaer)[![30621230](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/30621230?v=4&w=50&h=50&mask=circle)](https://github.com/aeioulisa)[![54334265](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/54334265?v=4&w=50&h=50&mask=circle)](https://github.com/michaels-lyft)[![11799671](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/11799671?v=4&w=50&h=50&mask=circle)](https://github.com/bstadlbauer)[![322624](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/322624?v=4&w=50&h=50&mask=circle)](https://github.com/AdrianoKF)[![54333860](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/54333860?v=4&w=50&h=50&mask=circle)](https://github.com/aalavian)[![7005765](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/7005765?v=4&w=50&h=50&mask=circle)](https://github.com/convexquad)[![48966647](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/48966647?v=4&w=50&h=50&mask=circle)](https://github.com/asahalyft)[![77167782](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/77167782?v=4&w=50&h=50&mask=circle)](https://github.com/apatel-fn)[![31381038](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/31381038?v=4&w=50&h=50&mask=circle)](https://github.com/lordnodd)[![23107192](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/23107192?v=4&w=50&h=50&mask=circle)](https://github.com/YmirKhang)[![7358951](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/7358951?v=4&w=50&h=50&mask=circle)](https://github.com/frsann)[![6984748](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/6984748?v=4&w=50&h=50&mask=circle)](https://github.com/jbrambleDC)[![125105](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/125105?v=4&w=50&h=50&mask=circle)](https://github.com/tekumara)[![37170063](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/37170063?v=4&w=50&h=50&mask=circle)](https://github.com/Qiwen-Yu)[![4308533](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/4308533?v=4&w=50&h=50&mask=circle)](https://github.com/rubenbarragan)[![422486](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/422486?v=4&w=50&h=50&mask=circle)](https://github.com/bethebunny)[![11269256](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/11269256?v=4&w=50&h=50&mask=circle)](https://github.com/sushrut111)[![61228633](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/61228633?v=4&w=50&h=50&mask=circle)](https://github.com/Tat-V)[![13070236](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/13070236?v=4&w=50&h=50&mask=circle)](https://github.com/TeoZosa)[![8817639](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/8817639?v=4&w=50&h=50&mask=circle)](https://github.com/ThomVett)[![17309187](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/17309187?v=4&w=50&h=50&mask=circle)](https://github.com/datability-io)[![30375389](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/30375389?v=4&w=50&h=50&mask=circle)](https://github.com/bimtauer)[![57967031](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/57967031?v=4&w=50&h=50&mask=circle)](https://github.com/varshaparthay)[![1778407](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1778407?v=4&w=50&h=50&mask=circle)](https://github.com/ybubnov)[![3741621](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/3741621?v=4&w=50&h=50&mask=circle)](https://github.com/palchicz)[![12450632](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/12450632?v=4&w=50&h=50&mask=circle)](https://github.com/ajsalow)[![49699333](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/in/29110?v=4&w=50&h=50&mask=circle)](https://github.com/apps/dependabot)[![13331724](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/13331724?v=4&w=50&h=50&mask=circle)](https://github.com/martinlyra)[![50860453](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/50860453?v=4&w=50&h=50&mask=circle)](https://github.com/charlie0220)[![6506810](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/6506810?v=4&w=50&h=50&mask=circle)](https://github.com/stephen37)[![65977800](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/65977800?v=4&w=50&h=50&mask=circle)](https://github.com/service-github-lyft-semantic-release)[![85753828](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/85753828?v=4&w=50&h=50&mask=circle)](https://github.com/csirius)[![26953709](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/26953709?v=4&w=50&h=50&mask=circle)](https://github.com/Pianist038801)[![84735036](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/84735036?v=4&w=50&h=50&mask=circle)](https://github.com/jsonporter)[![55718143](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/55718143?v=4&w=50&h=50&mask=circle)](https://github.com/anrusina)[![1388071](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1388071?v=4&w=50&h=50&mask=circle)](https://github.com/aviaviavi)[![58770001](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/58770001?v=4&w=50&h=50&mask=circle)](https://github.com/Professional0321)[![18363301](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/18363301?v=4&w=50&h=50&mask=circle)](https://github.com/jimbobby5)[![4023015](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/4023015?v=4&w=50&h=50&mask=circle)](https://github.com/pradithya)[![67166843](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/67166843?v=4&w=50&h=50&mask=circle)](https://github.com/vvasavada-fn)[![25364490](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/25364490?v=4&w=50&h=50&mask=circle)](https://github.com/haoyuez)[![50679871](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/50679871?v=4&w=50&h=50&mask=circle)](https://github.com/lupasarin)[![7515359](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/7515359?v=4&w=50&h=50&mask=circle)](https://github.com/narape)[![94349093](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/94349093?v=4&w=50&h=50&mask=circle)](https://github.com/SmritiSatyanV)[![200401](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/200401?v=4&w=50&h=50&mask=circle)](https://github.com/arturdryomov)[![24739949](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/24739949?v=4&w=50&h=50&mask=circle)](https://github.com/felixwang9817)[![10430635](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/10430635?v=4&w=50&h=50&mask=circle)](https://github.com/juandiegopalomino)[![405480](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/405480?v=4&w=50&h=50&mask=circle)](https://github.com/georgesnelling)[![1004789](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1004789?v=4&w=50&h=50&mask=circle)](https://github.com/dschaller)[![480621](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/480621?v=4&w=50&h=50&mask=circle)](https://github.com/davidxia)[![1335881](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1335881?v=4&w=50&h=50&mask=circle)](https://github.com/hoyajigi)[![31255434](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/31255434?v=4&w=50&h=50&mask=circle)](https://github.com/kennyworkman)[![4830700](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/4830700?v=4&w=50&h=50&mask=circle)](https://github.com/NitinAgg)[![69161722](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/69161722?v=4&w=50&h=50&mask=circle)](https://github.com/noobkid2411)[![25391173](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/25391173?v=4&w=50&h=50&mask=circle)](https://github.com/nicklofaso)[![21109744](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/21109744?v=4&w=50&h=50&mask=circle)](https://github.com/AlekhyaSasi)[![14992189](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/14992189?v=4&w=50&h=50&mask=circle)](https://github.com/eanakhl)[![1175392](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1175392?v=4&w=50&h=50&mask=circle)](https://github.com/adinin)[![7475946](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/7475946?v=4&w=50&h=50&mask=circle)](https://github.com/anton-malakhov)[![11796986](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/11796986?v=4&w=50&h=50&mask=circle)](https://github.com/avan-sh)[![304786](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/304786?v=4&w=50&h=50&mask=circle)](https://github.com/kinow)[![24402505](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/24402505?v=4&w=50&h=50&mask=circle)](https://github.com/Daeruin)[![86911142](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/86911142?v=4&w=50&h=50&mask=circle)](https://github.com/idivyanshbansal)[![10345184](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/10345184?v=4&w=50&h=50&mask=circle)](https://github.com/hasukmistry)[![29532638](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/29532638?v=4&w=50&h=50&mask=circle)](https://github.com/rokrokss)[![16461847](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/16461847?v=4&w=50&h=50&mask=circle)](https://github.com/JakeNeyer)[![14008978](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/14008978?v=4&w=50&h=50&mask=circle)](https://github.com/jeremydonahue)[![9272376](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/9272376?v=4&w=50&h=50&mask=circle)](https://github.com/jonasdebeukelaer)[![1633460](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1633460?v=4&w=50&h=50&mask=circle)](https://github.com/jmcarp)[![3033592](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/3033592?v=4&w=50&h=50&mask=circle)](https://github.com/kazesberger)[![19229049](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/19229049?v=4&w=50&h=50&mask=circle)](https://github.com/lsena)[![7548823](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/7548823?v=4&w=50&h=50&mask=circle)](https://github.com/Dread1982)[![36594527](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/36594527?v=4&w=50&h=50&mask=circle)](https://github.com/mishmanners)[![580328](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/580328?v=4&w=50&h=50&mask=circle)](https://github.com/ilikedata)[![1027207](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1027207?v=4&w=50&h=50&mask=circle)](https://github.com/orf)[![5346764](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/5346764?v=4&w=50&h=50&mask=circle)](https://github.com/fsz285)[![1568889](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1568889?v=4&w=50&h=50&mask=circle)](https://github.com/leorleor)[![937967](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/937967?v=4&w=50&h=50&mask=circle)](https://github.com/moose007)[![14996868](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/14996868?v=4&w=50&h=50&mask=circle)](https://github.com/v01dXYZ)[![93438190](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/93438190?v=4&w=50&h=50&mask=circle)](https://github.com/wanderer163)[![1043051](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1043051?v=4&w=50&h=50&mask=circle)](https://github.com/kylewaynebenson)[![21953442](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/21953442?v=4&w=50&h=50&mask=circle)](https://github.com/Gui11aum3)[![64676594](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/64676594?v=4&w=50&h=50&mask=circle)](https://github.com/abhijeet007rocks8)[![1174730](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1174730?v=4&w=50&h=50&mask=circle)](https://github.com/mouuff)[![44368997](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/44368997?v=4&w=50&h=50&mask=circle)](https://github.com/radiantly)[![36989112](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/36989112?v=4&w=50&h=50&mask=circle)](https://github.com/nishantwrp)[![790725](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/790725?v=4&w=50&h=50&mask=circle)](https://github.com/rodrigobaron)[![697033](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/697033?v=4&w=50&h=50&mask=circle)](https://github.com/vglocus)[![5732047](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/5732047?v=4&w=50&h=50&mask=circle)](https://github.com/stormy-ua)[![2845540](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/2845540?v=4&w=50&h=50&mask=circle)](https://github.com/RustedBones)[![471021](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/471021?v=4&w=50&h=50&mask=circle)](https://github.com/marschall)[![71284190](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/71284190?v=4&w=50&h=50&mask=circle)](https://github.com/gdungca-fn)[![26265392](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/26265392?v=4&w=50&h=50&mask=circle)](https://github.com/ttanay)[![3275593](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/3275593?v=4&w=50&h=50&mask=circle)](https://github.com/pradyunsg)[![66853113](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/in/68672?v=4&w=50&h=50&mask=circle)](https://github.com/apps/pre-commit-ci)[![107893](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/107893?v=4&w=50&h=50&mask=circle)](https://github.com/kmike)[![1300022](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1300022?v=4&w=50&h=50&mask=circle)](https://github.com/sirosen)[![1324225](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1324225?v=4&w=50&h=50&mask=circle)](https://github.com/hugovk)[![467294](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/467294?v=4&w=50&h=50&mask=circle)](https://github.com/bastimeyer)[![20280470](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/20280470?v=4&w=50&h=50&mask=circle)](https://github.com/drewyh)[![199429](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/199429?v=4&w=50&h=50&mask=circle)](https://github.com/dvarrazzo)[![1032633](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1032633?v=4&w=50&h=50&mask=circle)](https://github.com/dbitouze)[![18519037](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/18519037?v=4&w=50&h=50&mask=circle)](https://github.com/sethmlarson)[![11478411](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/11478411?v=4&w=50&h=50&mask=circle)](https://github.com/stonecharioteer)[![86675](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/86675?v=4&w=50&h=50&mask=circle)](https://github.com/estan)[![4748863](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/4748863?v=4&w=50&h=50&mask=circle)](https://github.com/pseudomuto)[![181308](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/181308?v=4&w=50&h=50&mask=circle)](https://github.com/htdvisser)[![1390277](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1390277?v=4&w=50&h=50&mask=circle)](https://github.com/jacobtolar)[![1391982](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1391982?v=4&w=50&h=50&mask=circle)](https://github.com/ezimanyi)[![3880001](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/3880001?v=4&w=50&h=50&mask=circle)](https://github.com/lpabon)[![770392](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/770392?v=4&w=50&h=50&mask=circle)](https://github.com/ArcEye)[![6178510](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/6178510?v=4&w=50&h=50&mask=circle)](https://github.com/mingrammer)[![5111931](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/5111931?v=4&w=50&h=50&mask=circle)](https://github.com/aschrijver)[![873434](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/873434?v=4&w=50&h=50&mask=circle)](https://github.com/panzerfahrer)[![16724](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/16724?v=4&w=50&h=50&mask=circle)](https://github.com/glasser)[![17330872](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/17330872?v=4&w=50&h=50&mask=circle)](https://github.com/murph0)[![419419](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/419419?v=4&w=50&h=50&mask=circle)](https://github.com/zetaron)[![1014](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1014?v=4&w=50&h=50&mask=circle)](https://github.com/sunfmin)[![504507](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/504507?v=4&w=50&h=50&mask=circle)](https://github.com/guozheng)[![8542033](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/8542033?v=4&w=50&h=50&mask=circle)](https://github.com/nagytech)[![8841470](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/8841470?v=4&w=50&h=50&mask=circle)](https://github.com/suusan2go)[![901479](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/901479?v=4&w=50&h=50&mask=circle)](https://github.com/mhaberler)[![6400253](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/6400253?v=4&w=50&h=50&mask=circle)](https://github.com/s4ichi)[![353644](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/353644?v=4&w=50&h=50&mask=circle)](https://github.com/dreampuf)[![12421077](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/12421077?v=4&w=50&h=50&mask=circle)](https://github.com/UnicodingUnicorn)[![809865](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/809865?v=4&w=50&h=50&mask=circle)](https://github.com/philiptzou)[![19378](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/19378?v=4&w=50&h=50&mask=circle)](https://github.com/timabell)
<!-- CONTRIBUTORS END -->
