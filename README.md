# DjangoMedicalStoreManagementSystem




## Login DETAILS
<pre>USername : admin</pre>
<pre>Password : admin</pre>


## Create runtime.txt
</pre>ADD Python Version in this File (E.G python-3.7.4)</pre>

## Create requirements.txt and Add Libraries
<pre>CHECK requirements.txt File</pre>

 
 ## Change Settings.py Setting
 <pre>First Allowed HOST DOMAIN NAME </pre>
 <pre>Second ADD Middleware "whitenoise.middleware.WhiteNoiseMiddleware" </pre>
 <pre>Third ADD CORS_ORIGIN_WHITELIST = ["ADD DOMAIN HERE WITH HTTP URL (E.G : http://localhost:3000)"] </pre>
 ## FOURTH ADD THIS SETTING in settings.py 
<pre>
import dj_database_url
prod_db=dj_database_url.config(conn_max_age=500)
DATABASES['default'].update(prod_db)
</pre>
