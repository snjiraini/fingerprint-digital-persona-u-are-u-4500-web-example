# Demo of Digitial Persona U.are.U 4500 Fingerprint Reader Web Solution

![demo_image_1](digital_persona_demo_1.jpg)

![demo_image_2](digital_persona_demo_2.jpg)

# Installation Windows 10 and 11 (it might work on other Windows versions)

1. Download Digital Persona Lite Client: https://crossmatch.hid.gl/lite-client/ and install to access the Fingerprint Reader from a browser e.g Chrome.

2. Download the project and run/open index.html.

# ANSI/ISO Compatibility

This application now uses ANSI/ISO compliant fingerprint templates:

- **Standard Format:** ANSI-INCITS 378-2004 (compatible with ISO/IEC 19794-2)
- **File Extension:** .ansi-fmr (Finger Minutiae Record)
- **Default Format:** The application now defaults to using the Intermediate format, which stores fingerprint data in ANSI/ISO compliant templates
- **Compatibility:** Templates can be used with other biometric systems that support these standards

When enrolling users, their fingerprint templates are stored in this standard format, ensuring interoperability with other fingerprint systems.
