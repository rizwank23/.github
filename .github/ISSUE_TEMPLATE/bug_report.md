---
name: Bug report
about: Create a bug report to help us improve
title: 'Falco not working on EKS'
labels: kind/bug
assignees: ''

---

<!-- Please use this template while reporting a bug and provide as much info as possible. Not doing so may result in your bug not being addressed in a timely manner. Thanks! -->

**Describe the bug**
Falco is not working on EKS. Pods going to Crashloopbackoff.

When we describe the pod it says,
Runtime error: error opening device /host/dev/falco0. Make sure you have root credentials and that the falco module is loaded.. Exiting.
<!-- A clear and concise description of what the bug is. -->

**How to reproduce it**

<!-- Minimal and precise steps to reproduce the bug. -->

**Expected behaviour**
all falco pods should be up and running
<!--  clear and concise description of what you expected to happen. -->

**Screenshots**
![image](https://user-images.githubusercontent.com/14146081/114687530-7e214500-9d31-11eb-8903-2ad84aee139a.png)

![image](https://user-images.githubusercontent.com/14146081/114687385-53cf8780-9d31-11eb-8d2d-fb01000ebc95.png)

<!-- If applicable, add screenshots to help explain your problem. -->

**Environment**

<!-- Please complete the following info. -->

- Falco version: falco-1.8.1
<!-- Use "falco --version". -->
- System info:
<!-- Falco has a built-in support command you can use  "falco --support | jq .system_info" -->
- Cloud provider or hardware configuration:
- OS:
<!-- Eg., output of "cat /etc/os-release". -->
- Kernel:
<!-- Eg., output of "uname -a". -->
- Installation method: kubernetes
<!-- Eg., Kubernetes, RPM, DEB, from source? -->
- helm command: helm install falco falcosecurity/falco -n falco

**Additional context**

<!-- Add any other context about the problem here. -->
