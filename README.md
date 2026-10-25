# 👋 Hi, I'm atg06

**I'm learning cybersecurity, and building as I learn.**

I started out of curiosity, and I'm trying to get a little better every day.
I see open source as both a school and a meeting place: I learn by diving into
real projects, and by contributing I get to meet people walking the same path.

---

## 🔭 What I'm up to

- 🛡️ **Open source contributions:** Small but solid contributions to
  security-focused projects: tested fixes, missing tests, clearer documentation
- 🧩 **Claude skills:** Useful skills that make repetitive work easier
- 🔧 **Small tools and extensions:** Things that don't exist yet and will
  genuinely make someone's work easier

## 🚀 Projects

### My repos

- [config-audit-tools](https://github.com/atg06/config-audit-tools): small read-only tools that check settings
- [security-skills](https://github.com/atg06/security-skills): Claude skills for everyday defensive work
- security-oss-team (private for now): my AI-assisted team for defensive security open source.
  I talk to a manager agent; specialists research, build, test and review, and I check everything before it ships.

**Tools** (`config-audit-tools/tools/`)

| Tool | What it does |
|---|---|
| `push-email-guard` | Blocks pushes that would leak a personal email in commit history |
| `git-config-audit` | Flags risky git settings (TLS off, plaintext credentials, unsafe protocols) |
| `ssh-config-audit` | Flags risky SSH client settings (host-key checks off, agent forwarding, weak algorithms) |
| `npmrc-audit` | Flags risky `.npmrc` settings without printing secret values |
| `mail-auth-audit` | Checks SPF, DKIM and DMARC records for a domain |
| `file-disguise-audit` | Finds files pretending to be something else (fake extensions, double extensions) |

**Skills** (`security-skills/skills/`)

| Skill | What it does |
|---|---|
| `security-txt` | Writes or audits an RFC 9116 `security.txt` |
| `scorecard-remediation` | Turns OpenSSF Scorecard results into a fix plan |
| `actions-oidc-migration` | Moves GitHub Actions from stored cloud keys to OIDC |
| `leaked-secret-response` | Walks through what to do when a secret was leaked |
| `suspicious-file-triage` | Safe, static-only look at a suspicious file |
| `phishing-email-triage` | Safe triage of a reported phishing email |

**Current focus:** social engineering defense (phishing, email authentication)
and defensive reverse engineering (suspicious-file triage).

**Open-source contributions in progress:**
[Lynis #1803](https://github.com/CISOfy/lynis/pull/1803),
[Checkov #7768](https://github.com/bridgecrewio/checkov/pull/7768)

---

## 🌱 What I want to learn

- How security vulnerabilities come to exist and how they get fixed
- Reading and understanding the code of real projects
- Thinking from the defensive side: knowing what needs protecting first
- How to write a good security report and a good contribution
- How to communicate respectfully and effectively with maintainers

## 🧭 My promises to myself

- **Quality over quantity.** I aim for 2 contributions every day, but quality
  comes first: a contribution is only worth sending if it's good
- **Stay on the defensive side.** I don't publish vulnerabilities I find; I report
  them privately, following each project's security policy
- **Respect maintainers' time.** Considered, tested contributions, not hasty noise
- **Share what I learn.** When I figure something out, I write it down so it helps others
- **Build without profit in mind.** My goal is to contribute and grow

## 🤝 Ways we could work together

- Contribute to the same project
- Exchange ideas about security or open source
- Give or get feedback on a skill or tool I've built
- Guide newcomers, and listen to those who guide me

## 💬 Let's talk

If you'd like to talk about security, open source, or building something
together, start a conversation in this repo's **Discussions** tab. I'd be
happy to chat 🙌

---

<!-- Enable after GitHub Sponsors approval:
💖 **Support:** [GitHub Sponsors](https://github.com/sponsors/atg06) helps me keep maintaining these tools.
-->

⭐ If you found something useful, a star motivates me.
