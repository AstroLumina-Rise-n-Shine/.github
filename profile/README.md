<div align="center">

<img src="https://pub-3a468a81beab43daa28dba00d60409d6.r2.dev/logo/Banner.png" alt="AstroLumina" width="600"/>

### ✨ Astrology bookings, payments & events — cloud-native, GitOps-driven ✨

*React frontend · Node.js micro-APIs · Docker Compose · Kubernetes · Helm · ArgoCD*

</div>

<hr style="border: 2px solid #30363d; border-radius: 5px;">

### 💻 Applications

<p align="center">
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Frontend">
    <img src="https://img.shields.io/badge/AstroLumina_Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="Frontend"/>
  </a>
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-AstrologyAPI">
    <img src="https://img.shields.io/badge/Astrology_API-7B42BC?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Astrology API"/>
  </a>
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-BookingAPI">
    <img src="https://img.shields.io/badge/Booking_API-017CFF?style=for-the-badge&logo=caldotcom&logoColor=white" alt="Booking API"/>
  </a>
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-PaymentAPI">
    <img src="https://img.shields.io/badge/Payment_API-635BFF?style=for-the-badge&logo=stripe&logoColor=white" alt="Payment API"/>
  </a>
</p>

| Repository | What lives here |
|---|---|
| [AstroLumina-Frontend](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Frontend) | React + Vite + Tailwind booking experience: natal, predictive & synastry charts, Moon & Astral calculators, events with seats, Stripe checkout |
| [AstroLumina-AstrologyAPI](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-AstrologyAPI) | Chart engine API: natal / predictive / synastry computations, timezone resolution, translation catalogs, Prometheus metrics |
| [AstroLumina-BookingAPI](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-BookingAPI) | Sessions & seats API: availability, Cal.com wiring, R2/D1 storage, booking emails |
| [AstroLumina-PaymentAPI](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-PaymentAPI) | Stripe API: products, prices, checkout & payment intents |

<hr style="border: 2px solid #30363d; border-radius: 5px;">

### ☸️ Platform & Delivery

<p align="center">
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-DockerCompose">
    <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose"/>
  </a>
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Kubernetes">
    <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  </a>
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Helm">
    <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm"/>
  </a>
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-ArgoCD">
    <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="ArgoCD"/>
  </a>
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Monitoring">
    <img src="https://img.shields.io/badge/Monitoring-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Monitoring"/>
  </a>
</p>

| Repository | What lives here |
|---|---|
| [AstroLumina-DockerCompose](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-DockerCompose) | Local & staging stacks: dev / staging / production Compose files, blue-green services, Traefik routing, per-env versions |
| [AstroLumina-Kubernetes](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Kubernetes) | Kustomize manifests per env: blue-green Deployments, live Services, Traefik IngressRoutes, HPA, NetworkPolicies, Doppler secrets |
| [AstroLumina-Helm](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Helm) | The `astrolumina` chart + per-env values: per-service live colors, pinned image tags, TLS & dashboard auth for production |
| [AstroLumina-ArgoCD](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-ArgoCD) | GitOps bootstrap: install RBAC, ApplicationSets for the K8s & Helm repos (manual sync), admin password rotation, CI |
| [AstroLumina-Monitoring](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Monitoring) | Observability values: kube-prometheus-stack config, per-env ServiceMonitors, dashboards & runbooks |

<hr style="border: 2px solid #30363d; border-radius: 5px;">

### 🏗️ Infrastructure as Code

<p align="center">
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Terraform">
    <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>
  </a>
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Ansible">
    <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible"/>
  </a>
</p>

| Repository | What lives here |
|---|---|
| [AstroLumina-Terraform](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Terraform) | KVM/libvirt VMs for the RKE2 cluster (control-plane + workers), cloud-init with Tailscale onboarding, CI with fmt/validate/tflint/Trivy |
| [AstroLumina-Ansible](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Ansible) | RKE2 cluster configuration: prerequisites, server & agent roles, playbooks, CI with lint/syntax-check/shellcheck |

<hr style="border: 2px solid #30363d; border-radius: 5px;">

### 📚 Docs & Tooling

<p align="center">
  <a href="https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Tools-n-Docs">
    <img src="https://img.shields.io/badge/Tools_n_Docs-FF4F80?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Tools and Docs"/>
  </a>
</p>

| Repository | What lives here |
|---|---|
| [AstroLumina-Tools-n-Docs](https://github.com/AstroLumina-by-Carmen-Ilie/AstroLumina-Tools-n-Docs) | Shared notes, runbooks & helper tooling for the whole platform |

<hr style="border: 2px solid #30363d; border-radius: 5px;">

### 🛠️ Stack at a glance

<p align="center">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white" alt="React"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white" alt="Vite"/>
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white" alt="Helm"/>
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white" alt="ArgoCD"/>
  <img src="https://img.shields.io/badge/Traefik-24A1C1?style=flat&logo=traefikproxy&logoColor=white" alt="Traefik"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white" alt="Prometheus"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white" alt="Ansible"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white" alt="Stripe"/>
  <img src="https://img.shields.io/badge/Doppler-FF4F80?style=flat&logo=doppler&logoColor=white" alt="Doppler"/>
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white" alt="Cloudflare"/>
  <img src="https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white" alt="Sentry"/>
</p>

<hr style="border: 2px solid #30363d; border-radius: 5px;">

<div align="center">

*Code → CI (lint · tests · scans) → auto-promote to staging (blue-green) → manual deploy · Git is the source of truth, ArgoCD keeps the cluster honest.*

**[Explore all repositories →](https://github.com/orgs/AstroLumina-by-Carmen-Ilie/repositories)**

</div>
