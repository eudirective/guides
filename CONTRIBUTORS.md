# Contributors Guide

This repository aggregates legal and policy information from public institutions, non‑governmental organisations (NGOs) and subject‑matter experts. It relies heavily on European Union documentation – much of which is re‑usable under Directive (EU) 2019/1024 on open data and the reuse of public‑sector information – but may also incorporate limited and lawful use of commentary and analysis from third parties. To maintain the integrity of the project and respect intellectual‑property laws, contributors are expected to follow the guidelines in this document.

---

## 1 Scope and principles

1. **Purpose of this file.** This guide sets out how to contribute new material to the repository, how to handle copyrighted works and quotations, and how to acknowledge sources. It is not a legal opinion but a practical set of recommendations.
2. **Audience.** Anyone proposing pull requests, edits, or new documents should read this guide before submitting their work.
3. **Relationship to other documents.** You should also review the repository’s `README.md`, licence file, and Code of Conduct (if present) to understand the project’s objectives and community expectations. If the repository contains a `CONTRIBUTING.md` for code contributions, the guidelines in that file still apply.
4. **Data protection.** Do not include personal data, case numbers tied to individuals, or any identifying details.

---

## 2 Copyright and re‑use by source type

### 2.1 Government documents

Most of the material in this project derives from EU institutions or other public bodies. Directive (EU) 2019/1024 establishes that public‑sector and publicly funded data should be reusable for commercial or non‑commercial purposes, and requires public bodies to make documents available in open, machine‑readable formats ([EUR‑Lex](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32019L1024)). Member States must facilitate reuse by providing information on rights and assisting users. Nonetheless, there are exceptions: the directive does not apply to documents where third parties hold intellectual‑property rights or where national law restricts access. Contributors should therefore:

- Use official texts (treaties, regulations, directives, case law) preferentially, as these are generally free to reuse. For EU documents, cite the CELEX number and provide a link to the source.
- Be aware that some government websites include photographs, logos or works supplied by private contractors.

### 2.2 NGO reports and legal bloggers

The repository occasionally includes commentary from NGOs, academic commentators and legal bloggers. These works are usually protected by copyright. Under the fair‑use doctrine in US law, it is permissible to use limited portions of a work – including quotes – for purposes such as commentary, criticism, news reporting or scholarly analysis ([Copyright.gov – Fair Use FAQ](https://www.copyright.gov/help/faq/faq-fairuse.html)). The Electronic Frontier Foundation explains that short quotations will usually be fair use and notes that “transformative” uses (where you add commentary or criticism) are favoured over mere copying ([EFF](https://www.eff.org/issues/bloggers/legal/liability/IP)). There are no hard and fast rules on how many words constitute “fair” use ([EFF](https://www.eff.org/issues/bloggers/legal/liability/IP)), so exercise judgement and keep excerpts concise.\
EU copyright laws are generally narrower than U.S. fair use. Quotation is harmonised under Article 5(3)(d) of the InfoSoc Directive: you may quote only to the extent required for purposes such as criticism, review or research, the source and author must be indicated, and the work must have been lawfully made available to the public. Some Member States apply these rules particularly strictly. For example, **France** limits quotations to short passages closely tied to commentary and requires strong justification; **Italy** requires scholarly or critical purpose and careful attribution; **Germany** allows quotation but insists on a close analytical link between the excerpt and the contributor’s own text. In practice, France and Italy are often considered the most restrictive for quotation rights within the EU.

> **Note:** This repository is hosted on GitHub in the U.S. DMCA rules apply to takedowns, but your own national law also applies to your contributions.

When quoting third‑party sources:

1. **Quote sparingly and accurately.** Use only the text necessary to support your analysis. Avoid reproducing large portions or the “heart” of the work. Clearly mark quotations with quotation marks.
2. **Provide attribution and a link.** Always identify the author and source. Contextual links – clickable text embedded in your sentence that leads directly to the source – are encouraged. If the source is a blog or NGO report, link to the specific page rather than the website’s homepage.
3. **Discuss or critique the quoted material.** Transformative use (commentary, critique or analysis) strengthens the case for fair use. Do not simply copy text without adding value.
4. **Check for a licence.** Some blogs or NGO publications are released under Creative Commons licences, which may grant more generous rights. Review the licence terms to ensure compliance (for example, attribution or share‑alike requirements).
5. **Use quotations as a prompt for further reading.** Keep them concise and contextualised so they spark interest in the original source rather than substitute for it. 
6. **Use abstracted form.** If in doubt, summarise or extract the information in your own words rather than copying. Keep quotations minimal, and always attribute the original source, even when paraphrasing.

### 2.3 Facts and ideas

Facts, ideas and data that are not expressed in a unique way are not subject to copyright protection. You are free to summarise and rephrase factual content, even if it originates from a copyrighted work ([EFF](https://www.eff.org/issues/bloggers/legal/liability/IP)). When doing so, still credit the source and, where appropriate, link to the document that inspired your summary.

---

## 3 Quotation and citation policy

### 3.1 In‑text citations and links

For most contributions, a contextual link in the body of your text is sufficient. Identify the source by name and add a hyperlink to the specific document or web page. This approach keeps the text readable and allows readers to verify your statements.

When you quote directly, include a clear attribution before or after the quoted passage and link to the original source. Example:

> As the Electronic Frontier Foundation notes, “short quotations will usually be fair use” ([EFF](https://www.eff.org/issues/bloggers/legal/liability/IP)).

### 3.2 Footnotes

Markdown supports footnotes, GitHub’s flavour of Markdown allows you to add footnotes using bracket syntax ([GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#footnotes)). A footnote is defined by a `[^identifier]` marker in the text and a corresponding reference at the bottom of the page:

```md
Here is a statement that needs a source.[^1]

[^1]: European Parliament and Council, Directive (EU) 2019/1024, EUR‑Lex, https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32019L1024
```

GitHub automatically renders footnotes as superscript numbers that link to the references at the bottom of the document. Footnotes are a good choice when multiple citations would clutter the main text. However, they are not supported in wikis, so avoid them in the wiki context.

### 3.3 Reference lists

For extensive documents or when dealing with many sources, you may choose to collect all references in a separate file (e.g., `references.md`) and link to that file from your contribution. Each entry in the reference list should include the author (if known), title, publication date and a URL or DOI. Use numbered identifiers (e.g., [1], [2]) in your main document to refer to the corresponding entry in `references.md`.

---

## 4 Contribution Workflow

### 4.1 Before you begin

1. **Read existing material.** Familiarise yourself with the repository’s structure and existing content to avoid duplication.
2. **Discuss major changes.** If you intend to add a substantial new section or restructure existing documents, open an issue to discuss your plan with maintainers before investing significant effort. For smaller fixes (typos, broken links, minor clarifications) you can proceed directly to a pull request.
3. **Check licences.** Ensure that any material you plan to contribute is compatible with the repository’s licence. If you include third‑party code or content, verify that its licence permits redistribution.

### 4.2 Making a contribution

*If the github workflow is too overwhelming for you, seek help from other contributors.*

1. **Fork and branch.** Fork the repository and create a new branch for your changes. Use a descriptive branch name (e.g., `add-guidance-on-eu-visa-directive`).
2. **Write clear commit messages.** Each commit message should summarise the change and reference the relevant issue or discussion when applicable.
3. **Follow style conventions.** Maintain consistent formatting and writing style. Use headings (`#`, `##`, etc.) to organise content and keep paragraphs short (3–5 sentences). Use bullet lists to group related items.
4. **Add citations.** When adding new information, cite your sources using contextual links, footnotes or the reference list as appropriate. Ensure that links are permanent (e.g., use DOI links or stable URLs).
5. **Respect the Code of Conduct.** All interactions, including comments and commit messages, should be professional and respectful.
6. **Submit a pull request.** When your branch is ready, open a pull request against the main branch. Include a summary of your changes and highlight any areas where maintainers should pay special attention. Be prepared to revise your contribution based on feedback.

**PR checklist**

- Sources linked and, where applicable, footnoted
- Quotes are minimal and attributed
- No personal data included
- Links use stable CELEX/ECLI/HUDOC/official sources
- File naming and metadata follow this guide

---

## 5 Final Remarks and Suggestions

- **Use open formats.** Prefer plain text (`.md`) whenever possible. Avoid proprietary formats unless necessary and clearly label them.
- **Avoid copyrighted images.** Do not upload photographs, logos or figures unless you have the right to do so. For diagrams, consider creating your own graphics or using images released under permissive licences.
- **Keep it neutral.** Maintain a neutral, descriptive tone in summaries. Opinions should be clearly marked as such and supported by evidence.
- **Review regularly.** Laws and policies evolve. Periodically review your contributions to ensure they remain accurate and up to date.



