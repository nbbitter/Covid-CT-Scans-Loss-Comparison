# Covid-CT-Scans-Loss-Comparison

Pytorch Deep learning project that compares in loss functions (cosine similarity loss and cross entropy loss) for diagnosing Covid in CT lung scans. Cosine Similarity apparantly has. Loss functions on two architectures, one less complex architecture and the other being ResNet on the predictive task of identifying Covid + patients through lung CT scans. The two loss functions are the commonly used cross entropy and less used cosine similarity loss. In a publication, apparently architectures trained with cosine similarity loss with smaller data sets, such as covid CT imagery, performed much better. In this project the basic architecture cosine similarity loss did yield better results consistent with the literature, however for the ResNet architecture cross entropy had the highest accuracy at a 50% threshold. The basic architecture trained with cosine loss had very high sensitivity which is desirable in this application and had slightly higher AUC than the ResNet with cross entropy, despite the ResNets higher accuracy at 50% at a classification threshold. Thus, the results suggest in practice the basic architecture trained with cosine similarity loss would be a more desirable choice for clinical usage, although ResNet with cross Entropy loss is still viable.
