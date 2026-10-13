---
name: write-interactive-tutorial-script
description: Write or rewrite original Simplified Chinese tutorial and explainer voiceover scripts with conversational hooks, viewer interaction, natural progress transitions, real tool-operation steps, system feedback, and restrained creator-owned tool mentions. Use for Douyin/Bilibili/short-video tutorials, software walkthroughs, AI tool explainers, multi-video lesson series, timed talking-head scripts, teleprompter copy, or when a draft feels like a manual or a mechanical “first/second/third” template.
---

# Write Interactive Tutorial Script

Create a script that sounds like a knowledgeable creator guiding a viewer through a real result. Keep the voice original. If the user references a living creator, extract only high-level mechanisms such as pacing, hook type, interaction, and transition logic; do not reproduce signature phrases or imitate the creator's distinctive voice.

## Gather the content contract

Establish these inputs from the request or available files:

- Topic and concrete viewer outcome.
- Audience knowledge level and main hesitation.
- Platform, target duration, and whether this is one video or a series episode.
- Exact user operations, button labels, inputs, and visible results.
- What the system does automatically after each operation.
- Terms requiring a plain-language explanation.
- Cost, access, factual, and product limitations.
- Relationship to the tool: third-party review, neutral demonstration, or creator-owned tool.

Inspect source material before writing when product behavior matters. Do not turn planned features, labels, or configuration fields into claims of working behavior.

If duration is unspecified, use 60–90 seconds for a focused short video. For a long workflow, propose one overview episode plus focused hands-on episodes rather than compressing every operation into one script.

## Choose the episode job

Select one primary job for each script:

- **Overview**: show the destination, map the workflow, and create reasons to watch the focused episodes.
- **Hands-on stage**: let the viewer complete one meaningful stage on screen.
- **Comparison or review**: establish criteria, show evidence, and state who each option suits.
- **Creator-built tool story**: begin with the user problem or demonstrated result, disclose ownership plainly, and explain why the tool was built.

Do not mix all four jobs into a short script.

## Build the attention arc

### 1. Open with consequence

Use the first two sentences to surface one of:

- A result the viewer wants to reproduce.
- A common misconception that blocks success.
- A surprising capability followed by proof.
- A costly mistake the workflow avoids.

Do not start with a greeting, biography, agenda list, or abstract definition unless the audience needs essential context.

### 2. Make a concrete promise

Tell the viewer what they will finish or understand. Keep the promise observable: a generated document, a 20-second preview, a configured voice, or a downloadable video.

### 3. Cross a natural threshold

Use an interactive bridge before the first action. Vary it according to context: invite the viewer to look, ask them to notice a state, warn them not to rush, or confirm what is already prepared. Avoid a generic recurring line such as “好，我们进入主题”.

## Write operation beats

For every major stage, include five functions in natural prose:

1. **Purpose** — why this action happens now.
2. **User action** — what to click, enter, upload, select, or review.
3. **System response** — what the tool calculates, generates, validates, or queues.
4. **Visible checkpoint** — what proves the stage is complete.
5. **Forward pull** — why the next stage now makes sense.

Do not expose these five labels in the spoken copy. Merge them into short conversational sentences.

Prefer result-bearing transitions:

- “现在文案和时长已经锁定了。先别急着生成人物，我们还要把画面基调定下来。”
- “看到分镜时间轴出现，就说明轻量分析已经完成。接下来先看小样，不用急着跑完整渲染。”

Avoid empty transitions:

- “第一步完成了，下面进入第二步。”
- “好，接下来我们继续操作。”

Use numbered steps only when the number helps the viewer remember or locate a UI step. Even then, vary the spoken entry and connect it to the previous result.

## Add interaction without chatter

Distribute interaction by function, not by a fixed phrase bank:

- **Invitation**: direct attention to a button, preview, comparison, or result.
- **Question**: surface the viewer's likely doubt before answering it.
- **Confirmation**: name the state that proves an operation worked.
- **Caution**: pause before a costly, irreversible, or commonly misunderstood action.
- **Anticipation**: preview the payoff of the next stage.
- **Participation**: ask the viewer to choose, predict, compare, or try with their own material.

Use one interaction beat around each major stage. Do not stack multiple rhetorical questions, repeat “大家”, or attach filler particles to every sentence.

For scripts longer than 60 seconds, read [references/interaction-patterns.md](references/interaction-patterns.md) for phrase functions, pacing variations, and the research basis.

## Mention a creator-owned tool transparently

Never disguise a creator-owned tool as an independent recommendation.

Follow this order:

1. Teach a useful method or show a real result.
2. State ownership once in plain language: “为了把这套流程跑通，我把它做成了一个工作台。”
3. Continue with a real operation instead of promotional adjectives.
4. After value is demonstrated, offer a low-pressure next step: viewers can use their own material to repeat the workflow.
5. State external costs, limitations, and manual review requirements where relevant.

Mention the tool at most twice in a short video. Avoid “最强”, “一键全自动”, “完全免费”, fake scarcity, or unverifiable outcome claims.

## Pace for speech

- Keep sentences short enough to read once without losing the subject.
- Put one main idea in each sentence.
- Insert a spoken reset or checkpoint every 15–25 seconds.
- Explain an unfamiliar term in one plain sentence at first mention.
- Let screen operations carry detail; the voiceover should explain intention, choice, and result.
- Use occasional conversational words such as “来看”, “注意”, “这时候”, or “先别急”, but vary them and remove any that do not change attention.

## Produce the requested format

When the user requests a full production package, return:

1. Three non-clickbait title options.
2. A short beat map stating hook, promise, operations, and payoff.
3. A time-coded script with independent visual cues.
4. A pure voiceover version containing only spoken copy.
5. A factual and product-claim checklist.

When the user asks only for copy, return the polished script without forcing the full package.

For a series, make each episode independently useful. Start with a one-sentence recap at most, deliver one stage-specific result, and end with a concrete reason to watch the next episode rather than a generic “下期见”.

## Quality gate

Before delivering, verify:

- The hook reaches the topic within two sentences.
- The viewer knows what they will obtain.
- Every operation states both the user action and system response.
- Each major transition carries a completed result or unresolved question.
- Interaction language is varied and tied to visible content.
- The script does not read like a numbered manual.
- A creator-owned tool is disclosed, not covertly promoted.
- Product behavior, button names, prices, and limitations are factual.
- External AI, TTS, avatar, or rendering costs are not hidden.
- The ending gives a useful action, comparison question, or next-episode payoff.
- The wording is original and does not reproduce a living creator's signature phrasing.
