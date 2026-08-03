# Amazon Simple Workflow Service

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon Simple Workflow Service (Amazon SWF) helps developers build, run, and scale background jobs that have parallel or sequential steps. It is a fully managed state tracker and task coordinator in the cloud that manages intertask dependencies, scheduling, and concurrency for application workflows.

## APIs

### Amazon Simple Workflow Service API

The Amazon SWF API provides programmatic access to manage workflows, activity tasks, decision tasks, and workflow execution history. It enables developers to coordinate distributed application components using asynchronous task processing and state tracking.

**Properties:**

- **Documentation**: [https://docs.aws.amazon.com/amazonswf/latest/developerguide/](https://docs.aws.amazon.com/amazonswf/latest/developerguide/)
- **APIReference**: [https://docs.aws.amazon.com/amazonswf/latest/apireference/](https://docs.aws.amazon.com/amazonswf/latest/apireference/)
- **GettingStarted**: [https://docs.aws.amazon.com/amazonswf/latest/developerguide/swf-dg-intro-to-swf.html](https://docs.aws.amazon.com/amazonswf/latest/developerguide/swf-dg-intro-to-swf.html)
- **Pricing**: [https://aws.amazon.com/swf/pricing/](https://aws.amazon.com/swf/pricing/)
- **FAQ**: [https://aws.amazon.com/swf/faqs/](https://aws.amazon.com/swf/faqs/)
- **OpenAPI**: [https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/openapi/amazon-swf-openapi-original.yml](https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/openapi/amazon-swf-openapi-original.yml)

## Common Properties

- **Portal**: [https://aws.amazon.com/](https://aws.amazon.com/)
- **Website**: [https://aws.amazon.com/swf/](https://aws.amazon.com/swf/)
- **Documentation**: [https://docs.aws.amazon.com/amazonswf/latest/developerguide/](https://docs.aws.amazon.com/amazonswf/latest/developerguide/)
- **Console**: [https://console.aws.amazon.com/swf/](https://console.aws.amazon.com/swf/)
- **TermsOfService**: [https://aws.amazon.com/service-terms/](https://aws.amazon.com/service-terms/)
- **PrivacyPolicy**: [https://aws.amazon.com/privacy/](https://aws.amazon.com/privacy/)
- **Support**: [https://aws.amazon.com/premiumsupport/](https://aws.amazon.com/premiumsupport/)
- **SignUp**: [https://signin.aws.amazon.com/signup?request_type=register](https://signin.aws.amazon.com/signup?request_type=register)
- **Login**: [https://aws.amazon.com/console/](https://aws.amazon.com/console/)
- **StatusPage**: [https://health.aws.amazon.com/health/status](https://health.aws.amazon.com/health/status)
- **GitHubOrganization**: [https://github.com/aws](https://github.com/aws)
- **Features**: 5 items
- **UseCases**: 4 items
- **SpectralRules**: [https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/rules/amazon-swf-spectral-rules.yml](https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/rules/amazon-swf-spectral-rules.yml)
- **Vocabulary**: [https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/vocabulary/amazon-swf-vocabulary.yaml](https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/vocabulary/amazon-swf-vocabulary.yaml)
- **NaftikoCapability**: [https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/capabilities/amazon-swf-workflow-management.yaml](https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/capabilities/amazon-swf-workflow-management.yaml)

## Artifacts

### Openapi
- `openapi/amazon-swf-openapi-original.yml`

### Json Schema
- `json-schema/amazon-swf-activityid-schema.json`
- `json-schema/amazon-swf-activitytask-schema.json`
- `json-schema/amazon-swf-activitytaskcanceledeventattributes-schema.json`
- `json-schema/amazon-swf-activitytaskcancelrequestedeventattributes-schema.json`
- `json-schema/amazon-swf-activitytaskcompletedeventattributes-schema.json`
- ... and 221 more

### Json Structure
- `json-structure/amazon-swf-activityid-structure.json`
- `json-structure/amazon-swf-activitytask-structure.json`
- `json-structure/amazon-swf-activitytaskcanceledeventattributes-structure.json`
- `json-structure/amazon-swf-activitytaskcancelrequestedeventattributes-structure.json`
- `json-structure/amazon-swf-activitytaskcompletedeventattributes-structure.json`
- ... and 221 more

### Json Ld
- `json-ld/amazon-swf-context.jsonld`

### Examples
- `examples/amazon-swf-poll-activity-task-example.json`
- `examples/amazon-swf-register-domain-example.json`
- `examples/amazon-swf-start-workflow-execution-example.json`

### Rules
- `rules/amazon-swf-spectral-rules.yml`

### Vocabulary
- `vocabulary/amazon-swf-vocabulary.yaml`

### Capabilities
- `capabilities/amazon-swf-workflow-management.yaml`
- `capabilities/shared/amazon-swf-shared.yaml`
