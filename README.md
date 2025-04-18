# edu-sentiment-analysis
# sentiment_test.py

texte = input("Entre un commentaire d'élève : ")

if "bien" in texte or "intéressant" in texte:
    print("Sentiment : POSITIF")
elif "nul" in texte or "ennuyeux" in texte:
    print("Sentiment : NÉGATIF")
else:
    print("Sentiment : NEUTRE")
