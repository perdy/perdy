<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=2800&pause=1200&color=F97316&background=00000000&vCenter=true&repeat=true&width=720&lines=%24+flama+serve+--model+file%3Dperdy.flm;AI+engineer+%26+software+architect;Co-founder+of+Vortico+%C2%B7+creator+of+Flama">
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=2800&pause=1200&color=C2410C&background=FFFFFF00&vCenter=true&repeat=true&width=720&lines=%24+flama+serve+--model+file%3Dperdy.flm;AI+engineer+%26+software+architect;Co-founder+of+Vortico+%C2%B7+creator+of+Flama">
  <img alt="$ flama serve --model file=perdy.flm" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=2800&pause=1200&color=F97316&background=00000000&vCenter=true&repeat=true&width=720&lines=%24+flama+serve+--model+file%3Dperdy.flm;AI+engineer+%26+software+architect;Co-founder+of+Vortico+%C2%B7+creator+of+Flama">
</picture>

<br>

AI engineer and software architect from Málaga, Spain. Co-founder of **[Vortico](https://vortico.tech)**, creator of **[Flama](https://flama.dev)**. I work on the systems that sit between a trained model and the people using it.

<p>
  <a href="https://www.linkedin.com/in/perdy"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.reddit.com/user/p3rdy"><img src="https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white" alt="Reddit"></a>
  <a href="https://arxiv.org/abs/2608.18733"><img src="https://img.shields.io/badge/arXiv-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white" alt="arXiv"></a>
  <a href="https://vortico.tech/team/japl/"><img src="https://img.shields.io/badge/CV-1a1a2e?style=for-the-badge" alt="CV"></a>
  <a href="https://vortico.tech"><img src="https://img.shields.io/badge/vortico.tech-1a1a2e?style=for-the-badge" alt="Vortico"></a>
  <a href="https://vortico.cloud"><img src="https://img.shields.io/badge/vortico.cloud-F97316?style=for-the-badge" alt="Vortico Cloud"></a>
</p>

---

### `GET /about`

```json
{
  "name": "José Antonio Perdiguero López",
  "role": "AI engineer & software architect",
  "from": "Málaga, Spain",
  "building": "Vortico, co-founder",
  "creator_of": "Flama",
  "focus": [
    "AI & data platform architecture",
    "model serving in production",
    "real-time data systems",
    "MLOps"
  ],
  "languages": ["es", "en"],
  "works_on": "the systems that sit between a trained model and the people using it"
}
```

### `GET /flama`

<a href="https://github.com/vortico/flama"><img src="https://raw.githubusercontent.com/vortico/flama/master/public/icon-192.png" width="56" align="left" alt="Flama"></a>

**[Flama](https://github.com/vortico/flama)** turns any trained model, predictive or generative, into a production API with almost no code. I created it and maintain it with [Miguel Durán-Olivencia](https://github.com/migduroli).

<br clear="left">

- **A model is a file.** One portable artifact carries the model, everything it needs at inference time, and the metrics it was promoted on.
- **Same file, any machine.** It runs on a laptop or a GPU server without being rebuilt.
- **Speaks the protocols you already use.** Existing tools and agents work against models you host yourself.
- **A real web framework underneath.** Your models live next to your ordinary endpoints, with validation, docs and authentication included.

```console
$ pip install flama
$ flama serve --model file=model.flm,url=/,name=model
```

<p>
  <a href="https://github.com/vortico/flama"><img src="https://img.shields.io/github/stars/vortico/flama?style=flat-square&color=F97316&label=stars" alt="Stars"></a>
  <a href="https://github.com/vortico/flama/releases"><img src="https://img.shields.io/github/v/release/vortico/flama?style=flat-square&color=F97316&label=release" alt="Release"></a>
  <a href="https://pypi.org/project/flama/"><img src="https://img.shields.io/pypi/dm/flama?style=flat-square&color=F97316&label=downloads" alt="Downloads"></a>
  <a href="https://github.com/vortico/flama/commits"><img src="https://img.shields.io/github/commit-activity/m/vortico/flama?style=flat-square&color=F97316&label=commits" alt="Commit activity"></a>
</p>

### `GET /vortico`

I co-founded [Vortico](https://vortico.tech) to build the tools we kept wishing existed: AI-powered solutions for real-world problems, from forecasting a market to putting a model in production. What we learn in research ends up in the products we build, and they come together on **[Vortico Cloud](https://vortico.cloud)**.

#### [Energy](https://vortico.cloud/solutions/energy/) · AI for power markets

A decision engine for the Spanish electricity market. It forecasts prices days ahead with explicit confidence levels, sizes each bid to your risk profile, and turns that into strategies for the Day-Ahead and Intraday sessions, ready to submit.

<sub>[Market Strategy](https://vortico.cloud/products/market-strategy/) · [Volume Plan](https://vortico.cloud/products/volume-plan/) · [Forecast Analysis](https://vortico.cloud/products/forecast-analysis/) · [Historical Analysis](https://vortico.cloud/products/historical-analysis/)</sub>

#### [Artificial Intelligence](https://vortico.cloud/solutions/ai/) · the AI lifecycle, unified

From first experiment to production API in one workflow, without stitching tools together or rebuilding infrastructure at every step. [Flama](https://vortico.cloud/products/flama/) is at its core, open source and free to use on its own.

#### [Cloud](https://vortico.cloud/solutions/cloud/) · the foundation under every product

Identity, access and operations shared by everything built on Vortico.

<sub>[AuthIAM](https://vortico.cloud/products/authiam/), authentication and access control for your own services · [PanOps](https://vortico.cloud/products/panops/), accounts, organisations and billing in one place</sub>

<sub>Open material: [flama.dev](https://github.com/vortico/flama-site) · [flama-examples](https://github.com/vortico/flama-examples) · [mlops-course](https://github.com/vortico/mlops-course) · [ml4ts-course](https://github.com/vortico/ml4ts-course)</sub>

### `GET /research`

<table>
  <tr>
    <td width="340">
      <a href="https://arxiv.org/abs/2608.18733"><img src="https://img.shields.io/badge/Flama:_production--ready_APIs,_ML_and_LLM_services-1a1a2e?style=flat-square&logo=arxiv&logoColor=white" alt="Flama paper"></a>
    </td>
    <td>
      J.A. Perdiguero López, M.A. Durán-Olivencia. <i>Flama: a Python framework for development and deployment of production-ready APIs, machine learning, and LLM services.</i> <a href="https://arxiv.org/abs/2608.18733">arXiv:2608.18733</a>
    </td>
  </tr>
  <tr>
    <td width="340">
      <a href="https://cordis.europa.eu/project/id/101235948"><img src="https://img.shields.io/badge/CIRCULAR_FUELS_%C2%B7_Marie_Sk%C5%82odowska--Curie_Actions-003399?style=flat-square" alt="CIRCULAR FUELS"></a>
    </td>
    <td>
      Vortico is a partner in <a href="https://cordis.europa.eu/project/id/101235948">CIRCULAR FUELS</a>, an EU-funded MSCA Staff Exchanges consortium of universities and companies across Spain, Italy, Germany and the UK. It researches turning biowaste into fuels and value-added materials, using process simulation and machine learning to extend that to more types of waste.
    </td>
  </tr>
</table>

### `GET /talks`

- **High-performant asynchronous APIs** · PyCon ES
- **New generation of APIs** · PyCon ES
- **Create, package and distribute your own Python application** · PyCon ES
- **Flama: Framework for Lightweight Applications and Machine learning Automation** · OpenSouthCode
- **Machine Learning services validation** · Test Academy
- **Flex schemas with PostgreSQL and Django** · OpenSouthCode

<sub>Slides and materials in <a href="https://github.com/perdy/speech">perdy/speech</a>.</sub>

---

<p align="center">
  <a href="https://vortico.tech">vortico.tech</a> · <a href="https://vortico.cloud">vortico.cloud</a> · <a href="https://flama.dev">flama.dev</a> · <a href="https://github.com/vortico">github.com/vortico</a>
</p>
