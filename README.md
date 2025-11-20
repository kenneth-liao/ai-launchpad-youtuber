# AI Launchpad Youtuber

The AI Launchpad Youtuber turns your Claude Code into a complete YouTube content strategist. Your content strategist will help you with:

1. Analyzing your YouTube channel performance
2. Crafting a YouTube channel strategy
3. Researching video topics
    - Existing content analysis
    - Competitor analysis
    - Content gap analysis
    - Trend analysis
4. Generating video titles
5. Creating video thumbnails
6. Crafting video hooks
7. Planning your next video

While following strict design requirements and best practices for generating high-converting YouTube content.

## Overview

The AI Launchpad Youtuber is completely powered by Claude Code plugins.

This project is both a starting point and demonstration of how to use the YT Content Strategist plugin from the [AI Launchpad Marketplace](https://github.com/kenneth-liao/ai-launchpad-marketplace).

To learn more about Claude Clode plugins, see the official [documentation](https://code.claude.com/docs/en/plugins)

## Requirements (Must Complete First)

If you don't have Claude Code installed yet, see the official [guide](https://code.claude.com/docs/en/setup#native-install-recommended).

You will also need the following dependencies:

1. Install [uv](https://docs.astral.sh/uv/getting-started/installation/)

2. Get a [YOUTUBE_API_KEY](https://developers.google.com/youtube/v3/getting-started)

3. Get a [GEMINI_API_KEY](https://aistudio.google.com/app/api-keys)

4. Install Thumbkit as a uv tool:

```bash
uv tool install git+https://github.com/kenneth-liao/thumbkit.git
```

Verify the installation by running the command `thumbkit` in any terminal. You should see the help menu.

## Getting Started

1. Copy `.env.example` to `.env` and fill in the required variables.

2. Add the [AI Launchpad Marketplace](https://github.com/kenneth-liao/ai-launchpad-marketplace).

Start Claude Code and run the following command:

```bash
/plugin marketplace add https://gitlab.com/company/plugins.git
```

3. Install the YT Content Strategist plugin:

```bash
/plugin install yt-content-strategist@ai-launchpad-marketplace
```

Or you can do this interactively by running `/plugin`.

4. Restart Claude Code for the plugin to take effect.

You can verify the plugin interactively by running `/plugin` and checking that `yt-content-strategist` is installed. You can also explore the skills, agents, and MCP servers available with the plugin.

You can also run `/context` to see the new MCP tools available through the plugin and their context window usage.

## Usage

You can now start using the content strategist. Here are some example prompts to try:

1. Research video topics

Research a video topic about turning Claude Code into a personal assistant.

2. Generate a video title

Generate a title for a video about turning Claude Code into a personal assistant.

3. Create a video thumbnail

Create a thumbnail for my next video titled "The AI Workflow Nobody Is Talking About"

4. Craft a video hook

Craft a hook for a video about turning Claude Code into a personal assistant.

5. Generate a complete video plan (includes research, title, thumbnail, hook, and outline)

Plan a video about turning Claude Code into my personal assistant.
