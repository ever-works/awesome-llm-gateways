# Awesome LLM Gateways

A curated directory of LLM gateways, routers and proxies that put many models behind one API, with routing, caching, fallbacks and cost controls.

## 📑 Table of Contents

- [Edge AI Gateways (5)](#edge-ai-gateways)
- [Managed Gateways (2)](#managed-gateways)
- [MCP Gateways (2)](#mcp-gateways)
- [Model Routers (7)](#model-routers)
- [Observability-First Gateways (2)](#observability-first-gateways)
- [Open-Source Gateways (4)](#open-source-gateways)


## Edge AI Gateways

- [Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway) - Cloudflare AI Gateway is a managed edge service that sits between applications and AI providers to provide caching, rate limiting, request retries, fallback models, and analytics. It operates on Cloudflare's global network with a generous free tier for observability and control. ([Read more](/details/cloudflare-ai-gateway.md)) `Free Plan` `Managed` `API` `AI-Powered` `Edge Computing` `Caching` `Free`
- [Gloo Gateway](https://www.solo.io/products/gloo-gateway) - Gloo Gateway is an Envoy-based API gateway with AI capabilities for traffic management, security, and observability across hybrid environments. It provides AI-specific routing, transformation, and policy enforcement for Kubernetes and VM workloads. ([Read more](/details/gloo-gateway.md)) `Freemium` `Enterprise` `Self-Hosted` `API` `AI-Powered` `Envoy-Based` `Kubernetes`
- [Kong AI Gateway](https://konghq.com/products/kong-ai-gateway) - Kong AI Gateway extends the Kong API gateway with AI-specific plugins for request/response transformation, token rate limiting, semantic caching, and model fallbacks. It targets enterprises needing governance, security, and traffic control for AI workloads at scale. ([Read more](/details/kong-ai-gateway.md)) `Freemium` `Enterprise` `Self-Hosted` `API` `AI-Powered` `Governance`
- [Vercel AI Gateway](https://vercel.com/docs/ai-gateway) - Vercel AI Gateway is a managed service that provides a unified API for multiple AI providers with edge caching, rate limiting, and observability. It integrates with Vercel's frontend cloud and supports streaming responses for real-time AI applications. ([Read more](/details/vercel-ai-gateway.md)) `Freemium` `Managed` `API` `AI-Powered` `Edge Computing` `Frontend Integration`
- [Zuplo](https://zuplo.com/) - Zuplo is a programmable, edge-native API gateway with built-in AI features for rate limiting, caching, and transformation of LLM traffic. It targets developers with a code-first approach, TypeScript policies, and global edge deployment for low-latency AI applications. ([Read more](/details/zuplo.md)) `Freemium` `Managed` `API` `AI-Powered` `Edge Native` `Programmable` `TypeScript`

## Managed Gateways

- [Baseten](https://www.baseten.co/) - Baseten is a managed ML infrastructure platform with Truss, an open-source model serving framework, and an LLM gateway for deploying models on autoscaling GPUs. It offers a unified API, cold-start optimization, and enterprise security for production inference. ([Read more](/details/baseten.md)) `Freemium` `Managed` `API` `AI-Powered` `Autoscaling` `Truss` `Cold Start Optimization`
- [Hugging Face Inference Endpoints](https://huggingface.co/inference-endpoints) - Hugging Face Inference Endpoints offers managed, autoscaling infrastructure to deploy any model from the Hub as a dedicated API. It provides secure, enterprise-ready endpoints with zero-configuration scaling and integrated observability for production workloads. ([Read more](/details/hugging-face-inference-endpoints.md)) `Freemium` `Managed` `API` `AI-Powered` `Model Hub Integration` `Autoscaling` `Enterprise`

## MCP Gateways

- [TensorZero](https://www.tensorzero.com/) - TensorZero is an open-source LLM gateway and control plane that unifies model access, observability, and optimization. It uses structured feedback to automatically improve prompts and model selection, targeting teams building production AI systems with continuous learning. ([Read more](/details/tensorzero.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `AI-Powered` `Control Plane` `Optimization`
- [TrueFoundry](https://www.truefoundry.com/) - TrueFoundry provides an ML control plane with an LLM gateway for deploying, monitoring, and optimizing models across clouds. It offers unified APIs, auto-scaling, cost controls, and guardrails for enterprise teams operationalizing LLMs at scale. ([Read more](/details/truefoundry.md)) `Freemium` `Enterprise` `Managed` `API` `AI-Powered` `Control Plane` `MLOps`

## Model Routers

- [AWS Bedrock](https://aws.amazon.com/bedrock) - Amazon Bedrock is a fully managed service offering a unified API to access foundation models from leading AI companies. It provides model customization, guardrails, agents, and knowledge bases with enterprise security and AWS integration for building generative AI applications. ([Read more](/details/aws-bedrock.md)) `Freemium` `Managed` `API` `AI-Powered` `Guardrails` `Agents` `Knowledge Bases` `Enterprise`
- [Fireworks AI](https://fireworks.ai/) - Fireworks AI provides a managed inference platform with a unified API for open-source and custom models. It features compound AI systems, function calling, JSON mode, and optimized serving engines for low-latency production deployments. ([Read more](/details/fireworks-ai.md)) `Freemium` `Managed` `API` `AI-Powered` `Compound AI` `Function Calling` `Low Latency`
- [Martian](https://www.withmartian.com/) - Martian is a model router that uses model understanding to dynamically route requests to the optimal LLM based on capability, cost, and latency. It provides a single API with automatic fallbacks, caching, and detailed analytics for production workloads. ([Read more](/details/martian.md)) `Freemium` `API` `AI-Powered` `Dynamic Routing` `Model Understanding` `Fallbacks`
- [Not Diamond](https://www.notdiamond.ai/) - Not Diamond is an AI model router that automatically selects the best LLM for each query using a meta-model trained on human preferences. It offers a unified API with intelligent routing, fallbacks, and cost optimization for developers seeking optimal model performance per task. ([Read more](/details/not-diamond.md)) `Freemium` `API` `AI-Powered` `Intelligent Routing` `Model Selection` `Cost Optimization`
- [OpenRouter](https://openrouter.ai/) - OpenRouter is a model router offering a unified API to access hundreds of open and closed-source LLMs with automatic failover, caching, and per-model pricing transparency. It serves developers and applications needing model diversity without managing multiple provider accounts. ([Read more](/details/openrouter.md)) `Freemium` `API` `AI-Powered` `Model Marketplace` `Cost Transparency`
- [Replicate](https://replicate.com/) - Replicate provides a cloud API for running open-source models with automatic scaling and per-second billing. It offers a unified interface for 1000+ models, model versioning, and fine-tuning capabilities for developers integrating AI into applications. ([Read more](/details/replicate.md)) `Freemium` `Managed` `API` `AI-Powered` `Model Marketplace` `Per-Second Billing` `Fine-tuning`
- [Together AI](https://www.together.ai/) - Together AI offers a cloud platform for running open-source models with a unified inference API, fine-tuning, and dedicated endpoints. It provides access to 200+ models with optimized serving, token-based pricing, and enterprise features for production workloads. ([Read more](/details/together-ai.md)) `Freemium` `Managed` `API` `AI-Powered` `Open Models` `Fine-tuning` `Dedicated Endpoints`

## Observability-First Gateways

- [Helicone](https://www.helicone.ai/) - Helicone is an open-source observability platform for LLMs that acts as a proxy to log requests, track costs, latency, and quality metrics. It supports self-hosted and cloud deployments with features for prompt versioning, experiments, and user feedback collection. ([Read more](/details/helicone.md)) `Open Source` `Self-Hosted` `Freemium` `API` `Observability` `Prompt Management`
- [Portkey](https://portkey.ai/) - Portkey is a managed AI gateway providing a unified API for 200+ models with built-in observability, caching, fallbacks, and cost controls. It offers a control plane for prompt management, evaluations, and guardrails targeting production LLM applications. ([Read more](/details/portkey.md)) `Freemium` `Managed` `API` `AI-Powered` `Observability` `Guardrails`

## Open-Source Gateways

- [Apache APISIX](https://apisix.apache.org/) - Apache APISIX is an open-source API gateway with AI plugins for LLM proxying, token rate limiting, semantic caching, and request/response transformation. It runs on etcd, supports plugin-based extensibility, and targets high-performance cloud-native traffic management. ([Read more](/details/apache-apisix.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `AI-Powered` `Plugin Architecture` `High Performance`
- [Bifrost](https://bifrost.ai/) - Bifrost is an open-source LLM gateway providing a single API for multiple providers with intelligent routing, caching, and cost optimization. It focuses on developer experience with TypeScript-first SDKs and supports self-hosted deployments for data privacy. ([Read more](/details/bifrost.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `AI-Powered` `TypeScript` `Cost Optimization`
- [Envoy AI Gateway](https://gateway.envoyproxy.io/) - Envoy AI Gateway is an open-source project extending Envoy Proxy with AI-specific filters for token-based rate limiting, model routing, request/response transformation, and observability. It provides a cloud-native data plane for AI traffic management in Kubernetes environments. ([Read more](/details/envoy-ai-gateway.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `AI-Powered` `Kubernetes` `Envoy Proxy`
- [LiteLLM](https://www.litellm.ai/) - LiteLLM is an open-source Python library and proxy server that standardizes calls to 100+ LLMs through a single OpenAI-compatible API. It supports load balancing, fallbacks, caching, and cost tracking for teams building multi-model applications. ([Read more](/details/litellm.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `AI-Powered` `Load Balancing`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This work may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this work, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg