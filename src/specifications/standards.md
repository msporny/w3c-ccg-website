---
layout: base.njk
basedir: ../..
title: "W3C Standards"
description: "Official W3C Recommendations for Verifiable Credentials and Decentralized Identifiers that enable secure, privacy-preserving digital credentials."
---

<div class="hero">
  <div class="container">
    <h1>Global Standards</h1>
    <p>
Official global standards that provide the foundation for secure,
interoperable verifiable credentials and decentralized identity systems
used worldwide.
    </p>
  </div>
</div>

<section class="content-section">
  <div class="container">
    <h2 class="section-title">Standards Overview</h2>
    <p class="section-subtitle">
The W3C has published a comprehensive family of specifications that enable
verifiable credentials and decentralized identifiers. These standards
provide the technical foundation for secure, privacy-preserving digital
credentials that work across different platforms and systems.
    </p>
  </div>
</section>

<section class="content-section">
  <div class="container">
    <h2 class="section-title">Verifiable Credentials</h2>
    <p>
The Verifiable Credentials family of specifications provides a complete
framework for creating, issuing, and verifying digital credentials:
    </p>
    <div class="feature-grid">
      <div class="feature-card">
        <h3>
          <i class="fas fa-database"></i><a href="https://www.w3.org/TR/2025/REC-vc-data-model-2.0-20250515/" target="_blank" rel="noopener noreferrer">
Verifiable Credentials Data Model v2.0
          </a>
        </h3>
        <p>
The core data model and architecture for verifiable credentials, defining
how credentials are structured and processed. This is the foundational
specification for all verifiable credential implementations.
        </p>
      </div>
      <div class="feature-card">
        <h3>
          <i class="fas fa-lock"></i><a href="https://www.w3.org/TR/2025/REC-vc-data-integrity-20250515/" target="_blank" rel="noopener noreferrer">
Verifiable Credential Data Integrity 1.0
          </a>
        </h3>
        <p>
Defines how to secure verifiable credentials using cryptographic proofs,
ensuring that credentials cannot be tampered with and can be verified
cryptographically.
        </p>
      </div>
      <div class="feature-card">
        <h3>
          <i class="fas fa-key"></i><a href="https://www.w3.org/TR/2025/REC-vc-di-eddsa-20250515/" target="_blank" rel="noopener noreferrer">
Data Integrity EdDSA Cryptosuites v1.0
          </a>
        </h3>
        <p>
Specifies EdDSA (Edwards-curve Digital Signature Algorithm) cryptographic
suites for securing verifiable credentials with high-performance digital
signatures.
        </p>
      </div>
      <div class="feature-card">
        <h3>
          <i class="fas fa-key"></i><a href="https://www.w3.org/TR/2025/REC-vc-di-ecdsa-20250515/" target="_blank" rel="noopener noreferrer">
Data Integrity ECDSA Cryptosuites v1.0
          </a>
        </h3>
        <p>
Defines ECDSA (Elliptic Curve Digital Signature Algorithm) cryptographic
suites for securing verifiable credentials, providing widely-supported
cryptographic protection.
        </p>
      </div>
      <div class="feature-card">
        <h3>
          <i class="fas fa-shield-alt"></i><a href="https://www.w3.org/TR/2025/REC-vc-jose-cose-20250515/" target="_blank" rel="noopener noreferrer">
Securing Verifiable Credentials using JOSE and COSE
          </a>
        </h3>
        <p>
Specifies how to secure verifiable credentials using industry-standard
JOSE (JSON Object Signing and Encryption) and COSE (CBOR Object Signing
and Encryption) formats.
        </p>
      </div>
      <div class="feature-card">
        <h3>
          <i class="fas fa-fingerprint"></i><a href="https://www.w3.org/TR/2025/REC-cid-1.0-20250515/" target="_blank" rel="noopener noreferrer">
Controlled Identifiers v1.0
          </a>
        </h3>
        <p>
Defines a framework for identifiers that can be controlled and managed by
their owners, providing the foundation for decentralized identity systems.
        </p>
      </div>
      <div class="feature-card">
        <h3>
          <i class="fas fa-list-ul"></i><a href="https://www.w3.org/TR/2025/REC-vc-bitstring-status-list-20250515/" target="_blank" rel="noopener noreferrer">
Bitstring Status List v1.0
          </a>
        </h3>
        <p>
Provides an efficient mechanism for checking the revocation and suspension
status of verifiable credentials using compact bitstring representations.
        </p>
      </div>
    </div>
  </div>
</section>

<section class="content-section">
  <div class="container">
    <h2 class="section-title">Decentralized Identifiers</h2>
    <p>
Decentralized Identifiers (DIDs) provide the foundation for decentralized
identity systems that don't rely on centralized authorities:
    </p>
    <div class="feature-grid">
      <div class="feature-card">
        <h3>
          <i class="fas fa-network-wired"></i><a href="https://www.w3.org/TR/did/" target="_blank" rel="noopener noreferrer">
Decentralized Identifiers (DIDs) v1.0
          </a>
        </h3>
        <p>
The core specification for decentralized identifiers, defining the
architecture, data model, and representations for identifiers that can be
created and controlled without centralized authorities.
        </p>
        <p><strong>Status:</strong> W3C Recommendation (July 2022)</p>
      </div>
      <div class="feature-card">
        <h3>
          <i class="fas fa-clipboard-list"></i><a href="https://www.w3.org/TR/did-use-cases/" target="_blank" rel="noopener noreferrer">
Use Cases and Requirements for Decentralized Identifiers
          </a>
        </h3>
        <p>
Documents the use cases and requirements that drove the development of the
DID specification, providing context and examples of how DIDs can be used
in real-world applications.
        </p>
        <p><strong>Status:</strong> W3C Working Group Note (March 2021)</p>
      </div>
    </div>
  </div>
</section>

<section class="content-section">
  <div class="container">
    <h2 class="section-title">Related Standards</h2>
    <div class="feature-grid">
      <div class="feature-card">
        <h3>
          <i class="fas fa-signature"></i><a href="https://www.rfc-editor.org/rfc/rfc9421.html" target="_blank" rel="noopener noreferrer">
IETF HTTP Message Signatures
          </a>
        </h3>
        <p>
RFC 9421 defines a mechanism for creating, encoding, and verifying digital
signatures over HTTP messages. This standard can be used with verifiable
credentials for secure HTTP-based credential exchange.
        </p>
        <p><strong>Status:</strong> IETF RFC (April 2023)</p>
      </div>
    </div>
  </div>
</section>

<section class="content-section">
  <div class="container">
    <h2 class="section-title">Implementation Guidance</h2>
    <ul>
      <li>
<strong>Start with the Data Model</strong> - Begin with the Verifiable
Credentials Data Model v2.0 to understand the core concepts and architecture
      </li>
      <li>
<strong>Choose Security Methods</strong> - Select appropriate cryptographic
suites based on your security requirements and compatibility needs
      </li>
      <li>
<strong>Consider DIDs</strong> - Use Decentralized Identifiers when you
need decentralized identity management without relying on centralized
authorities
      </li>
      <li>
<strong>Plan for Status</strong> - Implement credential status checking
using Bitstring Status List for efficient revocation management
      </li>
      <li>
<strong>Follow Best Practices</strong> - Refer to the specifications for
security considerations and implementation guidance
      </li>
    </ul>
  </div>
</section>

<section class="content-section">
  <div class="container">
    <h2 class="section-title">Additional Resources</h2>
    <ul>
      <li>
<strong><a href="https://www.w3.org/groups/wg/vc/" target="_blank" rel="noopener noreferrer">W3C Verifiable Credentials Working Group</a></strong> - The working
group responsible for developing and maintaining these specifications
      </li>
      <li>
<strong><a href="https://www.w3.org/groups/wg/did/" target="_blank" rel="noopener noreferrer">W3C Decentralized Identifiers Working Group</a></strong> - The working
group responsible for developing and maintaining the DID specifications
      </li>
      <li>
<strong><a href="https://w3c.github.io/vc-test-suite/" target="_blank" rel="noopener noreferrer">Implementation Reports</a></strong> - Documentation of interoperability
testing and implementation experiences
      </li>
      <li>
<strong><a href="https://www.w3.org/community/credentials/" target="_blank" rel="noopener noreferrer">W3C Credentials Community Group</a></strong> - Continues to incubate new features and specifications
      </li>
      <li>
<strong><a href="https://github.com/w3c/vc-test-suite" target="_blank" rel="noopener noreferrer">Test Suites</a></strong> - Comprehensive test suites to verify
specification compliance and interoperability
      </li>
    </ul>
  </div>
</section>