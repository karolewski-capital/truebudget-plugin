# TrueBudget for Claude

TrueBudget is double-entry bookkeeping for households, contractors and single-member LLCs. This plugin connects Claude to your TrueBudget books so you can ask about them and keep them up to date in plain words: "What did I spend on restaurants last month?", "Categorize the Shell charge as fuel", or "Reconcile my checking account against the October statement."

Claude reads balances, net worth, the balance sheet, profit and loss, budgets and transactions; records and categorizes transactions, splits and transfers; links refunds; manages categories, rules and receipts; and reconciles accounts against uploaded statements.

TrueBudget records money you already manage. No money moves through it: it never pays, transfers or charges anything, and it cannot change your connected financial accounts.

## What's inside

- A remote MCP server at `https://truebudget.ninja/api/mcp`, signed in with OAuth.
- The `truebudget-bookkeeping` skill, which tells Claude how TrueBudget signs amounts, which date "today" is, and when to preview a change before writing it.

## Setup

You need a TrueBudget account with books set up.

1. Install the plugin from the Claude directory, or in Claude Code:

   ```text
   /plugin install truebudget --marketplace karolewski-capital/truebudget-plugin
   ```

   Then choose Connect.
2. Sign in at truebudget.ninja.
3. Approve access. Untick "Create, update, transfer, and delete financial records" to connect read-only.

The assistant works on the books you have selected in TrueBudget.

## Try it

- What's my net worth, and how did it change this month?
- What did I spend on groceries last month?
- Show my uncategorized transactions from this week.

## Links

- Guide: https://truebudget.ninja/assistant
- Privacy: https://truebudget.ninja/privacy
- Support: https://truebudget.ninja/support
- Terms: https://truebudget.ninja/terms

## License

MIT. See `LICENSE`.
