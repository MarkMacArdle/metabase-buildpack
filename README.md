Forked to add installing the .jar file for the BigQuery community driver.

-----------------

Heroku Buildpack for Metabase

Add the following to your app.json:

"buildpacks": [
  {
    "url": "https://github.com/MarkMacArdle/metabase-buildpack"
  }
]