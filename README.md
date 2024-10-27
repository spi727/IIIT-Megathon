# IIIT-Megathon
Mental Health Concern Classification Using NLP
 Objective
 Participants are tasked with developing a NLP-based solution that automatically extracts,
 classifies, and performs deeper analysis of mental health concerns from user input. The
 solution should consist of five main components: polarity detection, keyword extraction
 (NER), concern classification, intensity scoring, and a timeline-based sentiment shift
 analysis.
 Task Breakdown
 1. Polarity Finder:
 Build a model that identifies the sentiment or emotional polarity (positive, negative, or
 neutral) of the user’s input. Additionally, detect shifts in sentiment when provided with
 multiple inputs over time, indicating worsening or improving conditions.
 2. Keyword Extractor (NER):
 Implement a Named Entity Recognition (NER) model that identifies and extracts
 mental health-related concern phrases from the user's input.
 ○ Example: For the input "I’ve been feeling very anxious lately," the model
 should extract the phrase "feeling very anxious."
 3. Concern Classifier:
 Create a classification model that takes the extracted concern phrases and maps
 them to predefined mental health categories such as "Anxiety," "Depression,"
 "Stress," "Insomnia," "Eating Disorder," etc.
 4. Intensity Scoring:
 Extend the concern classifier to produce an intensity score on a scale of 1-10,
 representing the severity of the concern based on contextual and linguistic cues.
 ○ Example: The phrase "I feel extremely anxious" should have a higher
 intensity score compared to "I feel a little anxious."
 5. Timeline-Based Sentiment Shift Analysis:
 Track changes in sentiment and concerns over time for each user input. This feature
 should help detect whether a user's mental health is improving or deteriorating based
 on a sequence of inputs over days, weeks, or months.
 ○ Example: Over multiple inputs, detect whether the user's mood is shifting
 from anxiety to depression or showing signs of recovery.
 End-to-End Pipeline
 The final solution should integrate the following components:
 1. Polarity Finder: Detects the emotional polarity and shifts in sentiment over time.
 2. Keyword Extractor (NER): Extracts concern-related keywords or phrases.
 3. Concern Classifier: Maps extracted keywords to predefined categories.
 4. Intensity Scorer: Provides a severity score for each concern.
 5. Timeline Sentiment Analyzer: Tracks the progression of mental health concerns
 over multiple inputs.
● ExamplePipeline:
 Input Sequence:
 Day 1: "I can’t sleep well and I feel very low."
 Polarity: Negative
 Extracted Concern 1: "can’t sleep well" → Category: "Insomnia" → Intensity: 6/10
 Extracted Concern 2: "feel very low" → Category: "Depression" → Intensity: 7/10
 Timeline Shift: Sentiment remains negative.
 Day 7: "I feel a bit better but still anxious."
 Polarity: Neutral
 Extracted Concern 1: "still anxious" → Category: "Anxiety" → Intensity: 4/10
 Timeline Shift: Signs of improvement from Depression to Anxiety.
 Expected Deliverables
 Participants must deliver the following components:
 1. Polarity Finder: A model that detects sentiment and tracks emotional shifts over
 time.
 2. Extractor: A functioning Named Entity Recognition (NER) model that accurately
 extracts mental health concern phrases.
 3. Classifier: A classification model that maps extracted concerns to predefined mental
 health categories.
 4. Intensity Scorer: A scoring system to assess the severity of the concern.
 5. Timeline-Based Sentiment Analyzer: A component that tracks the progression or
 improvement of mental health concerns over time.
 Evaluation Criteria
 ● Polarity Detection Accuracy: How well the model identifies the emotional polarity
 and tracks shifts over time.
 ● Extraction Accuracy: How well the model extracts mental health concern-related
 phrases from user input.
 ● Classification Precision: The accuracy with which the model maps the extracted
 concerns to predefined categories.
 ● Intensity Scoring: The accuracy of assigning appropriate intensity levels to
 concerns.
 ● Timeline Analysis: How well the model tracks and predicts the progression of
 mental health concerns over time.
 ● End-to-End Performance: The overall efficiency and reliability of the complete
 pipeline from raw user input to a classified, scored, and timeline-analyzed output.
 Sample Dataset
 mental_health_dataset
