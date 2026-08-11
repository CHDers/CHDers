<p align="center">
  <img src="./assets/transport-ai-banner.svg" width="100%" alt="CHDers · Transportation AI" />
</p>

<div align="center">

### 🚦 Transportation Data Mining · Spatio-Temporal Deep Learning · Intelligent Transportation

**交通数据挖掘 · 时空深度学习 · 智能交通感知**

Turning traffic data into models for **forecasting, perception and mobility intelligence**.

[GitHub](https://github.com/CHDers) ·
[Bilibili](https://space.bilibili.com/375719714) ·
[Email](mailto:chder1996@gmail.com)

</div>

---

## 👋 About Me

Hi, I'm **YanJun (CHDers)**. My main interest is **data-driven intelligent transportation**.


Compared with building a profile around a long list of generic technologies, I prefer to organize my work around one question:

> **How can traffic sensors, trajectories and videos be transformed into useful spatio-temporal representations for prediction and perception?**

```python
class CHDers:
    domain = "Transportation AI"

    research_focus = [
        "Traffic Data Mining",
        "Traffic Flow Forecasting",
        "Spatio-Temporal Graph Learning",
        "Traffic Computer Vision",
    ]

    methods = [
        "GCN", "GAT", "ChebNet", "STGCN",
        "Transformer / Informer",
        "YOLO", "OpenCV", "SORT / DeepSORT",
    ]

    data = [
        "PEMS traffic sensors",
        "METR-LA",
        "Taxi trajectories",
        "Roadside / driving video",
    ]

    goal = "Understand traffic with data, graphs and deep learning."
```


---

## 🧭 Research Focus

| Direction | What I work on | Typical methods / data |
|---|---|---|
| 🚥 **Traffic State Forecasting** | Traffic flow, speed and occupancy prediction | `PEMS` · `METR-LA` · time series |
| 🕸️ **Spatio-Temporal Graph Learning** | Modeling road-network spatial dependency and temporal dynamics | `GCN` · `GAT` · `ChebNet` · `STGCN` |
| 🎥 **Traffic Perception** | Vehicle detection, tracking, counting, lane-level volume and speed estimation | `YOLO` · `OpenCV` · `SORT/DeepSORT` |
| 🧑‍✈️ **Driver & Road Safety** | Drowsiness / yawning detection and lane perception | `dlib` · `EAR/MAR` · vision pipelines |

### From traffic data to traffic intelligence

```mermaid
flowchart LR
    A["🚦 Sensors<br/>Flow · Speed · Occupancy"] --> D["🧹 Data Mining<br/>Cleaning · EDA · Features"]
    B["📍 Trajectories<br/>Taxi / GPS"] --> D
    C["🎥 Traffic Video<br/>Vehicle · Lane · Driver"] --> D

    D --> E["🕸️ Representation<br/>Graph · Sequence · Vision"]
    E --> F["🧠 Modeling<br/>GNN · STGCN · Transformer · YOLO"]
    F --> G["📈 Forecasting<br/>Traffic State"]
    F --> H["👁️ Perception<br/>Detection · Tracking"]
    F --> I["🚘 Applications<br/>Traffic Metrics · Safety"]
```

---

# 🚀 Featured Transportation Projects

## 01 · Traffic Forecasting & Spatio-Temporal Learning

| Project | Focus | Highlights |
|---|---|---|
| **[Traffic Flow Prediction with Graph Neural Networks](https://github.com/CHDers/Traffic-Flow-Prediction-with-Graph-Neural-Networks)** | 🚥 Traffic flow forecasting | PyTorch implementations of **GCN / GAT / ChebNet** on **PEMS-04**; explores detector graph structure and flow / occupancy / speed data |
| **[STGCN-PyTorch](https://github.com/CHDers/STGCN-PyTorch)** | 🕸️ Spatio-temporal forecasting | PyTorch implementation of **STGCN** with a **METR-LA** traffic forecasting example |
| **[GCN Time-Series Prediction on Shenzhen Taxi Trajectories](https://github.com/CHDers/GCN-Time-Series-Prediction-Based-on-Taxi-Trajectory-Data-in-Shenzhen-City)** | 📍 Trajectory mining | Exploring graph-based time-series prediction using **Shenzhen taxi trajectory data** |

> 🚧 The Shenzhen taxi-trajectory repository is kept as an exploration project; its README currently notes that the required data still needs to be completed before the code can run end-to-end.

## 02 · Traffic Perception & Road Safety

| Project | Focus | Highlights |
|---|---|---|
| **[Lane-level Traffic Volume & Speed with YOLO12](https://github.com/CHDers/Detecting-traffic-volume-and-vehicle-speed-in-different-lanes-based-YOLO12)** | 🎥 Traffic video analytics | Detect vehicles and estimate **traffic volume / vehicle speed for different lanes** |
| **[Vehicle Counting with YOLO & OpenCV](https://github.com/CHDers/Vehicle-Counting-Based-on-YOLO-and-OpenCV)** | 🚗 Detection & tracking | Vehicle detection, tracking and counting pipeline with **YOLO + OpenCV** |
| **[Real-time Lane Bend Detection](https://github.com/CHDers/Real-time-lane-bend-detection-based-on-OpenCV)** | 🛣️ Lane perception | Real-time curved-lane detection using **OpenCV**, image filtering and sliding-window search |
| **[Drowsiness Detection](https://github.com/CHDers/Drowsiness-Detection)** | 🧑‍✈️ Driver safety | Driver drowsiness / yawning detection using facial landmarks and **EAR / MAR** features |

---

## 🧰 Transportation AI Toolbox

> Only technologies directly supported by the repositories highlighted above are listed here.

| Layer | Technologies / Methods |
|---|---|
| **Primary Language** | `Python` |
| **Deep Learning** | `PyTorch` |
| **Graph Learning** | `GCN` · `GAT` · `ChebNet` · `STGCN` |
| **Computer Vision** | `YOLO` · `OpenCV` · `dlib` |
| **Tracking** | `SORT` · `DeepSORT` |
| **Data Science** | `NumPy` · `Pandas` · `Matplotlib` |
| **Traffic Data** | `PEMS-04` · `METR-LA` · taxi trajectories · traffic / driving video |
| **Workflow** | `Git` · `GitHub Actions` |

<details>
<summary><b>🔬 Other ML / optimization explorations</b></summary>
<br/>

Alongside transportation research, I also explore broader machine-learning and numerical methods:

- [Solving Burgers Equation with PINNs](https://github.com/CHDers/Solving-Burgers-Equation-with-PINNs)
- [GNN Study From BiliBili](https://github.com/CHDers/GNN-Study-From-BiliBili)
- Transformer / Informer and deep time-series implementations
- Multi-GPU model training, optimization algorithms and related experiments

</details>




---

## 📊 GitHub Metrics

<!-- <p align="center">
  <a href="https://github.com/CHDers">
    <img
      src="./github-metrics-chders.svg"
      width="92%"
      alt="CHDers GitHub Metrics"
    />
  </a>
</p> -->


<p align="center">
  <img
    src="https://metrics.lecoq.io/CHDers?template=classic&isocalendar=1&languages=1&lines=1&people=1&gists=1&sponsorships=1&sponsors=1&reactions=1&followup=1&stars=1&repositories=1&discussions=1&achievements=1&notable=1&code=1&traffic=1&introduction=1&base=header%2C%20activity%2C%20community%2C%20repositories%2C%20metadata&base.indepth=false&base.hireable=false&base.skip=false&repositories.batch=100&repositories.forks=false&repositories.affiliations=owner&isocalendar=false&isocalendar.duration=half-year&languages=false&languages.limit=8&languages.threshold=0%25&languages.other=false&languages.colors=github&languages.sections=most-used&languages.indepth=false&languages.analysis.timeout=15&languages.analysis.timeout.repositories=7.5&languages.categories=markup%2C%20programming&languages.recent.categories=markup%2C%20programming&languages.recent.load=300&languages.recent.days=14&lines=false&lines.sections=base&lines.repositories.limit=4&lines.history.limit=1&lines.delay=0&stars=false&stars.limit=4&followup=false&followup.sections=repositories&followup.indepth=false&followup.archived=true&reactions=false&reactions.limit=200&reactions.limit.issues=100&reactions.limit.discussions=100&reactions.limit.discussions.comments=100&reactions.days=0&reactions.display=absolute&people=false&people.limit=24&people.identicons=false&people.identicons.hide=false&people.size=28&people.types=followers%2C%20following&people.shuffle=false&sponsorships=false&sponsorships.sections=amount%2C%20sponsorships&sponsorships.size=24&sponsors=false&sponsors.sections=goal%2C%20list%2C%20about&sponsors.past=false&sponsors.size=24&sponsors.title=Sponsor%20Me!&repositories=false&repositories.pinned=0&repositories.starred=0&repositories.random=0&repositories.order=featured%2C%20pinned%2C%20starred%2C%20random&discussions=false&discussions.categories=true&discussions.categories.limit=0&achievements=false&achievements.threshold=C&achievements.secrets=true&achievements.display=detailed&achievements.limit=0&notable=false&notable.from=organization&notable.repositories=false&notable.indepth=false&notable.types=commit&notable.self=false&traffic=false&code=false&code.lines=12&code.load=400&code.days=3&code.visibility=public&gists=false&introduction=false&introduction.title=true&config.timezone=Asia%2FShanghai"
    width="70%"
    alt="CHDers GitHub Metrics"
  />
</p>
---






## 🧊 My 3D Contribution

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CHDers/CHDers/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/CHDers/CHDers/output/github-contribution-grid-snake.svg" />
    <img src="https://raw.githubusercontent.com/CHDers/CHDers/output/github-contribution-grid-snake.svg" width="100%" alt="CHDers contribution snake" />
  </picture>
</p>

---

## 📬 Connect

<div align="center">

**Interested in Transportation AI, traffic forecasting, GNNs or traffic computer vision?**

I'm always happy to exchange ideas around **traffic data mining, spatio-temporal modeling and intelligent transportation**.

📮 **chder1996@gmail.com**  
🎬 **[Bilibili](https://space.bilibili.com/375719714)**  
💻 **[github.com/CHDers](https://github.com/CHDers)**

<br/>

<sub>🚦 Data → Graph → Model → Mobility Intelligence</sub>


</div>
