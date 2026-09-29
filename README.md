<div align="center">
  <h1>Hi, I'm Fadhil 👋</h1>
  <p><strong>Machine learning engineer · AI agents · ML platforms · experimentation</strong></p>
  <p>Stockholm · originally from Indonesia 🇮🇩 · <a href="https://fadhilmch.github.io">fadhilmch.github.io</a></p>
</div>

I like the part of machine learning that starts after the demo: making the system useful,
measurable, and reliable enough to keep running.

```python
@agent(id="fadhilmch", based_in="Stockholm 🇸🇪", roots="Indonesia 🇮🇩")
class Fadhil(MachineLearningEngineer):
    """Ships the model, then keeps it alive."""

    toolkit = [Python, Go, Kubernetes, Kubeflow, Azure, GoogleCloud]

    def solve(self, problem):
        while not problem.is_clear:
            problem = self.ask(problem, "but why?")

        return self.ship(simplest_thing_that_works(problem))

    @llm_eval(metrics=["relevance", "retrieval_recall", "groundedness", "latency"])
    def did_it_work(self, response):
        return response.is_relevant and response.is_grounded

    def on_error(self, error):
        return self.learn(error)  # production is where the interesting bugs live
```

## Now

At **Electrolux Group** I build and run:

- an **agentic knowledge assistant** used by 6,000 employees a month, in any language. I own its
  evaluation: relevance, retrieval recall, groundedness and latency.
- a **feedback-triage agent** that replays flagged questions, checks the evidence and routes each
  case to an owner.
- the **MLOps layer** for a production supply-chain optimizer.

## Before

Almost five years at **Traveloka** in Jakarta, leading the experimentation platform used by 30+
product teams for 800+ experiments a year.

- Modernized the platform: cloud cost down 95% year over year, API latency down 90%.
- Built a Go assignment service that held 50K+ requests per second in a 30-minute load test, with
  P95 under 100 ms.
- Built the ML serving engine and SDK behind about 40 model deployments, Kubeflow training pipelines,
  and a metric layer with 100+ reusable metrics.

Before that: a Spotify internship on bandits for notifications, an MSc in machine learning at KTH,
and electrical engineering in Bandung, mostly spent on robots and drones.

## Toolbox

`Python` · `Go` · `SQL` · `Kubernetes` · `Kubeflow` · `Terraform` · `Azure` · `Google Cloud` ·
`BigQuery` · `Redis` · `MLflow` · `RAG` · `LLM evaluation` · `A/B testing` · `bandits`

## Say hello

Happy to talk about AI in production, evaluation or experimentation. Off the clock I take photos,
make music, and treat coffee and cooking as small experiments ☕

[Website](https://fadhilmch.github.io) · [LinkedIn](https://www.linkedin.com/in/fadhilmch/) · [Email](mailto:fadhil.mochammad1095@gmail.com)
