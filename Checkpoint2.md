# Checkpoint 2: Face Recognition Distinguishes Known vs Unknown
## Goal

**Recognize authorized users and detect strangers.**

## Topics to Learn
1. Face Detection
2. Face Recognition

## Face Detection
### Understand:
1) Haar Cascades
2) HOG-based detection
3) CNN-based detection (basic idea)

## Face Embeddings

### Learn:

1) What embeddings are
2) Distance comparison
3) Threshold matching

## Face Recognition Workflow
1) Store known faces
2) Encode faces
3) Compare embeddings
4) Classify as known/unknown

## Recommended Resources
### YouTube
1) [Face Recognition Python Project | Face Detection Using OpenCV Python - Complete Tutorial](https://www.youtube.com/watch?v=JZZr0PjZsIk&t=1028s)
2) ["Face Recognition with OpenCV with Python" by 
ProgrammingKnowledge](https://www.youtube.com/watch?v=cnmMSZbVU4Y&list=PLS1QulWo1RIbp_ImnSEWEMRLnJVfEc-GR)

### Documentation
1) [face_recognition GitHub](https://github.com/ageitgey/face_recognition)


## Important Concepts
1) Embedding Distance
2) Faces are converted into vectors
3) Smaller distance → more similar faces
4) Threshold (typically between 0.5-0.6)

## Mini Tasks
1) Detect single face
2) Detect multiple faces
3) Label known face
4) Mark stranger as “Unknown”
5) Save unknown face snapshot

## Expected Output

Known users show their names, strangers trigger alerts.