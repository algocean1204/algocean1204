# Icons

프로필 배지에 쓰는 아이콘입니다. 공식 아이콘(Simple Icons)이 없는 항목만 직접 그렸습니다. 누구나 가져다 써도 됩니다.

| 아이콘 | 파일 | 쓰는 곳 |
|:--:|:--|:--|
| <img src="multi-agent-orchestration.svg" width="24" style="background:#1C3C3C"> | `multi-agent-orchestration.svg` | Multi-Agent Orchestration |
| <img src="ax-automation.svg" width="24"> | `ax-automation.svg` | AX Automation |
| <img src="codex.svg" width="24"> | `codex.svg` | Codex |
| <img src="agent-plugins.svg" width="24"> | `agent-plugins.svg` | Agent Plugins |
| <img src="hermes-agent.svg" width="24"> | `hermes-agent.svg` | Hermes Agent |

모두 24×24, 흰색 단색 SVG입니다. 밝은 배경에서는 흰색이라 잘 보이지 않습니다.

## shields.io 배지에 넣기

shields.io의 `logo` 값에는 파일 주소를 넣을 수 없어서, SVG를 base64로 바꿔 넣습니다.

```bash
B64=$(base64 < ax-automation.svg | tr -d '\n')
echo "https://img.shields.io/badge/AX_Automation-0B6E4F?style=for-the-badge&logo=data:image/svg%2bxml;base64,$B64"
```
