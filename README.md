# awesome-ml-monitoring

A curated list of awesome open source tools and commercial products for monitoring data quality, monitoring model performance, and profiling data 🚀

## Open-Source Tools

| Tool | Key Features | Data Types Supported | Models Supported | Pros | Cons | Links |
|------|-------------|---------------------|------------------|------|------|-------|
| **Evidently AI** | - Interactive reports & dashboards<br>- Data & model drift detection<br>- Target drift monitoring<br>- 100+ built-in metrics<br>- Test suites & real-time monitoring<br>- Bias detection | Tabular, Text, NLP, Computer Vision, LLMs, RAG systems | Classification, Regression, Multi-class, LLMs, Multi-modal | - Apache 2.0 license<br>- Well-documented<br>- Easy integration with MLflow<br>- Strong community support<br>- Open-core model | - No native image format support<br>- Limited to Python ecosystem | [GitHub](https://github.com/evidentlyai/evidently)<br>[Website](https://evidentlyai.com) |
| **Deepchecks** | - Comprehensive test suites<br>- Data integrity validation<br>- Model validation<br>- Continuous monitoring<br>- GitHub integration<br>- Export to HTML/JSON | Tabular, Image data | Classification, Regression, Object Detection, Computer Vision | - Holistic testing approach<br>- Multiple deployment options<br>- Integration with popular frameworks | - AGPL license (enterprise concern)<br>- OSS version limited for production<br>- Complex architecture | [GitHub](https://github.com/deepchecks/deepchecks)<br>[Website](https://deepchecks.com) |
| **WhyLogs** | - Lightweight data logging<br>- Statistical profiling<br>- Privacy-preserving<br>- Integration with WhyLabs platform<br>- Scalable data capture | Structured, Unstructured, Text, Tabular | Framework-agnostic | - Minimal overhead<br>- Data never leaves VPC<br>- Works with all ML frameworks<br>- Zero configuration | - Primarily SDK for WhyLabs<br>- Limited standalone features | [GitHub](https://github.com/whylabs/whylogs)<br>[Website](https://whylabs.ai) |
| **MLflow** | - Experiment tracking<br>- Model registry<br>- Model versioning<br>- Deployment management<br>- Artifact tracking | All data types | Framework-agnostic (TensorFlow, PyTorch, Scikit-learn, XGBoost, etc.) | - Industry standard<br>- Library-agnostic<br>- Strong ecosystem<br>- Easy integration | - Basic monitoring only<br>- Requires additional tools for advanced monitoring | [GitHub](https://github.com/mlflow/mlflow)<br>[Website](https://mlflow.org) |
| **Prometheus** | - Time-series metrics<br>- Alerting system<br>- Custom metrics<br>- Kubernetes integration<br>- PromQL query language | Metrics/Time-series | Model-agnostic | - Battle-tested<br>- Strong Kubernetes support<br>- Flexible alerting<br>- Large ecosystem | - Requires manual setup<br>- Not ML-specific<br>- Steeper learning curve | [GitHub](https://github.com/prometheus/prometheus)<br>[Website](https://prometheus.io) |
| **Seldon Core** | - Kubernetes-native deployment<br>- Advanced metrics<br>- Outlier detection<br>- A/B testing & canaries<br>- Inference graphs<br>- REST/GRPC microservices | All data types | TensorFlow, PyTorch, H2O, Python, Java wrappers | - Highly scalable<br>- Cloud & on-prem support<br>- Advanced ML features<br>- Framework-agnostic | - Kubernetes required<br>- Complex setup<br>- Business Source License (v2) | [GitHub](https://github.com/SeldonIO/seldon-core)<br>[Website](https://seldon.io) |
| **NannyML** | - Performance estimation without targets<br>- Confidence-based performance estimation (CBPE)<br>- Direct loss estimation (DLE)<br>- PCA-based multivariate drift<br>- Univariate drift detection<br>- Business value estimation | Tabular | Classification, Regression | - Novel estimation algorithms<br>- Detects drift before actuals arrive<br>- Links drift to performance<br>- Good visualization | - Python library only<br>- Requires scripting for automation<br>- Limited to tabular data | [GitHub](https://github.com/NannyML/nannyml)<br>[Website](https://nannyml.com) |
| **Great Expectations** | - Data validation<br>- Data profiling<br>- Pipeline testing<br>- Data documentation | Tabular, Databases | Data-centric (not model-specific) | - Strong data quality focus<br>- Comprehensive documentation<br>- Pipeline integration | - Not model-focused<br>- Data validation only | [GitHub](https://github.com/great-expectations/great_expectations)<br>[Website](https://greatexpectations.io) |

## Proprietary/Commercial Tools

| Tool | Key Features | Data Types Supported | Models Supported | Pros | Cons | Links |
|------|-------------|---------------------|------------------|------|------|-------|
| **Arize AI** | - End-to-end ML observability<br>- Embedding drift monitoring<br>- 2D/3D model visualization<br>- Root cause analysis<br>- Automatic drift detection<br>- Feature impact tracing | Tabular, NLP, Computer Vision, LLMs, Embeddings, Multi-modal | All model types including Generative AI | - Comprehensive platform<br>- Strong visualization<br>- Excellent for embeddings<br>- Enterprise-ready | - Proprietary/Paid<br>- Vendor lock-in<br>- Can be expensive | [Website](https://arize.com) |
| **Fiddler AI** | - Full-stack AI observability<br>- Explainable AI (XAI)<br>- Custom & proprietary SHAP<br>- Model debugging<br>- Performance monitoring<br>- Fairness assessment | Tabular, NLP, Computer Vision, LLMs | Generative & Predictive models | - Strong explainability<br>- Enterprise security<br>- Multi-framework support<br>- Good UI/UX | - Expensive<br>- Complex setup<br>- Proprietary platform | [Website](https://fiddler.ai) |
| **WhyLabs** | - Real-time observability<br>- Anomaly detection<br>- Data health monitoring<br>- Model health tracking<br>- Automatic alerts<br>- Privacy-preserving profiling | Structured, Unstructured, Text, LLMs | All model types | - Scalable (millions of events)<br>- Privacy-focused<br>- Easy integration<br>- No data leaves VPC | - SaaS only<br>- Cost scales with usage<br>- Limited customization | [Website](https://whylabs.ai) |
| **Aporia** | - Customizable monitoring<br>- Model explainability<br>- Real-time alerts<br>- ML observability platform<br>- Performance tracking | Tabular, NLP, LLMs | All ML use cases | - Highly customizable<br>- Good for various industries<br>- Easy to scale | - Newer player<br>- Less mature than competitors | [Website](https://aporia.com) |
| **TruEra** | - AI quality platform<br>- Model explainability<br>- Fairness assessment<br>- Robustness testing<br>- Performance estimation before ground truth<br>- Root cause analysis | Tabular, Predictive & Generative models | Classification, Regression, LLMs | - Comprehensive AI quality metrics<br>- Strong debugging capabilities<br>- Segment analytics<br>- Bias detection | - Enterprise pricing<br>- Complex platform<br>- Can be resource-intensive | [Website](https://truera.com) |
| **Arthur AI** | - AI performance monitoring<br>- LLM firewall (Arthur Shield)<br>- Bias & fairness detection<br>- Explainability<br>- Risk mitigation | Tabular, NLP, Computer Vision, LLMs | All model types | - Strong governance features<br>- Security-focused<br>- Compliance support<br>- LLM protection | - Proprietary<br>- Enterprise focus<br>- Higher cost | [Website](https://arthur.ai) |
| **Superwise** | - Fully automated observability<br>- Model health monitoring<br>- Drift detection<br>- Automated alerts<br>- Self-service SaaS | Tabular, NLP, LLMs | All model types | - Enterprise-grade<br>- Automated workflows<br>- Governance frameworks<br>- Policy enforcement | - SaaS only<br>- Cost at scale<br>- Less control | [Website](https://superwise.ai) |
| **AWS SageMaker Model Monitor** | - Automatic data capture<br>- Baseline creation<br>- Drift detection (data, concept, bias, feature)<br>- Integration with SageMaker<br>- CloudWatch integration | All data types | Framework-agnostic | - Native AWS integration<br>- Managed service<br>- Auto-scaling<br>- Built-in rules | - AWS ecosystem only<br>- Can be expensive<br>- Complex pricing | [AWS Docs](https://docs.aws.amazon.com/sagemaker/latest/dg/model-monitor.html) |
| **Censius** | - AI observability platform<br>- Model monitoring<br>- Explainability<br>- Drift detection | Tabular, NLP, Computer Vision | All model types | - Comprehensive monitoring<br>- Good visualization<br>- Proactive alerting | - Newer platform<br>- Limited information available | [Website](https://censius.ai) |

## Summary Notes

### License Types
- **Open-Source**: Apache 2.0, MIT, AGPL (with restrictions)
- **Proprietary**: Commercial licenses, often SaaS-based

### Integration Considerations
- Most tools integrate with popular ML frameworks (TensorFlow, PyTorch, Scikit-learn)
- Cloud platforms (AWS, Azure, GCP) have native solutions
- Open-source tools often require more setup but offer greater control
- Commercial tools provide managed services with enterprise support

### Choosing the Right Tool
- **For startups/small teams**: Evidently AI, MLflow, NannyML
- **For enterprises with budget**: Arize AI, Fiddler AI, TruEra
- **For AWS users**: SageMaker Model Monitor
- **For Kubernetes deployments**: Seldon Core, Prometheus
- **For LLM-specific needs**: Evidently AI, Arize AI, WhyLabs, TruEra
- **For privacy-sensitive applications**: WhyLabs (cloud version), self-hosted open-source options
