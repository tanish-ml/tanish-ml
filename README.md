# Hello there, I'm Tanish 👋

I'm a Data Scientist and AI Enthusiast passionate about building intelligent systems, training deep neural networks, and extracting actionable insights from complex data.

```python
import torch
import pandas as pd
from ai_architectures import DeepLearningModel

class Tanish(DeepLearningModel):

    def __init__(self):
        super(Tanish, self).__init__()
        self.name = "Tanish Mittal"
        self.role = "Data Scientist & ML Engineer"
        self.current_focus = "Mastering PyTorch and Advanced Neural Network Architectures"
        
    def get_capabilities(self):
        return {
            "core": ["Machine Learning", "Deep Learning", "Data Analytics"],
            "languages": ["Python", "SQL", "Bash"],
            "frameworks": ["PyTorch", "TensorFlow", "Scikit-Learn"],
            "data_ops": ["Pandas", "NumPy", "Matplotlib"],
            "infrastructure": ["Docker", "Linux", "AWS", "GCP", "Git"]
        }

    def forward(self, coffee, raw_data):
        """
        Standard forward pass for model training and deployment.
        """
        clean_data = self.preprocess(raw_data, fuel=coffee)
        insights = self.extract_patterns(clean_data)
        model = self.train_model(insights, optimizer=torch.optim.Adam)
        return model.deploy()

    def collaborate(self):
        return "I'm always open to collaborating on open-source AI and DS projects! 🚀"

    def get_contact(self):
        return "tanishmittal2212@gmail.com"

if __name__ == "__main__":
    me = Tanish()
    print(me.collaborate())
```

### ⚙️ Technologies & Tools

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,scikitlearn,pandas,numpy,docker,linux,aws,gcp,git,bash&perline=12" />
  </a>
</p>

### 📡 Let's Connect

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tanishmittal2212@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tanish-ml)
