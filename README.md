
<!-- -->


# spyridon/introduction.yaml

```yaml
apiVersion: human.io/v1alpha1
kind: human
metadata:
  name: spyridon
  location: germany
  labels:
    role: devops-engineer
    platform: linux-windows-hybrid #change to linux only down the line
    coffee: required #dangerous dependency

spec:
  age: 28 # new version pending

  personality:
    traits:
      - curious
      - stubborn  
      - lifts-heavy-things 
      - probably-debugging-right-now

  knowledge:
    fields:
      - systems engineering
      - platform engineering
      - distributed systems
      - cloud infra
      - automation
      - ci/cd
      - desired state
      - cost saving
      - security

  workExperience:
    programmingLanguages:
      - Python 
      - Go

    tooling:
      - Kubernetes
      - Docker 
      - Terraform
      - Ansible
      - GitHub 
      - Azure DevOps

    cloud:
      - Azure
      - GCP
      - Private Cloud

    operatingSystems:
      - Linux 
      - Windows 

    shell:
      - Bash
      - PowerShell 

  hobbies:
    - cooking
    - coding-for-fun
    - reading
    - powerlifting 
    - videogames 

  favoriteBooks:
    - "Permanent Record - Edward Snowden"
    - "Metro 2033 - Dmitri Glukhovsky"
    - "The Great Gatsby - F. Scott Fitzgerald"

  podcasts:
    - Lex Fridman
    - Andrew Huberman
    - WAN Show

  languages:
    english: fluent
    german: fluent
    spanish: fluent

  availability: 
    replicas: 1

  contact:
    linkedin: https://www.linkedin.com/in/spyridon-georgiou-devops

---
# deployment notes:
# work in progress
```

