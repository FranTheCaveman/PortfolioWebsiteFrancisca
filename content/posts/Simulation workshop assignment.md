+++
title = "Business Process Modelling - Simulation Workshop Assignment"
tags = ["BPM", "Information Systems", "Business"
, "BSYS601", "Signavio", "Blog"]
date = "2024-03-11"
+++


### BSYS601: Business Process Management - Simulation Workshop Assignment - A+ level (100%)

Below is the Simulation Workshop Assignment doc for the BSYS601 paper. If the preview does not work, click the link [here](https://drive.google.com/file/d/1V25qn4DyoiYgnP_XPjEIV0trFuCe9VB2/view).

{{< shortcodesnippet >}}

    <iframe src="https://drive.google.com/file/d/1V25qn4DyoiYgnP_XPjEIV0trFuCe9VB2/preview" width="640" height="480" allow="autoplay"></iframe>

{{< /shortcodesnippet >}}

Below is the Simulation Workshop Claim handling process diagram. If the preview does not work, click the link [here](https://drive.google.com/file/d/1IbBJvZ7otTEDEXpnCzkVsT3WI2qXRVso/view).

{{< shortcodesnippet >}}

    <iframe src="https://drive.google.com/file/d/1IbBJvZ7otTEDEXpnCzkVsT3WI2qXRVso/preview" width="640" height="480" allow="autoplay"></iframe>

{{< /shortcodesnippet >}}

Below is the Simulation output from Signavio. If the preview does not work, click the link [here](https://drive.google.com/file/d/14ByfvgU4qdYuzXvccbyyGZlQdXVr4tsa/view).

{{< shortcodesnippet >}}

    <iframe src="https://drive.google.com/file/d/14ByfvgU4qdYuzXvccbyyGZlQdXVr4tsa/preview" width="640" height="480" allow="autoplay"></iframe>

{{< /shortcodesnippet >}}

{{< details "Case Study" >}}

An insurance company, AAA, believes that they should take a careful look at the performance
of their claim-to-resolution process. The manager suspects that the process does not perform
sufficiently well when they experience spike in demand.

#### Process Description

The process starts when a call related to lodging a claim is received in the AAA call centre.
The call centre operator checks if the customer has enough information required to lodge a
claim (e.g., insurance policy number), this requires on average 120 seconds with 30 seconds
standard deviation per call. If the customer has enough information (9 in 10 customers do),
the operator then goes through a questionnaire with the customer (taking 300 seconds), enters
all relevant details (taking 120 seconds), and registers the claim (taking 120 seconds). For the
customer who does not have enough information, the operator advises them to prepare all the
necessary information, which takes 60 seconds and the call ends.

Once a claim has been registered, the claims handling officer evaluates the liability of the
customer, which requires 120 seconds. In 15% of the cases the customer is not liable, and
the call ends. For those cases that the customer is liable, the officer assesses the claim in
order to determine if the insurance company has to cover this liability and to what extent. This
operation is quite time consuming and requires 1200 seconds, leading to the rejection of 1 in
5 claims. For those rejected claims, the call ends. If the claim is accepted, the claims handling
officer calculates the payment (taking 120 seconds).

After that, the claims handling officer advises the customer of the amount to be paid (taking
120 seconds) and simultaneously, initiates the payment which requires 240 seconds. Finally,
the claims handling officer closes the claim, which takes 60 seconds), and the call ends.

During normal times, the insurance company receives about 1,000 calls per day, but during
storm scenarios, the number of calls increases to about 4,000 per day. There are 80 call
centre operators with $30 hourly pay and 150 claims handling officers with $50 hourly pay.
The claim handling process is open for services Mon-Fri, 9:00 – 17:00.

{{< / details >}}

#### Summary

This project involved

1. Modelling a business process diagram based on the case study description
2. Using Signavio's simulation tool to create 2 scenarios: "normal times" and "storm scenarios"
3. Running the simulation as multiple cases with the 1-day duration
4. Observing and comparing differences between: cycle times, costs, resource consumption, and bottlenecks
