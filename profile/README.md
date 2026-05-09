<table align="center">
  <tr>
    <td align="center" width="180">
      <img src="https://github.com/user-attachments/assets/55b9ae59-3689-4038-bcd5-b01b591382e9" alt="UC Berkeley logo" width="145"/>
    </td>
    <td align="center" width="180">
      <img src="https://github.com/user-attachments/assets/84defe28-a837-4be5-8397-43d8a98dea79" alt="TREx logo" width="125"/>
    </td>
  </tr>
</table>

<h1 align="center">TRansients EXtragalactic Research Group</h1>

<p align="center">
  <strong>Extragalactic transients, explosive astrophysics, and time-domain discovery at UC Berkeley</strong>
</p>


Welcome to the GitHub organization for the **TRansients EXtragalactic** research group at the University of California, Berkeley.

Our group studies energetic and rapidly evolving astrophysical phenomena beyond the Milky Way, including gamma-ray bursts, supernovae, luminous fast blue optical transients, tidal disruption events, and other explosive or accretion-powered transients. This GitHub organization serves as a shared home for our code, documentation, analysis tools, data-reduction workflows, and group knowledge base.

---

## About the Group

The TRansients EXtragalactic group focuses on the discovery, observation, modeling, and interpretation of extragalactic transient events. Our work spans observational astronomy, multi-wavelength follow-up, numerical and statistical modeling, data reduction, and population-level studies.

Topics of interest include, but are not limited to:

- Gamma-ray bursts, or GRBs
- Supernovae, or SNe
- Luminous fast blue optical transients, or LFBOTs
- Tidal disruption events, or TDEs
- Fast and rare extragalactic transients
- Multi-messenger and multi-wavelength transient follow-up
- Spectroscopic and photometric data analysis
- Host-galaxy studies
- Survey infrastructure, observing strategy, and transient classification

This organization is intended to support reproducible research, collaborative software development, shared analysis infrastructure, and long-term preservation of group knowledge.

---

## Organization Guide

This GitHub organization is intended to be both a research workspace and a long-term archive of group software, documentation, and project knowledge. The sections below describe how repositories should be created, organized, documented, permissioned, and maintained.

<details>
<summary><strong>Repository Types</strong></summary>

Repositories in this organization generally fall into a few broad categories.

### Knowledge Base and Documentation

These repositories contain shared group documentation, onboarding materials, observing guides, analysis notes, tutorials, and internal references.

Examples include:

- Group onboarding guides
- Telescope and instrument reduction notes
- Observing proposal templates
- Literature notes
- Coding standards
- Common troubleshooting guides
- Documentation for group infrastructure

These repositories are intended to help new and existing group members find information quickly and preserve institutional knowledge.

### Data Reduction Pipelines

These repositories contain code for reducing astronomical data from telescopes, instruments, surveys, or public archives.

Examples include:

- Imaging reduction workflows
- Spectroscopic reduction workflows
- Photometric calibration tools
- Astrometric calibration tools
- Host-galaxy subtraction utilities
- Light-curve construction tools
- Instrument-specific reduction scripts

Reduction repositories should include clear setup instructions, environment files, example commands, and notes on required inputs and outputs.

### Scientific Analysis Code

These repositories contain code used for scientific analysis, modeling, inference, visualization, and manuscript preparation.

Examples include:

- Light-curve fitting
- Spectral modeling
- Host-galaxy analysis
- Population studies
- Bayesian inference workflows
- Figure-generation scripts
- Reproducibility packages for papers

Repositories associated with publications should include enough documentation for another researcher to understand and reproduce the major results.

### Software Packages

Some repositories are maintained as reusable software packages rather than project-specific scripts.

These repositories should generally include:

- A clear README
- Installation instructions
- Dependency information
- Usage examples
- Tests, when appropriate
- Versioning or release notes
- Contribution guidelines

### Project-Specific Repositories

Some repositories are tied to a specific transient, sample, observing program, collaboration, or paper.

These may include:

- Analysis notebooks
- Data tables
- Reduction scripts
- Model outputs
- Draft figures
- Notes for collaborators
- Paper-specific reproducibility materials

Project-specific repositories should clearly state their purpose, current status, maintainer, and whether they are actively maintained.

</details>

---

## Creating a New Repository

<details open>
<summary><strong>When should I create a new repository?</strong></summary>

Create a new repository when the work is likely to be shared, maintained, reused, cited, or preserved beyond a single local analysis.

Good reasons to create a repository include:

- Starting a new science project
- Developing a reusable reduction or analysis pipeline
- Creating documentation for a group workflow
- Preparing code for a paper or public release
- Building a shared software package
- Maintaining scripts used by multiple group members
- Preserving analysis history for a specific transient, sample, or observing program

Avoid creating a new repository for very small, temporary, or purely personal scratch work unless it is expected to become useful to others.

</details>

<details>
<summary><strong>How to create a repository</strong></summary>

To create a new repository:

1. Go to the organization page.
2. Click **New repository**.
3. Choose a descriptive repository name.
4. Add a short repository description.
5. Choose **Private** by default unless the repository is intentionally public.
6. Initialize the repository with a `README.md`.
7. Add a `.gitignore` appropriate for the language or workflow.
8. Add a license only if the repository is public or intended for external reuse.
9. Add collaborators or teams with the minimum permissions needed.

Recommended default settings:

- Visibility: **Private**
- README: **Yes**
- `.gitignore`: **Yes**
- License: **Only if public or reusable**
- Branch protection: **Recommended for shared or publication-related repositories**

</details>

<details>
<summary><strong>Repository naming conventions</strong></summary>

Use names that are clear, searchable, and specific.

Recommended patterns:

```txt
project-name
transient-name-analysis
instrument-reduction
survey-name-tools
paper-shortname-reproducibility
software-package-name
group-knowledge-base
```
</details>
<details open>
<summary><strong>Managing Permissions</strong></summary>

Repository permissions should be managed carefully so that group members and collaborators have the access they need without exposing private work, unpublished results, proprietary data, or administrative settings unnecessarily.

As a general rule, use the **least-privilege principle**: give each person the lowest level of access that allows them to do their work.

### Permission levels

GitHub repositories typically support the following permission levels:

| Permission | What it allows | Recommended use |
|---|---|---|
| Read | View and clone the repository | Group members or collaborators who only need to inspect files |
| Triage | Manage issues and pull requests without changing code | Helpers managing project organization or documentation tasks |
| Write | Push branches, open pull requests, and contribute code | Active project contributors |
| Maintain | Manage repository settings without full administrative control | Repository maintainers or senior project members |
| Admin | Full control over repository settings and access | Organization admins, PIs, or designated technical leads |

Recommended defaults:

- Use **Read** for people who only need to view documentation or code.
- Use **Write** for active contributors.
- Use **Maintain** for people responsible for repository organization, issues, settings, or releases.
- Use **Admin** only when someone needs to manage access, visibility, deletion, transfer, or other sensitive settings.

Avoid giving **Admin** access by default.

### Organization-level versus repository-level access

Access can be granted at different levels:

- **Organization-level access** gives someone membership in the GitHub organization.
- **Team-level access** gives a group of people access to a set of repositories.
- **Repository-level access** gives a specific person access to one repository.

Whenever possible, use **teams** rather than adding many individuals separately. Teams make it easier to manage access when people join or leave projects.

Suggested team patterns:

```txt
group-members
postdocs
graduate-students
undergraduate-students
external-collaborators
project-name-team
paper-shortname-team
repository-maintainers
organization-admins
