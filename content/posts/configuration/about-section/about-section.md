---
title: "About Section"
date: 2020-06-08T06:20:50+06:00
hero: /images/posts/configuration/about-section-hero.svg
author:
  name: Md. Emruz Hossain
#   image: /assets/images/profile-image.jpg
categories:
- configuration
- configuration-about-section
---

{{< img src="/images/posts/configuration/about.png" >}}

```yaml
# your designation
designation: Software Engineer
# your company information
company:
  name: Example Co.
  url: "https://www.example.com"

# your resume
resume: "files/resume.pdf"

# a summary about you
summary: 'I am a passionate software engineer with x years of working
  experience. I built OSS tools for [Kubernetes](https://kubernetes.io/) using GO. My tools helps people to
  deploy their workloads in Kuberenetes. Sometimes, I work on some fun projects such as writing a theme etc.'

# your social links
# give as many as you want. use font-awesome for the icons.
socialLinks:
- name: Email
  icon: "fas fa-envelope"
  url: "example@gmail.com"

- name: Github
  icon: "fab fa-github"
  url: "https://www.github.com/example"

- name: Stackoverflow
  icon: "fab fa-stack-overflow"
  url: "#"

- name: LinkedIn
  icon: "fab fa-linkedin"
  url: "#"

- name: Twitter
  icon: "fab fa-twitter"
  url: "#"

- name: Facebook
  icon: "fab fa-facebook"

# your soft skills
# give the percentage between 50 to 100 with 5 interval.
# currently supported color: blue, yellow, pink, green
softSkills:
- name: Leadership
  percentage: 85
  color: blue
- name: Team Work
  percentage: 90
  color: yellow
- name: Communication
  percentage: 85
  color: pink
- name: Hard Working
  percentage: 85
  color: green
```
