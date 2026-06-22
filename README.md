# colab-templates

Ready-to-run Google Colab notebooks for compute-flexible jobs.

## Templates

| Notebook | Purpose | Time-to-first-run |
|---|---|---|
| [`colab_desktop_bootstrap.ipynb`](colab_desktop_bootstrap.ipynb) | Boots a full XFCE desktop + Chrome on a Colab VM, accessible via Chrome Remote Desktop. Generic, project-agnostic. | ~5 min |
| [`ds_signup_runner.ipynb`](ds_signup_runner.ipynb) | Runs `free-llms-signup`'s parallel DeepSeek signup batch on Colab via Xvfb + Brave. | ~6 min |

## Open in Colab

- **Desktop bootstrap (generic):** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GregSharma/colab-templates/blob/main/colab_desktop_bootstrap.ipynb)
- **Signup runner (specific):** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GregSharma/colab-templates/blob/main/ds_signup_runner.ipynb)

## Why

Colab is the cheapest way to get a fresh VM with ~50GB RAM and decent CPU. Most non-GPU automation work fits on it — the only friction is provisioning a usable headed environment. These templates take that from "afternoon project" to "two cells."
