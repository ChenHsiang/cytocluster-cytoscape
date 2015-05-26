CytoCluster is a [Cytoscape](http://www.cytoscape.org/) app for analysis and visualization of clusters from network,and has been tested on Cytoscape 3.0.X.
> [Please downlaod the manual.](https://docs.google.com/file/d/0B13gZNlVofBmajRTZmZnVmxVejA/edit?usp=sharing)
### **1. Introduction** ###
CytoCluster is a Cytoscape app for analysis and visualization of clusters from network. Three different graph clustering algorithms (HC-PIN<sup>1</sup>, OH-PIN<sup>2</sup>, IPCA<sup>3</sup> ) were implemented in CytoCluster. This app is developed by Yu Tang, supported and directed by Dr. Jianxin Wang and Dr. Min Li and Dr.Jiancheng Zhong, from Central South University.
### **2. Quick Start** ###
Following is a short quick start for the usage of CytoCluster, detailed information of the algorithms implemented in this plug-in can be found in related papers.
  1. Download and install Cytoscape3.0(http://www.cytoscape.org/).
  1. Download the Jar version of CytoCluster([CytoCluster.jar](https://docs.google.com/file/d/0B13gZNlVofBmeXkyMnYzNnV3UWM/edit?usp=sharing)).
  1. Start Cytoscape, install the CytoCluster.jar through App Manager(**Apps → App Manager → Install from file..**)
  1. Import or open a network.
  1. Click **App → CytoCluster → Start CytoCluster**.
  1. It will switch to CytoCluster tab on left panel, choose the clustering algorithm and keep all parameters as default or you can customize the parameters as you want.
  1. Click Analysis button.
  1. After analysis is done, results will be shown in right panel. You can check the attributes of the selected cluster or export the results if you like. Results can be sorted by score or size or modularity.

### **3. Contact Information** ###
If you any problems or suggestions of CytoCluster, please contact us at Email: **tangyu333@gmail.com**, **jxwang@mail.csu.edu.cn**, **limin@mail.csu.edu.cn**.

### **4. References** ###

  1. Wang J, Li M, Chen J, et al. A fast hierarchical clustering algorithm for functional modules discovery in protein interaction networks[J](J.md). Computational Biology and Bioinformatics, IEEE/ACM Transactions on, 2011, 8(3): 607-620.
  1. Wang J, Ren J, Li M, et al. Identification of Hierarchical and Overlapping Functional Modules in PPI Networks[J](J.md). 2012.
  1. Li M, Chen J, Wang J, et al. Modifying the DPClus algorithm for identifying protein complexes based on new topological structures[J](J.md). Bmc Bioinformatics, 2008, 9(1): 398.
