## CloudAccel Hardware Acceleration of Machine Learning Applications in the Cloud

### About CloudAccel

Emerging web applications like cloud computing, machine learning and big data analytics have increased significantly the workload on the data centres during the last years. Most of these applications are computational intensive and typical server processors cannot sustain the exponential increase of the network traffic of computation intensive applications.
A solution that can be used to overcome this problem is the use of hardware accelerators such as the ones based on FPGA. The use of highly specialized hardware accelerator can greatly advance server processors and can also increase significantly the performance of data centres given a fixed power budget.

The main objective of the CloudAccel project is to develop high performance hardware accelerators for widely used machine learning, graph computations and data analytics applications. The accelerators will be developed in the form of IP (Intellectual Property) cores and will be compatible to be uploaded, e.g. to the Amazon AWS webstore to be used as an instance by the cloud software developers. Since many hardware accelerators can be more efficient if they are optimized for specific dataset and workloads, CloudAccel will also develop a framework that will allow the automatic generator for hardware accelerators optimized not only for a specific machine learning application but also for the specific dataset and workloads (e.g. training set) that need to accelerate.

During this project, we will develop the configurable hardware accelerators in the form of IP cores for high performance FPGA-based hardware accelerators for widely used machine learning and graph computations applications. These templates will be developed in typical programming languages such as C or C++ that can be transformed to hardware through high level synthesis by inserting the right annotations (pragmas) for the efficient mapping in hardware resources. However, hardware accelerators cannot be easily configured to meet the application requirements with different datasets (input data, size of the arrays, etc.). Hardware platforms do not support the flexibility of software programming like dynamic memory management, and thus higher programming complexity is required for the efficient mapping of the kernel to the available hardware resources. Therefore, the main goal of the project will be the development of the hardware generators that will allow the automatic creating of hardware accelerators that are being optimized for the user’s datasets and application parameters. 
Finally, the last step will be the development of the required libraries and APIs for the specific kernels.

​Specifically, we will develop the APIs and the libraries for the widely-used frameworks such as Apache Spark, Torch, Google Tensorflow and Caffe that will make the use of the accelerators easy to instantiate and use by software and cloud programmers. The hardware accelerators will first be tested and validated in the local infrastructure (FPGA boards hosted in desktop PC through the PCIe interface and using the Xilinx SDAccel framework). After the verification and validation of the designs, the IP cores will be uploaded to online market places that support heterogeneous (FPGA) data center infrastructure such as Amazon AWS, IBM suppervessel and Google Cloud platform.​

### Publications

#### Book Chapters

1. [A quantitative comparison for Image Recognition on accelerated Heterogeneous Cloud Infrastructure](https://www.taylorfrancis.com/books/e/9780429399602)
Dimitris Danopoulos, Christoforos Kachris, Dimitrios Soudris, 
Heterogeneous Computing Architectures, Challenges and Visions
Taylor and Francis Publications, 2019

#### International Conferences


1. [Utilizing Cloud FPGAs towards the Open Neural Network Standard](https://cloudaccel.weebly.com/uploads/1/3/6/6/13662069/2020_suscom_paper.pdf)  
Dimitris Danopoulos, Christoforos Kachris, Dimitrios Soudris  
11th IEEE International Green and Sustainable Computing Conference (IGSC 2020), October 2020

2. [Hardware Acceleration of Decision Tree Learning Algorithm](https://cloudaccel.weebly.com/uploads/1/3/6/6/13662069/2020_mocast_decision_tree.pdf)  
Asim Zoulkarni, Christoforos Kachris, Dimitrios Soudris  
8th International Conference on Modern Circuits and Systems Technologies (MOCAST), September 2020
(Best Paper Award nomination), [Video](https://ml.zmml.uni-bremen.de/video/5f4b4cd6d42f1c7a6a8b4570)

3. [Automatic Generation of FPGA Kernels From Open Format CNN Models](https://www.fccm.org/past/2020/proceedings/2020/pdfs/FCCM2020-65FOvhMqzyMYm99lfeVKyl/580300a237/580300a237.pdf)  
Dimitris Danopoulos, Christoforos Kachris, Dimitrios Soudris  
2020 IEEE 28th Annual International Symposium on Field-Programmable Custom Computing Machines (FCCM)
pp. 237-237, May 2020

4. [Hardware Acceleration on Gaussian Naive Bayes Machine Learning Algorithm](https://cloudaccel.weebly.com/uploads/1/3/6/6/13662069/mocast_paper_naive_bayes.pdf)  
Georgios Tzanos, Christoforos Kachris, Dimitrios Soudris  
8th International Conference on Modern Circuits and Systems Technologies (MOCAST)
13-15 May 2019, Thessaloniki, Greece

5. [Approximate Similarity Search with FAISS framework using FPGAs on the cloud](https://cloudaccel.weebly.com/uploads/1/3/6/6/13662069/samos_faiss_paper.pdf)  
Dimitris Danopoulos, Christoforos Kachris, Dimitrios Soudris  
International Conference on Embedded Computer Systems, Architecture Modeling and Simulation (SAMOS)
July 7-11 2019, Samos Greece

6. [FPGA Acceleration of Approximate KNN Indexing on High-Dimensional Vectors](https://cloudaccel.weebly.com/uploads/1/3/6/6/13662069/faiss_recosoc.pdf)  
Dimitris Danopoulos, Christoforos Kachris, Dimitrios Soudris  
14th International Symposium on Reconfigurable Communication-centric Systems-on-Chip (ReCoSoC 2019)
July 1-3 2019, York - United Kingdom

### Source codes

[Open-source github](https://github.com/cloudaccel)

### Awards

#### NTUA Students granted the first place in the Open Hardware Contest organized by Xilinx in 2 categories

Students Dimitris Danopoulos and George Tzanos, supervised by research associate Dr. Christoforos Kachris and Prof. Dimitrios Soudris, developed a novel platform for the hardware acceleration of machine learning applications. The platform was developed from the Microprocessors Lab (National Technical University of Athens).

Specifically, Dimitris Danopoulos received the first price on the hardware acceleration category for his work on the acceleration of FAISS; a widely used application for efficient similarity search and clustering of dense vectors in a Xilinx Alveo FPGA board and cloud FPGA. George Tzanos received the first price on the pynq category (using the Zynq SoC) for the efficient acceleration of the Naïve Bayes algorithm for training and classification.

The work has been done under the project “CloudAccel: Hardware Acceleration of Machine Learning Applications in the Cloud” that has received funding from the Hellenic Foundation for Research and Innovation (HFRI) and the Genal Secretariat for Research and Technology (GSRT) under grant agreement no 2212.


![award1_xup2018](https://cloudaccel.weebly.com/uploads/1/3/6/6/13662069/d23563-0025.jpg)



### Contact

Christoforos Kachris

National Technical University of Athens (NTUA)
School of Electrical & Computer Engineering
Department of Computer Science
9 Heroon Polytechneiou, Zographou Campus
157 80 Athens - Greece

Email:
kachris @ microlab [dot] ntua [dot] gr

This project has received funding from the Hellenic Foundation for Research and Innovation
(HFRI) and the Genal Secretariat for Research and Technology (GSRT), under grant agreement no 2212 project “CloudAccel: Hardware Acceleration of Machine Learning Applications in the Cloud”.

