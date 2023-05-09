---
title: 'The IFMIF-DONES remote handling control system. Experimental setup for OPC UA integration'
authors:
  - "E. Valenzuela"
  - "A. Cano-Delgado"
  - "J. Cruz-Miranda"
  - mrouret
  - "G. Miccichè"
  - eros
  - "F. Arranz"
  - "J. Díaz"

author_notes:
date: '2023-07-08T17:44:35'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-08T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Fusion Engineering and Design'
publication_short: 'Fusion Eng'

abstract: "The devices used to carry out Remote Handling (RH) manipulation tasks in radiation environments address requirements that are significantly different from common robotic and industrial systems due to the lack of repetitive operations and incompletely specified control actions. This imposes the need of control with human-in-the-loop operations. These RH systems are used on facilities such PRIDE, CERN, ESS, ITER or IFMIF-DONES, the reference used for this work.
For the RH system is crucial to provide high availability, robustness against radiation, haptic devices for teleoperation and dexterous operation, and smooth coordination and integration with the centralized control room. To achieve this purpose is necessary to find the best approach towards a standard control framework capable of providing a standard set of functionalities, tools, interfaces, communications, and data formats to the different types of mechatronic devices that are usually considered for Remote Handling tasks. This previous phase of homogenization is not considered in most facilities, which leads towards a costly integration process during the commissioning phase of the facility.
In this paper, an approach to the IFMIF-DONES RH Control framework with strong standard support based on protocols such as OPC UA has been described and validated through an experimental setup. This test bench includes a set of physical devices (PLC, conveyor belt and computers) and a set of OPC UA compatible software tools, configured and operable from any node of the University of Granada network. This proof-of-concept mockup provides flexibility to modify the dimension and complexity of the setup by using new virtual or physical devices connected to a unique backbone. Besides, it will be used to test different aspects such as control schemes, failure injection, network modeling, predictive maintenance studies, operator training on simulated/real scenarios, usability or ergonomics of the user interfaces before the deployment. In this contribution, the results are described and illustrated using a conveyor belt set-up, a small but representative reference used to validate the RH control concepts here proposed."

# Summary. An optional shortened abstract.
summary:

tags:
  - Virtual Reality
  - Remote Handling
  - OPC UA
featured: false

links:
 - name: "Journal"
   url: "https://www.sciencedirect.com/science/article/pii/S0920379623003587"
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['tan19','eurofusion']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
