---
name: "Richárd Módis"
titles:
  - "DevOps Engineer"
  - "System Engineer"
  - "Cloud Engineer"
email: "modisrichard@gmail.com"
location: "Budapest, Hungary"
linkedin: "linkedin.com/in/richardmodis"
cv_pdf: "/Richard-Modis-CV-202602.pdf"

profile:
  text: >
    Senior DevOps Engineer with over 13 years of experience specialising in bridging
    the gap between legacy infrastructure and modern, automated cloud environments.
    Brings a "quality-first" mindset rooted in early career experience as a QA Engineer,
    ensuring systems are testable, monitorable, and scalable. Expert in architecting
    SDDC solutions in OCI and AWS and automating complex hybrid environments with
    Terraform and Ansible to create resilient, rightsized, and reproducible infrastructure.
    A firm believer that seniority is measured by team success, with a proven track record of
    mentoring colleagues to bridge skill gaps in Linux services and serving as a Technical
    Interviewer to vet and hire top-tier DevOps talent.
  stack:
    - label: "Cloud"
      value: "OCI (OCVS), AWS, On-prem to Cloud Migrations"
    - label: "IaC & CM"
      value: "Terraform/Terragrunt, Ansible, Puppet"
    - label: "CI/CD & Containers"
      value: "GitHub Actions, Docker, Octopus Deploy"
    - label: "Observability"
      value: "LogicMonitor, Prometheus/Grafana, Nagios, Zabbix"
  personal: "Beyond the keyboard: a dedicated home-lab enthusiast tweaking Linux setups and Raspberry Pis, and a proud father of three."

experience:
  - company: "GoTo"
    location: "Budapest, Hungary"
    roles:
      - title: "Senior DevOps Engineer"
        dates: "04/2023 – 01/2026"
        description: "Led infrastructure modernisation and cross-platform automation efforts within the Budapest TechOps team."
        bullets:
          - "**OCI Migration & CM:** Led end-to-end migration to OCI using Terraform and transitioned legacy Puppet code into standardised Ansible playbooks for Windows and Linux."
          - "**Infrastructure Leadership:** Acted as Linux SME and \"gatekeeper,\" proactively rightsizing resources based on long-term metrics to ensure cost-efficiency and stability with zero downtime."
          - "**CI/CD & Modernisation:** Orchestrated the transition to GitHub Actions, introduced Docker for standardised execution, and established robust code-review processes and ansible-lint."
          - "**High-Stakes Projects:** Migrated Windows file servers to redundant Ubuntu/Samba (LDAP/LVM/RAID), deployed Redis clusters to replace AppFabric, and monitored Cassandra via Prometheus/Grafana."
          - "**Developer Enablement:** Enhanced LogicMonitor observability and automated multi-distro Linux environments using Terragrunt and Ansible to ensure reproducible QA/dev environments."
      - title: "DevOps Engineer"
        dates: "10/2021 – 04/2023"
        bullets:
          - "Managed infrastructure and troubleshooting for legacy LogMeIn products (Pro, Central, Rescue, Hamachi)."
          - "Automated workflows to accelerate cloud migrations (OCI/AWS) using Terraform, Puppet, Octopus, and PowerShell."
          - "Monitored systems, managed SSL renewals, and participated in on-call rotations to ensure service stability."

  - company: "BT"
    location: "Budapest, Hungary"
    roles:
      - title: "Senior Infrastructure and Storage Engineer"
        dates: "12/2020 – 10/2021"
        bullets:
          - "Designed and maintained OEL/RHEL-based servers running on ESXi."
          - "Managed storage utilised by hundreds of servers using NetApp. Configured and managed enterprise backups using NetBackup and Veeam."
          - "Supported various cross-functional teams located in the UK and Germany and handled ticket-based technical incidents."
          - "Participated in on-call duty rotations."

  - company: "NewPush"
    location: "Budapest, Hungary"
    roles:
      - title: "System Engineer"
        dates: "12/2019 – 11/2020"
        description: "System Engineer responsible for overseeing all of NewPush's infrastructure."
        bullets:
          - "Managed physical and virtual machines hosted across multiple environments."
          - "Maintained and optimised a Kubernetes cluster and Docker environments for containerised applications."
          - "Deployed and managed secure VPN solutions and web hosting services."
          - "Administered backup storage and developed custom file-sync solutions tailored to customer needs."
          - "Met with Budapest-based customers face-to-face to discuss and define their specific business and technical requirements."

  - company: "Számlázz.hu"
    location: "Budapest, Hungary"
    roles:
      - title: "System Administrator"
        dates: "03/2017 – 11/2019"
        description: "Maintained and improved one of Hungary's leading invoicing platforms."
        bullets:
          - "Managed the entire infrastructure, including backend servers, firewalls, network security, and optimised mail server configurations."
          - "Monitored platform services to ensure a 99.99% SLA and executed deployments across testing and production environments."
          - "Engineered a scalable, redundant WordPress CMS environment featuring Apache load balancing, GlusterFS, and MySQL master-slave replication."
          - "Orchestrated the migration from CVS to Git/GitLab and implemented Jenkins to automate deployments and centralise cron job management."
          - "Developed custom OTRS workflows and deployed Metabase dashboards to visualise data and improve customer support efficiency."

  - company: "Pulilab"
    location: "Budapest, Hungary"
    roles:
      - title: "System Administrator"
        dates: "12/2014 – 03/2017"
        description: "Part of the Pulilab team working with various Danish clients (BasePointMedia, Aporta Digital, Trolex | Aporta)."
        bullets:
          - "Managed a hybrid infrastructure of 60+ physical and virtual servers, including backend cloud systems, on-premise portable hardware, and complex virtualised environments."
          - "Collaborated within cross-functional teams to build and maintain the Trolex | Aporta platform, leveraging Java/Python-based microservice architectures."
          - "Maintained a diverse service stack including Nginx and PostgreSQL with replication, while optimising system performance through service fine-tuning."
          - "Automated deployments and recoveries using Puppet, Packer, and custom shell scripts; evaluated Ansible to optimise deployment efficiency."
          - "Administered clustered ELK stacks (Elasticsearch, Logstash, Kibana) for centralised logging and ensured 24/7 stability via Nagios and Pingdom."

  - company: "Vidzor"
    location: "Budapest, Hungary"
    roles:
      - title: "Junior QA Engineer"
        dates: "10/2013 – 11/2014"
        bullets:
          - "Tested the Vidzor platform, including the HTML5 video player, editor, and library, using a variety of QA methodologies."
          - "Performed manual testing across all modern browsers and platforms to ensure wide-scale compatibility and user accessibility."
          - "Developed comprehensive test case scenarios and acceptance tests."
          - "Transitioned to test automation, focusing on expanding user acceptance tests and converting them into executable end-to-end tests."
          - "Leveraged tools such as Cucumber, Behave, Selenium, and PhantomJS to streamline testing processes."
          - "Managed client communications and resolved technical support requests."

education:
  - institution: "Budapest Business School"
    degree: "Bachelor of Science (B.Sc.)"
    field: "Business Information Technology (BIT)"
    dates: "Expected 2026"

skills:
  top:
    - "OCI"
    - "AWS"
    - "Ansible"
    - "Terraform"
  languages:
    - lang: "English"
      level: "Professional Working"
    - lang: "Hungarian"
      level: "Native or Bilingual"

certifications:
  - "VMware vSphere: Troubleshooting"
---
