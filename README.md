# IaC - Infrastructure as Code

<em>Infrastructure as Code is a core concept in DevOps about managing and provisioning infrastructure through code. It improves the collaboration and efficiency between teams. Also, it is important to implement DevOps pratices and CI/CD.</em>

<p>With this, we can write a script responsible for creating a new server, install OS, applications and configure everything together. It garanteers that we provision the same environment every time. When we codify and document our infrastructure configs, it helps to avoid undocumented configurations. And the advantages are:</p>

<li><b>Automation:</b> IaC lets you automate repetitive task, preventing errors and saving time.</li>
<li><b>Version Control:</b> track the changes in infrastructure configurations, because we have git to create commits about changes in this scope.</li>
<li><b>Recreate infrastructure in differents environments:</b> with IaC, it becomes easier to recreate infrastructure in different environments, such as development, staging, production and so on. Basically, it creates a template</li>

## Declarative vs. Imperative

<p>There is two types of approach while using IaC: <i>declative</i> and <i>imperative</i></p>

<li><b>Imperative:</b> you need to define all specific commands to achieve the desired configuration, step-by-step, and those commands need to be executed sequentially. Its a good approach to simple tasks</li>

<li><b>Declarative:</b> you need to define the final infrastucture state. "The end justifies the means". The focus should be to describe the resources you need and their configuration, instead thinking about steps. Its a good approach to complex systems.</li>

## Pulumi

<p>Pulumi is an IaC plataform that allows to use programming languages and tools to build, deploy, manage cloud infrastructure. It has its on SDK, CLI and provider packages to help coding.Pulumi is free and open source.</p>

<p>It has a SDK that helps create, deploy and manage AWS containers, serverless functions and infra</p>

