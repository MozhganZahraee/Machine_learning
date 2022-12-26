Anomaly detection is a crucial aspect of quality assurance in industrial manufacturing. In this project, we implemented the PaDiM model from Anomalib to identify defects in products or anomalous pixels within images. By training the model on normal products, we were able to evaluate its accuracy on both normal and defective products. To do this, we used the MVTec dataset, which includes 5000 images across 15 categories. The results of the testing process are images which including heatmaps and segmentations of any defects, can be found in the test-result directory within anomalib folder. For example, the result image of a broken bottle is as follows: 

<img src="anomalib\test_result\broken_small\008.png">

Performance was measured using the AUROC metric, which reflects the model's ability to classify images. A higher AUROC indicates better performance in distinguishing between normal and defective products.


