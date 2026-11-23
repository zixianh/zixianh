<div align="center">

# Hi, I'm Zixian (Bryan) He 👋

<a href="https://github.com/zixianh">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=4F7CAC&center=true&vCenter=true&width=640&lines=LLM+Evaluation+%26+Reliability;Causal+Inference+%26+Uncertainty+Quantification;AI+and+the+Online+Information+Ecosystem" alt="Research areas" />
</a>

[![arXiv](https://img.shields.io/badge/arXiv-2606.06781-b31b1b?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2606.06781)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zixian-he)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zixianh@usc.edu)

</div>

---

### 🧭 About Me

I study **how AI changes the way people use information**, and **how to draw reliable conclusions when model outputs are used as data**. My work combines **causal inference**, **uncertainty quantification**, and **LLM evaluation**, with applications to online knowledge platforms and computational social science.

My interest comes from industry. As a data analyst, I relied on AI-generated code to clean and restructure data, and saw how it could fill in ambiguous instructions with unstated assumptions, producing results that ran without error yet were quietly wrong. I now study failures like these: **model outputs that look correct but are not.**

<table>
<tr>
<td>🎓 <b>M.S. in Applied Data Science</b><br/><sub>University of Southern California</sub></td>
<td>🎓 <b>B.S. in Mathematics</b><br/><sub>University of Wisconsin–Madison</sub></td>
</tr>
</table>

---

### 📰 News

- 🎉 **Nov 2026** — *When Better Codebooks Are Not Enough* accepted to the **EACL 2027 Main Conference**

---

### 📄 Research

#### When Better Codebooks Are Not Enough: Predictive Performance and Rule Adherence in LLM Political Event Coding

![EACL 2027](https://img.shields.io/badge/EACL_2027-Main_Conference-2E7D32?style=flat-square)
[![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2606.06781)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/yibo-hu-lab/event-coding-reliability)

**Zixian He**, Bharath Raahul Murugesan, Patrick T. Brandt, Yibo Hu

> **Do LLMs actually follow the expert codebooks they are given?** Richer codebooks raise accuracy on political event coding (macro-F1 **0.457 → 0.633**), yet simply reversing the order of codebook entries changes **21%** of predictions.

<details>
<summary><b>Methods</b></summary>
<br/>

Controlled codebook changes (reordering entries, replacing label names with placeholders, reassigning definitions) separate classification accuracy from adherence to the supplied rules. Agreement across codebook orderings is measured with Fleiss' κ, and differences between conditions are assessed with bootstrap confidence intervals, across four open-source LLMs.

</details>

#### How Wikipedia Readership Shifted after ChatGPT

![Under Review](https://img.shields.io/badge/Status-Under_Review-F9A825?style=flat-square)

**Zixian He**, with Xinyu Chen and Ambra Amico

> **How do you estimate the effect of a technology that reaches everyone at once?** Placebo analyses back to 2015 show that much of the apparent post-ChatGPT decline in Wikipedia readership reflects recurring seasonality; the remaining evidence points to a shortfall concentrated in computing articles.

<details>
<summary><b>Methods</b></summary>
<br/>

Built a daily pageview panel of 10,000 English Wikipedia articles from raw hourly Wikimedia dumps. Estimated counterfactual readership with nuclear-norm-regularized matrix completion, benchmarked against synthetic control and difference-in-differences through pseudo-treatment validation, with split conformal prediction intervals for the estimated effects.

</details>

---

### 🔬 Research Interests

<table>
<tr>
<td width="50%" valign="top">

**📏 LLM Outputs as Measurements**<br/>
<sub>Measurement error, validation, and valid inference when model-generated labels replace human annotation</sub>

</td>
<td width="50%" valign="top">

**📈 Causal Inference & Uncertainty**<br/>
<sub>Counterfactual estimation when treatment reaches all units at once; prediction intervals under dependence and heavy tails</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🌐 AI & the Information Ecosystem**<br/>
<sub>When AI supplements or substitutes for sources like Wikipedia, and what that means for knowledge communities</sub>

</td>
<td width="50%" valign="top">

**🧪 LLM Evaluation & Robustness**<br/>
<sub>Reliability signals beyond accuracy, such as consistency under meaning-preserving changes</sub>

</td>
</tr>
</table>

---

### 🛠️ Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,r,pytorch,sklearn,git,latex,mysql,docker,vscode&perline=9" alt="Tools" />
</p>

---

<div align="center">

<sub>Feel free to reach out about LLM evaluation, causal inference, or AI and online information ✉️</sub>

</div>
