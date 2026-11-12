BRD to PRD:
Turn one Business Requirements Document (BRD) into one Product Requirements Document (PRD) or several PRDs organized by feature, release phase, or both. The skill interviews you about the decisions the BRD leaves open before it drafts.
Start here
1. Upload your BRD to a new AI chat, or paste the BRD if uploads are unavailable.
2. Copy [BRD_to_PRD_Prompt.txt](./BRD_to_PRD_Prompt.txt) into the chat.
3. Replace the example request at the end with your preferred scope and send it.
If your AI tool supports skills, use the standalone [SKILL.md](./SKILL.md) with its supported import method. The file includes the full workflow and the PRD template. If installation is unavailable, the copy-and-paste prompt works without it.
Example requests
!draft-prd Turn the uploaded BRD into one consolidated PRD.

!draft-prd Create one PRD per release phase. Start with Phase 1 only.

!draft-prd Create one PRD per feature in Phase 2. Ask me about any dependencies on Phase 1.

The ! prefix is part of the prompt text. It does not need to be registered as a command.
What you get
- A focused interview about scope, edge cases, dependencies, and acceptance criteria.
- A coverage map for multiple PRDs so you can see which features and phases each document covers.
- One or more drafts in the eight-section Standard PRD Structure, with requirements and acceptance criteria linked to the BRD or decisions you confirm.
- A clear record of open questions, assumptions, and decisions for later phases.
