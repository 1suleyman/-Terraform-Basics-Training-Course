# 🌍 Terraform Basics Training Course 

Welcome to my **Terraform learning journey!**
This repository documents my progress through the **Terraform Basics Training Course** on KodeKloud — covering everything from Infrastructure as Code fundamentals, Terraform syntax, providers, variables, state, modules, AWS integration, and advanced features like provisioners, debugging, and workspaces.

Each lab will be documented in its own folder with a README containing:

✅ Step-by-step commands
🐛 Troubleshooting notes
💡 Key takeaways

---

## 📘 Course Summary

By completing this course, I’ll develop hands-on skills in:

* 🌍 **Infrastructure as Code (IaC)** and how Terraform solves traditional IT challenges
* 🧱 **Terraform configuration basics** (HCL, variables, providers, resources)
* 🔌 **State management** — local state, remote state, and state locking
* ⚙️ **Terraform commands** — plan, apply, destroy, fmt, validate
* 🧩 **Inputs/outputs, expressions, meta-arguments (count, for_each)**
* ☁️ **Using Terraform with AWS** — IAM, S3, DynamoDB, EC2
* 📦 **Modules** — creating, consuming, and registry modules
* 🚀 **Provisioners** — remote-exec, file, and configuration flows
* 🐛 **Debugging & troubleshooting** Terraform
* 🔐 **Workspaces** — managing multiple environments (dev/stage/prod)
* 🧮 **Terraform functions & conditionals**

---

## 🗂️ Module Index

---

### 🔹 Module 1: Getting Started with Terraform

| Challenge | Title        | Link      | Key Skill                               |
| --------- | ------------ | --------- | --------------------------------------- |
| 1         | 🌍 Terraform HCL Basics Lab | 📂 [Repo](https://github.com/1suleyman/-Terraform-HCL-Basics-Lab/tree/main) | HCL configuration basics, identifying resource blocks, provider initialization, fixing argument errors, using local_file vs local_sensitive_file, running init/plan/apply/destroy, reading Terraform error messages |

---

### 🔹 Module 2: Terraform Basics

| Challenge | Title        | Link      | Key Skill                              |
| --------- | ------------ | --------- | -------------------------------------- |
| 1         | 🌍 Terraform Providers Lab | 📂 [Repo](https://github.com/1suleyman/-Terraform-Providers-Lab/tree/main) | Provider initialization (terraform init), reading .tf resource blocks, inspecting .terraform.lock.hcl, adding new config files, creating resources with the local provider, identifying partner vs community providers |
| 2         | 🌍 Terraform Multiple Providers Lab | 📂 [Repo](https://github.com/1suleyman/-Terraform-Multiple-Providers-Lab/tree/main) | Using multiple providers in one config, provider plugin installation, .terraform/providers inspection, creating local_file and random_pet resources, resolving lock-file errors, re-initializing Terraform after adding providers |
| 3         | 🌍 Terraform Variables Lab | 📂 [Repo](https://github.com/1suleyman/-Terraform-Variables-Lab/tree/main) | Terraform variable types, list indexing, map lookups, fixing invalid variable definitions, using variables inside resources, set(type) rules, running init/plan/apply with variable-driven configs |
| 4         | 🌍 Using Variables in Terraform Lab | 📂 [Repo](https://github.com/1suleyman/-Using-Variables-in-Terraform-Lab/tree/main) | Terraform variable types, list indexing, map lookups, fixing invalid variable definitions, using variables inside resources, set(type) rules, running init/plan/apply with variable-driven configs |
| 5         | 🕒 Terraform Resource Attributes Lab | 📂 [Repo](https://github.com/1suleyman/-Terraform-Resource-Attributes-Lab/tree/main) | Inspecting resource attributes, referencing attributes (resource.type.name.attribute), using time_static timestamps, creating dependent local_file resources, using terraform show to view exported attributes |
| 6         | 🔗 Terraform Resource Dependencies Lab | 📂 [Repo](https://github.com/1suleyman/-Terraform-Resource-Dependencies-Lab/tree/main) | Implicit vs explicit dependencies, using depends_on, referencing attributes for implicit ordering, creating tls_private_key + local_file chains, safe apply/destroy of dependent resources |
| 7         | 📤 Terraform Output Variables Lab | 📂 [Repo](https://github.com/1suleyman/-Terraform-Output-Variables-Lab/tree/main) | Inspecting outputs, using terraform output, identifying provider/resource types, creating new outputs with value, running init/plan/apply to generate and expose values |

---

### 🔹 Module 3: Terraform State

| Challenge | Title        | Link      | Key Skill                               |
| --------- | ------------ | --------- | --------------------------------------- |
| 1         | 📦 Terraform State Lab | 📂 [Repo](https://github.com/1suleyman/-Terraform-State-Lab/tree/main) | Understanding Terraform state, terraform.tfstate creation, state refresh behavior, inspecting state with terraform show, tracking resource attributes (IDs, IPs), JSON state structure |

---

### 🔹 Module 4: Working with Terraform

| Challenge | Title        | Link      | Key Skill                                |
| --------- | ------------ | --------- | ---------------------------------------- |
| 1         | 🛠️ Terraform Commands & Validation Lab | 📂 [Repo](https://github.com/1suleyman/-Terraform-Commands-Validation-Lab/tree/main) | Validating Terraform configs (terraform validate), fixing syntax & argument errors, understanding validate vs apply, formatting with terraform fmt, generating dependency graphs, inspecting providers with CLI tools, understanding provider plugin behavior |
| 2         | 🔄 Terraform Lifecycle Rules Lab | 📂 [Repo](https://github.com/1suleyman/-Terraform-Lifecycle-Rules-Lab/tree/main) | lifecycle rules, create_before_destroy, prevent_destroy, keepers map, random resource regeneration logic, state inspection |
| 3         | Coming soon… | 📂 Folder | e.g. mutable vs immutable infrastructure |


---

### 🔹 Module 6: Terraform with AWS

| Challenge | Title        | Link      | Key Skill                    |
| --------- | ------------ | --------- | ---------------------------- |
| 1         | Coming soon… | 📂 [Repo]() | e.g. AWS intro               |
| 2         | Coming soon… | 📂 [Repo]() | e.g. setup AWS account       |
| 3         | Coming soon… | 📂 Folder | e.g. IAM overview            |
| 4         | Coming soon… | 📂 Folder | e.g. IAM demo                |


---

### 🔹 Module 7: Remote State

| Challenge | Title        | Link      | Key Skill                     |
| --------- | ------------ | --------- | ----------------------------- |
| 1         | Coming soon… | 📂 [Repo]() | e.g. remote state and locking |
| 2         | Coming soon… | 📂 [Repo]() | e.g. S3 backend               |
| 3         | Coming soon… | 📂 Folder | e.g. remote state lab         |
| 4         | Coming soon… | 📂 Folder | e.g. state commands           |
| 5         | Coming soon… | 📂 Folder | e.g. state command lab        |

---

### 🔹 Module 8: Terraform Provisioners

| Challenge | Title        | Link      | Key Skill                            |
| --------- | ------------ | --------- | ------------------------------------ |
| 1         | Coming soon… | 📂 [Repo]() | e.g. EC2 intro                       |
| 2         | Coming soon… | 📂 [Repo]() | e.g. EC2 deploy demo                 |
| 3         | Coming soon… | 📂 [Repo]() | e.g. EC2 with Terraform              |
| 4         | Coming soon… | 📂 [Repo]() | e.g. Terraform provisioners          |
| 5         | Coming soon… | 📂 Folder | e.g. provisioner behavior            |
| 6         | Coming soon… | 📂 Folder | e.g. EC2 & provisioners lab          |
| 7         | Coming soon… | 📂 Folder | e.g. best practices for provisioners |

---

### 🔹 Module 9: Import, Tainting & Debugging

| Challenge | Title        | Link      | Key Skill             |
| --------- | ------------ | --------- | --------------------- |
| 1         | Coming soon… | 📂 [Repo]() | e.g. Terraform taint  |
| 2         | Coming soon… | 📂 [Repo]() | e.g. debugging        |
| 3         | Coming soon… | 📂 [Repo]() | e.g. taint/debug lab  |
| 4         | Coming soon… | 📂 Folder | e.g. Terraform import |
| 5         | Coming soon… | 📂 Folder | e.g. import lab       |

---

### 🔹 Module 10: Terraform Modules

| Challenge | Title        | Link      | Key Skill                     |
| --------- | ------------ | --------- | ----------------------------- |
| 1         | Coming soon… | 📂 [Repo]() | e.g. what modules are         |
| 2         | Coming soon… | 📂 [Repo]() | e.g. creating & using modules |
| 3         | Coming soon… | 📂 Folder | e.g. using registry modules   |
| 4         | Coming soon… | 📂 Folder | e.g. module lab               |

---

### 🔹 Module 11: Terraform Functions & Conditionals

| Challenge | Title        | Link      | Key Skill                           |
| --------- | ------------ | --------- | ----------------------------------- |
| 1         | Coming soon… | 📂 [Repo]() | e.g. additional Terraform functions |
| 2         | Coming soon… | 📂 [Repo]() | e.g. conditionals                   |
| 3         | Coming soon… | 📂 [Repo]() | e.g. functions & conditionals lab   |
| 4         | Coming soon… | 📂 Folder | e.g. Terraform workspaces           |
| 5         | Coming soon… | 📂 Folder | e.g. workspaces lab                 |
