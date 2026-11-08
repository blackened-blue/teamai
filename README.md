# Team AI

## Quick Start

Send this one line to your AI tool:

```text
Install the teamai skill: https://github.com/Tencent/teamai-cli/tree/main/skills/teamai , load the teamai skill
```

Once TeamAI is set up, just talk to the /teamai skill in your AI tool:

Join a team

```text
/teamai Help me join my team's TeamAI, repo URL is https://github.com/blackened-blue/teamai.git
```

Share with the team

Skills, rules, MCP servers, and other agent resources can all be shared:

```text
/teamai Share my <your-skill> skill with the team
```

Open the dashboard

```text
/teamai Open the TeamAI dashboard
```

## Product Overview

Three layers of capability, built on Git:

- Team Execution — make every agent work the team's way: skills, rules, culture, agents, hooks, MCP, workflows, env, models.
- Team Context (beta) — make every agent understand the team: learnings, codebase graph, teamwiki.
- Team Improvement (beta) — make every execution improve the team: usage, sessions, scorers, benchmarks.

<table>
  <thead>
    <tr>
      <th rowspan="2">Agent</th>
      <th colspan="9">Team Execution</th>
      <th rowspan="2">Team Context (beta)</th>
      <th colspan="4">Team Improvement (beta)</th>
    </tr>
    <tr>
      <th>skills</th><th>rules</th><th>culture</th><th>agents</th><th>hooks</th><th>mcp</th><th>workflows</th><th>env</th><th>models</th>
      <th>usage</th><th>sessions</th><th>scorers</th><th>benchmarks</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Claude Code</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td></tr>
    <tr><td>Codex</td><td align="center">✓</td><td align="center">✓¹</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td></tr>
    <tr><td>Qoder</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">—</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">—</td></tr>
    <tr><td>Kiro</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">—</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓³</td><td align="center">—</td></tr>
  </tbody>
</table>


✓¹ Rules stay on. They are not limited by path.

✓² Env reaches it only through teamai env exec.

✓³ Only workflows run with the skill driver are scored.

