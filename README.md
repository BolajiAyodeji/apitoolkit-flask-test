# apitoolkit-flask-test

A quick demo MBTPI (Myers-Briggs Personality Type Indicator) prediction application from my [Deploying Machine Learning Models to the Web](https://github.com/BolajiAyodeji/deploy-ml-web-workshop) workshop that uses [APIToolkit's Flask SDK](https://github.com/apitoolkit/apitoolkit-flask) for API monitoring and observability.

---

Add your credentials in a .env file:

```bash
FLASK_DEBUG=1
APITOOLKIT_API_KEY=
```

Install all the required packages:

```bash
pip install python-dotenv scikit-learn flask gunicorn apitoolkit_flask
```

Start the local server:

```bash
flask run
```
