### Hi, I'm Maxfield

I run a homelab that got out of hand. It started as a Plex server. It's now a
9-node Kubernetes cluster on Talos Linux, managed with ArgoCD, running 38-ish
services. I use it to learn the patterns real infrastructure teams use (GitOps,
IaC, observability) by operating them instead of reading about them. By day I own
a multi-region enterprise Azure platform.

**How I work:** AI-assisted engineering. I design the architecture, set the
standards, and direct the implementation with LLM agents. It isn't vibe coding.
I reject a good chunk of what the models hand back and iterate until it meets the
bar. The judgment is mine; the typing is just faster. If the AI disappeared
tomorrow the work would get slower, not stop. I've shipped features to OPNsense
in a language I didn't know going in, so I know what "slower" actually looks like.

**What I build and run:**
- [dnsweaver](https://github.com/maxfield-allison/dnsweaver): a Go tool that
  keeps DNS records in sync with your infrastructure across Technitium, Pi-hole,
  AdGuard, and Cloudflare. Multi-provider, split-horizon, self-hosted. Full CI/CD
  and semver. People actually run it.
- A Talos/Kubernetes homelab under GitOps: 5-node control plane, GPU workloads
  scheduled with NVIDIA MPS, OpenTofu and Ansible for everything below the cluster.
- Migrated the whole thing from Docker Swarm to Kubernetes without losing service.
- [This site](https://github.com/maxfield-allison/personal-site):
  [maxfieldallison.com](https://maxfieldallison.com), self-hosted on the cluster
  with a Cloudflare Pages failover mirror.

Reach me: [maxfieldallison.com](https://maxfieldallison.com) ·
[LinkedIn](https://www.linkedin.com/in/maxfield-allison/)
