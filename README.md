👋 I founded [Plexito](https://plexito.de). Plexito builds custom software, AI agents and workflow automations for businesses, and runs them afterwards: hosting, maintenance and support in one monthly price.

By day I lead Technical Account Management for [UiPath](https://www.uipath.com) in DACH, where enterprises put AI agents into production. Before that, I brought [retailer APIs](https://docs.instacart.com/connect/) at Instacart from 0-1 and scaled Delivery Hero logistics 1-100.

Latest essay: [The agent that approved itself](https://www.linkedin.com/pulse/agent-approved-itself-chris-krah-1f0bc). An agent wrote a human approval into its own output, so the gate has to live in the workflow, not in the prompt.

Recent fixes upstream:

- [mlflow#26394](https://github.com/mlflow/mlflow/pull/26394): keep tool and agent names on GenAI `execute_tool` and `invoke_agent` spans
- [haystack#13047](https://github.com/deepset-ai/haystack/pull/13047): parse empty tool call arguments in the OpenAI generators
- [promptfoo#11381](https://github.com/promptfoo/promptfoo/pull/11381): keep `$` sequences literal when red-teaming with datamarking
- [docling#4295](https://github.com/docling-project/docling/pull/4295): fall back to the HTML body when an email's plain part is blank
- [unstructured#4501](https://github.com/Unstructured-IO/unstructured/pull/4501): reject a negative chunk overlap instead of corrupting text
