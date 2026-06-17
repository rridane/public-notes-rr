# 📚 Mes notes  
*Sélection restreinte de mes notes autour des sujets devOps, infra, sécurité, architecture et machine learning.*

## Last sync: 2026-06-17 14:31


## 📋 Sommaire

- [Devops](#devops)
- [Languages](#languages)
- [Dns](#dns)
- [Protocols](#protocols)
- [Databases](#databases)
- [Security](#security)
- [Cheatsheets](#cheatsheets)
- [Bgp](#bgp)
- [Networking](#networking)
- [Probability](#probability)
- [Flutter](#flutter)
- [Authentication_mechanisms](#authentication_mechanisms)


## Authentication_mechanisms

### [session_management.adoc](security/authentication_mechanisms/session_management.adoc)
> Deep dive in session management

---
### [saml.adoc](security/authentication_mechanisms/saml.adoc)
> Deep introduction on saml authentication

---
### [basic_auth.adoc](security/authentication_mechanisms/basic_auth.adoc)
> Detail explanation about basic authentication

---
### [oauth2.adoc](security/authentication_mechanisms/oauth2.adoc)
> Deep dive in oauth2 authentication

---
### [openid_connect.adoc](security/authentication_mechanisms/openid_connect.adoc)
> Deep dive in openid connect

---

## Cheatsheets

### [dig_cheatsheet.adoc](cheatsheets/dig_cheatsheet.adoc)
> Dig cheatsheet

---
### [regex_cheatsheet.adoc](cheatsheets/regex_cheatsheet.adoc)
> Regex cheatsheet

---
### [jwt_cheatsheet.adoc](cheatsheets/jwt_cheatsheet.adoc)
> JWT cheatsheet (JWS & JWE)

---
### [gitignore_cheatsheet](cheatsheets/gitignore_cheatsheet)
> gitignore cheatsheet

---
### [saml_cheatsheet.adoc](cheatsheets/saml_cheatsheet.adoc)
> Saml 2.0 cheatsheet

---
### [openid_connect_cheatsheet.adoc](cheatsheets/openid_connect_cheatsheet.adoc)
> openid connect cheatsheet

---
### [cookies_cheatsheet.adoc](cheatsheets/cookies_cheatsheet.adoc)
> cookies cheatsheet

---
### [hash_and_signature_cheatsheet.adoc](cheatsheets/hash_and_signature_cheatsheet.adoc)
> hash and signatures cheatsheet

---
### [ansible_cheatsheet.adoc](cheatsheets/ansible_cheatsheet.adoc)
> ansible cheatsheet

---
### [cloudnative_pg_cheatsheet.yaml](cheatsheets/cloudnative_pg_cheatsheet.yaml)
> Complete cloudnative-pg reference guide covering cluster deployment, high availability, backups, monitoring, and operational commands for running PostgreSQL on Kubernetes.

---
### [dns_cheatsheet.adoc](cheatsheets/dns_cheatsheet.adoc)
> Dns cheatsheet

---
### [iptables_cheatsheet.adoc](cheatsheets/iptables_cheatsheet.adoc)
> Iptables CheatSheet

---
### [oauth2_cheatsheet.adoc](cheatsheets/oauth2_cheatsheet.adoc)
> oauth2 cheatsheet

---
### [session_management_cheatsheet.adoc](cheatsheets/session_management_cheatsheet.adoc)
> session management cheatsheet

---
### [vagrant_commands_cheatsheet](cheatsheets/vagrant_commands_cheatsheet)
> vagrant most useful commands

---

## Bgp

### [bgp_basic_overview.adoc](networking/protocols/bgp/bgp_basic_overview.adoc)
> BGP Basics: Understanding Path Propagation Across the Internet

---

## Networking

### [linux_kernel_networking.adoc](networking/linux_kernel_networking.adoc)
> Linux kernel networking (L2/L3) rebuilt from primitives: NAPI, skb, bridge FDB, FIB routing, qdisc/tc, the full RX/TX path.

---

## Probability

### [bernoulli.adoc](mathematics/probability/bernoulli.adoc)
> Bernoulli distribution from first principles: PMF, moments, variance proof, sufficient statistic.

---
### [binomiale.adoc](mathematics/probability/binomiale.adoc)
> Binomial built from Bernoulli: PMF, expectation, variance, sufficient statistic, conjugacy.

---
### [beta.adoc](mathematics/probability/beta.adoc)
> Beta distribution: discrete-to-continuous, Beta/Gamma functions (with proof), Beta-Binomial conjugacy.

---
### [bayes.adoc](mathematics/probability/bayes.adoc)
> Bayes theorem (continuous form), full Beta-Binomial conjugacy derivation, conjugate-prior catalogue.

---
### [bayes_cheatsheet.adoc](mathematics/probability/bayes_cheatsheet.adoc)
> Applied Bayes: choosing the model per problem type (conversion, counts, churn, variance) with worked numeric examples.

---

## Flutter

### [deep_dive_on_inherited_notifications.adoc](frontend/flutter/deep_dive_on_inherited_notifications.adoc)
> A deep dive into Flutter’s dependency and notification systems, explaining how InheritedWidgets and NotificationListeners propagate updates.

---
### [deep_dive_render_objects.adoc](frontend/flutter/deep_dive_render_objects.adoc)
> A comprehensive breakdown of the RenderObject architecture, covering RenderBox, ParentData, layout, paint, and semantics in Flutter.

---
### [deep_dive_tween_animations.adoc](frontend/flutter/deep_dive_tween_animations.adoc)
> An advanced exploration of Flutter’s animation system, including tickers, AnimationController, and tween-based interpolations.

---
### [deep_dive_flutter_internal_framework.adoc](frontend/flutter/deep_dive_flutter_internal_framework.adoc)
> An in-depth exploration of Flutter's internal framework, covering bindings, schedulers, and the full build/layout/paint pipeline.

---
### [deep_dive_gesture_handling.adoc](frontend/flutter/deep_dive_gesture_handling.adoc)
> A detailed analysis of Flutter’s gesture system, from pointer event dispatching to the gesture arena resolution process.

---

## Security

### [certificates.adoc](security/certificates.adoc)
> Deep dive into certificates

---
### [rbac.adoc](security/rbac.adoc)
> Authorization models in depth — RBAC, ABAC, ReBAC (Zanzibar/SpiceDB) — driven by a real-world access-governance narrative.

---
### [cookies.adoc](security/cookies.adoc)
> Understand cookies

---
### [hash_and_signature.adoc](security/hash_and_signature.adoc)
> Understand hash and signatures

---
### [jwt.adoc](security/jwt.adoc)
> Detailed explanation about jwt, including jws & jwe

---
### [hashicorp_vault.adoc](security/hashicorp_vault.adoc)
> Deep dive in hashicorp vault, including detailed pki implementation with cert-manager

---

## Devops

### [ansible.adoc](devops/ansible.adoc)
> ansible detailed documentation

---
### [kubernetes_networking.adoc](devops/kubernetes_networking.adoc)
> Deep dive in kubernetes networking, build a full kubernetes network just with linux commands, understand all key components.

---
### [molecule.adoc](devops/molecule.adoc)
> molecule framework, deep dive on ansible testing

---

## Languages

### [cue.adoc](languages/cue.adoc)
> Comprehensive deep dive into CUE: constraints, reusable schemas, comprehensions, validation...

---

## Dns

### [dns_basic_overview.adoc](networking/protocols/dns/dns_basic_overview.adoc)
> Essentials knowledge of dns protocol

---
### [dns_advanced.adoc](networking/protocols/dns/dns_advanced.adoc)
> Advanced concepts, security, spf, dnssec, dkim...

---

## Protocols

### [from_http_to_http3_and_grpc.adoc](networking/protocols/from_http_to_http3_and_grpc.adoc)
> HTTP/1 → HTTP/2 → HTTP/3, then gRPC: why the stream-id is the pivot invention, multiplexing & HPACK, QUIC over UDP, gRPC anatomy and enterprise-proxy traversal.

---

## Databases

### [cloudnative-pg-operator.adoc](databases/cloudnative-pg-operator.adoc)
> Running PostgreSQL HA on Kubernetes with CloudNativePG: failover state machine, quorum failover modeled as R+W>N, backup/PITR, synchronous replication, pooler.

---

---
_Généré automatiquement_