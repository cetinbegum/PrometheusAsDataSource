@cetinbegum ➜ /workspaces/PrometheusAsDataSource (main) $ kubectl get secret --namespace default grafana -o jsonpath="{.data.admin-password}" | base64 --decode ; echo

password: kO79OC8dX1DQcBI1OsicbMgnO5KOc5icJPlaouNI
username: admin