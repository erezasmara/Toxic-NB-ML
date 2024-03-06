# Project Description:
The Toxic Comments Classification Naive Bayes UI is designed to complement the TOXIC_NB_APIS, providing a user interface for toxicity classification.
It is built with Node.js and utilizes Express, HBS (Handlebars), and Nodemon for development. The UI communicates with the API service to classify text as toxic or non-toxic.

# Toxic Comments Classification Naive Bayes API
Project Structure:
```
Toxic_nb_apis
├─ .DS_Store
├─ Procfile
├─ README.md
├─ app.py
├─ requirements.text
├─ test.csv
└─ train.csv

```
Description:
This RESTful API service employs machine learning (Naive Bayes) to detect toxic text. The server, built with Python and Flask, handles incoming requests for toxicity classification. The project requires Python 3.8 or above, and the necessary dependencies can be installed using the provided requirements.txt file. Additionally, it utilizes training and testing datasets (train.csv and test.csv) for model training and evaluation.

Requirement:
- Python 3.8 or above
- pip module
- pandas module
- sklearn module
- data set train.csv & test.csv

Installation with pip
```
## sudo python3 -m pip install -U pandas
## sudo python3 -m pip install -U scikit-learn
## sudo python3 -m pip install -U termcolor
```

Start:\
python3 app.py

testing with CURL
```
curl -X POST -H "Content-Type: application/json" -d '{"data":"HELLO"}' http://localhost:5000
```
response
```
{
  "msg": "Have a nice day", 
  "result": true
}
```

 result :
  - true - text doesn't contains a toxic comment
  - false - contains toxic comment



# Toxic Comments Classification Naive base UI
Project structure:
```
Toxic_nb_UI
├─ README.md
├─ package-lock.json
├─ package.json
├─ public
│  ├─ css
│  │  ├─ form.css
│  │  ├─ loader.css
│  │  ├─ nav.css
│  │  ├─ popup.css
│  │  └─ style.css
│  ├─ img
│  │  ├─ bad.png
│  │  ├─ guru.png
│  │  ├─ ok.png
│  │  └─ profile_pic.jpeg
│  └─ js
│     └─ app.js
├─ src
│  ├─ app.js
│  └─ utils
│     └─ toxic.js
├─ templates
│  ├─ partials
│  │  ├─ footer.hbs
│  │  └─ header.hbs
│  └─ views
│     ├─ 404.hbs
│     ├─ about.hbs
│     ├─ help.hbs
│     ├─ home.hbs
│     └─ index.hbs

```
Description:
Toxic applications UI

Requirements:
- node.js 12 +
- "express": "^4.17.1",
- "hbs": "^4.1.2",
- "nodemon": "^2.0.14",
- "request": "^2.88.2"

Start:
- npm install
- npm run start

### snapshoots.
![image](https://user-images.githubusercontent.com/33747218/232039512-41d0d304-efd2-4a15-adac-029ee2120f13.png)


### Model Mahcines Learning results.
  ![image](https://user-images.githubusercontent.com/33747218/137753235-911b5d86-b84c-41cc-bdc3-db3fa2bd0b74.png)
  ![image](https://user-images.githubusercontent.com/33747218/137753228-106a34fb-f981-43b1-a0a1-8b1b6076b1ed.png)



