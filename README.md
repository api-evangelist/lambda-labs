# Lambda (lambda-labs)

Lambda (formerly Lambda Labs) is a GPU cloud provider offering on-demand NVIDIA GPU instances, 1-Click Clusters of 16-2,000+ interconnected H100 and B200 GPUs, long-term reserved Hyperplane capacity, filesystems, firewalls, and SSH key management. Lambda Cloud is accessed via a REST control-plane API, the web console, and SDKs/CLI tooling.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lambda-labs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lambda-labs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** 3rd-Party

## Tags

- AI
- Cloud
- Clusters
- Compute
- GPU
- Inference
- Machine Learning

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### Lambda Cloud API

The Lambda Cloud API is the REST control plane for launching, listing, starting, stopping, and terminating GPU instances, managing SSH keys, firewalls, filesystems, images, and instance types. It supports on-demand single instances and underpins programmatic access to Lambda's GPU fleet.

- **Human URL:** [https://docs.lambda.ai/api/cloud](https://docs.lambda.ai/api/cloud)
- **Base URL:** `https://cloud.lambda.ai/api/v1`

#### Tags

- Cloud
- Compute
- Filesystems
- Firewalls
- GPU
- Instances
- REST
- SSH Keys

#### Properties

- [Documentation](https://docs.lambda.ai/api/cloud)
- [Documentation](https://docs.lambda.ai/public-cloud/cloud-api/)
- [Postman Collection](collections/lambda-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lambda-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lambda 1-Click Clusters

Lambda 1-Click Clusters provision interconnected clusters of 16 to 2,000+ NVIDIA H100 SXM or B200 GPUs for short-duration distributed training workloads. The product is exposed through the Lambda Cloud console and is integrated with the Cloud API surface.

- **Human URL:** [https://docs.lambda.ai/public-cloud/1-click-clusters/](https://docs.lambda.ai/public-cloud/1-click-clusters/)

#### Tags

- B200
- Clusters
- GPU
- H100
- Training

#### Properties

- [Documentation](https://docs.lambda.ai/public-cloud/1-click-clusters/)
- [Postman Collection](collections/lambda-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lambda-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lambda Cloud Filesystems

Lambda Cloud Filesystems provide persistent, sharable storage attached to on-demand instances for datasets and checkpoints. Filesystems are managed through the Cloud API and console.

- **Human URL:** [https://docs.lambda.ai/public-cloud/filesystems/](https://docs.lambda.ai/public-cloud/filesystems/)

#### Tags

- Filesystems
- Persistent Storage
- Storage

#### Properties

- [Documentation](https://docs.lambda.ai/public-cloud/filesystems/)
- [Postman Collection](collections/lambda-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lambda-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lambda Inference API

Lambda Inference API is an OpenAI-compatible REST gateway at https://api.lambda.ai/v1 that serves hosted open-source language models (Llama, DeepSeek, Hermes, Qwen, and others) behind the standard OpenAI Chat Completions surface. Chat completion responses can be streamed as HTTP Server-Sent Events by setting "stream":true on the POST /chat/completions request body; the SSE stream emits chat.completion.chunk events terminated by a data [DONE] sentinel. As of 2026-05-29 Lambda has announced the Inference API is winding down in favor of customer self-hosted deployments on Lambda GPU instances.

- **Human URL:** [https://docs.lambda.ai/public-cloud/lambda-inference-api/](https://docs.lambda.ai/public-cloud/lambda-inference-api/)
- **Base URL:** `https://api.lambda.ai/v1`

#### Tags

- AI
- Chat
- Completions
- Inference
- LLM
- OpenAI Compatible
- SSE
- Streaming

#### Properties

- [Documentation](https://docs.lambda.ai/public-cloud/lambda-inference-api/)
- [Documentation](https://lambda.ai/inference)
- [AsyncAPI](asyncapi/lambda-labs-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/lambda-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lambda-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://lambda.ai)
- [Developer](https://docs.lambda.ai)
- [Documentation](https://docs.lambda.ai)
- [Portal](https://cloud.lambda.ai)
- [Sign Up](https://cloud.lambda.ai/sign-up)
- [Login](https://cloud.lambda.ai/login)
- [Pricing](https://lambda.ai/service/gpu-cloud)
- [Blog](https://lambda.ai/blog)
- [Terms of Service](https://lambda.ai/legal/terms-of-service)
- [Privacy Policy](https://lambda.ai/legal/privacy-policy)
- [Support](https://lambda.ai/contact)
- [GitHub Organization](https://github.com/LambdaLabsML)
- [LinkedIn](https://www.linkedin.com/company/lambda-labs)
- [SDK](https://lambda.ai/lambda-stack-deep-learning-software)
- [Features](undefined)
- [G P Us](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
