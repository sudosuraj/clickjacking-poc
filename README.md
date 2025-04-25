# Clickjacking Proof of Concept (PoC)

This repository contains a simple Clickjacking Proof of Concept (PoC) tool designed to demonstrate how websites can be vulnerable to Clickjacking attacks.

## How to Use
### 1. Visit https://sudosura.github.io/clickjacking-poc.html, and you open the page, you’ll be prompted to enter the URL of the website you want to test for clickjacking vulnerabilities.
### 2. Enter the domain or URL and boom!

## What is Clickjacking?

Clickjacking is a malicious technique where an attacker tricks a user into clicking on something different from what the user perceives, potentially leading to actions such as changing settings or making unintended purchases. This tool helps test if a website is vulnerable to Clickjacking.

The PoC works by embedding a target URL inside an iframe and checking if the website loads without frame busting protections, such as the `X-Frame-Options` or `Content-Security-Policy` headers.

## Features
- Test any website for Clickjacking vulnerabilities.
- Provides mitigation and remediation steps for securing against Clickjacking.
- Displays the status of the website (vulnerable or protected).

