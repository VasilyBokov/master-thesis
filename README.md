# master-thesis
**Approaching Efficient Training of Quantum Feature Maps in Kernel Methods.**


In recent years, a substantial body of research has emerged to explore the integration of quantum computing into machine learning kernel methods, with a particular focus on leveraging the capabilities of near-term intermediate-scale quantum computers. Within this realm, algorithms based on parameterized quantum circuits have emerged as promising candidates for application on these quantum devices. However, training parameterized quantum circuits in kernel methods becomes computationally expensive in the case of large input datasets.
To address this challenge, the master's thesis presents a novel approach for training quantum feature maps applied to binary classification tasks, which represent parameterized quantum circuits capable of embedding input data into Hilbert space. 
It avoids the cost function evaluation with the pairwise calculations of kernel matrix elements and estimates it solely through SWAP tests. We divide the dataset into
two parts, construct density matrices proportional to kernels, and estimate the Hilbert-Schmidt distance between an introduced ”ideal” kernel and the encoded kernel using SWAP tests only. The cost function is equal to this distance and allows finding the optimal feature map parameters, enhancing class separation. This study establishes the model's viability through classification experiments on three standard datasets commonly employed for benchmarking classical machine learning models.
For all of them, significant improvements in classification accuracy after the training were obtained. The characteristics of the quantum circuit in use, such as expressibility and entanglement capability, were evaluated and discussed. To mitigate the quantum hardware requirements, a batch-based approach was introduced and assessed. The batch-based classifier yielded similar results on the benchmark datasets. Furthermore, potential applications for the developed algorithms in quantum and quantum-enhanced data analysis models, including Support Vector Machines and Principal Component Analysis, were investigated, considering both near-term and long-term applications. Overall, the proposed algorithm can be utilized in conjunction with kernel methods, incorporating quantum computers at various stages of their workflow.
