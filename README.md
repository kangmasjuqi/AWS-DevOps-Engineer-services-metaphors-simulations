# AWS DevOps Engineer services metaphors simulations

## 📌 What is this?

This HTML is a **simple interactive dashboard UI** to learn AWS DevOps services.

- Left side = menu (list of AWS services)
- Right side = content area (changes when you click)

---

## How to Use

Open the `pizza.html` file in your web browser to start using the app.

---

## Samples

<img width="3420" height="1870" alt="AWS-DevOps-Engineer-services-metaphors-simulations-04-06-2026_05_38_PM" src="https://github.com/user-attachments/assets/20a2ee49-ec5a-4608-b274-f9e2d4140497" />
<img width="3420" height="2140" alt="AWS-DevOps-Engineer-services-metaphors-simulations-04-06-2026_05_38_PM (1)" src="https://github.com/user-attachments/assets/822ac6a7-8609-4443-8bc5-c142d3af2dca" />
<img width="3420" height="1816" alt="AWS-DevOps-Engineer-services-metaphors-simulations-04-06-2026_05_39_PM" src="https://github.com/user-attachments/assets/13a304cf-6592-432c-8a7b-3232f8bc7883" />
<img width="3420" height="1816" alt="AWS-DevOps-Engineer-services-metaphors-simulations-04-06-2026_05_39_PM (1)" src="https://github.com/user-attachments/assets/7aa8c220-84f5-4b84-a761-33dc74ee1273" />
<img width="3420" height="1816" alt="AWS-DevOps-Engineer-services-metaphors-simulations-04-06-2026_05_40_PM" src="https://github.com/user-attachments/assets/343f676d-685b-4019-82ef-df2f9f8133d4" />
<img width="3420" height="1816" alt="AWS-DevOps-Engineer-services-metaphors-simulations-04-06-2026_05_40_PM (1)" src="https://github.com/user-attachments/assets/74c73604-81b6-410f-855b-dfed797b9dc7" />
<img width="3420" height="1816" alt="AWS-DevOps-Engineer-services-metaphors-simulations-04-06-2026_05_40_PM (2)" src="https://github.com/user-attachments/assets/c1543a23-c21f-4624-b262-f4cff7aff09d" />



---


## 🧠 Categories

Services are grouped into sections:

### CI/CD
- CodePipeline
- CodeBuild
- CodeDeploy
- CodeCommit
- CodeArtifact
- Elastic Beanstalk

### Infrastructure as Code
- CloudFormation
- CDK
- Systems Manager

### Compute
- ECS
- EKS
- Lambda
- Auto Scaling

### Monitoring
- CloudWatch
- X-Ray
- EventBridge

### Governance
- Config
- CloudTrail
- IAM

### Networking
- Route 53
- ELB
- SQS
- SNS
- S3

---

## ⚙️ How Interaction Works

Each button:

```
onclick="show('something')"
```

👉 Means:
- There must be a JavaScript function like:

```
function show(section) {
  document.getElementById("main-area").innerHTML = ...
}
```

👉 It changes the content inside:

```
<div id="main-area"></div>
```

---

## 🎯 Purpose of This Code

This UI is designed to:

- Help you **learn AWS services**
- Use **real-world analogy (pizza restaurant)**
- Simulate DevOps flow

---

## 🧠 Simple Mental Model

- Sidebar = **menu of topics**
- Main area = **lesson content**
- Button click = **switch lesson**

---

## ⚡ One-Line Summary

> This is a **clickable learning dashboard** for AWS services using simple HTML + JavaScript.

---

## 🚀 Optional Improvements

If you want to improve:

- Add real JavaScript `show()` logic
- Add animations
- Use React instead of plain HTML
- Load content dynamically (API or JSON)

---

## ✅ Done

You now understand:
- Layout
- Buttons
- Interaction flow

