# Swiggy Delivery Performance Analytics Dashboard

Interactive analytics dashboard for understanding food delivery performance using simulated Swiggy-like data.

Built with **Gradio**, **Plotly**, **Pandas** and **NumPy** — perfect for portfolio showcase, data analysis interviews, or learning interactive data apps.


Live Demo:(https://huggingface.co/spaces/suchitra23/swiggy-delivery-dashboard)  


## ✨ Features

- Realistic simulated delivery data generation (traffic, distance, preparation time, city effects)
- Multiple interactive visualizations:
  - Delivery time distribution with late threshold marker
  - Scatter plot: Time vs Customer Rating (with delay impact simulation)
  - City-wise performance comparison (late % + average rating)
- Adjustable number of simulated orders (200–5000)
- Clean, responsive UI with modern theme
- Performance caching & input validation
- Professional code structure suitable for production-level mini projects

## 📊 Key Business Insights You Can Explore

- How delivery time impacts customer satisfaction
- Which cities tend to have higher late delivery probability
- Realistic correlation between time taken and ratings
- Effect of distance & traffic on overall performance

## 🚀 Quick Start (Local Development)

### Prerequisites

- Python 3.9+
- Git

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR-USERNAME/swiggy-analysis.git
cd swiggy-analysis

# 2. Create & activate virtual environment (recommended)
python -m venv venv
source venv/bin/activate          # Linux / macOS
venv\Scripts\activate             # Windows

# 3. Install dependencies
pip install -r requirements.txt
