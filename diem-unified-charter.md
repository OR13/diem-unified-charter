## Background

An emblem is a device, symbol, or figure adopted and used as an identifying mark.
In culture, emblems such as a flag, badge or coat of arms communicate group identity.
In speech, emblems are specific nonverbal gestures or signals that have a direct verbal translation and are widely understood within a particular culture or community.
The emblems of the International Committee of the Red Cross (ICRC)  are symbols of protection under the Geneva Conventions and are to be worn by all medical and humanitarian personnel and also displayed on their vehicles and buildings while they are in an active warzone, and all military forces operating in an active warzone must not attack entities displaying these emblems.
ISO 7010 defines a set of emblems that can be used to identify hazards, these include the skull and crossbones for toxic material, the ionizing radiation symbol and the biological hazard symbol.
The white cane is an international emblem for visually impaired pedestrians.
The international symbol for deafness is a white ear with a strip through it on a blue background.
A tactile symbol is used to communicate with vision impaired individuals.
For example, a trapezoid with bars indicating numbers, or a heart with textures to indicate emotions.
These emblems/symbols require a sense of sight, or touch to become known to the receiver.
"To bear an emblem" means to use or adopt a symbol, figure, or device as an identifying mark. 
To "verify an emblem" means to confirm the authenticity or legitimacy of a particular symbol or design, often by checking its details against a known standard or reference point.
Emblems may be observed by verifiers without the knowledge of the bearer displaying the emblem, or may be presented to a specific verifier upon request.

To be effective, the semantics of an emblem must be well known, and the emblem must be easily recognizable, and distinguishable from other emblems.

## Introduction

There is a need to sense emblems/symbols through digital communication channels, in contrast to visual or tactile sense and communication.
This need arises due to the increasing relevance and impact of cyber operations on human rights, commerce, and security.
An NFPA 704 Symbol can communicate flammability, health, reactivity and special notices and extensions.
A digital emblem provides a mechanism for communicating the attributes or status of an asset that bears the emblem.
Digital emblems extend the range of identifying marks from the physical (visual and tactile) to the digital realm.
The presence of a digital emblem represents a new signal available to cyber operators, one which can be combined with existing operational procedures to reduce uncertainty and improve decision making.

The DIEM working group produces documents which describe the creation, presentation, validation and interpretation of digital emblems.

## Initial Scope

Under the current charter, the working group is limited to the presentation / discovery of digital emblems for the following digital assets: 

* domain names
* hostnames
* ip addresses

Designs for QRCodes, NFC, Bluetooth, and other discovery mechanisms are currently out of scope.

The working group will first describe a high level informational architecture and data model.
After the architecture and data model are published as an informational RFC, the working group will specify a single concrete serialization and a discovery mechanism based on the DNS.
The working group will coordinate with relevant working groups within the IETF and other SDOs to ensure that existing standards are leveraged appropriately.
The working group will not produce any standard track generic serialization formats.
The working group will not produce any standard track extensions to the DNS. 
The working group will not develop novel security mechanisms, cryptographic primitives, or digital signature schemes.
Until the architecture document is published, the working group will develop and maintain an informational use cases and requirements document, but is not required to request publication of this document.

### Investigation of Serialization Formats

The working group will research, analyze and evaluate application layer serialization formats for suitability to the initial scope.
The working group will attempt to match the conventions for serializing data structures used in the discovery protocols, for example, key value strings in DNS records or structured field values in http.
This work must be completed in the use cases and requirements document, and the architecture must not assume any specific serialization formats or discovery mechanisms.

### Investigation of Securing Mechanisms

The working group will research, analyze and evaluate securing mechanisms for digital emblems.
The group is not required to describe object level securing mechanisms, in the case that existing protocol level securing mechanisms are sufficient, for example DNSSEC for DNS records, or TLS for well known HTTPS URLs.
This work must be completed in the use cases and requirements document, and the architecture must not assume any specific securing mechanism or discovery mechanisms.

### Design of Emblem Types

The working group will describe at least one digital emblem suitable for indicating protection under international humanitarian law.
The working group will describe at least one digital emblem suitable for indicating the presence of a hazard or a certification of the absence of a hazard.
This work must be completed in the use cases and requirements document, and must not assume any specific serialization format or discovery mechanisms.

### Use Cases and Requirements

The working group will develop an informational document describing use cases and requirements for the initial proposed standards.
Although this document is listed as a deliverable, it is not required to be published as an RFC.

### Architecture

The working group will develop an informational document describing the architecture, terminology and data model of digital emblems.
This document must not assume any specific serialization formats, securing mechanisms, discovery mechanisms, or use cases.
This document must be published as an informational RFC, before any proposed standard documents can be adopted by the working group.

### Initial Serialization

A proposed standard describing the first serialization format for digital emblems.
This document may describe a mandatory to implement securing mechanism.
If a securing mechanism is described, this document must describe at least one mandatory to implement cryptographic algorithm which is already supported by the securing mechanism.
This document must be published as a proposed standard RFC, and must not assume any specific use cases.

### Initial Discovery Mechanism

A proposed standard describing the use of the DNS as the initial presentation/discovery mechanism for digital emblems.
This document may describe a mandatory to implement securing mechanism.
This document must be published as a proposed standard RFC, and must not assume any specific serialization formats, or use cases.

### Initial Emblem Types

A proposed standard describing the use of the Initial Serialization and Initial Discovery Mechanism for no more than two of the emblem types described in the use cases and requirements document.
This document must be published as a proposed standard RFC, and must not be adopted until after the publication of the Initial Serialization and Initial Discovery Mechanism has been requested.

