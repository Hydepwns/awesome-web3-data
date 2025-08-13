# Contributing to awesome-web3-data

Thank you for considering contributing to awesome-web3-data! We welcome contributions from the community to help improve and expand this curated list of high-quality Web3 data resources, tools, and APIs.

## How to Contribute

1. **Fork the Repository**: Start by forking the repository to your GitHub account.

2. **Clone the Repository**: Clone the forked repository to your local machine.

    ```bash
    git clone https://github.com/your-username/awesome-web3-data.git
    ```

3. **Create a New Branch**: Create a new branch for your contribution.

    ```bash
    git checkout -b my-new-branch
    ```

4. **Make Your Changes**: Add your changes to the repository. This could include adding new resources, fixing typos, or improving existing content.

5. **Commit Your Changes**: Commit your changes with a descriptive commit message.

    ```bash
    git add .
    git commit -m "Add: <Name of resource> to <Section>"
    ```

6. **Push to Your Fork**: Push your changes to your forked repository.

    ```bash
    git push origin my-new-branch
    ```

7. **Submit a Pull Request**: Open a pull request to the main repository. Provide a clear description of your changes and why they should be merged.

## Submission Checklist

Please ensure each submission meets the following:

- The entry includes: **Name**, **URL**, and a **neutral one-line description**.
- Place it in the correct section. If unsure, suggest a new section in your PR.
- Sort alphabetically within the section.
- Use consistent terminology: standardize on **ETH** (not “Ethereum”) in descriptions, unless part of a proper noun.
- Avoid marketing language; prefer neutral, factual phrasing.
- Do not add duplicate entries across sections.
- Links are reachable (no obvious 404s). Our CI runs a link checker on PRs.
- If open source, consider linking the project’s GitHub repo directly.

## Style Guide

- **Capitalization**: Use product names as styled by the project (e.g., Viem, Wagmi, DeFiLlama). Use "ETH" elsewhere.
- **Descriptions**: One sentence, concise, neutral. End with a period.
- **Chains**: Mention chain context when relevant (e.g., "Solana RPC", "Cosmos explorer").
- **Formatting**: Markdown list item per resource: `- [Name](https://url/) - Description.`
- **Badges**: Do not add generic badges to entries.

## Scope and Quality Bar

- Focus is on data: analytics, indexers, datasets, ETL, infra, RPC, oracles, NFT data, SDKs.
- Exclude trading bots, pure wallets without analytics, unrelated marketing sites.
- Prefer widely used or well-documented resources.

## Automated Checks

On each pull request, CI runs:

- `awesome-lint` for awesome-list best practices
- `markdownlint` for Markdown style
- A link checker for dead links

Address any CI findings in your PR.

## Code of Conduct

By participating in this project, you agree to abide by the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/).

## Getting Help

If you have any questions or need assistance, feel free to open an issue on the GitHub repository or reach out to the maintainers.

Thank you for your contributions!

- axol.io <3
