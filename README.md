BRD to PRD:
Turn one Business Requirements Document (BRD) into one Product Requirements Document (PRD) or several PRDs organized by feature, release phase, or both. The skill interviews you about the decisions the BRD leaves open before it drafts.
Option 1: Install the skill
1. Open [SKILL.md](./SKILL.md) on GitHub. Click the download arrow in the file toolbar, between the copy and pencil icons. Keep the filename SKILL.md.
   - If the arrow is unavailable, click Raw, then use Save As (Ctrl+S on Windows or Cmd+S on Mac). Save the file as SKILL.md. If Windows offers a file type, choose All Files so it doesn't add .txt.
2. In your AI platform, open its custom skills area. If it accepts a standalone Markdown skill, import SKILL.md and enable BRD to PRD. If your platform requires a different package format or does not support skill installation, use Option 2 below.
3. Start a new chat and upload your BRD. If your platform has a skill picker, select BRD to PRD there.
4. Send !draft-prd followed by what you want drafted. Answer the skill's follow-up questions to clarify scope and gaps before it writes the PRD.
Option 2: Copy and paste the prompt
1. Open [BRD_to_PRD_Prompt.txt](./BRD_to_PRD_Prompt.txt).
2. Upload your BRD in a new AI chat, or paste the BRD if uploads are unavailable.
3. Copy everything below the divider in the prompt file into your message. Replace the example request at the end with your preferred scope, then send it.
4. Answer the follow-up questions. The prompt uses the same workflow and PRD format without installing a skill.
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
