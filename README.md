# SaathiCheck

SaathiCheck is a privacy-first prototype that helps first-time investors identify common warning signs in suspicious investment messages.

## Problem

First-time investors may receive messages that promise guaranteed returns, create urgency, request money, ask for an OTP, or use links to impersonate a trusted organisation. It can be difficult to recognise these signs before harm occurs.

## What the prototype does

1. Lets a user paste the text of a message after removing personal details.
2. Checks for transparent, predefined warning patterns including guaranteed returns, urgency, payment requests, OTP or PIN requests, risky links, approval claims, secrecy, and remote-access requests.
3. Explains why every matched phrase needs caution.
4. Provides a safer next step, such as withholding payment or contacting a bank through a known number.
5. Supports English and Hindi and offers browser-based read aloud where available.

## Privacy and safety

- The analysis runs locally in the browser.
- Message text is not uploaded, stored, or sent to a server.
- It does not request OTPs, banking details, SMS messages, or account access.
- It provides no stock tips, investment recommendations, price predictions, or investment outcome predictions.
- It is a screening aid. A match does not prove fraud, and no match does not prove a message safe.

## Run locally

Download this folder and open `index.html` in a modern web browser. No installation or internet connection is required for the core message check.

## Technology

- HTML
- CSS
- Vanilla JavaScript
- Browser Web Speech API for the optional read-aloud feature

## Future work

- Validate messages and safety wording with anonymised, consented examples.
- Add Indian regional languages with review by native speakers.
- Test with users of varying digital and financial literacy.
- Connect users to verified reporting and support information after appropriate review.

## Hackathon alignment

SaathiCheck is designed for investor protection and safer financial behaviour. It focuses on warning signs, independent verification, accessibility, privacy, and clear communication of uncertainty.

