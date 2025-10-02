# Building Voice Agents with OpenAI

Workshop at AI Engineer World's Fair 2025

## Requirements

- Node.js 22 or newer with npm installed.

  We will use Node.js for a consistent experience for all attendees but `bun` and `deno` are supported by the SDK.

- An OpenAI account with an OpenAI API key stored as `OPENAI_API_KEY` environment variable

## Setup

Clone this repository to have access to the boilerplate code for our workshop

```bash
git clone git@github.com:ricardovelezz09-lgtm/voice-agents-with-OpenAI.git
cd voice-agents-with-OpenAI
npm install
```

This will automatically install the [OpenAI Agents SDK](https://openai.github.io/openai-agents-js), [`zod`](https://zod.dev) and TypeScript for you.

## Running your code

### 01-basic

The following command will execute your `index.ts` file:

```bash
npm run start:01
```

### 02-voice

The following command will start up the development server for your Next.js app:

```bash
npm run start:02
```

## Resources

- [Agents SDK Quickstart](https://openai.github.io/openai-agents-js/guides/quickstart)
- [Agents SDK Voice Quickstart](https://openai.github.io/openai-agents-js/guides/voice-agents/quickstart/)
- [Agents SDK Examples](https://github.com/openai/openai-agents-js-internal/tree/main/examples)
- [Details about Voice Agent Features](https://openai.github.io/openai-gents-js/guides/voice-agents/build/)
- [Voice Agents Guide on the OpenAI Docs](https://platform.openai.com/docs/guides/voice-agents)
