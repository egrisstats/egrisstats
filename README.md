<p align="center">
  <a href="https://egrisstats.org/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/egriss-10-years-white.png">
      <img src="assets/egriss-10-years-blue.png" alt="EGRISS, Expert Group on Refugee, IDP and Statelessness Statistics, 10 years" width="720">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://egrisstats.org/"><img alt="Website" src="https://img.shields.io/badge/website-egrisstats.org-1d2d5a?style=flat-square"></a>
  <a href="https://egrisstats.org/"><img alt="Recommendations" src="https://img.shields.io/badge/recommendations-IRRS%20%C2%B7%20IRIS%20%C2%B7%20IROSS-3a78b9?style=flat-square"></a>
  <a href="#repositories"><img alt="Repositories" src="https://img.shields.io/badge/repositories-10-55c3c9?style=flat-square"></a>
</p>

The **Expert Group on Refugee, IDP and Statelessness Statistics (EGRISS)** brings together national statistical offices, international organisations and other experts to improve official statistics on refugees, internally displaced persons and stateless persons. It developed the three international recommendations endorsed by the UN Statistical Commission: the **IRRS** (refugees), **IRIS** (internally displaced persons) and **IROSS** (statelessness).

This GitHub account holds the code and data tools of the **EGRISS Secretariat**, hosted by UNHCR in Copenhagen.

## Repositories

### GAIN Survey (Global Annual Inclusion survey)

| Repository | What it does | Language |
|---|---|---|
| [gain-evidence-pipeline](https://github.com/egrisstats/gain-evidence-pipeline) | Finds possible new GAIN examples (statistical activities that include refugees, IDPs and stateless persons) and prepares the follow-up with the institutions concerned | R |
| [GAIN_post-collection](https://github.com/egrisstats/GAIN_post-collection) | Finds a public source link and report cover for each GAIN example (2021 to 2025) | Python |
| [EGRISS_GAIN_Clean_Scripts](https://github.com/egrisstats/EGRISS_GAIN_Clean_Scripts) | Cleans and aligns the GAIN survey data | R |
| [EGRISS_GAIN_AR_Split_Script](https://github.com/egrisstats/EGRISS_GAIN_AR_Split_Script) | Produces the GAIN annual report analysis, one script per section | R |
| [EGRISS_GAIN_PowerBI](https://github.com/egrisstats/EGRISS_GAIN_PowerBI) | Prepares GAIN data for the Power BI dashboard | R |
| [GAIN-Dashboard](https://github.com/egrisstats/GAIN-Dashboard) | GAIN dashboard | R |
| [gain-data-chatbot](https://github.com/egrisstats/gain-data-chatbot) | Browser chatbot that answers questions from the GAIN analysis-ready datasets | Python |
| [gain_sdg_workstream](https://github.com/egrisstats/gain_sdg_workstream) | Living map of comparable SDG indicators for refugees, IDPs and stateless people drawn from GAIN examples ([open the map](https://egrisstats.github.io/gain_sdg_workstream/)) | HTML |

### Methodological work

| Repository | What it does | Language |
|---|---|---|
| [idq-map](https://github.com/egrisstats/idq-map) | Maps causing events to the EGRISS identification questions, for the methodological paper on identification questions supported by a UNHCR Data Innovation Grant ([open the site](https://egrisstats.github.io/idq-map/)) | R, HTML |

### Communication

| Repository | What it does | Language |
|---|---|---|
| [EGRISS_Reach_Media](https://github.com/egrisstats/EGRISS_Reach_Media) | Social media analysis of EGRISS outreach | R |

## About these copies

The repositories above were first built under [@mitrovif](https://github.com/mitrovif) and copied here on 6 October 2026, with their full commit history, so that the Secretariat keeps its own record of the work.

- **Keeping the copies in sync.** A workflow in this repository ([sync-from-originals.yml](.github/workflows/sync-from-originals.yml)) copies new commits, branches and tags from the originals every day. The list of repositories is in [sync/repos.txt](sync/repos.txt). It needs a secret called `SYNC_TOKEN`: an access token of this account that can write to its repositories. It never overwrites changes made here; a repository that has its own commits is skipped and reported.
- **Pull requests.** Pull requests cannot be moved between accounts. Their changes are in the commit history, and a list of them with links to the originals is in [pull-request-history](pull-request-history).
- **Taking over.** When the work moves fully to this account, delete the line for that repository in `sync/repos.txt` (or the whole workflow) and work here directly.

## Contact

EGRISS Secretariat, [egrisstats.org](https://egrisstats.org/)
