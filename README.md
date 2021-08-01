# facial-expression recognition-with-Deep-Learning
Deep learning is a newly-emerged machine learning theory, and has received extensive attentions in pattern recognition, signal processing, computer vision, etc. Deep belief networks (DBNs) is a representative method of deep learning and has a strong ability of unsupervised feature learning. by combining DBNs with multi-layer perceptron (MLP), a new method of facial expression recognition based on deep learning is proposed. The proposed method integrates the DBNs's advantage of unsupervised feature learning with the MLP's classification advantage. Experimental results on two benchmarking facial expression databases, i.e., the JAFFE database and the Cohn-Kanade database, demonstrate the promising performance of the proposed method for facial expression recognition, outperforming the other state-of-the-art classification methods such as the nearest neighbour, MLP, support vector machine, the nearest subspace, as well as sparse representation-based classification.

# facial-expression
Our face is an intricate, highly differentiated part of our body – in fact, it is one of the most complex signal systems available to us. It includes over 40 structurally and functionally autonomous muscles, each of which can be triggered independently of each other.

The facial muscular system is the only place in our body where muscles are either attached to a bone and facial tissue (other muscles in the human body connect to two bones), or to facial tissue only such as the muscle surrounding the eyes or lips.

# Classify the emotions
Facial expressions are only one out of many correlates of emotion, but they might be the most apparent ones. Humans are obviously able to produce thousands of slightly varying sets of facial expressions – however, there is only a small set of distinctive facial configurations that almost every one associates with certain emotions, irrespective of gender, age, cultural background and socialization history.

These categorical emotions are:
![image](https://user-images.githubusercontent.com/73308203/127771404-6f539df0-7684-4030-a881-9be9baa6865e.png)


ekmans basic emotions

The finding that almost everyone can produce and recognize the associated facial expressions of these emotions has led some researchers to the (debated!) assumption that they are universal.

# Technology 
## Face detection
The position of a face is found in a video frame or image, which can be achieved by applying the Viola Jones Cascaded Classifier algorithm, for example. This might sound sophisticated, but you can actually find this technology in the camera of your iPhone or Android smartphone as well. The result is a face box framing the detected face.
## Feature detection
Within the detected face, facial landmarks such as eyes and eye corners, brows, mouth corners, the nose tip etc. are detected. After this, an internal face model is adjusted in position, size, and scale in order to match the respondent’s actual face. You can imagine this like an invisible virtual mesh that is put onto the face of the respondent: Whenever the respondent’s face moves or changes expressions, the face model adapts and follows instantaneously. As the name indicates, the face model is a simplified version of the respondent’s actual face. It has much less details, (so-called features) compared to the actual face, however it contains exactly those face features to get the job done. Exemplary features are single landmark points (eyebrow corners, mouth corners, nose tip) as well as feature groups (the entire mouth, the entire arch of the eyebrows etc.), reflecting the entire “Gestalt” of an emotionally indicative face area.
## Feature classification
Once the simplified face model is available, position and orientation information of all the key features is fed as input into classification algorithms which translate the features into Action Unit codes, emotional states, and other affective metrics.

![image](https://user-images.githubusercontent.com/73308203/127771544-4eaa6195-a252-4243-ba5c-6f3268f7479b.png)
# Facial Expression Analysis (FEA): Application fields
1. Consumer neuroscience and neuromarketing
2. Media testing & advertisement
3. Psychological research
4. Clinical psychology and psychotherapy
5. Medical applications & plastic surgery
6. Software UI & website design
7. Engineering of artificial social agents (avatars) 

# Reference
https://cise.ufl.edu/research/learndialogue/pdf/LearnDialogue-Grafsgaard-EDM-2013.pdf
