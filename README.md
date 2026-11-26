![ProofPath](assets/proofpath-banner.png)

# ProofPath

Verifiable custody for school transport.

ProofPath is a UniHack 2026 project by team 404 Braincells from Edith Cowan University (ECU) Sri Lanka.

## The problem

In Sri Lanka, a school child can change hands up to four times a day: from a guardian to the van driver, from the driver to the school, from the school back to the driver, and from the driver to a guardian at home.

Today these handovers are confirmed by word of mouth, phone calls and WhatsApp messages. When a child is not where they should be, there is no shared record of who last had them.

## How ProofPath works

- Every handover is confirmed by the two adults who see the child change hands. Their phones exchange a short-lived signed QR code, so both people must be in the same place.
- At the school gate, staff confirm the whole van at once after a headcount.
- If a confirmation is missing, the system raises an alarm. A trip cannot close while a child is still with the driver.
- A guardian can name someone else to collect their child, using a one-time pass that cannot be reused or copied.
- At the end of each day, the records are sealed on the Cardano blockchain as salted fingerprints, with no names or personal details. Private details and the one-time collector passes are handled on Midnight.

ProofPath records who confirmed each handover. It does not replace staff checks, safeguarding procedures or emergency services.

## Built with

- A web app that runs in the phone's browser, with no app store needed
- A coordinator server for real-time custody and alerts
- Cardano, with smart contracts written in Aiken, for the public daily record
- Midnight, with smart contracts written in Compact, for private credentials and proofs

Everything runs on test networks. No real money is used.

## Status

We are building ProofPath in a private repository while the work is in progress. We will push the code to this repository once we have a first working version.

## Team

404 Braincells, Edith Cowan University Sri Lanka

- Hansaka Jayasuriya (team leader)
- Janitha Illankoon (lead developer)
- Danula Osanda
