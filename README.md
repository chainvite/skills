# Chainvite

Create Chainvite events from a conversation with Claude: describe the event, finish it in the composer, and save or publish it only after you approve. Claude can also read what is on, your invites and your inbox.

## Use it

Tell Claude about the event you want ("dinner for 12 at my place next Friday at 8"). Claude drafts it and shows a card asking for anything still missing. It saves the draft, and publishes it, only after you approve each step.

Sign in with your Chainvite account when you connect the Chainvite connector.

## Install

In Claude, add the Chainvite plugin from the directory. In another agent, install the skills with:

```bash
npx skills add Chainvite/skills
```

and add the Chainvite connector, `https://mcp.chainvite.com/mcp`, in that agent's connector or MCP settings.

## Data

The plugin sends what you ask and the changes you approve to your Chainvite account through https://mcp.chainvite.com, and nowhere else. The plugin stores nothing itself. It cannot reach a wallet, a payment or an escrow.
