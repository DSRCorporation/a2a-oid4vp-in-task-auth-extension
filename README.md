# OID4VP In-Task Authentication Extension

This directory contains the specification for the **OID4VP In-Task Authentication Extension v1** for the Agent2Agent (A2A) protocol.

## Purpose

The OpenID for Verifiable Presentations (OID4VP) In-Task Authentication extension provides an option to use OID4VP protocol for A2A In-Task authentication.

The integration of OID4VP flow allows Server Agents to perform additional authentification by requesting Verifiable Presentations (VPs) from the client.
Such VP-based authorization enables Just-In-Time (JIT) authorization – server can dynamically request specific credentials during a Task execution without breaking the protocol flow.

Suggested integration provides clear protocol boundaries that set minimal restrictions on A2A and OID4VP protocols and allow usage of all features specified by these protocols.

## Specification

The full specification (v1 Draft) can be found [here](./v1/spec.md).

## Sample Implementation - TODO