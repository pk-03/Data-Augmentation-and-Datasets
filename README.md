# DATA-AUGMENTATION AND DATASETS 
<br>
<p> 
This includes the Data Augmentations techniques and dataset we got from the back-translation augmentation technique! </p>


<span>
Back-translation is a widely used data augmentation technique in NLP that enhances model performance by diversifying the dataset while retaining the original meaning of the text. In this study, we leveraged Google Translate for back-translation to augment a Hindi sentiment classification dataset. Reviews were initially translated from Hindi to English and then back to Hindi. Additionally, we incorporated French as a second intermediate language to introduce further variation, as the syntactic differences between French and Hindi provided unique transformations.

This dual approach generated paraphrased versions of the reviews, expanding the dataset’s size and variety. The augmented data maintained the core sentiment of the original text while introducing structural diversity, which improved the model’s generalization to linguistic variations. By training a transformer-based sentiment classification model on this enriched dataset, we achieved better training stability and higher model accuracy.
</span>
