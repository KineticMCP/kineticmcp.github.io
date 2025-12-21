---
layout: default
title: Documentation - Salesforce MCP Server
---

<div class="pt-32 pb-20 px-6 bg-gray-50 dark:bg-neutral-900 min-h-screen">
    <div class="max-w-4xl mx-auto">
        <div class="mb-12">
             <a href="/" class="text-brand-blue font-bold text-sm mb-4 inline-block">&larr; Back to Home</a>
            <h1 class="text-5xl font-black tracking-tight mb-4">Documentation</h1>
            <p class="text-xl text-gray-500">Getting started with Salesforce MCP Server.</p>
        </div>

        <div class="bg-white dark:bg-neutral-800 p-10 rounded-[2rem] shadow-sm border border-gray-100 dark:border-white/5 prose dark:prose-invert max-w-none">
            <h2>Introduction</h2>
            <p>
                Salesforce MCP Server implements the Model Context Protocol (MCP) to allow AI agents to interact with your Salesforce instance.
                This enables capabilities like reading records, searching SOQL, and executing DML operations within a rigorous security context.
            </p>

            <h3>Quick Start</h3>
            <p>The fastest way to run the server is via Docker.</p>

            <pre><code>docker run -d \
  -e SF_USERNAME=your_username \
  -e SF_PASSWORD=your_password \
  -e SF_SECURITY_TOKEN=your_token \
  -p 8000:8000 \
  kineticmcp/server</code></pre>

            <h3>Configuration</h3>
            <p>You need a Connected App in Salesforce with the following scopes:</p>
            <ul>
                <li>api</li>
                <li>refresh_token</li>
                <li>offline_access</li>
            </ul>

            <h3>Connecting to Claude Desktop</h3>
            <p>Add the following to your <code>claude_desktop_config.json</code>:</p>
            <pre><code>{
  "mcpServers": {
    "salesforce": {
      "command": "docker",
      "args": ["run", "-i", "--rm", "kineticmcp/server"]
    }
  }
}</code></pre>

            <div class="not-prose mt-12 p-6 bg-brand-blue/5 rounded-2xl border border-brand-blue/20">
                <h4 class="font-bold text-brand-blue mb-2">Need more help?</h4>
                <p class="text-sm text-gray-600 dark:text-gray-400 mb-4">Check out our full repository for detailed setup guides and advanced configuration.</p>
                <a href="https://github.com/kineticmcp/kinetic-mcp-server" class="text-sm font-bold underline">Go to GitHub &rarr;</a>
            </div>
        </div>
    </div>
</div>
