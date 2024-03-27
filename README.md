# ResearchStudy FHIR Source

This repository contains FHIR ResearchStudy resources to be used as a source for a proof of concept research study directory application.

The test endpoint will collect all resources located in the `resources/{resource-type}` directory
and return them in a `Bundle` for `GET /{resource-type}`.
