# LITELLM

> Anticloud offline package — upstream: BerriAI/litellm @ `main`.

## What This Project Does

The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format with cost tracking, guardrails, load balancing, and logging [Bedrock, Azure, OpenAI, Anthropic, OpenAI, VertexAI, vLLM, Nvidia NIM]

**Topics:** ai-gateway, anthropic, azure-openai, bedrock, gateway, langchain, litellm, llm, llm-gateway, llmops, mcp-gateway, openai, openai-proxy, rust, rust-ai, vertex-ai

## Upstream README

<h1 align="center">
        🚅 LiteLLM
    </h1>
    <p align="center">
        <p align="center">LiteLLM AI Gateway
        </p>
        <p align="center">Open Source AI Gateway for 100+ LLMs. Self-hosted. Enterprise-ready. Call any LLM in OpenAI format.</p>
        <p align="center">
        <a href="https://render.com/deploy?repo=https://github.com/BerriAI/litellm" target="_blank" rel="nofollow"><img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render" height="40"></a>
        <a href="https://railway.com/deploy/RhvhdC?referralCode=7mRv9K&utm_medium=integration&utm_source=template&utm_campaign=generic"><img src="https://railway.com/button.svg" alt="Deploy on Railway" height="40"></a>
        <a href="https://console.aws.amazon.com/cloudshell/home" target="_blank" rel="nofollow"><img src="./.github/deploy-on-aws.png" alt="Deploy on AWS" height="40"></a>
        <a href="https://ssh.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https%3A%2F%2Fgithub.com%2FBerriAI%2Fterraform-google-litellm&cloudshell_git_branch=v1.105.0&cloudshell_workspace=examples%2Fdefault&cloudshell_tutorial=TUTORIAL.md&cloudshell_image=gcr.io/ds-artifacts-cloudshell/deploystack_custom_image&shellonly=true" target="_blank" rel="nofollow"><img src="./.github/deploy-on-gcp.png" alt="Deploy on GCP" height="40"></a>
        </p>
    </p>
<h4 align="center"><a href="https://docs.litellm.ai/docs/simple_proxy" target="_blank">LiteLLM Proxy Server (AI Gateway)</a> | <a href="https://docs.litellm.ai/docs/enterprise#hosted-litellm-proxy" target="_blank"> Hosted Proxy</a> | <a href="https://litellm.ai/enterprise"target="_blank">Enterprise Tier</a> | <a href="https://www.litellm.ai/ai-gateway" target="_blank">Website</a></h4>
<h4 align="center">
    <a href="https://pypi.org/project/litellm/" target="_blank">
        <img src="https://img.shields.io/pypi/v/litellm.svg" alt="PyPI Version">
    </a>
    <a href="https://github.com/BerriAI/litellm" target="_blank">
        <img src="https://img.shields.io/github/stars/BerriAI/litellm.svg?style=social" alt="GitHub Stars">
    </a>
    <a href="https://www.ycombinator.com/companies/berriai">
        <img src="https://img.shields.io/badge/Y%20Combinator-W23-orange?style=flat-square" alt="Y Combinator W23">
    </a>
    <a href="https://wa.link/huol9n">
        <img src="https://img.shields.io/static/v1?label=Chat%20on&message=WhatsApp&color=success&logo=WhatsApp&style=flat-square" alt="Whatsapp">
    </a>
    <a href="https://discord.gg/wuPM9dRgDw">
        <img src="https://img.shields.io/static/v1?label=Chat%20on&message=Discord&color=blue&logo=Discord&style=flat-square" alt="Discord">
    </a>
    <a href="https://www.litellm.ai/support">
        <img src="https://img.shields.io/static/v1?label=Chat%20on&message=Slack&color=black&logo=Slack&style=flat-square" alt="Slack">
    </a>
    <a href="https://codspeed.io/BerriAI/litellm?utm_source=badge">
        <img src="https://img.shields.io/endpoint?url=ht

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
