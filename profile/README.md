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

<h1 align="center">TRansient EXtragalactic Research Group</h1>

<p align="center">
  <strong>Extragalactic transients, explosive astrophysics, and time-domain discovery at UC Berkeley</strong>
</p>


Welcome to the GitHub organization for the **TRansient EXtragalactic** research group at the University of California, Berkeley.

Our group studies energetic and rapidly evolving astrophysical phenomena beyond the Milky Way, including gamma-ray bursts, supernovae, luminous fast blue optical transients, tidal disruption events, and other explosive or accretion-powered transients. This GitHub organization serves as a shared home for our code, documentation, analysis tools, data-reduction workflows, and group knowledge base.

---

## About the Group

The TRansient EXtragalactic group focuses on the discovery, observation, modeling, and interpretation of extragalactic transient events. Our work spans observational astronomy, multi-wavelength follow-up, numerical and statistical modeling, data reduction, and population-level studies.

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

## What This Organization Contains

Repositories in this organization generally fall into several categories.

### 1. Knowledge Base and Documentation

These repositories contain shared group documentation, onboarding materials, observing guides, analysis notes, tutorials, and internal references.

Examples may include:

- Group onboarding guides
- Telescope and instrument reduction notes
- Observing proposal templates
- Literature notes
- Analysis conventions
- Coding standards
- Common troubleshooting guides
- Documentation for group infrastructure

These repositories are intended to help new and existing group members find information quickly and preserve institutional knowledge.

### 2. Data Reduction Pipelines

These repositories contain code for reducing astronomical data from telescopes, instruments, surveys, or public archives.

Examples may include:

- Imaging reduction workflows
- Spectroscopic reduction workflows
- Photometric calibration tools
- Astrometric calibration tools
- Host-galaxy subtraction utilities
- Light-curve construction tools
- Instrument-specific reduction scripts

Where possible, reduction repositories should include clear instructions, environment files, example commands, and notes on required inputs and outputs.

### 3. Scientific Analysis Code

These repositories contain code used for scientific analysis, modeling, inference, visualization, and manuscript preparation.

Examples may include:

- Light-curve fitting
- Spectral modeling
- Host-galaxy analysis
- Population studies
- Bayesian inference workflows
- Figure-generation scripts
- Reproducibility packages for papers

Repositories associated with publications should aim to include enough documentation for another researcher to understand and reproduce the major results.

### 4. Software Packages

Some repositories may be maintained as reusable software packages rather than project-specific scripts.

These repositories should generally include:

- A clear README
- Installation instructions
- Dependencies
- Usage examples
- Tests, when appropriate
- Versioning or release notes
- Contribution guidelines

### 5. Project-Specific Repositories

Some repositories are tied to a specific transient, sample, observing program, or paper.

These may include:

- Analysis notebooks
- Data tables
- Reduction scripts
- Model outputs
- Draft figures
- Notes for collaborators
- Paper-specific reproducibility materials

Project-specific repositories should clearly state their purpose, current status, and whether they are actively maintained.

---

## Public and Private Repositories

This organization contains both **public** and **private** repositories.

### Public Repositories

Public repositories are visible outside the group and may be used for:

- Open-source software
- Published analysis code
- Reproducibility packages
- Public documentation
- Community-facing tools

Before making a repository public, please make sure that it does not contain private data, proprietary observations, credentials, unpublished results that should remain confidential, or collaborator-restricted materials.

### Private Repositories

Private repositories are used for internal group work and may contain:

- Ongoing analyses
- Internal documentation
- Unpublished results
- Proprietary or embargoed data products
- Draft figures or manuscript materials
- Collaboration-sensitive notes
- Observing plans and internal logistics

Private repositories should still be organized, documented, and maintained carefully. Private does not mean temporary or undocumented.

### Data and Access Restrictions

Do not commit sensitive or restricted material unless the repository is specifically intended for that purpose and access has been reviewed.

In general, avoid committing:

- Raw proprietary data when not needed
- Authentication tokens
- Passwords
- API keys
- Personal credentials
- Large generated files
- Temporary analysis outputs
- Files that should instead be stored in an archive, cloud drive, or institutional storage system

Use `.gitignore` files where appropriate.

---

## Repository Guidelines

Each repository should include a README that explains:

- What the repository is for
- Who maintains it
- Whether it is active, archived, experimental, or publication-related
- How to install or set up the code
- How to run the main workflow
- What data are required
- Where outputs are written
- Any important caveats
- How to cite the repository or associated paper, if applicable

For code repositories, we recommend including:

- `README.md`
- `LICENSE`, if public
- `environment.yml`, `requirements.txt`, or `pyproject.toml`
- `.gitignore`
- Example scripts or notebooks
- Tests, if the code is intended to be reusable
- Documentation for major functions or workflows

For project repositories, we recommend including a short status section, such as:

```md
## Status

This repository is:
- Active / archived / under development
- Public / private
- Associated with: paper, project, transient, observing program, or internal workflow
- Maintainer: Name or GitHub handle
