# Technical Roadmap for the Digital Public Goods Alliance

Embracing our values of openness and transparency, we are hereby documenting our [product roadmap](https://app.zenhub.com/workspaces/digital-public-goods---technical-roadmap---5f9c4ed1abaaf60010f1bf2e/roadmap) and [product backlog](https://app.zenhub.com/workspaces/digital-public-goods---technical-roadmap---5f9c4ed1abaaf60010f1bf2e/board?repos=169535457,296865900,308700920,171995289) in this repository. We are using **ZenHub** as the Agile Project Management due to its smooth integration with GitHub.

For a clear distinction between the roadmap and the backlog, please refer to [this article](https://www.romanpichler.com/blog/product-roadmap-product-backlog/):

* The **product roadmap** is a strategic product-planning tool that shows how the product is likely to grow across several major releases. It creates a continuity of purpose, facilitates stakeholder collaboration, helps acquire funding, and makes it easier to coordinate the development and launch of different products.
* The **product backlog** contains the outstanding work necessary to create a product including epics and user stories, workflow diagrams, user-interface design sketches, and mock-ups. It is a tactical tool that directs the work of the development team and that provides the basis for tracking the project progress

## 📑 Product Roadmap

Our current [product roadmap](https://app.zenhub.com/workspaces/digital-public-goods---technical-roadmap---5f9c4ed1abaaf60010f1bf2e/roadmap) covers Q4 2020 (with some spillover into Q1 2021), and will be reviewed during the 3rd week of December to update it for Q1 2021. These are our priorities for this quarter:
* [Support the Financial Inclusion Community of Practice](https://app.zenhub.com/workspaces/digital-public-goods---technical-roadmap---5f9c4ed1abaaf60010f1bf2e/issues/dpgalliance/technical-roadmap/5): The Financial Inclusion Community of Practice (CoP) is in full swing during Q4 2020. As part of their activities, the CoP is looking into a set of DPG nominees, for which we will collect a full submission and review these submissions.
* [Release the next version of the Digital Public Goods Standard](https://app.zenhub.com/workspaces/digital-public-goods---technical-roadmap---5f9c4ed1abaaf60010f1bf2e/issues/dpgalliance/technical-roadmap/4): Since the release of v1.0 of the [DPG Standard](https://digitalpublicgoods.net/standard/) we have open a period for community input, and received a number of proposed changes. We have already developed [governance guidelines](https://github.com/DPGAlliance/DPG-Standard/blob/master/governance.md), and we need to triage the proposals received and release a new version incorporating the approved changes.
* [Build an API for Digital Public Goods](https://app.zenhub.com/workspaces/digital-public-goods---technical-roadmap---5f9c4ed1abaaf60010f1bf2e/issues/dpgalliance/technical-roadmap/1): Develop and deploy a public API for anyone to query data about the existing registry of digital public goods.
* [Crowdsource the validation of DPG submission](https://app.zenhub.com/workspaces/digital-public-goods---technical-roadmap---5f9c4ed1abaaf60010f1bf2e/issues/dpgalliance/technical-roadmap/2): In order to scale up the screening of nominees as digital public goods, we will build a webapp that will enable the crowdsourcing of validating the full submissions the DPG Alliance receives.
* [Data-driven submission form](https://app.zenhub.com/workspaces/digital-public-goods---technical-roadmap---5f9c4ed1abaaf60010f1bf2e/issues/dpgalliance/technical-roadmap/3): The current [submission form](https://digitalpublicgoods.net/submission) is implemented using Google Forms, and we have observed several missing features that we would like to add. An initial prototype is already built at [this repository](https://github.com/lacabra/submission-digitalpublicgoods/).

## 🛠 Product Backlog

We are aiming for a [DEEP: **D**etailed appropriately, **E**stimated, **E**mergent, and **P**rioritised](https://www.romanpichler.com/blog/make-the-product-backlog-deep/) product [backlog](https://app.zenhub.com/workspaces/digital-public-goods---technical-roadmap---5f9c4ed1abaaf60010f1bf2e/board?repos=169535457,296865900,308700920,171995289), and we are conducting two-week sprints.

## 🤝 Contributing

We welcome community contributions to advance the work of the Digital Public Goods Alliance in alignment with the roadmap outlined above. Some highlights include:

If you have **1 hour or less** available:

- [ ] Review and [endorse](https://github.com/DPGAlliance/DPG-Standard#-endorsements) the [Digital Public Goods Standard](https://github.com/DPGAlliance/DPG-Standard)
- [ ] After reviewing the standard above, weigh in the [existing discussions](https://github.com/DPGAlliance/DPG-Standard/pulls) of proposed modifications to the standard. Browse the open pull requests, and comment specifically on those marked [Community-Discussion-Period](https://github.com/DPGAlliance/DPG-Standard/pulls?q=is%3Apr+is%3Aopen+label%3ACommunity-Discussion-Period).
- [ ] Review the current [registry of DPG nominees](https://digitalpublicgoods.net/registry/) and [submit a nomination](https://docs.google.com/forms/d/e/1FAIpQLSdGzlBiecPBlVvJXmcMKXF3zdxASY8vGnrdnNNwp7fVKb169A/viewform?usp=sf_link) for a missing project.

If you have about **1/2 day** available:

- [ ] Browse issues marked [Good First Issue](https://github.com/unicef/publicgoods-candidates/issues) in the `unicef/publicgoods-candidates` repository. These typically involve doing a little bit of research in a number of potential Digital Public Goods grouped by sector or source, followed up by [submitting one nomination](https://digitalpublicgoods.net/submission) for each of them.
- [ ] There is currently a known bug in the submission process that causes all pull requests opened automatically to fail schema validation. They need to be triaged and amended manually. This would be a huge help. If you are interested, comment on the issues labeled [pending review](https://github.com/unicef/publicgoods-candidates/pulls?q=is%3Apr+is%3Aopen+label%3A%22pending+review%22), and we will give you `triage` permissions to assist in this task.
- [ ] *We are developing a crowdsourcing validation tool, when it is completed this will be a great opportunity to contribute with the validation of submissions (no coding skills needed!). Click on the `Watch` button at the top of this page, and we will notify when this opportunity becomes available*

If you have the equivalent of **several full days** available (spread over the course of a several weeks):
- [ ] You can help us developing the data-driven submission form. It involves Javascript, [React](https://reactjs.org/), [NextJS](https://nextjs.org/), [data-driven forms](https://data-driven-forms.org/), and integration with [GitHub's API](https://docs.github.com/en/free-pro-team@latest/rest).

## :memo: License

This repository only contains content, and it is licensed under a [Creative Commons Attribution 4.0 International License](LICENSE).

[![CC BY 4.0][cc-by-image]](LICENSE)

> This is a human-readable summary of (and not a substitute for) the license.
> 
> You are free to:
> * **Share** — copy and redistribute the material in any medium or format
> * **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.
> 
> The licensor cannot revoke these freedoms as long as you follow the license terms.
> 
> * **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
>
> No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

[cc-by-image]: https://licensebuttons.net/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY-%204.0-lightgrey.svg
