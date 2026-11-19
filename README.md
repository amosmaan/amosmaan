### Hi, I'm Abdirisaq 👋

```python
from dataclasses import dataclass, field

@dataclass
class DataEngineer:
    name: str = "Abdirisaq Osmaan"
    role: str = "Degree Apprentice → BI Engineer / Data Engineer"
    based_in: str = "London, UK"
    stack: list[str] = field(default_factory=lambda: [
        "SQL", "Python", "pandas", "QuickSight", "AWS"
    ])
    currently_learning: list[str] = field(default_factory=lambda: [
        "NumPy & pandas", "Git", "data modelling", "dbt"
    ])
    interests: list[str] = field(default_factory=lambda: [
        "Analytics engineering", "Data pipelines", "Football / FPL analytics"
    ])

    def current_focus(self) -> str:
        return "Turning raw data into reliable, useful insight 📊"


if __name__ == "__main__":
    me = DataEngineer()
    print(f"Hello, World! I'm {me.name}, {me.current_focus()}")
```

---

### 🔨 Currently building
**[python-foundations](https://github.com/amosmaan/python-foundations)**: Python exercises and a small FPL command-line tool, part of a 12-month BIE/DE learning pathway.

---

### 🗂️ Projects

| Project | What it does | Skills | Status |
|---|---|---|---|
| [python-foundations](https://github.com/amosmaan/python-foundations) | Exercise solutions + an FPL player-lookup CLI | Python, OOP, Git | 🟡 In progress |
| [sql-pandas-practice](https://github.com/amosmaan/sql-pandas-practice) | The same problems solved in SQL and pandas, plus star-schema designs | SQL, pandas, data modelling | ⚪ Planned |
| [analysis-showcase](https://github.com/amosmaan/analysis-showcase) | Analysis from start to finish + a live Streamlit dashboard | Statistics, visualisation, storytelling | ⚪ Planned |
| [mini-data-pipeline](https://github.com/amosmaan/mini-data-pipeline) | API → Parquet → dbt, Dockerised and tested in CI | Python, Docker, dbt, pytest | ⚪ Planned |
| [fpl-data-platform](https://github.com/amosmaan/fpl-data-platform) | Scheduled FPL pipeline with streaming + AWS | Dagster/Airflow, AWS, Spark | ⚪ Planned |

---

### 🧰 Tech stack

**Comfortable with:** SQL (window functions, CTEs, Athena / Redshift) · QuickSight · Excel · dashboard design

**Learning now:** Python · pandas · NumPy · Git

**Up next:** dbt · Docker · AWS Glue / S3 / Lambda · Spark · Kinesis

---

### 💼 Experience
**Data Analyst Degree Apprentice @ Amazon (Data & BI)** 2024 – present:
Building dashboards, automating manual reporting processes and developing internal workflow apps, alongside a degree in data analysis.

---

### 🎓 Education & certifications
- 🎓 Digital and Technology Solutions Professional Degree Apprenticeship BSc (Honours) (in progress)
- ☁️ AWS Certified AI Practitioner & Cloud Practitioner certification holder
- 🎯 *Next:* AWS Certified Data Engineer – Associate

---

### 📫 Connect
[LinkedIn](https://www.linkedin.com/in/abdirisaq-o-199365312/) 

![GitHub stats](https://github-readme-stats.vercel.app/api?username=amosmaan&show_icons=true&hide_border=true&count_private=true)
