<h1 align="left" id="asoba-title">:sunny: We're Asoba</h1>
<h3 align="left">Pioneering Solutions for Clean Energy Trading and Policy Development</h3>

<p align="left">
  <a href="https://github.com/AsobaCloud">
    <img src="https://img.shields.io/github/stars/AsobaCloud?style=for-the-badge&color=green" alt="Asoba GitHub Stars"/>
  </a>
  <a href="https://github.com/orgs/AsobaCloud/repositories">
    <img src="https://img.shields.io/badge/Repositories-View%20All-blue?style=for-the-badge" alt="Asoba Repositories"/>
  </a>
  <a href="https://asoba.co">
    <img alt="Website" src="https://img.shields.io/website?url=https%3A%2F%2Fasoba.co&style=for-the-badge">
  </a>
  <a href="https://www.linkedin.com/company/asoba-co/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin">
  </a>
</p>

<a href="https://github.com/AsobaCloud/sdk">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=AsobaCloud&repo=sdk&theme=vue" alt="Asoba SDK" align="right" />
</a>

- :office: &nbsp;We're building **energy forecasting and policy analysis tools**
- :zap: &nbsp;Currently working on **Ona API** for energy data and forecasting
- :brain: &nbsp;Developing **RAG-enhanced LLMs** for policy analysis and energy insights
- :earth_africa: &nbsp;Supporting **multi-region deployment** for data sovereignty
- :chart_with_upwards_trend: &nbsp;Creating energy forecasting models with **SageMaker**
- :mailbox: &nbsp;Reach out to us on our **[website](https://asoba.co/contact-us)**

<br>
<a href="https://app.asoba.co">
<img src="https://github.com/user-attachments/assets/eea6b5b0-d875-4f37-a5b5-d270402ec656">
</a>




<h2 align="left" id="asoba-tech">Our Tech Stack</h2>

> Technologies and frameworks powering our clean energy solutions

<table>
  <tr>
    <td align="center" width="96">
      <a href="#asoba-tech">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="48" height="48" alt="Python" />
      </a>
      <br>Python
    </td>
    <td align="center" width="96">
      <a href="#asoba-tech">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="48" height="48" alt="React" />
      </a>
      <br>React
    </td>
    <td align="center" width="96">
      <a href="#asoba-tech">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="48" height="48" alt="JavaScript" />
      </a>
      <br>JavaScript
    </td>
    <td align="center" width="96">
      <a href="#asoba-tech">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="48" height="48" alt="Node.js" />
      </a>
      <br>Node.js
    </td>
    <td align="center" width="96">
      <a href="#asoba-tech" >
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" width="48" height="48" alt="AWS" />
      </a>
      <br>AWS
    </td>
    <td align="center" width="96"> 
      <a href="#asoba-tech" >
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="48" height="48" alt="Docker" />
      </a>
      <br>Docker
    </td>
    <td align="center"  width="96">
      <a href="#asoba-tech">
        <img src="https://cdn.worldvectorlogo.com/logos/aws-lambda-1.svg" width="48" height="48" alt="AWS Lambda" />
      </a>
      <br>Lambda
    </td>
    <td align="center" width="96">
      <a href="#asoba-tech" >
        <img src="https://symbols.getvecta.com/stencil_25/5_dynamodb.1a1344e5be.svg" width="48" height="48" alt="DynamoDB" />
      </a>
      <br>DynamoDB
    </td>
  </tr>
</table>

<h2 align="left">Our Key Projects</h2>

<table>
  <tr>
    <td>
      <h3><a href="https://github.com/AsobaCloud/api">Ona API</a></h3>
      <p>Core energy forecasting API with data interpolation, ML modeling, and regional deployments</p>
      <p><strong>Tech:</strong> Python, AWS Lambda, SageMaker, DynamoDB</p>
    </td>
    <td>
      <h3><a href="https://github.com/AsobaCloud/ona-front-end">Ona On-Demand</a></h3>
      <p>React-based frontend for interacting with fine-tuned LLMs for policy analysis</p>
      <p><strong>Tech:</strong> React, Express.js, AWS Bedrock</p>
    </td>
  </tr>
  <tr>
    <td>
      <h3><a href="https://github.com/AsobaCloud/dispatch">Electricity Dispatch Algorithm</a></h3>
      <p>Algorithm used for optimized electricity scheduling for a mini-grid system</p>
      <p><strong>Tech:</strong> AWS Lambda, S3, Python</p>
    </td>
    <td>
      <h3><a href="https://github.com/AsobaCloud/sdk">Ona SDK</a></h3>
      <p>Client libraries for seamless integration with our energy forecasting API</p>
      <p><strong>Features:</strong> Authentication, Data Upload, Forecast Retrieval</p>
      <p><strong>Languages:</strong> JavaScript, Python</p>
    </td>
  </tr>
</table>

## 🚀 Getting Started

### Prerequisites
- Node.js 16+ and Python 3.9+
- AWS CLI configured with appropriate credentials
- GitHub access to AsobaCloud organization
- Auth0 and Stripe accounts (for full functionality)

### Quick Start

1. **Clone the repositories**
```bash
git clone https://github.com/AsobaCloud/api.git
git clone https://github.com/AsobaCloud/ona-front-end.git
```

2. **Set up the backend**
```bash
cd api
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env
# Edit .env with your configuration
python app.py
```

3. **Set up the frontend**
```bash
cd ona-front-end
npm install
cp .env.example .env
# Edit .env with your API endpoint and Auth0 config
npm run dev
```

4. **Access the application**
- Frontend: http://localhost:3000
- API: http://localhost:8000
- API Docs: http://localhost:8000/docs

## 📋 Development Workflow

### Automated Test Criteria System

Every new issue created in our repositories automatically receives comprehensive test criteria to ensure quality and completion verification. This system:

- ✅ Applies within 60 seconds of issue creation
- ✅ Detects issue type (API, Frontend, ML, Infrastructure, Security)
- ✅ Enforces CLAUDE.md compliance principles
- ✅ Requires objective completion verification
- ✅ Includes cross-region deployment validation

### Issue Management

All development work is tracked through GitHub Issues and organized in the [Ona Power Tools Platform Project Board](https://github.com/orgs/AsobaCloud/projects/2).

### Development Standards

**Code Quality:**
- All code must pass linting (ESLint for JS/TS, Black/Flake8 for Python)
- Minimum 80% test coverage for new features
- Peer review required for all PRs
- Documentation required for public APIs

## :seedling: Our Impact

At Asoba, we're building AI solutions that:

- 📊 Enable better energy trading and decision-making
- 🔍 Provide clear policy insights through RAG-enhanced LLMs
- ⚡ Help organizations transition to distributed energy markets
- 🌱 Support sustainable development with advanced forecasting

<!-- links -->
[website]: https://asoba.co "Asoba Website"
[linkedin]: https://www.linkedin.com/company/asoba-co/ "Asoba LinkedIn"
