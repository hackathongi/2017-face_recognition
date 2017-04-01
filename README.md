# 2017-face_recognition

Interficie de reconeixement facial

Basat en Openface (http://cmusatyalab.github.io/openface/).

Entrenat amb un conjunt de cares autoritzades classificades per nom i amb un conjunt no autoritzat. En funcio de si reconeix un autoritzat o no:
Autoritzat -> Dir "Hola %nom!", (Obrir porta?)
No Autoritzat -> Dir "Intruso!", Disparar catapulta, sirena?

OpenFace (models de http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2, https://storage.cmusatyalab.org/openface-models/nn4.small2.v1.t7, https://storage.cmusatyalab.org/openface-models/celeb-classifier.nn4.small2.v1.pkl) 
Python 2 (numpy, dlib, pandas, scikit-learn, pygame)
OpenCV
LuaJit (luarocks, dpnn, csvigo)
