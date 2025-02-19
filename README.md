# Poisonous Mushroom Detector

**Final Project for the Building AI Course**  

## Summary

This AI model analyzes an image of a mushroom and determines whether it is **poisonous or edible**. Additionally, it provides useful information about the mushroom, such as its scientific name, potential uses, and habitat.  

## Background  

Foraging for wild mushrooms is an increasingly popular activity, especially in countries like Norway, where forests are rich with edible fungi. My wife, an avid mushroom forager, often ventures into the forests near Oslo with her foraging group. However, **mistaking a poisonous mushroom for an edible one can be fatal**.  

This AI aims to provide an additional layer of safety by assisting foragers in identifying mushrooms with a simple **image-based classification system**.  

##  How It Works  

1. The user takes a **photo** of a mushroom using their smartphone or camera.  
2. The AI model processes the image and classifies the mushroom as **edible, poisonous, or unknown**.  
3. The system provides **additional details**, such as scientific classification, common uses, and warnings.  

### Use Cases  
- **Foragers & Hikers:** Identify mushrooms in the wild before consuming them.  
- **Educational Tool:** Learn about different mushroom species and their properties.  
- **Emergency Aid:** Prevent accidental poisoning by providing quick identification.  

## Data Sources & AI Methods  

### Data Collection  
- **Wikipedia & Mycology Databases:** Information on mushroom species, toxicity, and uses.  
- **Google Images & Open Datasets:** High-quality images for training an image classification model.  
- **Foraging Communities & Expert Contributions:** Real-world data from experienced foragers.  

### AI Techniques  
- **Convolutional Neural Networks (CNNs):** Used for image classification to distinguish between different mushroom species.  
- **Transfer Learning:** Fine-tuning pre-trained models (e.g., ResNet, MobileNet) to improve accuracy with a smaller dataset.  
- **Natural Language Processing (NLP):** Extracting structured information from Wikipedia descriptions.  

## Challenges  

- **Accuracy & Safety Risks:** Even the best AI may misidentify a mushroom. Users must always exercise caution and verify with experts.  
- **Limited Data:** Some rare mushroom species have very few publicly available images.  
- **Similar-Looking Species:** Many poisonous mushrooms resemble edible varieties, making classification difficult.  

## Future Improvements  

- **Expand to Other Wild Foods:** Identify berries, fruits, and edible plants to assist foragers further.  
- **Augmented Reality Integration:** Provide real-time overlays highlighting mushroom properties using AR glasses or smartphone cameras.  
- **Community-Driven Database:** Allow users to contribute verified images and feedback to improve accuracy over time.  

## Acknowledgments  

- **The Building AI Course Team** for the learning experience.  
- **My wife** for her endless passion for mushrooms and inspiring this project.  
