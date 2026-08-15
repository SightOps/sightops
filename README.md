# Hi, I'm Jackson Mwangi 👋

**Pharmacist building software for pharmacy and healthcare operations.**

I'm the builder behind **SightOps** — a multi-tenant healthcare operations platform designed around the real workflows of pharmacies, clinics, and growing healthcare businesses.

My work sits at the intersection of:

**Pharmacy • Healthcare • Software Engineering • SaaS • Business Operations**



## What I'm building

### SightOps

SightOps is a healthcare operations platform built to help pharmacies and healthcare businesses run their day-to-day operations with greater accuracy, visibility, and control.

It brings together operational areas including:

* Point-of-sale and selling workflows
* Inventory and stock management
* Batch tracking and FEFO
* Procurement and purchasing
* Multi-branch operations
* Financial and operational workflows
* Clinical and patient workflows
* Healthcare revenue operations
* Business intelligence and performance analytics
* KRA / eTIMS compliance
* Payment and collection integrations

But the interesting part isn't the list of features.

The real challenge is building the **systems underneath them** so that inventory, money, patients, transactions, and operational state remain correct as the business grows.



## Why I build differently

I don't approach healthcare software purely from the software side.

**I work in the domain I'm building for.**

That means many engineering problems start with a real operational question:

> **How should this actually work in a pharmacy?**

Then the question becomes:

> **How do we model that correctly in software?**

This has taken me deep into problems such as:

* Multi-tenant SaaS architecture
* PostgreSQL data modelling and integrity
* Transactional systems
* Inventory state and stock ledgers
* FEFO allocation and batch management
* Financial and operational ledgers
* Healthcare revenue workflows
* Background processing and workload isolation
* API and integration design
* Production performance
* Observability and instrumentation
* Idempotent payment processing
* Compliance integrations
* Designing systems that remain understandable as they grow



## Engineering philosophy

I care less about whether software works in a demo and more about whether it **survives contact with reality**.

A production system should be:

**Correct when the data matters.**

**Fast when users are under pressure.**

**Observable when something goes wrong.**

**Resilient when workloads increase.**

**Explicit about business rules.**

**Simple enough to reason about.**

One principle has become particularly important to me:

 **Don't solve complexity by hiding it. Model it properly.**

A pharmacy is already complex.

Inventory has batches, quantities, costs, expiries, and movements.

Money has obligations, settlements, adjustments, and history.

Healthcare has patients, encounters, services, charges, and operational workflows.

Good software shouldn't pretend these things are simple.

It should make their complexity **structured, traceable, and manageable.**



## From one pharmacy to multi-tenant SaaS

One of the most interesting parts of building SightOps has been watching the engineering problems change as the system grows.

What works for:

**one pharmacy**

doesn't necessarily work for:

**multiple branches**

and what works for multiple branches doesn't automatically work for:

**many independent organizations sharing the same platform.**

That progression forces different questions around:

* Tenant isolation
* Database architecture
* Concurrency
* Performance
* Data integrity
* Workload isolation
* Subscription boundaries
* Auditability
* Operational visibility
* Failure recovery

These are the problems I'm increasingly interested in solving.

---

## Selected engineering problems

Some of the problems I'm currently exploring through SightOps include:

### Operational truth vs historical evidence

Designing inventory systems where fast operational state and detailed historical ledger evidence can serve different purposes without sacrificing correctness.

### Keeping the selling path fast

Designing pharmacy POS workflows so that expensive reconciliation and secondary processing don't unnecessarily slow down the critical transaction path.

### Multi-tenant workload isolation

Building a shared SaaS architecture where independent organizations can operate on the same platform without one organization's workload unnecessarily degrading another's experience.

### Integration isolation

Separating external compliance and integration workloads from core business transactions so that failures or slow external systems don't become failures of the core application.

These problems sit at the intersection of **software architecture, databases, business rules, and real-world operations.**

---

## Building from the domain outward

My background gives me an unusual perspective on software development.

I don't want to build healthcare software that merely **looks like healthcare software**.

I want to understand the workflow first.

Who performs the action?

What state changes?

What should be recorded?

What happens if the transaction fails halfway?

What happens when the workload doubles?

What happens when there are multiple branches?

What happens six months later when someone needs to understand why a number changed?

Those questions increasingly shape how I design SightOps.


## The stack

My current work involves technologies such as:

**Python • FastAPI • PostgreSQL • Supabase • JavaScript • REST APIs • GitHub • Cloud Infrastructure**

But I'm more interested in **systems and architecture** than collecting technologies.

The technology is the implementation.

**The hard part is getting the model right.**


## What I'm exploring

I'm particularly interested in:

* Healthcare technology
* Pharmacy systems
* Operational SaaS
* Multi-tenant architecture
* Transactional data systems
* Inventory systems
* Financial systems
* PostgreSQL
* Distributed and background workloads
* Production performance
* Observability
* Business process automation
* Turning messy real-world workflows into reliable software


## Beyond the code

My goal isn't simply to write more software.

It's to build software that makes the people using it **better at their jobs**.

A pharmacist should spend less time fighting inventory problems.

A manager should be able to understand what is happening across their branches.

A business owner should be able to trust the numbers.

And a healthcare organization should be able to grow without its operational systems becoming the bottleneck.

That's the kind of software I want to build.


## Currently

I'm actively building and evolving **SightOps** from a working healthcare operations platform into a scalable multi-tenant SaaS system.

The journey is taking me deeper into:

**Software Architecture • Database Engineering • Financial Systems • Healthcare Workflows • Performance Engineering • Production Reliability**

I'm still a pharmacist.

I'm also becoming a systems builder.

**SightOps is where those two worlds meet.**


### Building useful systems for the real world.

**Pharmacy • Healthcare • Software • SaaS • Automation • Production Systems**
