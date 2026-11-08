# Hi, I'm Aravind

Data Scientist / Data Engineer based in Skövde, Sweden. I turn raw, messy event data into production ML systems, and in my own time I build ML and analytics tools for the games I play.

Currently: MSc in Data Science at the University of Skövde, and looking for an **MSc thesis in ML for games**, especially mining gameplay telemetry to understand how players actually behave versus what designers intended.

<img src="koi/koi.gif" width="256" alt="Pixel-art koi generated from my GitHub activity">

<sub>My koi, redrawn nightly from my GitHub activity with <a href="https://github.com/yalongwastaken/git-koi">git-koi</a>.</sub>

## Featured projects

| Project | What it is | Key result |
|---|---|---|
| [osu-pulse](https://github.com/rapidvind/osu-pulse) | Real-time osu!mania telemetry (session > play > miss events) with an unsupervised ML layer: clustering, anomaly detection, regression | Every method checked against a baseline; random forest R² 0.71 vs 0.01 for the Poisson baseline |
| [ManiaMapper](https://github.com/rapidvind/ManiaMapper) | Generates playable osu!mania beatmaps from raw audio with a difficulty-conditioned encoder-decoder (BiLSTM + causal LSTM, ~7M parameters) | Shipped end to end as a FastAPI web app on GCP |
| [mariokart8-build-prediction](https://github.com/rapidvind/mariokart8-build-prediction) | Hand-built 52-track dataset predicting the best build per track | Found target leakage behind a fake R² of 0.99; honest result traced to players converging on 6 meta builds |
| [k8s-traffic-autoscaling-lab](https://github.com/rapidvind/k8s-traffic-autoscaling-lab) | Local multi-node Kubernetes cluster with traffic-driven autoscaling (HPA) | Full setup and debugging docs |

## Work

**Data Engineer at a healthtech company**, remote, 2024 to present. HIPAA-compliant environment.
- Built an OCR/LLM extraction engine that cut manual data entry by about 88%
- Rebuilt the prediction pipeline: 15 minutes down to under 30 seconds per sample
- Behavioural analytics that flags at-risk clients from event patterns (17% of the client base)
- Took over infrastructure: CI/CD with preview environments cut deploys from a full day to about 30 minutes

## How I work

- **Honest evaluation first:** baselines, cross-validation, and saying so when a model doesn't beat the baseline
- **Fix the data at the source** instead of working around it downstream
- **Ship it:** projects end as something people can run, not just a notebook

## Toolbox

**ML:** PyTorch, scikit-learn, XGBoost, clustering, anomaly detection, sequence models (LSTM), feature engineering

**Data:** Python, SQL, Spark (Scala), pandas, ETL pipeline design, event and log data

**Infra:** Docker, Kubernetes, CI/CD (GitHub Actions), GCP, AWS, Redis

## Outside work

Rhythm games (osu!mania), Valorant, Hollow Knight and Silksong (modding), bouldering, basketball, strategy board games.

## Contact

[LinkedIn](https://linkedin.com/in/aravind-dora-889814179) · aravinddora45@gmail.com · open to thesis and data/ML roles
