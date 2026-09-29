<div align="center">
  <h1>Hi, I'm Fadhil 👋</h1>
  <p><strong>Machine learning engineer · AI agents · ML platforms · experimentation</strong></p>
  <p>Stockholm 🇸🇪 · originally from Indonesia 🇮🇩 · <a href="https://fadhilmch.github.io">fadhilmch.github.io</a></p>
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

## What I'm curious about

- How agents coordinate, and how to evaluate them honestly
- Evaluation that shows whether an AI system actually works
- ML platforms that make the right path the easy path
- Experiments that help teams learn instead of guess
- Boringly reliable services: observable, fault-tolerant, simple to operate
- Starting with the user and the problem, then choosing the technology

## Toolbox

`Python` · `Go` · `SQL` · `Kubernetes` · `Kubeflow` · `Terraform` · `Azure` · `Google Cloud` ·
`BigQuery` · `Redis` · `MLflow` · `RAG` · `LLM evaluation` · `A/B testing` · `bandits`

## Off the clock

I take photos, make music, design things now and then, and treat coffee and cooking as small
experiments ☕

## Say hello

Happy to talk about agents, evaluation or experimentation.

[Website](https://fadhilmch.github.io) · [LinkedIn](https://www.linkedin.com/in/fadhilmch/) · [Email](mailto:fadhil.mochammad1095@gmail.com)
