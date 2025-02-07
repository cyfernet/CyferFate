[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![CodeStyle](https://img.shields.io/badge/Check%20Style-Google-brightgreen)](https://checkstyle.sourceforge.io/google_style.html) [![Style](https://img.shields.io/badge/Check%20Style-Black-black)](https://checkstyle.sourceforge.io/google_style.html) [![Build Status](https://travis-ci.org/FederatedAI/FATE.svg?branch=master)](https://travis-ci.org/FederatedAI/FATE)
[![codecov](https://codecov.io/gh/FederatedAI/FATE/branch/master/graph/badge.svg)](https://codecov.io/gh/FederatedAI/FATE)
[![Documentation Status](https://readthedocs.org/projects/fate/badge/?version=latest)](https://fate.readthedocs.io/en/latest/?badge=latest)
[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/from-referrer/)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/6308/badge)](https://bestpractices.coreinfrastructure.org/projects/6308)


<div align="center">
  <img src="./doc/images/FATE_logo.png">
</div>

# CyferFate: CyferNet AI’s Decentralized Federated Learning Framework

CyferFate is CyferNet AI’s flagship open-source framework designed to empower enterprises and institutions to collaboratively train AI models on distributed data while ensuring top-tier data security and privacy. By integrating state-of-the-art secure computation protocols—including homomorphic encryption and multi-party computation (MPC)—CyferFate supports diverse federated learning scenarios ranging from logistic regression and tree-based algorithms to deep learning and transfer learning.

CyferFate is hosted under the auspices of CyferNet AI and adheres to a robust technical charter that defines contribution responsibilities and project oversight. You can review the [CyferFate Technical Charter](https://github.com/CyferNetAI/CyferFate-Community/blob/master/CyferFate_Technical_Charter.pdf) for detailed guidelines on technical contributions and community governance.

<https://cyferfate.docs.io/en/latest>

---

## Getting Started 

CyferFate can be deployed on a single node for testing or scaled across multiple nodes to achieve enterprise-level performance, reliability, and manageability. Choose the deployment approach that best matches your environment:

- **Release Versions:**  
  Download the latest release from our [CyferFate Release Portal](https://github.com/CyferNetAI/CyferFate/wiki/Download).

### Version ≥ 2.0

#### Standalone Deployment

- **Single-Node Deployment:**  
  Deploy CyferFate on a single node using our PyPI package, pre-built Docker images, or dedicated installers. This approach is ideal for initial testing and development. Refer to our [Standalone Deployment Guide](./deploy/standalone-deploy/) for detailed instructions.

#### Cluster Deployment

- **Multi-Node Deployment:**  
  For large-scale, production-grade federated learning, deploy CyferFate across multiple nodes. Our framework supports:
  - **CLI-Based Cluster Deployment:** Use command-line tools to orchestrate a CyferFate cluster.
  - **Docker-Compose Deployment:** Leverage Docker Compose for rapid and reliable cluster setup.

---

## Quick Start

- **Training Demo – CyferFate Only:**  
  Follow our [Training Demo with CyferFate Installed from PyPI](doc/2.0/cyferfate/ml) for a streamlined introduction.
- **Integrated Deployment – CyferFate & CyferFlow:**  
  For a complete ecosystem experience, see our [Quick Start Guide for CyferFate and CyferFlow](doc/2.0/cyferfate/quick_start.md).

---

## Advanced Use

- **Privacy-Preserving (Homo Mode):**  
  Learn how to train and predict securely with CyferFate’s homo mode by following the [CyferFate Homo Mode Guide](./doc/2.0/cyferfate/homo_quick_start.md).
- **Running Advanced ML Modules:**  
  Explore how to run custom ML launchers with CyferFate by referring to our [Advanced ML Launcher Documentation](./doc/README.md#run-ml-modulessince-v200).

### More Examples

- **Machine Learning Examples:**  
  Check out our [ML Examples](examples/launchers) for practical applications.
- **Pipeline Examples:**  
  Explore our [Pipeline Examples](examples/pipeline) that demonstrate end-to-end federated modeling.

---


### Social Media

Follow us on Twitter: [@CyferFateAI](https://twitter.com/cyfernet_ai)



## License

CyferFate is released under the [Apache License 2.0](LICENSE).

---

By leveraging a robust, open-source framework with advanced secure computation protocols, CyferFate sets a new standard for federated learning—empowering organizations to collaboratively build powerful AI models without compromising data privacy.

This interconnected ecosystem of tools and documentation ensures that CyferFate remains at the forefront of secure, scalable, and privacy-preserving federated learning.
