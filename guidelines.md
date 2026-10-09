# Microproduct Guidelines

[Handbook](README.md) | [Build Session 1](build%20session%20checklist/build-session-1.md) | [Build Session 2](build%20session%20checklist/build-session-2.md) | [Build Session 3](build%20session%20checklist/build-session-3.md) | [Demo Video Guidelines](demo-video-guidelines.md)

These guidelines are intentionally lightweight. We will continue adding context, examples, and constraints throughout the build sessions.

Keep a tab on this page as you build.

## What is a microproduct?

A **microproduct** is a focused app that:

* Solves a real problem
* Creates real value
* Has a clearly defined user
* Is small enough to build, test, and demonstrate quickly

The goal is not to build a startup.

The goal is to build something **useful**.

---

## 1. Think in terms of value

Value does not need to mean revenue.

A product can create meaningful value without having a business model, charging users, or ever being monetized.

A simple way to think about total value is:

$$
\text{Value} = N \times V
$$

Where:

| Variable | Meaning |
| --- | --- |
| $N$ | Number of people who use the product |
| $V$ | Value created per person |

The value per person does not need to correspond to an actual transaction.

Ask:

> If this product disappeared tomorrow, how much utility would a user feel they had lost?

An open source tool might be completely free while still saving someone hours of work.

A public service might never generate revenue while still creating enormous value.

You can think of this as an **implicit dollar value**, even when nobody is actually paying.

---

## 2. Decompose per capita value

We can go one level deeper:

$$
V = D \times I
$$

Where:

| Variable | Meaning |
| --- | --- |
| $D$ | Duration or frequency of the value |
| $I$ | Intensity of the value |

Therefore:

$$
\boxed{\text{Value} = N \times D \times I}
$$

Different products create value in very different ways.

| Product | Duration / Frequency | Intensity |
| --- | --- | --- |
| Amber Alert | Low | Very high |
| Weather app | High | Low |
| Daily productivity tool | High | Medium |
| Emergency navigation tool | Low | Very high |

There is no single correct combination.

A product can be valuable because it solves a small problem repeatedly or because it solves an extremely important problem once.

---

## 3. You should be User One

For this tournament, there is one important constraint:

> **You should be the first user of your product.**

If nobody uses your product:

$$
N = 0
$$

Then:

$$
\text{Value} = 0 \times D \times I = 0
$$

You can argue that millions of people *might* use something.

You can argue that the problem *could* be extremely valuable.

But going from:

$$
N = 0 \rightarrow N = 1
$$

is already a major step.

Start with yourself.

You are the **N of 1**.

Build something that solves a problem you genuinely experience, then demonstrate that it creates value for at least one real person.

From there, you can ask:

$$
N = 1 \rightarrow 10 \rightarrow 100 \rightarrow \dots
$$

---

## The lens

As you build, keep asking:

* **Who is the user?**
* **What problem are they experiencing?**
* **What value does solving it create?**
* **How often does that value occur?**
* **How important is it when it occurs?**
* **Would I genuinely use this myself?**

Start small.

Solve something real.

Create value for **N = 1** first.
