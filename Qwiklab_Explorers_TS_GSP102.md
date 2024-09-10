# Cloud Spanner: Qwik Start || [GSP102](https://www.cloudskillsboost.google/focuses/1774?parent=catalog) ||

# # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

### Run the following Commands in CloudShell

```
export REGION=
```
```
gcloud spanner instances create test-instance \
  --config=regional-$REGION \
  --description="Test Instance" \
  --nodes=1


gcloud spanner databases create example-db --instance=test-instance

gcloud spanner databases ddl update example-db --instance=test-instance \
  --ddl="CREATE TABLE Singers (
    SingerId INT64 NOT NULL,
    FirstName STRING(1024),
    LastName STRING(1024),
    SingerInfo BYTES(MAX),
    BirthDate DATE,
    ) PRIMARY KEY(SingerId);"
```


# Congratulations ..!!🎉  You completed the lab shortly..😃💯

# *Well done..!* 👏

# Thank you for visiting.... :) 🗯️

# [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)
